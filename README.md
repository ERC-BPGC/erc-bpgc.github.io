# ERC Website

The Official Website of the Electronics and Robotics Club of BITS Goa.

Built using Jekyll Framework

## Installation Instructions(Windows)

Requirements: git, ruby, gem, jekyll

1. Install Scoop: A command line tool for installing and managing software.

   ```shell
   powershell
    iex (new-object net.webclient).downloadstring('https://get.scoop.sh')
   ```

2. Install Curl: A command line tool for transferring data with URL syntax.

   ```shell
   scoop install curl
   curl https://get.scoop.sh
   ```

3.  Install Ruby.  
    -  Go to this [link](https://rubyinstaller.org/) to download the latest version of Ruby.  
    -  Run the installer and add the bin folder from the Ruby folder in the C: drive to your PATH.

## Running Local Host Server

In root directory of the repository, run the following command:

```shell
bundle exec jekyll serve
```

Output: 

```shell
Configuration file: C:/Users/<path to repository>/erc-bpgc.github.io/_config.yml  
    Source: C:/Users/<path to repository>/erc-bpgc.github.io  
Destination: C:/Users/<path to repository>/erc-bpgc.github.io/_site  
Incremental build: disabled. Enable with --incremental  
Generating...  
DEPRECATION WARNING on line 7 of C:/Users/<path to repository>/erc-bpgc.github.io/_sass/libs/_skel.scss:  
!global assignments won't be able to declare new variables in future versions.  
Consider adding `$breakpoints: null` at the top level.  
Please add the following to your Gemfile to avoid polling for changes:  
gem 'wdm', '>= 0.1.0' if Gem.win_platform?  
Auto-regeneration: enabled for 'C:/Users/<path to file>/erc-bpgc.github.io'  
Server address: http://127.0.0.1:4000  
Server running... press ctrl-c to stop.  
Note:- Ruby and gemfile are required to run the server
```

Copy the Server Address given into your browser.  
Reload the browser tab when you make changes.

