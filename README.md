smconf.org <img src="http://i.imgur.com/Cj4rMrS.gif" height="40" alt="Swimming Octocat" title="smconf.org"> [![GitHub issues](https://img.shields.io/github/issues/silicon-mountain/smconf.org.svg)](https://github.com/silicon-mountain/smconf.org/issues) [![GitHub stars](https://img.shields.io/github/stars/silicon-mountain/smconf.org.svg)](https://github.com/silicon-mountain/smconf.org/stargazers) [![GitHub license](https://img.shields.io/badge/license-AGPL-blue.svg)](https://raw.githubusercontent.com/silicon-mountain/smconf.org/master/LICENSE)
==============

Silicon Mountain Conference website was created, and is maintained by [The Silicon Mountain](https://en.wikipedia.org/wiki/Silicon_Mountain) developers in the Mountain Area of Cameroon. If you want to contribute to this project, fork the repository and follow the steps below to contribute.


### Installing Python 3.6

Follow this link to install Python 3.6 on your Linux OS: http://python-guide-pt-br.readthedocs.io/en/latest/starting/install3/linux/. We recommend developers to use Linux for development to make things easier for everyone. This step is to allow us use `python3` in-built `http.server` module to deploy the website during development.


### Change to home directory

```
$ cd ~/
```


### Clone your Fork

```
$ git clone https://github.com/<your-github-handle>/smconf.org.git
```
Replace `<your-github-handle>` with your actual Github username. For example, In @Ch3nkula's case : `git clone https://github.com/ch3nkula/smconf.org.git`.


### Build & Deploy locally

```
$ python3 -m SimpleHTTPServer <any-free-port> // E.g. python3 -m http.server 8000
```
OR If you're using an in-built PHP server

```
$ php -S localhost:<any-free-port> // E.g. php -S localhost:8000
```


### Testing on your browser

Open up your browser and type the link: http://localhost:``<any-free-port>`` E.g. http://localhost:8000 .Hayyy! You should have the website served via HTTP successfully if the website loads locally :+1:.


### License

smconf.org is licensed under [GPLv3](LICENSE).
