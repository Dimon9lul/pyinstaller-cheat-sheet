# pyinstaller-cheat-sheet

1. ```
   pyinstaller <filename> --onefile
   ```
   Allows to install everything into one file instead of a scattered directory.
2. ```
   pyinstaller --collect-all <package-name> <filename>
   ```
   Installs the whole package. Helps prevent import errors.
3. ```
   pyinstaller --noconsole <filename>
   ```
   Removes the console.
   
<hr>

### Full list of options and documentation [here.](https://pyinstaller.org/en/stable/usage.html#options)
