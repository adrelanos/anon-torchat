# /etc/skel/.torchat/torchat.ini for Anonymity Distribution Workstations #

TorChat config file /etc/skel/.torchat/torchat.ini which
prevents Tor over Tor.

See also:
https://tor.stackexchange.com/questions/427/is-running-tor-over-tor-dangerous
## How to install `anon-torchat` using apt-get ##

1\. Add [Whonix's Signing Key](https://www.whonix.org/wiki/Whonix_Signing_Key).

```
sudo apt-key --keyring /etc/apt/trusted.gpg.d/whonix.gpg adv --keyserver hkp://ipv4.pool.sks-keyservers.net:80 --recv-keys 916B8D99C38EAF5E8ADC7A2A8D66066A2EEACCDA
```

3\. Add Whonix's APT repository.

```
echo "deb http://deb.whonix.org stretch main" | sudo tee /etc/apt/sources.list.d/whonix.list
```

4\. Update your package lists.

```
sudo apt-get update
```

5\. Install `anon-torchat`.

```
sudo apt-get install anon-torchat
```

## How to Build deb Package ##

Replace `apparmor-profile-torbrowser` with the actual name of this package with `anon-torchat` and see [instructions](https://www.whonix.org/wiki/Dev/Build_Documentation/apparmor-profile-torbrowser).

## Contact ##

* [Free Forum Support](https://forums.whonix.org)
* [Professional Support](https://www.whonix.org/wiki/Professional_Support)

## Payments ##

`anon-torchat` requires [payments](https://www.whonix.org/wiki/Payments) to stay alive!
