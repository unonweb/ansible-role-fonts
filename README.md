TO DO
=====

NOTES
=====

```sh
/usr/share/fonts # system-wide
~/.local/share/fonts # user-specific
~/.fonts # user-specific
```

LINKS
=====

- https://github.com/ryanoasis/nerd-fonts/releases
- https://github.com/ryanoasis/nerd-fonts/releases/download/v3.3.0/CodeNewRoman.zip

USE
===

```yml
# fonts
- ansible.builtin.import_role:
	name: fonts
	vars:
	fonts_system_download: 
	- url: https://github.com/ryanoasis/nerd-fonts/releases/download/v3.3.0/CodeNewRoman.zip
		name: CodeNewRoman
```
