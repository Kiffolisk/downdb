# downdb
bad package manager made in c++

## how to install manually
download the downdb file from the releases, from browser or from command line, then execute this:
```bash
chmod +x ./downdb && sudo cp ./downdb /usr/bin/downdb
```

## installing a package
```bash
sudo downdb install [name]
```
OR
```bash
downdb install [name]
```
(if not executing as root, executing without "sudo" will ask root password)
