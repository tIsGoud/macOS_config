# macOS config

My default settings for macOS.

## macos_config

My personal settings based on [Jeff Geerling's dotfiles](https://github.com/geerlingguy/dotfiles).

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

Run the script and the default settings are saved in `before.txt`, it waits for user input to continue.

Leave the terminal session and make your change.

Return to the terminal session and press the return-key to save the changed "defaults" in `after.txt`.

Use a "diff" tool to view the differences.