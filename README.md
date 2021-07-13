#In canvas we have to add two span ,

        <canvas id="myCanvas" width="800" height="600"></canvas>
        <br><br >
        <span>Color - </span> 
        <input type="text" id="color">
        <span>Width Of the line - </span> 
        <input type="text" id="width_of_line">
        <button onclick="clearArea();">Clear Area</button>

#we have to add mouseEvent(e)

canvas.addEventListener("mousedown", my_mousedown);
    function my_mousedown(e)
    {
        color = document.getElementById("color").value;
        width_of_line = document.getElementById("width_of_line").value;
        mouseEvent = "mouseDown";
    }
