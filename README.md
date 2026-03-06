# multisim-ubuntu

 Instalar wine e winetricks
```bash
sudo apt install wine winetricks
```
 Criar prefixo 32bits

```bash
WINEARCH=win32 WINEPREFIX=~/wol/multisim14 winetricks mdac27 jet40 dotnet40 mfc80 vcrun2005 corefonts gdiplus
```
 Configurar para rodar no windows 7:
```bash
WINEARCH=win32 WINEPREFIX=~/wol/multisim14/ winetricks win7
```

Entre na pasta do instalador do Multisim e rode:

```bash
WINEARCH=win32 WINEPREFIX=~/wol/multisim14/ wine setup.exe
```
Espere concluir a instalação.

Para iniciar o Multisim:

```
WINEPREFIX=~/wol/multisim14 wine "C:\Program Files\National Instruments\Circuit Design Suite 14.1\Multisim.exe"
```


``
WINEPREFIX=~/wol/multisim14 wine license.exe
``
