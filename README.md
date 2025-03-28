# Obsidian Syncer

This is a ZSH script that automates the process of syncing an Obsidian vault with a remote Git repository.

## Features

- Pulls the latest changes from the remote repository
- Adds all changes to the local repository
- Commits the changes with a predefined commit message
- Pushes the changes to the remote repository
- Sends a desktop notification with the details of the last change
- Handles errors and provides a detailed error message if any issues occur

## Usage

1. Clone the repository to your local machine.
2. Update the following variables in the script:
   - `git_message`: The commit message to be used when committing changes.
   - `local_path`: The path to your Obsidian vault.
   - `icon_path`: The path to the Obsidian icon used in the desktop notification.
3. Run the script using the following command:

   ```bash
   zsh obsidian-syncer.sh
   ```

   This will automatically sync your Obsidian vault with the remote Git repository and send a desktop notification with the details of the last change.
## Dependencies
- ZSH shell
- notify-send command (part of the libnotify-bin package on Ubuntu/Debian)
- Git

