# zoomin 
<button onclick="goFullscreen('embededGame'); return false">Fullscreen</button>
 
<script>
function goFullscreen(id) {
    var element = document.getElementById(id);
    if (element.mozRequestFullScreen) {
      element.mozRequestFullScreen();
    } else if (element.webkitRequestFullScreen) {
      element.webkitRequestFullScreen();
    }
}
</script>
