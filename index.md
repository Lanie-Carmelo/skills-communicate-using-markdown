# Level 1 Heading, largest

## Level 2 Heading

### Level 3

#### Level 4

##### Level 5

###### Level 6, smallest
![A red and purple illustrated bird flying and the words "Life of a Rare Bird"](https://laniecarmelo.tech/wp-content/uploads/2024/11/Red-and-Purple-Modern-Illustrative-Bird-Logo.png)

```
# Does not rely on package managers
# Recommended for ephemeral environments (e.g. CI jobs)
# Supports Linux, BSD, and macOS

# Requires Curl & GnuPG:
#        Alpine: apk add curl gnupg
#   CentOS/RHEL: yum install -y curl gnupg
# Ubuntu/Debian: apt install -y curl gnupg
#   AmazonLinux: yum install -y --allowerasing gnupg2

(curl -Ls --tlsv1.2 --proto "=https" --retry 3 https://cli.doppler.com/install.sh || wget -t 3 -qO- https://cli.doppler.com/install.sh) | sudo sh
```
