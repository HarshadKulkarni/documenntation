# documenntation

```
Force Homebrew to ignore SSL verification

export HOMEBREW_CURLRC=1
echo "-k" >> ~/.curlrc

Then run:

/bin/bash -c "$(curl -fsSLk https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
