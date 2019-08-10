# my-dot-files

## Re: vim setup

The base for this vim setup is [ets-labs python-vimrc](https://github.com/ets-labs/python-vimrc). Hence, .vimrc file was initialized by:

```shell
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ets-labs/python-vimrc/master/setup.sh)"
```

Then, I adjusted it a little bit to myself:
```shell
wget https://raw.githubusercontent.com/gorskim/my-dot-files/master/.vimrc
mv .vimrc.1 .vimrc
```

YCM installation:
```shell
sudo apt install build-essential cmake python3-dev
cd ~/.vim/bundle/YouCompleteMe && python3 install.py --clang-completer
```

Note: 

* Vundle is necessary, of course. 
* YCM needs additional installation.
