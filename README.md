# Lock Screen Script with Blurred Background and Custom Indicator

This script captures a screenshot of your current screen, applies a blur effect, overlays an icon, and then locks the screen using `i3lock-color`. The script will remove the screenshot once the screen is unlocked.

## Prerequisites

Make sure you have the following dependencies installed:

- `scrot` for taking screenshots
- `imagemagick` for image manipulation
- `i3lock-color` for locking the screen with custom options

## Installation

### Install Dependencies

#### Debian-based Systems (e.g., Ubuntu)

Open a terminal and run:

```bash
sudo apt update
sudo apt install scrot imagemagick
```
#### Arch-based Systems 

Open a terminal and run:

```bash
sudo pacman -S scrot imagemagick
```


### Clone the script
```bash
git clone  https://github.com/Mohamed-Rebbouh/i3lock-blur-current-screen.git
```
note :
Dont'forget Make the script executable after you navigate to this dir run 
```
chmod +x lock.sh
```