# Sci-Fi3 - A preconfigured i3 style/design kit  


## Requirements  

i3-wm
Polybar
Konsole  
  

## Instructions

TODO: Add auto install shell script

Clone the repo  
```git clone https://github.com/AlmightyFloppyFish/Sci-Fi3 && cd Sci-Fi3```

Set Sci-Fi3 i3 config as used config  
```mkdir ~/.i3/ && mv ./i3-config ~/.i3/config```

Set polybar config as used config  
```mkdir -p ~/.config/scibar/
mv polybar_config ~/.config/scibar/config
mv startpolybar.sh ~/.config/scibar/launch.sh```  

Set bashrc as used .bashrc (Optional | If you skip this step you'll have to enable polybar manually)
```mv ~/.bashrc ~/.bashrc.bak && mv bashrc ~/.bashrc```  

Install konsole profile/colors
```mv Main.colorscheme ~/.local/share/konsole/
mv "SciFi3.profile" ~/.local/share/konsole/```
Select SciFi3 as profile in Konsole settings

