# flobb's turnbinds
# versatile turnbinds with customizable turnspeeds for CS2 

This config uses a workaround to add the legacy convars **cl_yawspeed** and **cl_pitchspeed** from Counter-Strike: Source  
back into Counter-Strike 2 using **only console commands**, like in the good ol' days.   
In my opinion using this is better than using external turnbind programs for these reasons:
- far more options to create binds
- visual feedback
- audio feedback
- as easy to use as external software
- ability to change settings ingame using developer console


It has one singular drawback compared to external stuff, which I am going to explain at the end.
>[!NOTE]
>Basically all of this should also work for Counter-Strike: Global Offensive.

## Features:

### cl_yawspeed
Using this config allows the user to change yawspeed by typing **cl_yawspeed_[value] into the developer console**.
>[!NOTE]
>300 is the maximum/default cl_yawspeed value. 1 is the mininum value.

`cl_yawspeed_[300-1]`

### cl_pitchspeed
Using this config allows the user to change pitchspeed by typing **cl_pitchspeed_[value] into the developer console**.
>[!NOTE]
>45 is the maximum/default cl_pitchspeed value. 1 is the mininum value.

`cl_pitchspeed_[45-1]`

### fixed cl_yawspeed/cl_pitchspeed binds
Simply bind as many keys as you want to different cl_yawspeed/cl_pitchspeed commands.

`bind "[key]" "cl_yawspeed_[value]"`

`bind "[key]" "cl_pitchspeed_[value]"`

### toggle/cycle cl_yawspeed/cl_pitchspeed binds
**Cycle between** two, three or four different cl_yawspeed settings using **one single key**.    
**Cycle between** two or three different cl_pitchspeed settings using **one single key**.  
As an added bonus, you can **pair the toggle/cycle keys together with fixed binds** that also influence the cycle alias.  
Also there's an option to **automatically reset** the cl_yawspeed cycle alias when you **reset your stage/run**.

### hold-to-activate cl_yawspeed binds
**Hold-to-activate binds** need to be actively held down to change the cl_yawspeed setting.  
**Not pressing/letting go** of any of these binds **will result in a customizable default cl_yawspeed setting** being activated.  
This config supports up to three hold-to-activate binds, resulting in four different speed settings using them.

### visual feedback
- **hud color** change
- **crosshair color** change
- **both hud and crosshair color** change
- 9 different colors for all of the above

### audio feedback
- **add sounds** to the binds
- 21 different sounds

### full readability
Every single config file has a header explaining it's use. I'm not keeping any secrets here.  
Also I tried my best making this easy to read and understand.

### full customization
In the included `turnbinds\settings.cfg` file I have given many customizations options together with explanations and examples on how to make this **your very own** config.  
If you've tinkered with Counter-Strike configs before and want to add more features for yourself I recommend also checking out the `turnbinds\setup\setup.cfg` file.

## How to use:

1. Download the `.zip` file containing the config files. (right side under "releases")
2. Extract all files from the `.zip` archive.
3. Move folder called `turnbinds` including all of its contents to  
   `[Drive]:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg`
4. Set up the config using the `settings.cfg` in the `turnbinds` folder.
5. To execute the config type `exec turnbinds\exec.cfg` into the developer console. The screenshot shows how it could look after.
6. You can also add `exec turnbinds\exec.cfg` to your `autoexec.cfg`.
<img width="2040" height="1440" alt="20261105122006_1" src="https://github.com/user-attachments/assets/eb13515b-b6db-443e-acdf-5f1b239f2249" />

>[!NOTE]
>Your console will not show the confirmation text on startup, if you use the autoexec method.

## The drawback to using this instead of external turnbinds
Since cl_yawspeed/cl_pitchspeed don't actually exist as convars ingame this config "emulates" those by modifying the turnleft/turnright and turnup/turndown commands respectively.  
The negative effect this has is that you can't modify the turnspeed while it's active. That means for the turnspeed change to take effect you need to briefly stop turning and start turning again.  

### Special Thanks to INSPECTRO from Cybershoke for helping me figure this stuff out.
<img width="4100" height="475" alt="banner_shoke_anthrazit" src="https://github.com/user-attachments/assets/01df9424-7de2-40b0-8295-f4221597aebe" />
If you wanna surf in CS2 I recommend doing so on the Cybershoke servers. They actually playtest stuff in contrast to some other server providers and the leaderboards are very competetive.


## Coming Soon
- Steam Guide
- Russian Language Version





