# Legacy11
### Create a Windows 11 Installer USB for Legacy BIOS'

---

## Instructions:

1. Open a separate computer running windows 10/11

2. Acquire a <a href="https://github.com/MineFartS/tiny11">tiny11</a> image.

3. Mount the tiny11 ISO using Windows Explorer.

4. Insert a USB Drive with at least 8GB

5. Run the builder script:
```powershell
irm https://raw.githubusercontent.com/MineFartS/legacy11/refs/heads/main/build.ps1 | iex
``` 

6. Follow the instructions given and wait for script to complete.

7. Unplug the flash drive from your computer and plug it into the target computer

8. Boot the target computer from the flash drive

9. Navigate through the windows installer *(It uses the windows 10 installer, but it will install windows 11)*

10. Follow the onscreen instructions to install windows and wait for the installation to complete