settings.json is used for vs code settings. Its path is: %AppData%/code/User

simple.ahk is script used in autorun to run commands by keys. Its path is: %AppData%\Microsoft\Windows\Start Menu\Programs\Startup

To get a list of vs code extensions: `code --list-extensions > extensions.txt`

To install extensions: `cat extensions.txt | xargs -L 1 code --install-extension`
