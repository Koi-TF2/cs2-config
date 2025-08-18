# Koi's CS2 Config

To install:

1) Drag the `autoexec.cfg` file into the `\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg\` folder

2) Set the preferred advanced launch options via Steam library CS2 game Properties -> General tab:

Windowed Borderless 4:3 res (recommended stretched to screen + change m_yaw to match - the config uses a 4:3 stretched m_yaw by default):
- LAUNCH GAME ONCE AND SET MANUALLY. THIS MODE WITH RESOLUTION LAUNCH OPTIONS NOT (YET) SUPPORTED.
- SETTINGS -> VIDEO -> VIDEO -> CHOOSE Display Mode "FULLSCREEN WINDOWED", Aspect Ratio "NORMAL 4:3", Resolution "1440X1080"
- THEN USE: `-refresh 240 -novid -console -nojoy -nosteamcontroller -nohltv -noquicktime -precachefontchars -useforcedmparms -noforcemaccel -noforcemspd -forcenovsync`

Windowed Borderless 16:9 res:

`-windowed -w 1920 -h 1080 -noborder -refresh 240 -novid -console -nojoy -nosteamcontroller -nohltv -noquicktime -precachefontchars -useforcedmparms -noforcemaccel -noforcemspd -forcenovsync`

Fullscreen 4:3 res (recommended stretched to screen + change m_yaw to match - the config uses a 4:3 stretched m_yaw by default):

`-fullscreen -w 1440 -h 1080 -refresh 240 -novid -console -nojoy -nosteamcontroller -nohltv -noquicktime -precachefontchars -useforcedmparms -noforcemaccel -noforcemspd -forcenovsync`

Fullscreen 16:9 res:

`-fullscreen -w 1920 -h 1080 -refresh 240 -novid -console -nojoy -nosteamcontroller -nohltv -noquicktime -precachefontchars -useforcedmparms -noforcemaccel -noforcemspd -forcenovsync`
