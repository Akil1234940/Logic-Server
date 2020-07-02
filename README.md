# Logic Server

This is an encrypted copy of Logic Server for BombSquad.
This only works on Linux for now.

## Installation

Just use the following commands on any Linux Machine (preferably hosted  on cloud) and you should have a working copy in a few minutes.

```bash
sudo apt -y update
sudo apt install -y python python2.7 libsdl2-2.0.0 libpython2.7 python-pip git
git clone https://github.com/Awesome-Logic/Logic-Server.git
cd Logic-Server
```


**Important: Make sure that you properly edit the config.py as per the instructions in it.**

## Usage

To update the server, simply use git pull.
```bash
cd Logic-Server
git pull
```
The server will stop working if it finds a new version and is not updated.

## Feature Requests
For changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)
