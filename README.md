<div align="center">
	<h1>Hilbish</h1>
	<blockquote>
	🎀 a nice lil shell for lua people made with go and lua
	</blockquote>
</div>

Hilbish is an interactive Unix-like shell written in Go, with the config
and other code written in Lua.  
It is currently in a Beta state. Though very fit for daily usage,
updates may contain breaking changes.

# Screenshots
<div align="center">
<img src="gallery/default.png"><br><br>
<img src="gallery/terminal.png"><br><br>
<img src="gallery/pillprompt.png">
</div>

# Links
- **[Documentation](https://github.com/Hilbis/Hilbish/wiki)**
- **[Gallery](https://github.com/Hilbis/Hilbish/discussions/36)** - See
more screenshots of Hilbish in action

# Building
Prebuilt binaries are not yet provided, so to try it out you'll have to manually compile.  

**NOTE:** Hilbish is currently only officially supported and tested on Linux

### Prerequisites
- [Go 1.16](https://go.dev)

- GNU Readline

On Fedora, readline can be installed with:  
```
sudo dnf install readline-devel
```  

On Debian/Ubuntu and distros based on them, it can be installed with:  
```
sudo apt install libreadline-dev
```

### Install
```sh
git clone https://github.com/Hilbis/Hilbish
cd Hilbish
make build
sudo make install
# Or 
sudo make all
```

Alternativly, if you use Arch Linux, you can compile Hilbish with an **(unofficial)** AUR package
```sh
yay -S hilbish-git
```
Or install a prebuilt binary from an **(unofficial)** AUR package
```sh
yay -S hilbish
```

### Uninstall
```sh
sudo make uninstall
```

# Contributing
Any kind of contributions to Hilbish are welcome!   
Make sure to read [CONTRIBUTING.md](CONTRIBUTING.md) before getting started.

### Special Thanks To
Everyone here who has contributed:
<a href="https://github.com/Hilbis/Hilbish/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Hilbis/Hilbish" />
</a>

*Made with [contributors-img](https://contrib.rocks).*

### Credits
- [This blog post](https://www.vidarholen.net/contents/blog/?p=878) which
is how Hilbish now inserts a newline even if output doesn't have one.

# License
Hilbish is licensed under the MIT license.  
[Read here](LICENSE) for more info.
