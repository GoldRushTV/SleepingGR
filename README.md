**Dissclamer** 

It is a Vencore QuickCSS

It was made by vending.machine (name from Discord) on Discord and change by me

If you are in the Vencore(libVencore) Discord server here is the Link

https://discord.com/channels/1015060230222131221/1028106818368589824/1044717748778971157

![I_need_space](https://github.com/GoldRushTV/SleepingGR/blob/main/images/blank.png)		


Image was made by adryd325 (name from Github) and change by me

here is the original image

https://github.com/adryd325/oneko.js/blob/main/oneko.gif

![neko](https://raw.githubusercontent.com/adryd325/oneko.js/refs/heads/main/oneko.gif)		                             

		              
![I_need_space](https://github.com/GoldRushTV/SleepingGR/blob/main/images/blank.png)		               
               
		
                
This is how my version looks like

![image1](https://github.com/GoldRushTV/SleepingGR/blob/main/images/image1.png)

This is the code if you want it too

```CSS
[class^="channelTextArea"]::after {
    content: "";
    width: 32px;
    height: 32px;
    bottom: calc(100% - 3px); /* Mess with the - 3px to change its vertical position */
    right: 0px; /* Switch this from right to left to put it on the left side, or increase/decrease to change its position */
    position: absolute;
    image-rendering: pixelated;
    pointer-events: none;
    background-image: url("https://raw.githubusercontent.com/GoldRushReal/SleepingGR/refs/heads/main/GR.gif");
    animation: oneko 2s infinite; /* change 2s to make the animation slower/faster */
}

@keyframes oneko {
    /*
    if you open the background image in ur browser, you will see that it has way more frames
    so if you want, you could make ur own keyframes for a different animation
    the top left frame is 0 0, second top row is -32 0, second row second is -32 -32 and so on
    the ...00001% makes it so that there's no transition between the frames, so if you wanted say 3 frames, you'd do 0%, 33.3%; 33.30001%, 66.6%; 66.60001%, 100%
    */
    0%, 50% {
        background-position: -64px 0;
    }
    50.0001%, 100% {
        background-position: -64px -32px;
    }
}
```

note:
this was once on the accound ![GoldRushReal](https://github.com/GoldRushReal), but I am not using this accound anymore.
