# CSS To The Killing

## Assignment 
For my assignment I choose to do the: ‘Modular Control Panel’. 
The 2 CSS architecture that I want to use are: @layer and Style queries. 

The challenge with this assignment is that I have to learn new techniques and that I have to think outside of the box. I’m not good in those things so that’s what I want to work on. 

## Idea
I made 2 moodboards to begin with. 1 of photo’s of the website that we got to look at the Control Panels. 

![Moodboard 1](https://github.com/xiaonanpols21/css-to-the-rescue/blob/main/img/readme/moodboard-1.jpg)

And one on [Pinterest](https://nl.pinterest.com/xiaonanpols21/css-to-the-rescue/)

![Moodboard 2](https://github.com/xiaonanpols21/css-to-the-rescue/blob/main/img/readme/moodboard-2.png)

I talked with Nils to help me brainstorm of an idea. I said to him that I want to do something with a screen and a keyboard. He looked at my moodboards and said some stuff of changing the heat when you click on a button. And with that I came up with the idea of killing stuff. So this is my idea:

### Kids killer

I am going to make an Arcade machine where you can click on buttons and something will happen on the screen. I thought of making a Kids killer machine. 

Kids are in the room and with the buttons you can change the rooms or other to kill them. 

For example:

- Change heat of the room, then the color of the room will change. More sweat come on the faces of the kids.
- Shut down the windows of the room so that they sweat more and more after you change the heat. (So the pattern of buttons that you click does matter, so in that case you can kill them faster. You have to think logically, kind of).
- And when you wait too long, kids will undo things to save themselves. So you have to be fast.
- Kids can go on levels to die so the point of it is that their heads have to explode. 
- You can throw grenades in the room but that does not mean that they will die right away tho. They will change just more durty. But the more durty they can die tho but not that extreme or something. 

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

## Resources
- https://www.flickr.com/photos/192959875@N05/53382522722/in/pool-controlpanel/
- https://www.flickr.com/photos/154808163@N02/53302205646/in/pool-controlpanel/
- https://www.flickr.com/photos/9716802@N02/2521039431/in/pool-controlpanel/
- https://www.flickr.com/photos/9716802@N02/24494186518/in/pool-controlpanel/
- https://www.flickr.com/photos/ddm_creative_imaging/53008443453/sizes/l/
- https://www.flickr.com/photos/ddm_creative_imaging/52929471314/sizes/l/
- https://cambridgedynamics.com/automation/control-panel-design-and-build/
- https://nl.vecteezy.com/vector-kunst/6581802-set-van-zieke-mensen-met-verschillende-symptomen
- https://nl.vecteezy.com/vector-kunst/1377102-little-kids-friendly-character-set
- https://nl.vecteezy.com/vector-kunst/1759689-happy-cute-kid-girl-with-different-poses
- https://nl.vecteezy.com/vector-kunst/101875-gratis-boom-vector
- https://nl.vecteezy.com/vector-kunst/105778-gratis-radiator-vector
- https://nl.vecteezy.com/vector-kunst/14531368-spreker-icoon-vector-muziek-systeem-audio-doos-geluid-systeem-stereo-spreker-geluid-icoon-vector-geisoleerd-symbool-teken
- https://nl.vecteezy.com/vector-kunst/6817337-pop-art-design-elementen-retro-bliksemschicht
- https://nl.vecteezy.com/vector-kunst/577093-kruk-stoel-zitmeubelen-illustratie
- https://nl.vecteezy.com/vector-kunst/2525492-glas-van-water-plat-ontwerp-geisoleerd-op-blauwe-achtergrond
