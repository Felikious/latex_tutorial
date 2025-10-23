# latex_tutorial
## How to add multiple languages to latex editor overleaf
1. Menu -> Compiler -> (change it to XeLaTeX)
2. Add in the header 
     1. \usepackage{polyglossia} 
     2. \setmainfont{Times New Roman}  
     3. \newfontface\greekfont[Script=Greek]{Times New Roman}
     4. \setdefaultlanguage{greek} 
     5. \setotherlanguage{english}

##Now you can write in both greek and english
