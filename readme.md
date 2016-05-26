Python CUrses Reddit Browser (PCURB) is supposed to be a curses interface in Python 3, ncurses and PRAW

PCURB is for reading comments and discussions, since images and links are somewhat harder to represent in a terminal environment. For these look up terminal-based browsers like Lynx or w3m instead. PCURB focuses on its aim to provide a more comfortable experience reading Reddit comments, not the entire Web.

### How to run
First, obviously, Python 3, [PRAW](https://praw.readthedocs.io/en/stable/) and ncurses are required. I haven't run across any ncurses bindings for Python 3 on Windows, so I guess that's not an option.

Run it simply by typing ./pcurb in a terminal. You can pass it "help", "h" or "-h" to get a short help ; type a subreddit name as argument to open that subreddit. (for instance, "./pcurb gifsofotters")

When looking at a subreddit, use the up and down arrow keys to scroll, or Q to quit.

Press M ("more"), then type a number, then press Enter and wait to see comments. Once there, use arrow keys to scroll or press Q to quit.


### Current state

Unusable. There's a problem when recursively displaying comments that makes it so they step on each other, and I can't quite pin it down on something.


### Contributing & Licensing

Feel free to modify, contribute, fork or redistribute all this. That being said, please change the author in the user agent (the "by /u/.." field). I wouldn't want to get in trouble.
