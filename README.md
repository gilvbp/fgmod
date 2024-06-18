## Installation
```sh
curl https://raw.githubusercontent.com/FakeMichau/fgmod/main/prepare.sh | sh --
```
This will create a folder called ``fgmod`` in your home directory with a wrapper ``fgmod`` inside of it.

Before running it, at least take a look at prepare.sh and fgmod.sh, piping stuff blindly into sh is not wise.

## Usage
After running the script, you will be given the exact command. In case you missed it, look below.

For Steam, add this to the launch options ``/home/USERNAME/fgmod/fgmod %COMMAND%``  
For Heroic, add this as a new wrapper ``/home/USERNAME/fgmod/fgmod``  
Just replace USERNAME with your own.

### AUR package
There is PKGBUILD, download that and fgmod.sh, you know what to do with it - ``makepkg``. Usage is simpler, just add ``fgmod`` as a wrapper.