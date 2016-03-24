# Software Installation

To install the software you need:

1. Visit [the mu download page](http://ardublockly-builds.s3-website-us-west-2.amazonaws.com/?prefix=microbit/raspberry_pi/)
2. Click on the lowest link in the list, for the latest version of **mu**
3. Run LXTerminal and type the following commands

```bash
cp ~/Downloads/mu* ~/mu
cd ~/
chmod +x mu
```
You'll also need the Python `pyowm` library. You can install this by typing the following into LXTerminal

```bash
sudo pip3 install pyowm
```
