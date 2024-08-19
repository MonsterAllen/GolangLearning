## How to install
1. Download dev package from this website https://go.dev/doc/install

2. get the sudo premission 

```
sudo su

```
3. Remove any previous Go installation by deleting the /usr/local/go folder (if it exists), then extract the archive you just downloaded into /usr/local, creating a fresh Go tree in /usr/local/go:

```
rm -rf /usr/local/go && tar -C /usr/local -xzf go1.23.0.linux-amd64.tar.gz
```

4. Add /usr/local/go/bin to the PATH environment variable.

```
export PATH=$PATH:/usr/local/go/bin
```

5.Verify that you've installed Go by opening a command prompt and typing the following command:

```
go version
```
