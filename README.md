# pyinstaller-cheat-sheet

1. Allows to install everything into one file instead of a scattered directory.
   ```
   pyinstaller <filename> --onefile
   ```
3.
   Installs the everything from an imported package. Helps prevent import errors.
   ```
   pyinstaller --collect-all <package-name> <filename>
   ```
5. 
   Removes the console.
   ```
   pyinstaller --noconsole <filename>
   ```
<hr>

### Full list of options and documentation [here.](https://pyinstaller.org/en/stable/usage.html#options)
