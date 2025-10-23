# latex_tutorial
## How to add multiple languages to latex editor overleaf
1. Menu -> Compiler -> (change it to XeLaTeX)
2. Add in the header 
     \usepackage{polyglossia} 
     \setmainfont{Times New Roman}  
     \newfontface\greekfont[Script=Greek]{Times New Roman}
     \setdefaultlanguage{greek} 
     \setotherlanguage{english}

Now you can write in both greek and english
