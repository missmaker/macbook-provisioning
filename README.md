# macbook-provisioning
## - Construct Mac Environment
### 1.Install Homebrew
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"  
### 2.Clone Repository  
$ git clone https://github.com/missmaker/macbook-provisioning.git
### 3.Install bundle
$ brew tap Homebrew/bundle  
### 4.Install
$ brew bundle

## - Install Python Packages
### 1.Collect installed packages
$ pip freeze > requirements.txt  
### 2.install packages
$ pip install -r requirements.txt  

## - Prepare Mac Environment
### You can create a Brewfile from all the existing Homebrew packages you have installed with
$ brew bundle dump  
### You can check there's anything to install/upgrade in the Brewfile by running:
$ brew bundle check  

## - Relation
### mas-ci
> A simple command line interface for the Mac App Store.    
> Using mas list will show all installed applications and their product identifiers.  
> $ mas list  
> It is possible to search for applications by name using mas search which will search the Mac App Store and return matching identifiers  
> $ mas search Xcode  
> To install or update an application simply run mas install with an application identifier    
> $ mas install 808809998  
> https://github.com/mas-cli/mas  
