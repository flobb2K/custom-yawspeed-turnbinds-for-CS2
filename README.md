# flobb-s-turnbinds
# Turnbind config for Counter-Strike 2/Counter-Strike: Global Offensive

This config uses a workaround to add the legacy convars cl_yawspeed and cl_pitchspeed from Counter-Strike: Source  
back into Counter-Strike 2 using only console commands **like in the good ol' days**.  
In my opinion this can be better than most external turnbind programs because of the extra features/customization options.  
It has one singular drawback compared to external stuff which im going to explain at the end.
>[!NOTE]
>Most of this should also work for Counter-Strike: Global Offensive.

## Features:

### cl_yawspeed
Using this config allows the user to change yawspeed by typing **cl_yawspeed_[number] into console**.
>[!NOTE]
>300 is the maximum/default yawspeed value. 1 is the mininum value.

`cl_yawspeed_[300-1]`

### cl_pitchspeed
Using this config allows the user to change pitchspeed by typing **cl_pitchspeed_[number] into console**.
>[!NOTE]
>45 is the maximum/default pitchspeed value. 1 is the mininum value.

`cl_pitchspeed_[45-1]`

### fixed binds
Simply bind as many keys as you want to different cl_yawspeed commands.

`bind "[key]" "cl_yawspeed_[number]"`

### cycle keys
**Cycle between** two, three or four different yawspeed settings using **one single key**.
As an added bonus you can **pair the cycle key with fixed binds** that also influence the cycle alias.
Also there's an option to **automatically reset** the cycle alias when you **reset your stage/run**.

### "speed key" 
This type of bind can change between two different yawspeeds. One of them is active while the "speed key" is **not being pressed**.
The other setting will activate while **holding down** the "speed key".

### visual feedback
- **hud color** change
- **crosshair color** change
- **both hud and crosshair color** change
- 9 different colors for all of the above

### audio feedback
- **add sounds** to the binds
- 3 different sounds

### full readability
Every single config file has a header explaining it's use. I'm not keeping any secrets here.  
Also I tried my best making this easy to read and understand.

### full customization
In the included `turnbinds\settings.cfg` file I have given many customizations options together with explanations and examples on how to make this **your very own** config.  
If you've tinkered with Counter-Strike configs before and want to add more features for yourself I recommend also checking out the `turnbinds\setup\setup.cfg` file.

## How to use:

1. Download the `.zip` file containing the config files.
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





