# macOS config

My default settings for macOS.

Based on the 'dotFiles' from Jeff Geerling.

## macos_config

My personal settings based on the Jeff Geerling's file.

Differences:
- Some personal preferences.
- Safari
    - Safari Developer settings working in Sonoma
- Spotlight
    - Disable new volume indexing does not work in Sonoma.
- Mail
    - Group and sort conversations.
- TextEdit
    - Disable RichText.
    - UTF-8 encoding.
- Terminal, disable "last login" and MOTD
- Machine name, edit the file to provide your name

## setMachineName

A script to set the machine name.

## defaults_test

A script to test "defaults".

Default settings are stored in `before.txt`, it waits for user input to continue.

In that time make your change, press <return> and use a "diff" tool to view the differences.