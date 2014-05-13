UserAgents.plist
================

Additional User Agents for Safari User Agent switcher menu

![Alt text](screenshots/UserAgents.png?raw=true)

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

## License
Licensed under the MIT license.

Copyright (c) 2014 [Sander Heilbron](http://www.sanderheilbron.nl)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
