#### ARCH SET_UP GUIDE ####

# What does a typical arch system gives you?
  | **Component**           | **Description**                                   |
  |-------------------------|---------------------------------------------------|
  | **Kernel**              | The core of the OS, responsible for hardware interaction. |
  | **Base System**         | Essential utilities like `coreutils`, `bash`, `filesystem`, etc. |
  | **Pacman**              | Package manager for installing and managing software. |
  | **Systemd**             | System and service manager.                      |
  | **NetworkManager**      | Manages network connections.                     |
  | **Logind**              | Manages user logins and sessions.                |
  | **grub**                | Bootloader for booting the system.               |
  | **FSTAB**               | File system table for mounting partitions.       |
  | **Initramfs**           | Initial RAM filesystem for booting.              |
  | **Locale**              | Default language settings.                       |
  | **Timezone**            | Default system time zone.                        |
  | **User**                | Default user account created during installation.|
  | **Shell**               | Default shell, usually `bash`.                   |
  | **Vim**                 | Text editor installed by default.                |

# What is needed to be installed?
Disk mounting tools (fstab, maybe ntfs-3g for external drives)
Basic utilities (curl, wget, git, tar, unzip)
Optional: firewall (ufw, firewalld, nftables, Fail2Ban[for_SSH_protection]), vpn(wireguard-tools [very light one and coustomizable via /etc/wireguard.conf], openvpn, kill_switch)
Optional: audio/video support (pulseaudio, brightnessctl, etc.), file_manager(dolphin or you can avoid), terminal(kitty), .img,.jpg,.png or other files viewer 
Optional: hyprland/wayland(lightweight environent), librewolf(for browsing securely with NoScript and uBlock Origin)
Optional: hyprshot, emoji-cli, obs-studio


Here’s the overall summary in paragraph form:

You want to set up a customized Arch Linux environment, using **TTY3** for login instead of any graphical login manager, with a clean and minimalist approach. Your setup includes **Waybar** to show the **Arch logo** at the top left, a graphical **RAM usage bar** similar to Kali Linux, and the **time for multiple timezones**. You also want **Kitty** terminal to launch with **two split panes**, one running **Aquarium** (a fish tank simulation) and the other showing **Neofetch**, and all of this should start automatically on login via **systemd**. For **TTY3**, you aim to customize the login greeting and terminal prompt using **ASCII art** and custom messages, adjusting the **bash prompt** for readability. Regarding security, you're setting up a **VPN** and configuring strong firewall rules to secure your browsing. You’ve chosen **`lsd`** (LSDeluxe) or **`exa`** as replacements for the `ls` command to display **icons** and **colors** directly in the terminal, making file navigation feel like a file manager without needing a graphical one. Kitty is configured to use **Nerd Fonts** for icon support, ensuring a smooth visual experience with file types and icons displayed in your terminal. Everything is designed for minimalism, efficiency, and security, focusing on providing a complete terminal-based experience without relying on GUI-based tools.



For configuring DNS "/etc/resolv.conf" better prefer safer ones.
NOTE :~~dhcpcd is another important file/command in pacman to set your ip incase networkmanager of iwd don't do it for you else your network connection will show error.











# Wallpaper-arch
  The wallpaper I like to use in my arch linux.
