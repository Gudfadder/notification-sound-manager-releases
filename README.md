# Notification Sound Manager
<br>
<img width="852" height="524" alt="image" src="https://github.com/user-attachments/assets/bcec4dd7-34cc-431c-b565-714eea9d7df0" />
<br>
<br>

A lightweight Linux desktop application for customizing notification sounds.
Notification Sound Manager lets you choose separate sounds for:
- General notifications
- Email notifications
- Login/startup
- Discord

It only reads and adds sound to the notifications that occur, it does not replace the notifications nor the sound.
So it would be wise to turn off the notification sound in the applications you want this app to provide sound for, 
unless you like hearing different sounds stacked on top of each other.

NB: Turning off notifications for the apps you want this to provide sound for, makes this app unable to function as intended.

**Version 1.3.0**

### What's new in 1.3.0

- Rebranded to **Notification Sound Manager**
- Debian package renamed to `notification-sound-manager`
- Existing `notification-manager` installations are replaced automatically during upgrade
- Desktop launcher updated
- App-grid name shortened to **Notify Sound**
- Window title updated to **Notification Sound UI**
- Existing settings remain compatible
- Independent volume controls remain available for:

  * General notifications
  * Login sound
  * Discord
  * Email

### Supported Email Clients
Email notifications are currently recognized from:
- Thunderbird
- Evolution
- KMail
- Geary
- Mailspring
- Claws Mail

## Installation
Download the latest `.deb` package from the **Releases** section.
Then install it with:
```bash
sudo apt install ./notification-sound-manager_1.3.0_all.deb
``` 
Replace the 1.3.0 section of the code with whatever version you downloaded. Newest is always better unless i specify otherwise.
