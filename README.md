# Login-screen-themes
Tested on Ubuntu 20.04



## INSTALLATION
First, you will need to install libglib2.0-dev-bin with 

     sudo apt install libglib2.0-dev-bin

Then, you can download the script with the command below:

    wget github.com/thiggy01/change-gdm-background/raw/master/change-gdm-background
    
And set it as an executable with 

    chmod +x change-gdm-background

## USAGE
Run the script with root privileges such as sudo ./change-gdm-background /path/image.(clr+l for copy image directory)
such as : 
          
     sudo ./change-gdm-background /home/pakhi/Downloads/Wallpaper/image.jpg

If you see a message login image sucessfully changed, then, when you restart gdm or reboot your computer, your gdm background should be covered with the image you selected.

You can restore your original gdm theme any time with 
    
    sudo ./change-gdm-background --restore.

## CHANGE COLOR
Now you can change that annoying purple color to any color you like. Just type 

    sudo ./change-gdm-background \#yourhexcode and voilá, you changed it. 
    
Your color hex format should be of six characters like \#407294 or three characters like \#6ac.
