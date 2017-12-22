# Static Blog Generation using Jekyll

## Introduction
 - What is jekyll ?
 - Why to use jekyll / What does is offer ?


### 1. Setting things up 

#### Installing Ruby

**Linux**

 - install RVM (ruby version manager)

```bash
gpg --keyserver hkp://keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB
```

```bash
\curl -sSL https://get.rvm.io | bash -s stable
```

- enabling rvm post installation (during first run )

```bash
source /../../*.sh
```

- install latest ruby version 2.4.3 [as of today]

```
rvm install 2.4.3
```
- working with RVM 

```bash
rvm list 
```

```bash
rvm use 2.4.3
```

install jekyll and bundler
```
gem -v # Note the gem version
```

```
gem install jekyll bundler
```

- install some more jupyter related gems as part of project dependencies ( to be installed as and when required [coverd later] )


### 2. Getting started on using jekyll

**jekyll --help**

 - basic commands 

```
jekyll new
```

```
jekyll build
```

```
jekyll serve
```

- project/directory structure
- configurations
- customizability and themes
