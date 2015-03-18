# Mac configurations

An update to the old IT Configurations notes.

- Set up superuser

## Before rebuilding any machine

- Disable automatic login if enabled.  This is often used on media nodes.
- Deauthorize iTunes on old copy and record in LastPass.
- Disconnect time machine clients.
- Disconnect attached drives and verify access from another, non-networked machine.
- Set Backblaze on manual backup or delete.
- Delete or transfer ssh keys if present.
  - If deleting, unlink sites using ssh keys.  Sites may include:
    - [Github](https://github.com/settings/ssh)
    - [Heroku](https://devcenter.heroku.com/articles/keys)
  - If transferring use Dropbox or some other solution that preserves attributes.
- Copy Xcode credentials if present.
- Disable firefox sync (under preferences).
- Unlink dropbox.
  - Linked computers listed on [dropbox site](https://www.dropbox.com/account#security)
- Disconnect Chrome.
- Turn off/disconnect all networking.
- Copy disk using Disk Utility/restore if restore possibly needed.
- Check the copy.  Network should be off to avoid hitting services.

## Create install drive (Mavericks)

Need to update this section for Yosemite.

- From [http://www.macworld.com/article/2056561/how-to-make-a-bootable-mavericks-install-drive.html](http://www.macworld.com/article/2056561/how-to-make-a-bootable-mavericks-install-drive.html)
- `sudo /Applications/Install\ OS\ X\ Mavericks.app/Contents/Resources/createinstallmedia --volume /Volumes/Untitled --applicationpath /Applications/Install\ OS\ X\ Mavericks.app --nointeraction`

## General Mac setup

- Rename internal hard drive.  Easiest way is to expose the HD via Finder preferences and edit.
  - YYYY.MM.DD MACHINE LOCATION # (for example, 2013.10.26 babalupa internal 1)
- Rename computer (under Sharing).
- Add the node to the list of devices in LastPass.### System preferences
- Fully patch/update system via App store.  Accept automatic updates.
- Install everything using a package system (App Store, homebrew, homebrew-cask) if at possible.
- In general, store all data off of system drive.
- Verify disk and permissions with Disk Utility.
- Remove apps from dock.
- Add users.  Typically use first initial + last name.
- Reboot.
- Sometimes it is easier to set up screen sharing to configure the machine from an existing node.

### System Preferences

* General: -
* Desktop & Screen Saver
  * Start after 1 hour
  * Set background
  * Show with clock
  * Hot corners: top left screen saver
* Dock: On left and hide
* Mission Control: -
* Language & Text: -
* Security & Privacy
  * Require password 5 seconds after sleep or screen saver begins
  * Require an administrator to access locked preferenes (advanced)
  * Disable remote control infrared receiver (advanced)
* Spotlight
  * Turn off shortcuts
* Notifications:

Hardware

* CDs & DVDs: -
* Displays: -
* Energy Saver
  * Sleep settings (never for computer, 1 hr for display)
  * Start up automatically after power failure (media nodes)
  * Show UPS status
  * Enable power nap (if available)
* Keyboard
  * Use standard function keys
  * Turn on invert under accessibility shortcuts
* Mouse:
  * Set lower right corner for secondary click
* Trackpad:
  * Set lower right corner for secondary click
* Print & Scan
  * Install printers
* Sound

Internet & Wireless

* iCloud:
  * Setup keychain
* Internet accounts: All
* Network:
  * Setup wifi(s)
  * media nodes should have tunneled IP
* Bluetooth:
* Sharing
  * Set computer name (use lower case)
  * Allow screen sharing by eevenson only
  * Allow remote login by eevenson only
  * Share home folder to self

System

* Users & Groups
  * Turn off password hints
  * Turn on fast user switching
  * Set guest user options as desired
  * Add other users
  * Add automatic login if needed (Media Player on Sharpi)
* Parental Controls
* App Store
  * Automatic everything
* Dictation & Speech: -
* Date & Time
  * Show date
  * Show seconds
  * Flash separators
* Startup Disk
* Time Machine
  * Hide if not used
* Accessibility

### Set finder preferences

* New finder window shows user home
* Sidebar settings
* Show tab bar
* Show path bar
* Show status bar
* Show as list
* Show battery percentage

### App Store 1

Limit to apps needed for install.

* Install system updates
* Xcode
  * Install device support
  * Install command line tools (automatic with Mavericks)
  * Set to update automatically
  * Download other components and documentation as desired
* iPhoto
  * General, connecting camera opens no application
  * Connect to server hosted photo library if possible

### Bash profile file
Use:

  echo "Initializing with ~/.bash_profile"

  # homebrew configuration
  export PATH="/usr/local/bin:${PATH}"

  # homebrew cask configuration
  export HOMEBREW_CASK_OPTS="--appdir=/Applications"

  # textmate configuration
  export EDITOR="/usr/local/bin/mate -w"
  
  # z configuration
  . `brew --prefix`/etc/profile.d/z.sh

### [Homebrew](http://brew.sh/)

* Install Xcode and command line tools first.
* Install homebrew per website.  Currently, this is `ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
* Set `export PATH="/usr/local/bin:${PATH}"` in `.bash_profile` and `source .bash_profile` (above in bash profile file)
* `brew doctor`
* brew install group:
  * `brew install git mongodb node phantomjs scons tree z`

### [Homebrew cask](https://github.com/phinze/homebrew-cask)

- Install homebrew first.
- Install homebrew cask per website.  Currently, this is
  - `brew install caskroom/cask/brew-cask`
- Add [homebrew-versions](https://github.com/caskroom/homebrew-versions) - "alternate versions of Casks for homebrew-cask"
  - `brew tap caskroom/versions`
* Set HOMEBREW_CASK_OPTS per [these instructions](https://github.com/phinze/homebrew-cask/blob/master/USAGE.md#options) and restart.  Currently this is `export HOMEBREW_CASK_OPTS="--appdir=/Applications"` in `.bash_profile` and `source .bash_profile`
* brew cask install group:
  * `brew cask install dropbox`
* Configure dropbox (to allow access to this document)
  * Link
  * Disable camera input
  * Set selective sync
* brew cask install group:
  * `brew cask install alfred bittorrent-sync colloquy cyberduck firefox github gnucash google-chrome google-hangouts google-drive handbrake inkscape minecraft mongo mumble pandoc postgres silverlight skype sourcetree spectacle steam submlime-text3 textmate transmission unrarx virtualbox vagrant vlc xquartz`
* Add to homebrew cask search scope to Alfred per [usage instructions](https://github.com/phinze/homebrew-cask/blob/master/USAGE.md).  Currently, this is `/opt/homebrew-cask/Caskroom`.  Start typing in the search scope selection dialog to enter the path.  Note, directory won't exist until after first install.
* Activate Alfred Powerpack
* Open and close firefox and chrome.
* brew cask install group:
  * `brew cask install lastpass backblaze-downloader`
* Backblaze
* Individual apps (best order):
  * alfred
    * Launch at login and use sync folder.
  * google-chrome
    * Set mail as home page
  * google-drive
    * Sign in
  * backblaze (if needed)
    * Warn after 1 day
    * No throttle, faster backups
    * No size limit
  * firefox
    * Setup sync
  * sourcetree (do not install via the App Store!!)
    * Re-register
    * Use the setup wizard
    * Add accounts
    * Set project folder
    * Under git preferences, set do not fast-forward when merging, always create commit
    * Use system git
    * Automatically check for updates
    * Use fixed-width font for commit messages
    * Uncheck confirm switching branches when working copy is clean
    * Select all files when seleting commit
    * Git stage files on double click
    * Open links on github.com with sourcetree
  * spectacle
    * start up
  * steam
    * Remove from login items
    * Kerbal Space Program
      * MechJeb
      * KAS
      * Editor Extensions
  * sublime-text3
    * [package control](https://packagecontrol.io/installation#st3)
      * better coffeescript
      * eco
      * sublimelinter
        * sublimelinter-coffee
          * `npm install -g coffee-script` first.
        * sublimelinter-json
        * sublimelinter-pylint
          * `sudo easy_intall pip`
          * `pip install pylint`
  * textmate
    * Add to `.bash_profile`: `export EDITOR="/usr/local/bin/mate -w"` and `source .bash_profile` (from bash profile above)
    * Add coffeescript, python django, python django templates, and reStructuredText bundles
    * Watch for nightly builds
    * Install shell support
    * Set mac classic theme
    * Exclude files matching:
      * `{*.{o,pyc},Icon\r,CVS,_darcs,_MTN,\{arch\},blib,*~.nib}`
    * Include files matching:
      * `{*,.bowerrc,.buildpacks,.buildpacks_bin_download,.coveragerc,.env,.gitattributes,.gitignore,.htaccess,.jshintrc,.noserc,.pylintrc,.slugignore,.tm_properties}`
    * Trailing whitespace: [http://tm2tips.tumblr.com/post/42657705618/strip-trailing-whitespace-on-save-with-callbacks](http://tm2tips.tumblr.com/post/42657705618/strip-trailing-whitespace-on-save-with-callbacks)
  * transmission (capture settings)
    Blocklist: http://john.bitsurge.net/public/biglist.p2p.gz
  * vlc
    * Set update checking.

## Transfers

* Get ssh keys if transferring:
  * `scp eevenson@airframe.local:.ssh/id_rsa* .`

### App store 2

Other useful apps.

* 3Hub
  * Add buckets
  * Use https
  * Set download folder
* Downcast
  * iCloud connection
* Twitter
  * Scroll to top
  * Add other account(s)
* OmniFocus
  * Sync
  * Expose all columns
* Others as desired
  * Do not install sourcetree -- get that via homebrew cask

### Other installs

* Remote desktop
* [BasicTexX](http://www.tug.org/mactex/morepackages.html) -- after installing:
  - `sudo tlmgr update --self`
  - amssymb (?)
  - longtable (?)
  - graphicx (?)
  - `sudo tlmgr install ulem`
* RubyGems
  * `sudo gem update --system`
  * `sudo gem install foreman compass`
* Node package manager
  * `npm install -g yo generator-webapp`
* [Eve Online](https://secure.eveonline.com/Download)
  - Turn off gatekeeper for first start (be sure to turn back on)
  - Auto play
  - Mark my orders
  - Set column ordering on market
  - Set range on market to region
  - Show compact member list for chat
  - …

  1. Character sheet/Skills
    1. Show all skills
    1. Highlight partials
  1. First start takes a while
  1. Window mode
  1. No movie
  1. No music
  1. Optimize for performance
  1. Turn off captain's quarters
  1. Set overview settings
  1. Quit without confirmation
  1. Display & Graphics
  1. Audio & Chat
  1. General Settings
    1. Lock windows when pinned
  1. Shortcuts:
    1. Window
      1. M: manage nearest control tower
      1. O: edit overview
      1. ALT-Q: set overview
    1. Combat
    1. General
    1. Navigation
    1. Modules
    1. Movement
    1. Drones
    1. Character Creation
  1. Reset Settings
  1. Language

* ssh keys
  * github [instructions](https://help.github.com/articles/generating-ssh-keys)
  * heroku [instructions](https://devcenter.heroku.com/articles/keys)

### Other setup

* iTunes
  * Rename library (computer.username)
  * Share library
  * Set equalizer to Rock
  * Authorize computer
    * Currently authorized listed in LastPass
  * Turn on home sharing
  * Sign in and connect iTunes Match
  * Prevent syncing
  * General
    * Show all
    * View all
  * Playback
  * Store
    * Prefer 1080p
  * Parental
  * Devices
  * Advanced
* vagrant
  * `vagrant plugin install vagrant-vbguest`
  * Might need: `sudo /Library/StartupItems/VirtualBox/VirtualBox restart` per [http://end.io/virtualbox-on-os-x-10-9-mavericks/](http://end.io/virtualbox-on-os-x-10-9-mavericks/)

## oilplus

Use standard config.

### Additional installs

* HP Photosmart C7200 printer
