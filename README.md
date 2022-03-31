Teclado Magic Keyboard Apple PT-PT (Português de Portugal) para Windows (sem admin rights)
=============================================
![image](https://user-images.githubusercontent.com/3984909/160826955-056b9cda-33bc-4d26-b074-e18a3450c7f9.png)

This [AutoHotkey](https://www.autohotkey.com/) configuration file makes usual keyboard shortcuts work with an Apple keyboard on Windows. 

It has been further amended to be suited for the Mac Magic Keyboard layout of Portuguese from Portugal.

If it's not working for applications running with admin permissions, it might be the problem that AHK is not, see [this question on StackOverflow](https://stackoverflow.com/a/8457852/723769).

Installation
------------

- Download [AutoHotkey](https://www.autohotkey.com/download/) ZIP version (version `1.1.*`) and extract it preferably to `$HOME\AppData\Local\Programs\AutoHotkey`
- Run the `MacKeyboard.ahk` file (save the file as UTF8 with BOM)
- Put the `MacKeyboard.ahk` file or a shortcut to the file in your Autostart folder to run it automatically on startup.
- You must also define in `Typing Settings`-> `Advanced Keyboard Settings` a PT-PT keyboard layout.

![image](https://user-images.githubusercontent.com/3984909/160840610-08662af6-8de9-4adf-bbb8-07df4eccac57.png)
