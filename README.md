# Use it like this:


`https://raw.githubusercontent.com/petr-nazarov/preseed/main/debian.cfg`
or
`https://rb.gy/s257jl`
On the boot menu (where you see "Install", "Graphical Install", etc.), highlight Install.

Press the Tab key (or 'e' if you are using a UEFI system).

You will see a line of boot parameters. Move to the end of that line, add a space, and type:
Bash

```
auto=true priority=high url=https://raw.githubusercontent.com/your-url-here
```

Press Enter.

