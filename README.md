# Instashell v1.5.4
## Author: github.com/cyberkallan
## IG: instagram.com/arz_beats
### Don't copy this code without give me the credits, nerd! 
Instashell is an Shell Script to perform multi-threaded brute force attack against Instagram, this script can bypass login limiting and it can test infinite number of passwords with a rate of +400 passwords/min using 20 threads.

## Legal disclaimer:
Usage of InstaShell for attacking targets without prior mutual consent is illegal. It's the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program 

![insta](https://user-images.githubusercontent.com/56509491/66737997-0dbf0c80-ee8b-11e9-934d-0c8efd9bef90.jpg)

### Features
- Multi-thread (400 pass/min, 20 threads)
- Save/Resume sessions
- Anonymous attack through TOR
- Check valid usernames
- Default password list (best +39k 8 letters)
- Check and Install all dependencies

### Usage:
```
git clone https://github.com/cyberkallan/instashell-bruitforce
cd instashell-bruitforce
chmod +x instashell.sh
service tor start
sudo ./instashell.sh
```

### Install requirements (Curl, Tor, Openssl):

```
chmod +x install.sh
sudo ./install.sh
```

### How it works?

Script uses an Android ApkSignature to perform authentication in addition using TOR and rotating the ip address to avoid blocking. 
The script uses Instagram-py algorithm, see the project at: https://github.com/antony-jr/instagram-py

### Donate!
Support the authors:

<noscript><a href="https://liberapay.com/thelinuxchoice/donate"><img alt="Donate using Liberapay" src="https://liberapay.com/assets/widgets/donate.svg"></a></noscript>
