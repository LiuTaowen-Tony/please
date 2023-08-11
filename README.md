A copilot in command line

![Example](img/example.gif)

Usage

``` bash
please print the first 10 fib numbers
```

``` bash
please rename all the files change tom to jerry
```

Install

``` bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements

mkdir $HOME/bin
cp please $HOME/bin/please
chmod +x $HOME/bin/please
ln -s venv $HOME/bin/venv
echo '$PATH=$PATH:$HOME/bin'>> ~/.zshrc
```

