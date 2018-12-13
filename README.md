# ChristmasCard

For my Christmas card, I made a scene with a house, snowman, snow, and moon. The moon is moving horizontally back and forth, the snow is falling. Additionally, a boarder appears when the screen is clicked. One piece of code that I thought was clever was making for loops for the border rather than drawing each ellipse individually. Below is the code for drawing the border when the mouse is pressed:

    if(mousePressed){
    for(int i = 0; i<17; i+=2)//green dots along left
        {
        fill(94, 153, 118);//green
        ellipse(10, t+i*x , t, t);//circles
        }
    
    for(int i = 1; i<17; i+=2)//red dots along right
        {
        fill(227, 56, 22);//red
        ellipse(10, t+i*x , t, t);//circes
        }

    for(int i = 0; i<17; i+=2) //red dots on left
        {
        fill(230, 69, 69);//red
        ellipse(390, t+i*x, t, t);//circles
        }

    for(int i = 1; i<17; i+=2)//green dots on right
        {
        fill(94, 153, 118);//green
        ellipse(390, t+i*x, t, t);//circles
        }

    for(int i = 1; i<19; i+=2)//red dots on top
        {
        fill(252, 8, 8);//red
        ellipse(t+(i*x), 10, t, t);//circles
        }

     for(int i = 2; i<19; i+=2)//green dots on top
        {
        fill(94, 153, 118);//green
        ellipse(t+i*x, 10, t, t);//circles
        }
        }







