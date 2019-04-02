# git check (python code pep checker)
[![Say Thanks](https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg)](https://saythanks.io/to/anshul217)

git check this is an helper command line utility to help developer to check code pep standards and also provides optional pre-commit to make sure developer pushes pep standard code in repo.

This is a bash script which can be used like "git check -d src/"

One can find out usage of this command using "git check -h"

## Prerequisites
1. bash
2. flake8

## Installation

Place git-check file to your bin and reload path variable environment variable.
Here are steps:-
1. create your bin dir using this command if does not exists:
   mkdir ~/bin
2. place git-check file in this directory.
3. give executable permission to this file. using chmod +x git-check
4. Export your bin directory to the PATH using following steps
5. Open ~/.bash_profile
6. add export PATH=$PATH:/Users/<your user name>/bin
7. close this file and run command source ~/.bash_profile

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Installing git pre-commit

To check pep standards at time of commit add pre-commit file to your repo
Here are steps:-
1. go to your project .git/hooks/
2. if pre-commit file exists then add code of pre-commit file in repo to your pre-commit file else place pre-commit at this location.
3. give executable permission to this file. using chmod +x pre-commit
4

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)