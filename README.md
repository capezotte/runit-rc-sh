# runit-rc-sh

Tentative rewrite of Artix's runit-rc package for compatibility with more lightweight sh implementations (dash and busybox sh). 

# Todo (in order of priority?)

- Check whether sv.d/root actually works properly on shutdown
- Test cryptsetup and lvm2 on a machine that uses them
- Rely less on `math_check` ( `((` polyfill )
- Avoid `local` keyword
