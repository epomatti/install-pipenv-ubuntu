# Install pipenv

Using python 3:

```sh
sudo apt install python3-pip
pip3 install --user pipenv
python3 -m site --user-base
```

Add next line to `~/.profile`:

```
export PATH="$PATH:~/.local/bin"
```

and then `source ~/.profile`

You might need to add `--python` variant depending on your setup:

```sh
pipenv install --python=/usr/bin/python3.6
```

Reference:

http://manpages.ubuntu.com/manpages/eoan/en/man1/pipenv.1.html
