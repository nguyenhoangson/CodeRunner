# CodeRunner [![Build Status](https://travis-ci.org/nguyenhoangson/Code-Runner.svg?branch=master)](https://travis-ci.org/nguyenhoangson/Code-Runner)


Code Runner uses Docker as sandboxing environment

# Prerequisites
To use CodeRunner package, it requires the following dependencies to be installed: 

```console
Docker: 1.11.2 
```

```console
Docker-machine: 0.7.0
```

```console
python 2.7.11
```

# Step by Step setup guide   
Guide to set up for Ubuntu 14.04.4 LTS, but for other Ubuntu version, it should also work properly

Install python 2.7.11

```console
python 2.7.11
```

Clone master branch of this repository for the latest version of Code-Runner

```console
git clone --depth=50 --branch=master https://github.com/nguyenhoangson/Code-Runner.git 
cd Code-Runner
```

Change mode for set up scripts and run them to set up

```console
chmod 755 ./scripts/*
./scripts/install_docker
./scripts/install_docker_machine
pip install -r requirements.txt
```

Finally run example.py file to see if everything is set up properly
```console
python example.py
```

# User Guide 


