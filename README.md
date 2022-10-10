# A small explanation of how to use this tool:
<b>
This is the bolo sword custom heirloom <b>
 
1. Extract this tool into a folder somewhere. <b>

2. Drag and drop Common_sdk.json onto RePak.exe <b>
  
3. When you do this you will see a cmd prompt for a brief second and there will be 2 files inside of the build folder. <b>
  
4. Drag those files into the paks/Win64 Folder in your R5Reloaded directory <b>
  
## Adding custom textures:

[Texture Info](https://github.com/MCLOLSMAN/common_sdk.rpak/blob/main/Texture%2C%20material%20info.txt) <b>

Make sure that the textures are IN ORDER when adding custom ones.
Repak is very picky with the DDS texture files. Make sure not to edit them with Gimp, Use paint.net.
  

slot1 _col <b>
 
slot2 _nml <b>
 
slot3 _gls/_exp <b>
 
slot4 _spc <b>
 
slot5 _ilm <b>
 
slot6 _ao <b>
 
slot7 _cav/cvt <b>
 
slot8 _opa <b>

## Adding custom models

Make sure that models are extracted as .RMDL and a ptov. Must be placed in the coresponding folder found in Legion+ <b>

An example would be ""mdl/Weapons/vinson/ptpov_vinson.rmdl""


## Animations
The animations have to be ones found in r5. <b>
They do not need to be added anywhere, just put the path in the json. <b>
