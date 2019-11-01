# Counter-Strike Global offensive configuration

## Launch options

Use following launch options for CS:GO

```text
-tickrate 128
```

## Setup

Copy configuration manually, usually `%STEAMDIR` is located at something like
`C:\Program Files (x86)\Steam`.

```text
cp *.cfg     "%STEAMDIR%/steamapps/common/Counter-Strike Global Offensive/csgo/cfg/autoexec.cfg"
cp video.txt "%STEAMDIR%/userdata/%STEAM3ID%/730/local/cfg/video.txt"
```

## Practice

The practice config is useful to practice grenades. The configuration is
inspired (or you might say copied) from [Tobys
CS](https://www.tobyscs.com/csgo-practice-config/). To load the practice config
just start a local game with bod and run `exec practice`.  The useful binds for
pracies is already added in the `autoexec.cfg`.

| Key | Binding               |
| --- | --------------------- |
| n   | noclip                |
| l   | cast_ray              |
| v   | give for each grenade |
