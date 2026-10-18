# win-config
windows installation overview by Whispy: https://wispydocs.pages.dev/windows/

### ricing-tools: 

- <a href="https://github.com/glzr-io/glazewm">GlazeWM</a>/ i3 tiling wm like

- <a href="https://github.com/LGUG2Z/komorebi">komorebi</a>/ bspwm tiling-wm like
  
- <a href="https://yasb.dev/">YASB Reborn</a>/ highly customizable bar

- <a href="https://github.com/amnweb/thide">Taskbar Hide</a>/ hide/show the taskbar

- <a href="https://flowlauncher.com/">Flow Launcher</a>/ macOS spotlight like, supports community-made plugins

- <a href="https://www.voidtools.com/">Everything Search</a>/ locate files and folders instantly

- <a href="https://nilesoft.org/">Nilesoft Shell</a>/ highly customizable context menu manager

- <a href="https://github.com/Open-Shell/Open-Shell-Menu">Open-Shell</a>/ classic windows start menu like, has the ability to disable "Win" key

- <a href="https://ohmyposh.dev/">oh-my-posh</a>/ shell customization

- <a href="https://github.com/aristocratos/btop4win">btop4win++</a>/ resources monitor in cli

- <a href="https://github.com/fastfetch-cli/fastfetch">fastfetch</a>/ system information tool in cli/

- <a href="https://github.com/karlstav/cava">cava</a>/ audio visualizer in cli

- <a href="https://github.com/cowboy8625/rusty-rain">rusty-rain</a>/ matrix rain in cli

<hr>

### winget install
    ``` glazewm ```
    winget install glzr-io.glazewm

    ``` komorebi ```
    Set-ItemProperty 'HKLM:\SYSTEM\CurrentControlSet\Control\FileSystem' -Name 'LongPathsEnabled' -Value 1
    winget install LGUG2Z.komorebi
    winget install LGUG2Z.whkd

    ``` misc ```
    winget install AmN.yasb 
    winget install Flow-Launcher.Flow-Launcher
    winget install voidtools.Everything
    winget install Nilesoft.Shell
    winget install Open-Shell.Open-Shell-Menu

    ``` cli ```
    winget install aristocratos.btop4win
    winget install Fastfetch-cli.Fastfetch
    winget install karlstav.cava
    winget install cowboy8625.rusty-rain

    ``` shell ```
    winget install JanDeDobbeleer.OhMyPosh --source winget
    oh-my-posh font install meslo

<hr>

### yasb.config preview
<s><h4>pr31yi5jp3bgnhuu (unmaintained) <i>(forked from i3 WinBars/Louis047)</i></h4>

<b>I. jtwsq4dw</b> <i>(aka Light)</i>

<img src="https://github.com/user-attachments/assets/d0c1ca4e-ba5b-466b-8f27-1af68fb52986" width="49%"></img>
<img src="https://github.com/user-attachments/assets/b4eff597-937c-4c66-b9b3-ed2600580798" width="49%"></img> 
<img src="https://github.com/user-attachments/assets/c719a2df-e15b-4f8a-a5aa-140885215eb2" width="98%"/>

<b>II. kpwgnhuo</b> <i>(aka Sharp)</i>

<img width="98%" src="https://github.com/user-attachments/assets/a82ea1a9-809c-4f0f-8d9b-a24d5b4251ab" />

<b>III. qtosg4d3p7zy</b> <i>(aka Tachyon)</i>

<img width="49%" src="https://github.com/user-attachments/assets/6fb73039-31d2-46e8-8b69-4df8332a7512" />
<img width="49%" src="https://github.com/user-attachments/assets/a4d850e8-6f6c-4d4c-a50e-1ffe5fdd30ee" />

</s>


<h4>kpwg1auipiwo <i>(forked from Shibumi/MrDLingters)</i></h4>

<img width="98%" src="https://github.com/user-attachments/assets/2df0b11c-ce0a-4b82-88ef-731ae6dcb18f" />

<hr>

### Usage

<i>glazewm</i> 

`` C:\Users\%username%\.glzr\glazewm\config.yaml ``

<i>komorebi</i>

```
C:\Users\%username%\komorebi.json
C:\Users\%username%\.config\whkdrc
```

<i>yasb</i>

```
C:\Users\%username%\.config\yasb\config.yaml
C:\Users\%username%\.config\yasb\styles.css
```

<hr>

### wallpaper used in preview
- https://steamcommunity.com/sharedfiles/filedetails/?id=915680280
  
- https://steamcommunity.com/sharedfiles/filedetails/?id=3175692671
  
- https://steamcommunity.com/sharedfiles/filedetails/?id=1883906261

- https://steamcommunity.com/sharedfiles/filedetails/?id=845514446
