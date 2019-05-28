# kkonfig
K8S context selector

## Prerequisites ##

- `kubectl`
- `awk`
- `sed`

## Installation ##

```
mkdir ~/bin
mkdir ~/.bash_completion
install ./kkonfig ~/.bin/kkonfig
cp kkonfig-completion ~/.bash_completion/ 
```

```
echo "#KKONFIG Completion:" >> ~/.bash_profile
echo "source ~/.bash_completion/kkonfig-completion" >> ~/.bash_profile
```

# Usage #

```kkonfig NAME OF YOUR CONTEXT```
