# powerpoint Karaoke decker
Randomly creates a .pptx deck (one file) by slapping together
* a boring welcome page
* 5 random slides from the `assets` folder,
* a Thank you page.

# Why would you need this?
Ok, so the _real_ fun is created by Vincent. He built a random
slide generator for powerpoint Karaoke. But the
issue with his machinery is it generates
live on-screen only. You cannot load that into powerpoint.

So, Vincent generated a few hundred slides offline
for me, and I set out to generate actual decks.

All the credits for the assets go to Vincent.
You can book him for a fun game of Powerpoint Karaoke with your team.

More about [Vincent on Twitter](https://twitter.com/vinwijnl).

# install & run
1. You need Python installed on your machine
1. `pip install -r requirements.txt`
1. `python main.py`

Should do the trick. Pick up the decks in
`/generated/deck_xx.pptx`
