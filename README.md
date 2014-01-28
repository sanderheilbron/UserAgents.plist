UserAgents.plist
================

Additional User Agents for Safari User Agent switcher menu

![Alt text](/screenshots/UserAgents.png?raw=true)

## Additional User Agents
**Search Engine Bots:**
* Googlebot/2.1
* Googlebot/2.1 &mdash; Smartphone
* Googlebot-Mobile/2.1 &mdash; Feature phone
* Bingbot/2.0
* YandexBot/3.0

**Android:**
* Android 4.0.4, Samsung Galaxy S3
* Android 2.2, Samsung Galaxy Tab

## Usage
Download the file [UserAgents.plist](https://raw.github.com/sanderheilbron/UserAgents.plist/master/UserAgents.plist) to your Desktop.
Close Safari and launch the Terminal app. Copy the modified file into Safari, enter the following command in the Terminal:

    $ sudo cp ~/Desktop/UserAgents.plist /Applications/Safari.app/Contents/Resources/UserAgents.plist

Relaunch Safari and you’ll see the new User Agents in the User Agent switcher menu.

## Requirements
* Mac: Safari 4 or later
* To enable User Agent switching, you need first to activate the Developer menu in the ‘Advanced’ tab of Safari’s preferences.
