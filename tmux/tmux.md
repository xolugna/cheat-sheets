# TMUX cheat sheet

    ~/.tmux.conf conf file of tmux  
    tmux source-file ~/.tmux.conf   save changes on tmux conf file  
    tmux new  -s name               create new tmux session  
    tmux ls                         list tmux sessions  
    tmux attach -t name             attach to tmux session  
    tmux kill-session -t name       kill session    
    exit                            kill window



## With Prefix  (Ctrl + b)  

### Windows

    c       create new window 
    ,       rename pane  
    &       kill window  
    n       next window  
    p       previous window  
    w       choose window from a list
    number  go to window  

### Panes
    %       vertical split  
    "       horizontal split  
    z       zoom in and out  
    x       kill pane  
    arrow   move 

### Edit mode
    [               edit mode  
    ?               search  
    space           copy mode  
    enter           copy to buffer  
    ]               paste what u copy 
    :               go to line  
    Escape          Clear selection                      
    j    	        Cursor down                    
    h               Cursor left                       
    l               Cursor right                             
    L               Cursor to bottom line   
    M               Cursor to middle line                     
    H               Cursor to top line                        
    k               Cursor up                                 
    d               Delete entire line                        
    D               Delete to end of line                     
    $               End of line                               
    :               Goto line                                 
    C-d             Half page down                         
    C-u             Half page up                           
    C-f             Next page                               
    w               Next word                             
    p               Paste buffer                         
    C-b             Previous page                           
    b               Previous word                             
    q               Quit mode                                 
    C-Down or J     Scroll down      
    C-Up or K       Scroll up                       
    n               Search again                              
    ?               Search backward                           
    /               Search forward                            
    0               Start of line                        




### View
    {                           Move the current pane left  
    }                           Move the current pane right
    (holding C prefix) arrow    Change size  
    space                       Rotate 


## Others
    d   detach  
    ?   help usage  
    t   time

## : Terminal
    break-pane  
    split-pane  
    join-pane -s :number  	    send pane to  
    join-pane -t :number  	    join pane from  
    source-file ~/.tmux.conf    save chanegs on tmux conf file


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


