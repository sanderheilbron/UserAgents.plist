UserAgents.plist
================

Additional User Agents for Safari User Agent switcher menu

## Additional User Agents
* Internet Explorer 10.0
* Googlebot/2.1
* Googlebot-Mobile/2.1 &mdash; Smartphone
* Googlebot-Mobile/2.1 &mdash; Feature phone
* Bingbot/2.0
* YandexBot/3.0

## Usage
Download the file [UserAgents.plist](https://raw.github.com/sanderheilbron/UserAgents.plist/master/UserAgents.plist) to your Desktop.
Close Safari and launch the Terminal app. Copy the modified file into Safari, enter the following command in the Terminal:

    $ sudo cp ~/Desktop/UserAgents.plist /Applications/Safari.app/Contents/Resources/UserAgents.plist

Relaunch Safari and you’ll see the new User Agents in the User Agent switcher menu.

## Requirements
* Mac: Safari 4 or later
* To enable user-agent switching, you need first to activate the Developer menu in the ‘Advanced’ tab of Safari’s preferences.
