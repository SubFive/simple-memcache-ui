# text-based user interface for Memcached 1.4.31+

### Installation
```
git clone https://github.com/jairovsky/simple-memcache-ui.git
cd simple-memcache-ui
pip3 install -r requirements.txt
```

### Usage

`python3 src/main.py <memcache-host> <memcache-port>`

- <kbd>r</kbd>: refresh key list
- <kbd>f</kbd>: flush/clear key list
- <kbd>enter</kbd>: show key contents on the right panel
- <kbd>d</kbd>: delete key
- <kbd>y</kbd>: copies the contents displayed on the right panel to the clipboard
