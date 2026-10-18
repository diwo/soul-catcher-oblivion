# Soul Catcher

This is a mod for the original [The Elder Scrolls IV: Oblivion](https://en.wikipedia.org/wiki/The_Elder_Scrolls_IV:_Oblivion) released in 2006.

This mod changes how soul gems are selected when capturing souls so that you can spend less time making
sure high quality gems are not wasted on petty souls and let the gems fill themselves up naturally.

Soul Catcher comes with the following configurable tweaks:

* Capturing a larger soul replaces a smaller soul occupying the soul gem (default: enabled)
* Shrink souls when capturing to fit smaller soul gems when a larger gem is not available (default: enabled)
* Prevent souls from being captured into a normal soul gem if they wouldn't fully fill one (default: disabled)
* Prevent non-grand souls from being captured into black soul gems (default: enabled)
* Passively charge up the Azura's Star as you capture souls to fill up other soul gems. Whenever a soul is captured,
  a percentage of its charge points (e.g. 800 for Common Soul) is added to the Azura's Star charges. (default: 20%)
* Allow the Azura's Star hold more charge points than 1600 while still spending at most 1600 at a time (default: 3200)

### Installation
* Install [OBSE](https://github.com/llde/xOBSE/releases) version 22 or newer
* Download the latest [release](https://github.com/diwo/soul-catcher-oblivion/releases)
  and extract the archive into the `/data` directory of your Oblivion installation