# multisim-ubuntu

```bash
sudo apt install wine winetricks
```

```bash
WINEARCH=win32 WINEPREFIX=~/wol/multisim14 winetricks mdac27 jet40 dotnet40 mfc80 vcrun2005 corefonts gdiplus
```

```bash
WINEARCH=win32 WINEPREFIX=~/wol/multisim14/ winetricks win7
```

Entre na pasta do Multisim e rode:

```bash
WINEARCH=win32 WINEPREFIX=~/wol/multisim14/ wine setup.exe
```

Iniciar o Multisim:

```
WINEPREFIX=~/wol/multisim14 wine "C:\Program Files\National Instruments\Circuit Design Suite 14.1\Multisim.exe"
```
