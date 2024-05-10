# FlappyBird

This took me a long time to make and I thank you for trying the game out :)

This project may be used for reference or as open-source

## Quick Start

Run the following commands in the root directory

```shell
python3 -m venv .venv
source .venv/bin/activate
pip3 install -r requirements.txt

python3 main.py
```

## Disclaimer

For all you programming nerds, I KNOW that the 2 implementations of `main()` and `main_inverted()` are unnecessary since only a few paramters changed. I implemented it that way just in case I want to add more cool stuff exclusive to both gamemodes individually, which would be a clusterfuck harder to do with a single game class.

The main menu implementation is a bit messy, I'll fix that eventually

This program isn't technically the most optimal it can be, but literally any system should be able to run this, regardless of specs
