# Ubuntu `pipenv`

Ubuntu 20.04 was used with this scripts:

```sh
apt install python3-pip
pip3 install pipenv

echo "" >> ~/.profile
echo 'export PATH="$PATH:~/.local/bin"' >> ~/.profile
source ~/.profile

pipenv --version
```

Reference:

[pipenv Documentation](http://manpages.ubuntu.com/manpages/focal/en/man1/pipenv.1.html)
