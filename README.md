# Omega-theme-template
Template theme for [Omega-Themes](https://github.com/Omega-Numworks/Omega-Themes).

This is a theme based on [Nord](https://www.nordtheme.com/)

## Download
On the Omega repo execute the python script `themes/theme_manager.py` with the argument `--download <github_user>/<repo_name>/<branch>`  
for this repo it would be ```$ python themes/theme_manager.py --download  NilsPonsard/Omega-theme-template/master ```



## File `theme.json` :
At the root of the repo, the file is defining the color palette and the icon set used ( line 3 : `"icons": "omega_nord",`), this icon set must be : 
- The name of an official icon set, these are actually :    
    - `epislon_light`
    - `omega_dark`
    - `omega_light`
- Or a "path-like" string pointing to a github repo, formatted this way :   
`<github_user>/<repo_name>/<branch>/<icons_folder>`   
here this string is :  `NilsPonsard/Omega-Themes/master/icons`
- Or the name of a folder in the `themes/icons/` folder
## Folder `icons` : 
Contains the icon set of your theme, optionnal
