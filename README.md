# ukcc13

This repository contains all the resources for United Kingdom Community Cup 13 osu!(lazer) tournament client. 

For information on how to setup and use the osu! lazer tournament client, see [D I O's YouTube tutorial](https://www.youtube.com/watch?v=l_nFynsxKRs&t=371s&pp=ygUbb3N1IGxhemVyIHRvdXJuYW1lbnQgY2xpZW50) for a comprehensive overview. 

## How to use this repository

1. Navigate to the osu!(lazer) tournament folder, usually `C:\Users\<username>\AppData\Roaming\osu\tournaments`, and clone this repository at this location. Alternatively, download this repository as a .zip and extract to a folder in the same location mentioned.
 
### Lazer Setup

1. In the osu!(lazer) tournament client on the Setup page, select `ukcc13` from the Current Tournament drop down.

### OBS Setup

1. Install the [obs-plugin-countdown](https://github.com/ashmanix/obs-plugin-countdown/releases/tag/2.0.11).
2. Install the [Hanken Grotesk font](https://fonts.google.com/specimen/Hanken+Grotesk).
3. Relaunch OBS if you had it open, goto `Scene Collection`->`Import`. On the window that just opened, click the `...` and select the `UKCC_13_Gameplay.json` file at the location of this repository. Click `import`.
4. Switch to the imported Scene Collection by going to `Scene Collection`->`UKCC_13_Gameplay`

   - If you get the missing files window, click `...` in the New File box, navigate to the `Videos` folder of this repository and choose the `obstitle.mp4` file and then click `Apply`.

#### Things you may ask
- If the font for the timer is not correct, in the timer properties select the font `Hanken Grotesk ExtraBold` with the Font style as `ExtraBold`.
- If you can't see the Countdown Timer pane, goto `Docks`->`Countdown Timers`. This should open a new window which you can dock wherever you want in your OBS layout.
- To link the Countdown Timer to the onscreen timer, in the Countdown Timers panel click the `⚙️`. In this new window, set the Source to `Timer` and untick the `Days` and `Hours` checkboxes on the Display Format. Click `Apply` then in the Countdown Timers panel click on `🔄️` to reload and set the timer.

**If you have any further questions, please ask in the discord server and someone should be able to help.**

## Thanks

- All videos created by [kaetwo](https://linktr.ee/o.kae)
- Mod icons originally by [-makoto yuki](https://osu.ppy.sh/community/forums/topics/265638?n=1), modified by myself. 
