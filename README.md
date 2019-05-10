# vimrc
my customized vimrc, using vundle to manage plugins.

clone this repo , then 

```shell
sh setup.sh
```
Follow the above step, you need to manually change pymode_exec_path in ~/.vimrc
for example:
```
let g:syntastic_python_python_exec='/path/to/your/python'
```

Ignore warnings, type Enter.

then you'll be free to use it.


**some cheatsheet**
```
leader key: \
commment: <leaderkey>+'cc'
uncomment: <leaderkey>+'c '
undo: u
insert a line above: O
insert a line below: o
exit to command mode: jj or kk 
pdb: <leaderkey>+'b'
visual mode: v
select a block: hjkl
intent: > <
copy: y
past: p
delete: x D dd
doc end: G
doc begin: gg
buffer: <F9> <F10>
vsplit xxxx.py xxx.py
next buffer: ctrl + 'ww' or ctrl + 'w' + lrtb
```
