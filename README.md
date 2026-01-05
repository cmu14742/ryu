This is a fork of Ryu that is maintained for specific use of the 14742 course at
Carnegie Mellon University.  It is adjusted to run in Ubuntu 22.04, so it will be
gradually pruned of content and features that are not relevant to use in the course.

The original README can be found in the unmaintaind Ryu repo at https://github.com/faucetsdn/ryu.

----------

Install Ryu from source:
```sh
git clone https://github.com/cmu14742/ryu
cd ryu; pip install .
```

To run an application:
```sh
ryu-manager /path/to/your/app.py
```
