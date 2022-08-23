<div align=center>
  <img width=500 src='https://user-images.githubusercontent.com/20311086/186057854-255040f7-320c-43b9-b617-0871bfbc75a5.png' />
  <br>
<span><span><span style="color:#ED4A46;">p</span><span style="color:#70B433;">r</span><span style="color:#DBB32D;">e</span><span style="color:#368AEB;">t</span><span style="color:#EB6EB7;">t</span><span style="color:#3FC5B7;">y&nbsp;</span></span><span><span style="color:#E67F43;">c</span><span style="color:#A580E2;">o</span><span style="color:#FF87B2;">n</span><span style="color:#F4E06D;">f</span><span style="color:#FF87B2;">i</span><span style="color:#A580E2;">g&nbsp;</span></span><span><span style="color:#E67F43;">f</span><span style="color:#3FC5B7;">i</span><span style="color:#EB6EB7;">l</span><span style="color:#368AEB;">e</span><span style="color:#DBB32D;">s</span></span></span>
  <hr>

<sup><i>Original: <a href="https://github.com/squigglezworth/dotfiles"><code>squigglezworth/dotfiles</code></a> — Mirror for easier fetching: <a href='https://github.com/squigzy/squigzy.github.io/'><code>squigzy/squigzy.github.io</code></a></i></sup>
</div>

### To install these on a new system... [^1]

- <a href="https://wiki.debian.org/DebianInstaller/Preseed">Preseed</a> a Debian installation with <a href='.preseed'>`.preseed`</a> (served at <a href="https://squigzy.github.io/.preseed">`squigzy.github.io/.preseed`</a>)<br>
- The preseed fetches this repo, enables <a href="systemd/autologin.conf">autologin</a>, installs <a href='bash/bashrc'>`~/.bashrc`</a>, and creates a blank `~/.init` file<br>
- On the first login, <a href='bash/bashrc'>`~/.bashrc`</a> will see `~/.init` and call <a href='.setup/init.sh'>`.setup/init.sh`</a>, which will orchestrate the installation & configuration of everything else<br>

[^1]:...which you really shouldn't do unless you know what you're doing.
