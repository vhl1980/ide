# Ide

## VIM

Tips for split
https://vi.stackexchange.com/questions/64/is-it-possible-to-split-vim-window-to-view-multiple-files-at-once#:~:text=You%20can%20either%20split%20vim,vert%20ba%20to%20split%20vertically.

You can either split vim windows by opening multiple files using -o, -O, -o2 parameters.  
Or if you're already editing multiple files in one window, you can use :ba to split horizontally or :vert ba to split vertically.  
:[N]ba[ll] [N] :[N]sba[ll] [N] Rearrange the screen to open one window for each buffer in the buffer list.  
:vert[ical] {cmd} Execute {cmd}. If it contains a command that splits a window, it will be split vertically.  

