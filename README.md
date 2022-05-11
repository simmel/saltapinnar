## How to use

1. Clone this repo
1. Install salt
   ```terminal
   $ python3 -m venv venv
   $ source venv/bin/activate
   $ pip3 install salt==3004.1
   ```
1. Iterate!
   ```terminal
   $ $EDITOR states/* pillars/*
   $ salt-call state.apply
   ```
