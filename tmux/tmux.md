# TMUX cheat sheet

~/.tmux.conf &rarr; conf file of tmux  
tmux source-file ~/.tmux.conf &rarr; save chanegs on tmux conf file  
tmux new  -s name &rarr; crate new tmux session  
tmux ls &rarr; list o tmux sessions  
tmux attach -t name &rarr; attach to tmux session  
tmux kill-session -t name &rarr; kill session  
tmux ls &rarr; tmux sessions  
exit &rarr; kill window



## With Prefix  (C + b)  

### Windows

c &rarr; create new window  
number &rarr; go to window  
, &rarr; rename pane  
& &rarr; kill window  
n &rarr; next window  
p &rarr; previous window  
w &rarr; choose window from a list

### Panes
% &rarr; vertical split  
" &rarr; horizontal split  
z &rarr; zoom in and out  
x &rarr; kill pane  
arrow &rarr; move 

### Edit mode
[ &rarr; edit mode  
? &rarr; search  
space &rarr; copy mode  
enter &rarr; copy to buffer  
] &rarr; paste what u copy 
: &rarr; go to line  
Escape &rarr; 	Clear selection                  
j   &rarr;	Cursor down                          
h &rarr;		Cursor left                    
l  &rarr;	Cursor right                         
L  &rarr; Cursor to bottom line   
M &rarr;  Cursor to middle line                 
H  &rarr; Cursor to top line                    
k  &rarr; Cursor up                             
d &rarr;  Delete entire line                    
D  &rarr; Delete to end of line                 
$  &rarr; End of line                           
:  &rarr; Goto line                             
C-d  &rarr; Half page down                     
C-u &rarr;  Half page up                       
C-f  &rarr; Next page                           
w &rarr;  Next word                         
p &rarr;  Paste buffer                     
C-b &rarr;  Previous page                       
b  &rarr; Previous word                         
q  &rarr; Quit mode                             
C-Down or J &rarr;  Scroll down      
C-Up or K  &rarr;  Scroll up                   
n  &rarr; Search again                          
?  &rarr; Search backward                       
/  &rarr; Search forward                        
0  &rarr; Start of line                        




### View
{ &rarr; Move the current pane left  
} &rarr; Move the current pane right
(holding C prefix) arrow &rarr; change size  
space &rarr; rotate 


## Others
d &rarr; detach  
? &rarr; help usage  
t &rarr; time

## : Terminal
break-pane  
split-pane  
join-pane -s :number &rarr;	send pane to  
join-pane -t :number &rarr;	join pane from  
source-file ~/.tmux.conf	&rarr; save chanegs on tmux conf file


Its a good idea to rebind C + b (prefix) so when using tmux over ssh

Tmux: Logging Plugin
https://github.com/tmux-plugins/tmux-logging
prefix Alt Shift P --> save complete pane history to a file


[//]: # ( 
Will remove that in another place
Terminal
Alt . + going throght history as argument
C a go to head
C e go to end
)


