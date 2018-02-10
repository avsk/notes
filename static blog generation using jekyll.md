# Static Personal Blog Generation using Jekyll


**Contents**

- Introduction
- Setting things up
	- Installing Ruby
    - Working with RubyGem 
- Getting Started with Jekyll
	- Project/directory structure
	- Configurations
	- Customizability and themes
- Using Jekyll Themes
	- Choosing a theme
	- Methods of integrating and using themes
- Features to consider for blog
	- Sitemap
    - Comments
    - Social Media integration
    - SEO
    - Tags
    - Read time
    - JSON resume
 - Demo (using basically basic theme from minimal-mistakes author Kevin Rose)
 
    
 
### Introduction

 - What is jekyll ?
 
 - Why use jekyll ?
 
 
### Setting things up

#### Installing Ruby

``Linux``

 - Install RVM (ruby version manager)

```bash
gpg --keyserver hkp://keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB
```

```bash
\curl -sSL https://get.rvm.io | bash -s stable
```

- Enabling rvm post installation (during first run )

```bash
source /../../*.sh
```

- Install latest ruby version 2.4.3 [as of writing]

```
rvm install 2.4.3
```
- Working with RVM 

```bash
rvm list 
```

```bash
rvm use 2.4.3
```

``Windows``


#### Working with RubyGem 

The RubyGems software allows you to easily download, install, and use ruby software packages on your system. The software package is called a ``gem`` which contains a packaged Ruby application or library.

RubyGems.org is the Ruby community’s gem hosting service.

Ruby 1.9 and newer ships with RubyGems built-in - since our installed version of ruby is 2.4.3 we wouldn't require to explicitly install rubygem.

The ``gem`` command allows you to interact with RubyGems

Some useful commands are shown below :

- Check the installed version of RubyGem
```
gem -v
```

- Installing gem 
```
gem install jekyll
```

- Un-installing gems
```
gem uninstall jekyll
```

- Listing out the installed gems
```
gem list
```
- Finding gem from the rubygems.org repository 

```
gem find ^jekyll*
```
use of regex pattern is allowed in the query.

- Updating a gem

```
gem update jekyll

```

#### Installing gem packages 


- install [jekyll] 


> Jekyll is a simple, blog aware, static site generator

[``docs``](https://jekyllrb.com/docs/home/)


- install [bundler] 

> Bundler manages an application's dependencies through its entire life, across many machines, systematically and repeatably

[``docs``](http://bundler.io/docs.html)


```
gem install jekyll
gem install bundler
```

- install some more jekyll related gems as part of project dependencies ( to be installed as and when required [coverd later] )


### Getting started with Jekyll

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


======================

[jekyll]:https://rubygems.org/gems/jekyll
[bundler]:https://rubygems.org/gems/bundler