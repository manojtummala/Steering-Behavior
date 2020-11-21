# Steering-Behavior
you can check it out [here](https://manojtummala.github.io/Steering-Behavior/)

I have applied here the [steering behavior algorithm](http://www.red3d.com/cwr/steer/) 

and also used like in a similar way to flee away the particles that consist the text when mouse courser is near...

We can use this same flee and arrive logic in various aspects such as terraforming the points that are in text format into some other character...

To create the points such as they are occupieing the spaces where the text has to be given is done as:
```bash
var points = font.textToPoints('Something New !!', 100, 350, 128);
```
This here is a function that is already existing in p5JS library.. for processing there is another kind of function.

Just keep all the positions of the text in an array and then place the points in those places..

# Steering-Behavior: 
here it means that every particle is given some velocity and has some desired acceleration or speed.. 
        
   now we have to give it a random position on the canvas and a fixed target as per text..
   and now constrain that when the cursor is neaar their desired speed becomes negitive and they **flee** away..
   and then they have to arrive back at the target(that is the text area).. by the same way they are steered away..
  
Check out the code.. it is self explanatory mostly.. 
