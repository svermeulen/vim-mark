This is a mirror of [Ingo Karkat's Mark plugin](http://www.vim.org/scripts/script.php?script_id=2666).
The [vim-scripts](https://github.com/vim-scripts/Mark--Karkat) depot is out of date.

DESCRIPTION 
This plugin adds mappings and a :Mark command to highlight several words in 
different colors simultaneously, similar to the built-in 'hlsearch' 
highlighting of search results and the * command. For example, when you 
are browsing a big program file, you could highlight multiple identifiers in 
parallel. This will make it easier to trace the source code. 

This is a continuation of vimscript #1238 by Yuheng Xie, who doesn't maintain 
his original version anymore and recommends switching to this fork. This 
plugin offers the following advantages over the original: 
- Much faster, all colored words can now be highlighted, no more clashes with 
  syntax highlighting (due to use of matchadd()). 
- Many bug fixes. 
- Jumps behave like the built-in search, including wrap and error messages. 
- Like the built-in commands, jumps take an optional [count] to quickly skip 
  over some marks. 
- Marks can be persisted, and patterns can be added / subtracted from 
  mark highlight groups. 
