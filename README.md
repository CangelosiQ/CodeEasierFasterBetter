---------------------------------------------------------------------------
%                                                                         %
%                        CODE EASIER FASTER BETTER                        %
%          very simple tools for an enhanced coding experience            %
%                                                                         %
%    by Cangelosi Quentin (Jul. 2017) [cangelosi.quentin@gmail.com]       %
%                                                                         %
---------------------------------------------------------------------------

Folders and Files:
    - scripts:
        # presentation.py
        # 
..........................................................................

    I   - Introduction

    II  - Description of the scripts
        a. presentation.py

    III - What's next?

..........................................................................
I - Introduction

This repository is for very simple tools that I implemented to accelerate 
and simplify my process of coding while keeping quality output and clear 
scripts. For now it is just a beginning, if you read this and have ideas 
for new "simplification" tools I would be glad to hear them.

..........................................................................
II - Description of the scripts

    a. presentation.py
    
    I like to have a very clear output when running simulations, with 
    separating lines, information about the progression, titles, etc.
    The thing is, I don't like to waste time each time to reproduce these
    features so I created functions to help with this:
        
        - title(__yourTitle__): Make a good looking title with your text 
        inside
        
        - line(): Draw a line so that you can have a visual separation
        between your prints
        
        - big_iter(i,info=None): Print a remarkable output for each 
        iteration of your simulation. You just give the number of the 
        iteration and you get a well organized output with big separations
        at each iterations. You can also add a string 'info' to give you
        extra information about the progress of your work.
        
        - imports(list): I don't like to see my scripts full of import lines
        here is a solution to make it one line. (VERY primitive for now, I 
        basically just made it work for my current project but next update 
        should be more "generalized")
        

        
..........................................................................
III - What's next?

Good question...