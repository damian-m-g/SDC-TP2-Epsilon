# SDC-TP2-Epsilon

## For peers: how to quick-setup Ruby on your machine to run this code.

Most GNU/Linux machines comes with Ruby installed, it doesn't matter if the version is old, I myself used the native that comes with Linux Mint an it's 3.0.X, so as long as you have >= 3.0.X you are good to go. Check this on your terminal with:  
  
`ruby -v`

Let me know if you have a version that doesn't fit the requirements for this project. After that, you need to install a few things, but **make sure you are standing in the root of this project when you do it (check that with `pwd`)**. In this order:

```text
sudo apt install ruby-dev
sudo gem install ffi
/bin/ruby /bin/bundle install
```

You are ready now to run the Ruby script with:

`ruby higher_layer.rb`
