# kkonfig
K8S context selector

## Prerequisites ##

- `kubectl`
- `awk`
- `sed`

## Installation ##

```
git clone git@github.com:grifonas/kkonfig.git
cd kkonfig
mkdir ~/bin
mkdir ~/.bash_completion
install ./kkonfig ~/bin/kkonfig
cp kkonfig-completion ~/.bash_completion/ 
```

```
echo "#KKONFIG Completion:" >> ~/.bash_profile
echo "source ~/.bash_completion/kkonfig-completion" >> ~/.bash_profile
```

# Usage #

- Changing K8S context: 

```kkonfig NAME_OF_YOUR_CONTEXT```

- Listing K8S contexts:

```kkonfig```


