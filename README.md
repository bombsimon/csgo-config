# Counter-Strike Global offensive configuration

## Launch options
Use following launch options for CS:GO

```
-d3d9ex -nojoy -novid -console -tickrate 128 +exec autoexec
```

## Setup
Assumes bash is installed (Linux Bash W10 or Cygwin).

```
# Remove old files
rm \
  "%STEAMDIR%/steamapps/common/Counter-Strike Global Offensive/csgo/cfg/autoexec.cfg" \
  "%STEAMDIR%/userdata/%STEAM3ID%/730/local/cfg/video.txt

# Copy new files
cp autoexec.cfg "%STEAMDIR%/steamapps/common/Counter-Strike Global Offensive/csgo/cfg/autoexec.cfg"
cp video.txt    "%STEAMDIR%/userdata/%STEAM3ID%/730/local/cfg/video.txt
```

Or just copy them manually, usually `%STEAMDIR` is located at something like
`C:\Program Files (x86)\Steam`.
