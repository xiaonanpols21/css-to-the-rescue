# CSS To The Rescue
## Assignment 
For my assignment I choose to do the: ‘Modular Control Panel’. 
The 2 CSS architecture that I want to use are: Nesting and Style queries. 

The challenge with this assignment is that I have to learn new techniques and that I have to think outside of the box. I’m not good in those things so that’s what I want to work on. 

## Idea
I made 2 moodboards to begin with. 1 of photo’s of the website that we got to look at the Control Panels. 

![Moodboard 1](https://github.com/xiaonanpols21/css-to-the-rescue/blob/main/img/readme/moodboard-1.jpg)

And one on [Pinterest](https://nl.pinterest.com/xiaonanpols21/css-to-the-rescue/)

![Moodboard 2](https://github.com/xiaonanpols21/css-to-the-rescue/blob/main/img/readme/moodboard-2.png)

I talked with Nils to help me brainstorm of an idea. I said to him that I want to do something with a screen and a keyboard. He looked at my moodboards and said some stuff of changing the heat when you click on a button. And with that I came up with the idea of killing stuff. So this is my idea:

### Idea 1: Kids killer
I am going to make an Arcade machine where you can click on buttons and something will happen on the screen. I thought of making a Kids killer machine. 

Kids are in the room and with the buttons you can change the rooms or other to kill them. 

For example:

- Change heat of the room, then the color of the room will change. More sweat come on the faces of the kids.
- Shut down the windows of the room so that they sweat more and more after you change the heat. (So the pattern of buttons that you click does matter, so in that case you can kill them faster. You have to think logically, kind of).
- And when you wait too long, kids will undo things to save themselves. So you have to be fast.
- Kids can go on levels to die so the point of it is that their heads have to explode. 
- You can throw grenades in the room but that does not mean that they will die right away tho. They will change just more durty. But the more durty they can die tho but not that extreme or something. 

### Idea 2: Make your significant other
I am going to make a simulator where you can style the perfect match for yourself. TanTan is an Asian dating app so that's why the name is TanTan en the person is familiar to an Asian person. 

## Code inspiration
**[Time with a div](https://codepen.io/elad2412/pen/DBeNNZ?editors=1100)**
```css
@keyframes timer{
    0%{
        width:10px;
    }

    100%{
        width:300px; 
        display:block;
    }
}
```

**[Time with numbers countdown](https://codepen.io/elad2412/pen/wvabjXy?editors=1000)**

```css
.count-down .count::before, .count-down .count::after {
    animation: countdown 100s step-end 1 forwards;
    content: "";
    width: 1ch;
}

@keyframes countdown {
  0% {
    content: "9";
  }
  10% {
    content: "8";
  }
  20% {
    content: "7";
  }
  30% {
    content: "6";
  }
  40% {
    content: "5";
  }
  50% {
    content: "4";
  }
  60% {
    content: "3";
  }
  70% {
    content: "2";
  }
  80% {
    content: "1";
  }
  90%, 100% {
    content: "0";
  }
}
```

**[Way of playing with the buttons](https://codepen.io/sowg/pen/GRvQxpN?editors=0110)**

![Code inspiration 1](https://github.com/xiaonanpols21/css-to-the-rescue/blob/main/img/readme/codepen-inspiration-1.png)

**[Active buttons](https://codepen.io/brundolf/pen/beagbQ)**

```css
&:active {
    background:linear-gradient(to right, #565e6a 0%, #333 100%);
}
```

## Sketch
### Idea 1: Kids killer
![Schets](https://github.com/xiaonanpols21/css-to-the-rescue/blob/main/img/readme/schets-1.png)
Here you have a screen where the content will be displayed. And then underneath you have the controls. 

You can:

- Shut down the window
- Turn on the heat
- Turn on the volume
- Throw grenades
- Give them bad candy
- Make oxygen go away
- Let the water fall

### Idea 2: Make your significant other
![Schets](https://github.com/xiaonanpols21/css-to-the-rescue/blob/main/img/readme/schets-2-1.png)
Here you have a screen where the content will be displayed. And then underneath you have the controls. 

You can:

- Change hair style
- Change skin color
- Change clothes
- Switch gender

## Design
### Idea 1: Kids killer
![Design](https://github.com/xiaonanpols21/css-to-the-rescue/blob/main/img/readme/design-1.png)

### Idea 2: Make your significant other
![Design](https://github.com/xiaonanpols21/css-to-the-rescue/blob/main/img/readme/design-2.png)

## Versions
### Version 1
![Versie 1](https://github.com/xiaonanpols21/css-to-the-rescue/blob/main/img/readme/versie-1.png)
I started to make the inputs in the HTML and some styling. But I just couldn't firgure out how to make a switch and a round slider. 

### Version 2
![Versie 2](https://github.com/xiaonanpols21/css-to-the-rescue/blob/main/img/readme/versie-2.png)
With the Codepens from Sanne I could understand better how to build my idea on screen. 

![Form > section](https://github.com/xiaonanpols21/css-to-the-rescue/blob/main/img/readme/versie-2-2.png)
First in the HTML I had a form but when you click on the buttons, the page will refresh but that's not what I want so I changed form to section. But then I thought that I should also change fieldset to section.

### Version 3
![Versie 3](https://github.com/xiaonanpols21/css-to-the-rescue/blob/main/img/readme/versie-3-1.png)
Now I have made radio buttons to choose which hair you want for your character. 

![Versie 3](https://github.com/xiaonanpols21/css-to-the-rescue/blob/main/img/readme/versie-3-2.png)
![Versie 3](https://github.com/xiaonanpols21/css-to-the-rescue/blob/main/img/readme/versie-3-3.png)
I did that with adding the images into the HTML and than in the CSS you do hide it with display none. 

### Version 4
![Versie 4](https://github.com/xiaonanpols21/css-to-the-rescue/blob/main/img/readme/versie-4-1.png)
All my controls are working right now.

- Swtich: Change gender
- Rotate switch: Choose 3 different outfits, it starts with no clothes
- Slider: Change skin color
- Buttons: Change hair style

![Versie 4](https://github.com/xiaonanpols21/css-to-the-rescue/blob/main/img/readme/versie-4-2.png)
Instead of disnplay none when input is checked, I have now that the url changes. This way the url changes to the right urls automatically when the switch is changed to the oposite gender. 

![Versie 4](https://github.com/xiaonanpols21/css-to-the-rescue/blob/main/img/readme/versie-4-3.png)
I use container styles to change the the url of the rotate switch for the clothing. --clothes 2 here says: if value is 2 of the input name clothes than change the url to this one.

![Versie 4](https://github.com/xiaonanpols21/css-to-the-rescue/blob/main/img/readme/versie-4-4.png)
To change the skin color, I use filter: brightness. Nils helped me with this one to make the calculation. But I don't understand it well yet. 

### Version 5
I have added an Easter Egg, so if you can find it, let me know. 

I also cleaned my code. When Sanne helped me he was amazed that I use nesting for everything. So I thought I should clean my code and should not nest where the places are empty. So if I have:

```css
body {
  section {
    section {
      div {

      }
    }
  }
}
```

I should do:
```css
body section section {
  div {

  }
}
```
### Version 6
![Versie 6](https://github.com/xiaonanpols21/css-to-the-rescue/blob/main/img/readme/versie-6-1.png)
I wanted to change the color of the title with an animation from left to right. The letter should wait when the letter before is 100% purple.

![Versie 6](https://github.com/xiaonanpols21/css-to-the-rescue/blob/main/img/readme/versie-6-2.png)
I had that at first. I did that to add a data type in the html.

![Versie 6](https://github.com/xiaonanpols21/css-to-the-rescue/blob/main/img/readme/versie-6-3.png)
And give each span a delay. 

![Versie 6](https://github.com/xiaonanpols21/css-to-the-rescue/blob/main/img/readme/versie-6-4.png)
But when I had that, I wanted to repeat the animation. But that can't because than you have to make difficult calculation for each span to return the animation. So I changed it with the help of docent. 

### Version 7
![Versie 7](https://github.com/xiaonanpols21/css-to-the-rescue/blob/main/img/readme/versie-7-1.png)
So now I have what I wanted.

![Versie 7](https://github.com/xiaonanpols21/css-to-the-rescue/blob/main/img/readme/versie-7-2.png)
I use background-image linear-gradient. And give each span a delay.

![Versie 7](https://github.com/xiaonanpols21/css-to-the-rescue/blob/main/img/readme/versie-7-3.png)
To let the text jump, you can't use translate because than the background-image will not work. So I use padding to do it.

## Progress discussion
### Talking 1
I talked with Sanne about my first idea. He said that it was not a good idea to keep up with this subject. I can keep the controls but change the kids to monsters or something to make it more friendly. Sighn. So I should rethink about my project.

After some thinking I go with my second idea of making a simulator to make your siginifant other

Sanne helped me to understand to make a rotate slider and to make a casino switch because I said to him that I was stuck of understanding how to make these things.

- https://codepen.io/shooft/pen/OJGJeVa
- https://codepen.io/shooft/pen/BaEagwe

### Talking 2
![Versie 4](https://github.com/xiaonanpols21/css-to-the-rescue/blob/main/img/readme/versie-4-1.png)
I showed my work, which was until version 4. Sanne asked me what I was most proud of. I tolled him about the Clothing slider. I didn't knew that I could do that. 

When I first started with my first idea, I had this idea and thought: How can I make this a reality? When I first started with coding of my design, I was a bit stuck and didn't know how where to begin. But when I got hulp to make the first start, it worked so that's what I'm proud of. That I could make my idea a reality. 

Further, Sanne said I can make easter eggs so that's what I did the next week. 

### Talking 3
I showed my project and a few things came up to change:

- Title more playfull
- Rotate slider, change clothes so that it is like that the character gets more clothes. Other wise the input style is not right
- Make the slider thumb more thick

## Resources
- https://nl.vecteezy.com/vector-kunst/1377102-little-kids-friendly-character-set
- https://cambridgedynamics.com/automation/control-panel-design-and-build/
- https://nl.vecteezy.com/vector-kunst/1759689-happy-cute-kid-girl-with-different-poses
- https://nl.vecteezy.com/vector-kunst/13396613-chinese-restaurant-leeg-interieur-tekenfilm-vector
