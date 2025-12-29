# Description
simple bash program to switch between different wireguard configs.
requires sudo (for wireguard)

# Features
- Easily switch between different wireguard configs from `/etc/wireguard/configs` directory
- Show current IP address, location and config name
- CLI interface provided by dialog
  
# Dependencies
- wg-quick
- curl
- dialog

# Additional tool
- `whatismyip` to check the current IP of the client device

# Usage
First set executable permissions with `chmod +x wg-switch` and run `./wg-switch`. Or, copy the files from the scripts directory to a valid $PATH, and set permissions and use from terminal.
