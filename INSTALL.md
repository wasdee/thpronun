# How to install 
because ``thpronun`` has some dependencies that must be installed before ``thpronun``

## on macOS
1. get [homebrew](https://brew.sh/) installed
1. get [macports](https://www.macports.org/install.php) installed
1. ``brew install help2man autoconf automake libtool autoconf-archive pkg-config gettext``
2. ``sudo port install libthai``
3. ``export PKG_CONFIG_PATH=/usr/local/lib/pkgconfig:/usr/local/lib:/opt/local/lib:/opt/local/lib/pkgconfig``
3. ``./configure``
4. ``make``
