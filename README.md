# windows_powershell

A place to edit powershell with oh-my-posh

- Step 1: [https://github.com/microsoft/cascadia-code/releases]
- Step 2: If you using zsh with powerline you will need DejaVu fonts [https://dejavu-fonts.github.io/Download.html]
- Step 3: [https://docs.microsoft.com/en-us/windows/terminal/tutorials/powerline-setup]
- Step 4: Add theme file: funny.omp.json, to location: C:\Users\USER\Documents\WindowsPowerShell\Modules\oh-my-posh\3.135.1\themes, or whereever themes are located. Searching for "agnoster.omp.json" will help.
- Step 5: Run notpad $PROFILE -> Yes create file add lines:
```bash
Import-Module posh-git
Import-Module oh-my-posh
Set-PoshPrompt -Theme funny
```
or whatever theme you prefer.
