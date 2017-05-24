smconf.org <img src="http://i.imgur.com/Cj4rMrS.gif" height="40" alt="Swimming Octocat" title="smconf.org"> [![GitHub issues](https://img.shields.io/github/issues/silicon-mountain/smconf.org.svg)](https://github.com/silicon-mountain/smconf.org/issues) [![GitHub stars](https://img.shields.io/github/stars/silicon-mountain/smconf.org.svg)](https://github.com/silicon-mountain/smconf.org/stargazers) [![GitHub license](https://img.shields.io/badge/license-AGPL-blue.svg)](https://raw.githubusercontent.com/silicon-mountain/smconf.org/master/LICENSE)
==============

Silicon Mountain Conference website was created, and is maintained by [The Silicon Mountain](https://github.com/silicon-mountain) developers in Buea. If you want to contribute to this project, fork the repository and follow the steps below to contribute.


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
Replace `<your-github-handle>` with your actual Github username. For example, mine is: `git clone https://github.com/ch3nkula/smconf.org.git`.


### Build & Deploy locally

```
$ python3 -m http.server
```
Deployment by default is on port 8000 when using the `python3`'s in-built HTTP server.


### Testing on your browser

Open up your browser and type the link: https://localhost:8000. Hayyy! You should have the website served via HTTP successfully if the website loads locally :+1:.


### License

smconf.org is licensed under [Apache](LICENSE).
