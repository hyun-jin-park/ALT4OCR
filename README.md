### ALT4OCR
- updated Alp's Labeling tool for OCR(character annotation)
- Original ALT is here (https://alpslabel.wordpress.com/2017/01/26/alt/)
### Install 
1. Install ImageJ (https://imagej.nih.gov/ij/download.html) and start 
2. Install ActionBar Plugin (https://imagejdocu.tudor.lu/doku.php?id=plugin:utilities:action_bar:start)
3. Copy this repository under Plugin>ActionBar folder 
   - If there is not ActionBar folder under ImageJ>Plugins, create it    
4. register this actionbar macro as auto run 
  4.1 Click Edit > Options > Startup 
  4.2 Paste this command  
`
     run("Action Bar","/plugins/ActionBar/ALT.txt");  
`
5. restart ImageJ 
