# blobs

##### Assumptions
> Ensure you have pipenv installed `brew install pipenv`
> Using zsh as your terminal.

### Python Environments
###### New Env
`pipenv --three` (Python3)
###### Install a Requirement
`pipenv install [PACKAGE]`
###### Install a Dev Requirement
`pipenv install --dev [PACKAGE]`

### Environment Switching
`echo "function work() {cd ~/code/$1; pipenv shell}" >> ~/.zshrc`
