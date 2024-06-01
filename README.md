# Minecraft Server Info
## Install Oracle JDK 21 on Debian

The Oracle JDK is not fully open source implementation of Java SE specification. It is packaged with additional tools and features that are not available in the standard Java APIs. If your application needs support from Oracle on updates and security patches in a timely manner, then this is a better option for you.

Oracle JDK 21 can be downloaded from Oracle Downloads pages. If you’re a CLI user, this can be downloaded using `wget` or `curl`.

```sh
wget https://download.oracle.com/java/21/latest/jdk-21_linux-x64_bin.deb
```
Once the package is downloaded, perform install with the apt or dpkg package management tool available for Debian users.
```sh
sudo dpkg -i jdk-21_linux-x64_bin.deb
```

link: [CraftBukkit 1.20.1](https://download.getbukkit.org/craftbukkit/craftbukkit-1.20.1.jar)
