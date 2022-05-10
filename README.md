# atari-games
Beating Atari Games using RL


Google colab hack to prevent it from timing out
``` Java
function KeepClicking(){
   console.log("Clicking");
   document.querySelector("colab-left-pane").click()
}setInterval(KeepClicking,60000)
```
The _colab-left-pane_ can be any element; preferably non-responsive to mouse-click
