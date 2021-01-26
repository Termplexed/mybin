# mybin

Various linux scripts

### `binhelp` : print number(s) in various representaions.
```
$ binhelp 136:139
From: (0x88 to 0x8B) (0o210 to 0o213) (136. to 139.)
      136.  0000 0000 1000 1000  0x00000088        210o
      137.  0000 0000 1000 1001  0x00000089        211o
      138.  0000 0000 1000 1010  0x0000008a        212o
      139.  0000 0000 1000 1011  0x0000008b        213o
```

### `mkvarious` : create executable script file with appropriate shebang

1. Put it in for example `~/bin`
2. Create links for types:
   `ln -s sh mkvarious`
   `ln -s python mkvarious`
   `ln -s bash mkvarious`
3. `mksh foo` creates the file `foo` with `+x` set and a `!#/bin/sh` head.

Opens file with `$ed` (set in script to vim) if no second option is used.

Modify script to meet your needs.
