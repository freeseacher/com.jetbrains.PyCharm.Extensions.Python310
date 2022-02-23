# com.jetbrains.PyCharm.Extensions.Python310 

Let's bring python 3.10 to flatpak distr of PyCharm

This work is massively based on https://github.com/flathub/com.jetbrains.PyCharm.Extensions.Python2-7

# how to build

```
flatpak-builder --repo repo  build com.jetbrains.PyCharm.Extensions.Python310.yaml   --force-clean --user
```

# adding repo
```
flatpak remote-add --user mypython repo --no-gpg-verify
```

# how to install 

```
flatpak install --user mypython com.jetbrains.PyCharm.Extensions.Python310 --reinstall
```
