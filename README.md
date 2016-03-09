##Command Line Unicode Characters in the Miscellaneous Symbols and Pictographs Block
This is only a list of aliases that map the uppercase name of the symbol/pictograph to the actual symbol or pictograph.

###Installation 
💻


* Paste the contents of `cliemo_bash_profile` into your `~/.bash_profile` or `/etc/bashrc` 
* Then `source ~/.bash_profile`

###Usage
All aliases are UPPERCASE, so to search, you start typing the word in upper case, then you can just tab to complete. 
Like so... (I put the keys to press in square brackets `[ ]`)

    ~$ PI[tab]
    PIG    PIG_FACE    PIG_NOSE    PILE_OF_POO  PILL   PINEAPPLE   PINE_DECORATION PISTOL
    ~$ PINE[tab]
    PINEAPPLE        PINE_DECORATION  
    ~$ PINEA[tab]
    ~$PINEAPPLE[enter]
    ~$🍍
    ~$PINEAPPLE | pbcopy[enter]
    ~$

Now 🍍 is on my clipboard and I can paste it right into my résume using `command+v` or `control+v`. You'll for sure get the gig with some flashy picto-shit in your résume!

###How do I search all these pictographs?

Since it's just a list in your `~/.bash_profile`, you can `grep` it like this...

    ~ $ grep -i "pizza" ~/.bash_profile 
    108:alias SLICE_OF_PIZZA="echo 🍕"
     ~ $ 

Now I know that it's called SLICE\_OF\_PIZZA, not just PIZZA, that's why I couldn't find it before.


###You're missing a bunch

Yea, I know. this was a quick and dirty list that I put together from Wiki. Feel free to add and to help me out instead of just bitching about it.
    🍍

