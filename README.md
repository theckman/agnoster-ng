# agnoster-ng

`agnoster-ng` is a ZSH theme which is expected to be used within `oh-my-zsh` or
within `antigen` + `oh-my-zsh`. This theme originated from the version of the
`agnster` distributed with `oh-my-zsh`.

`agnoster` is a theme which was originally by [Isaac Wolkerstorfer](https://github.com/agnoster).
It was then added and enhanced as part of the [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)
distribution. The original version by Isaac can be found
[here](https://github.com/agnoster/agnoster-zsh-theme).

The biggest difference between `agnoster` in `oh-my-zsh` and `agnoster-ng`, is
the addition of the `AGNOSTER_CURRENT_PATH` variable which allows you to change
how the path is rendered on your prompt. By default it uses the `agnoster`
behavior of printing the full path if a path relative to your home directory
isn't available (`/var/path/to/file`, or `~/path/to/file`).

If you're working many directories down, your prompt can start to get very long.
To use only the name of the current folder, you can set `AGNOSTER_SHORT_PATH=1`.
That would make the folder `~/path/to/file` render as just `file`.

To have these settings persist, just drop them in to your `.zshrc` file.`

## License
This is released under the `MIT License`. Because this was copied from the
`oh-my-zsh` project, it shares the same license and the copyright was retained.
Please see the `LICENSE` file for more details.
