project('gtk-browser', 'c')
gtkdep = dependency('gtk+-3.0')
webgtkdep = dependency('webkit2gtk-4.0')
executable('tsinfo', 'browser.c', dependencies : [gtkdep, webgtkdep], install : true)
