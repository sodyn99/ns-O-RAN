# ns-o-ran

This repository is a fork of the [ns-O-RAN-flexric](https://github.com/Orange-OpenSource/ns-O-RAN-flexric) repository.

```bash
git clone --recurse-submodules https://github.com/sodyn99/ns-O-RAN.git
```

## Prerequisites

- Requirements

  ```bash
  sudo apt-get update
  sudo apt-get install -y build-essential git cmake libsctp-dev autoconf libpcre2-dev libpcre3-dev ccache
  sudo apt install python3.13 # (or ealier version, but 3.6+ required)
  sudo apt-get install gcc-12 g++-12
  sudo update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-12 12
  sudo update-alternatives --install /usr/bin/g++ g++ /usr/bin/g++-12 12
  sudo update-alternatives --config gcc
  sudo update-alternatives --config g++
  ```

- [Docker](https://docs.docker.com/engine/install/)
- [Docker Compose](https://docs.docker.com/compose/install/)
- SWIG

  ```bash
  mkdir -p ~/Downloads
  cd ~/Downloads
  git clone https://github.com/swig/swig.git
  cd swig
  ./autogen.sh
  ./configure
  make
  sudo make install
  make -k check
  ```

## Installation

Please go to the [README.md](https://github.com/sodyn99/ns-O-RAN/tree/main/docs#installation-instructions) for the installation instructions of the original repository.

### O-RAN SC Near-RT RIC

