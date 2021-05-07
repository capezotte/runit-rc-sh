# runit-rc-sh

Tentative rewrite of Artix's runit-rc package for compatibility with more lightweight sh implementations (dash and busybox sh). 

# Todo (in order of priority?)

- Fix unescaped \e appearing in Linux console during boot
- Still have bashisms: dmesg, cryptsetup, root
- Rely less on math\_check (AKA mental polyfill for (()
- Maybe forgo local altogether?
