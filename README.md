# homebrew-tap

My tap where you can install various programs using homebrew. 

This repo is mostly automated. It's meant to store taps that homebrew can use to install programs. So, yeah, this repo is pretty boring on purpose. 

When you want to install one of the programs in this repo, you can run `brew install levibostian/tap/foo` and homebrew will automatically look in `github.com/levibostian/homebrew-tap/Formula/foo.rb` to install that formula to then install the program. [Learn more](https://github.com/Homebrew/brew/blob/master/docs/How-to-Create-and-Maintain-a-Tap.md)