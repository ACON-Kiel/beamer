# Beamer template
for presentations from the Chair of Automatic Control at the Kiel University in LaTeX (beamer)

### Installation guide
* Ubuntu (TEX Live)
  * Clone/Download the repository into your local _TEXMFHOME_-folder, which is normally located at _$HOME/texmf/_. Use the subfolder _tex/latex/_ according to the TeX directory structure.
  * Update the database by running the _mktexlsr_ command in your command line.

* Windows
  * **TEX Live**:
      Clone/Download the repository into your local _TEXMFHOME_-folder, which is normally located at _%USERPROFILE%/texmf/_. Use the subfolder _tex/latex/_ according to the TeX directory structure.

  * **MiKTeX**:
    * Clone/Download the repository into your local _localtexmf_ folder. This folder does not necessarily exist and can be added in the **MiKTeX settings** program (for example _%USERPROFILE%/localtexmf/_). Use the subfolder _tex/latex/_ according to the TeX directory structure.
    * Update the database using the _Refresh FNDB_ button in the **MiKTeX settings** program.

* OSX (MacTeX/TEX Live)
  * Clone/Download the repository into your local _TEXMFHOME_-folder, which is normally located at _~/texmf/_. Use the subfolder _tex/latex/_ according to the TeX directory structure.
  * Update the database using the _texhash_ command.

### Different themes
* Student
  * Student version of the template
  * Usage with:
	* `\usetheme[studenteng]{ACON}` for the english version
	* `\usetheme[student]{ACON}` for the german version
* Staff
  * Staff version of the template
  * Usage with:
	* `\usetheme{ACON}` for the english version
	* `\usetheme[german]{ACON}` for the german version

  
### Test/Example
In order to test the example switch 
