Ruby/Rails environment for Mavericks
====================================

- Install XCode from the app store.
 
- Install XCode command-line tools.

```
    xcode-select --install 
```

- Install home brew.  http://brew.sh/
 
```
    ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)" 
```

- Install database development packages.
 
```
    brew install postgresql 
    brew install mysql 
```
 
- Install RVM.  https://rvm.io/rvm/install
 
```
    curl -sSL https://get.rvm.io | bash 
    rvm requirements 
```
 
- Exit your open terminal and open a new one.
 
- Install ruby 2.0 via RVM (this makes gem management with user permissions simpler.)
 
```
    rvm install 2.0 
```
    
- Install rails
 
```
    gem install rails -v '3.2.13' 
```
    
- Make a rails app, install the default gems
 
```
    rails new first_app 
    cd first_app 
    bundle install 
```
 