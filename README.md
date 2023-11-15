# Antarctic Oh My Posh
Antarctic for Oh My Posh.

## Installation 
1. Download and install [Nerd Fonts](https://www.nerdfonts.com/font-downloads). By default, it uses the [Hack Font](https://www.programmingfonts.org/#hack).
2. Add the following line at the top of your Microsoft.PowerShell_profile.ps1 (If you don't have that, follow this [guide](https://lazyadmin.nl/powershell/powershell-profile/)).

    ```pwsh
    oh-my-posh init pwsh --config "$env:POSH_THEMES_PATH/antarctic.omp.json" | Invoke-Expression
    ```

3. Download the `antarctic.omp.json` file.
4. Paste in `C:\Users\*username*\AppData\Local\Programs\oh-my-posh\themes`.
5. Restart your terminal and done.

## Oh My Posh + Windows Terminal
If you are using the Windows Terminal and want to integrate Antarctic for Oh My Posh, follow this instructions.

Replace the contents of `"defaults"`
```pwsh
    "profiles": 
    {
        "defaults": {},
```
with the contents of `windows-terminal-theme-OhMyPosh.json`.

