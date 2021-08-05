# codeblocks


```bash
curl -L https://sourceforge.net/projects/codeblocks/files/Sources/20.03/codeblocks-20.03.tar.xz -o codeblockssource.tar.xz
mkdir codeblocks
cp codeblockssource.tar.xz ./codeblocks
cd codeblocks/
tar -xvf codeblockssource.tar.xz
cd codeblocks-20.03/
```

```bash
dnf -y install libtool wxGTK3-devel  compat-wxGTK3-gtk2
#Package libtool-2.4.6-25.el8.x86_64 is already installed.
#Package wxGTK3-devel-3.0.4-11.el8.x86_64 is already installed.
#Package compat-wxGTK3-gtk2-3.0.4-11.el8.x86_64 is already installed.
#rm -f /var/lib/rpm/__db*

#wx-config
#root@marcrhel82 ~]# wx-config --version
#3.0.4
  
echo `wx-config --prefix`/share/aclocal >> /usr/share/aclocal/dirlist
```


```bash
dnf -y group install "Development Tools"
```


```bash
./bootstrap
./configure
make
make install
```

```bash
codeblocks
```

