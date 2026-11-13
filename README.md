# flobb's turnbinds
# Turnbinds with customizable turnspeeds for CS2/CSGO

This config uses a workaround to add the legacy convars `cl_yawspeed` and `cl_pitchspeed` from ***Counter-Strike: Source*** to the newer games ***Counter-Strike 2*** and its predecessor ***Counter-Strike: Global Offensive*** <ins>using only console commands</ins>, like in the good ol' days.  
It also adds a multitude of <ins>different binds and customization options</ins>, that allow full use of these lost but not forgotten console commands.

## Features:
### cl_yawspeed
This config allows the user to ***change yawspeed*** by typing `cl_yawspeed_[value]` into the <ins>developer console</ins>.
>[!IMPORTANT]
>`cl_yawspeed` can be set to any value from 1 to 300. Only use whole numbers!

### cl_pitchspeed
This config allows the user to ***change pitchspeed*** by typing `cl_pitchspeed_[value]` into the <ins>developer console</ins>.
>[!IMPORTANT]
>`cl_pitchspeed` can be set to any value from 1 to 45. Only use whole numbers!

### Fixed Binds
Bind as many keys as you want to different cl_yawspeed/cl_pitchspeed commands!  

`bind "[key]" "cl_yawspeed_[value]"`  
`bind "[key]" "cl_pitchspeed_[value]"`

### Toggle/Cycle Binds
- ***Cycle between*** two, three or four different `cl_yawspeed` settings using <ins>one single key</ins>.    
- ***Cycle between*** two or three different `cl_pitchspeed` settings using <ins>one single key</ins>.  
- Ability to ***pair Fixed Binds with the Toggle/Cycle Binds***, so they'll also influence the cycle alias.  
- Option to ***automatically reset*** the `cl_yawspeed` cycle alias everytime you ***reset your stage/run***.

### Hold-to-Activate Binds
***Hold-to-Activate Binds*** <ins>need to be actively held down</ins> to change the `cl_yawspeed` setting.  
<ins>Not pressing/letting go</ins> of any of these binds will result in a ***customizable default*** `cl_yawspeed` setting being activated.  
This config supports ***up to three Hold-to-Activate Binds***, resulting in four different speed settings using them.
>[!WARNING]
>This type of bind ***does not work together with Fixed and/or Toggle/Cylcle Binds***!

### Visual Feedback
- ***hud color*** change
- ***crosshair color*** change
- ***both hud and crosshair color*** change
- 9 different colors for all of the above
>[!NOTE]
>Crosshair color change **does not work in CS:GO***!

### Sound Effects
- ***add sounds*** to the binds
- 21 different sounds

### Full Readability
Every single config file has it's own header explaining it's use. I'm not keeping any secrets here. Also I tried my best making this ***easy to read and understand***.

### Full Customization
In the included `turnbinds\settings.cfg` file, I have given ***many customizations options***, so you can make this ***your very own*** config.  
If you've tinkered with Counter-Strike configs before and want to add more features yourself, I recommend also checking out the `turnbinds\setup\setup.cfg` file.

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

## Why should I use this config and not external turnbind software?
### The advantages
- far more options to create binds
- visual feedback
- sound effects
- ability to change settings ingame using developer console
- this will never get you banned (also works in FACEIT lol)

### The drawback
Since cl_yawspeed/cl_pitchspeed don't actually exist as convars ingame this config "emulates" those by modifying the turnleft/turnright and turnup/turndown commands respectively. The negative effect this has is that you can't modify the turnspeed while it's active. That means for the turnspeed change to take effect you need to briefly stop turning and start turning again.

## Special Thanks to INSPECTRO from Cybershoke for helping me figure some of this stuff out.
<img width="4100" height="475" alt="banner_shoke_anthrazit" src="https://github.com/user-attachments/assets/01df9424-7de2-40b0-8295-f4221597aebe" />
If you wanna surf in CS2 I highly recommend doing so on the Cybershoke servers. They offer a long list of features and actually playtest stuff in contrast to some other server providers. Also the leaderboards are very competetive.

## Coming Soon:
- Steam Guide
- Russian Language Version





