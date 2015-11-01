# os-secondscreen
os-secondscreen is an in-browser second screen for [OpenSong](http://opensong.org). It shows the slide that is currently presented full-screen in a browser. It can be used to easily setup an additional display using a computer, tablet or TV in combination with e.g. a Chromecast.

The OpenSong Second Screen app is a readonly client for the [OpenSong API](http://opensong.org/pages/api.html). It uses a websocket connection to OpenSong. It can not be used as a remote control for OpenSong.

The features are:
- display of the current slide as image
- display of lyrics and verses including chords using [opensong.js](https://github.com/deepflame/opensong.js)


## What is OpenSong?

> OpenSong is a free, open-source software application created to manage lyrics, chords, lead sheets, overheads, computer projection, and more.
>
> OpenSong releases are available for Microsoft Windows, Mac OSX, and Linux operating systems.
>
> [Download](http://opensong.org/d/downloads) the full application for free and give it a try!


### Requirements

  - An installation of OpenSong
  - Enabled automation API in OpenSong (to enable, goto the generic settings, on the system tab)
  - The files in the repository, (optionally running on a webserver)

### Usage

Open the file secondscreen.html (using your webserver url, if installed on a webserver).
On the first screen, enter the hostname and the port on which OpenSong can be reached from the client. The secondscreen application does not run any server side code. The connection to OpenSong is made from the computer that loads the web page. Now click 'Show slides' to see the image as rendered by OpenSong. Click 'Show lyrics' to show the songs rendered using opensong.js.


## License

[GNU General Public License v2.0 (GPL-2.0)](http://opensource.org/licenses/gpl-2.0.php)
