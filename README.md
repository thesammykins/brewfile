# brewfile

This repository contains multiple Brewfiles for setting up different environments on new Macs. Each Brewfile includes taps, brews, casks, and VSCode extensions for various use cases.

## Brewfiles

### brewfile
This is the main Brewfile for general-purpose use. It includes essential tools and applications.

**Usage:**
1. Ensure Homebrew is installed on your Mac. If not, install it using the following command:
   ```
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)" && brew install git
   ```
   
3. Run the following to pulldown this repo to your ~/Documents folder

   ```
   git clone https://github.com/thesammykins/brewfile.git ~/Documents/brewfile
   ```

Run the following command to install the contents of the Brewfile:

```
brew bundle --file=brewfile
```

**brewfile-per**
This Brewfile includes personal applications and settings, as well as Mac App Store applications.
Usage:

1. Make sure you have Homebrew installed as mentioned above.
2. Run the following command to install the contents of the Brewfile:

```
brew bundle --file=brewfile-per
```
**brewfile-laptop**
This Brewfile is specifically tailored for setting up a laptop environment, mainly for new work devices.

Usage:

Verify that Homebrew is installed.

Run the following command to install the contents of the Brewfile:

```
brew bundle --file=brewfile-laptop
```
**Notes**
Each Brewfile includes taps, brews, casks, and VSCode extensions that are commonly used.

The brewfile-per and brewfile-laptop include additional tools and applications specific to personal use and laptop setup, respectively.
You can customize these Brewfiles by adding or removing entries as needed.

**Troubleshooting**
If for some reason these aren't working properly, try the following steps:

**Ensure Homebrew is up-to-date by running:**
```
brew update
```
Check for any issues with Homebrew by running:
```
brew doctor
```
If an application fails to install, try installing it individually to identify the problem:
```
brew install <application>
```
