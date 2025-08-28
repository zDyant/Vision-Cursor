## Vision Cursor, a minimalist cursor inspired by Windows 11 style

![Preview](./assets/preview.png)

# Installation Guide:

<details>
<summary>
    Windows
</summary>
  
  Open .zip file with WinRAR or 7Zip.

  Move folder with files on desktop or wherever you want.

  Open it, right click on Install.inf file and select the Install option.

  Go to [Control Panel > Mouse > Pointers] or [Settings > Personalization > Themes > Mouse Cursor > Pointers]

  Select the Cursor in the Scheme menu.

</details>

<details>
<summary>
    Linux 
</summary>
    
extract `vision.cursor.tar.gz`

```bash
tar -xvf vision.cursor.tar.gz
```
Move the extracted folder to `icons` folder, change `<color>` to `black` or `white`
```bash
mv Vision-<color> ~/.icons/        	       # Install to local users
sudo mv Vision-<color> /usr/share/icons/      # Install to all users
```

Now, change your cursor using Gnome, or other manager

</details>

# Uninstallation Guide
<details>
 <summary>
    Linux
 </summary>

Uninstallation
```bash
rm ~/.icons/visioncursor<color>                  # Remove from local users
sudo rm /usr/share/icons/visioncursor<color>     # Remove from all users
```

</details>
