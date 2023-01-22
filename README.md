# nnn-plugs
Home-crafted nnn plugins created for my own use. Happy to share under the Open Unlicense

- - - - - - - - - 
## arcenc & arcdec ## 

ISSUE: I often want to email others (or myself!) files/attachments - sometimes entire directories - 
containing sensitive info such as account numbers, passwords, etc. Before doing so, I want 
to compress larger files and then password protect (i.e., robustly encrypt) the files.

nnn is an outstanding file manager! Being able to accomplish this compression & encryption
easily within nnn would be ideal for me.

SOLUTION: So I crafted a couple of simple plugin scripts...

1. arcenc - Archive Encryption using tar archival tools & gpg encryption
2. arcdec - Archive Decryption, also using tar and gpg

Dependencies ... well, you need to have tar and gpg installed, which I suspect is not 
unusual for most Linux installations.
- - - - - - - - - 

## ethunder ##

ISSUE: Many times, while navigating around within the `nnn` file manager, I want to send 
a particular file via email ... either to myself (to fetch on another PC via my 
email account) or more commonly to a family member, friend, or business associate.

BTW, I use the latest version of Mozilla's Thunderbird. 

Frankly, it's a pain to (1) leave `nnn` (2) access my Thunderbird email app (3) create a new message, 
(4) fish around to find that file I saw within `nnn` that I'd wanted to attach, (5) attach it,
(6) then start composing my message (7) send it off (8) go back to `nnn` and resume whatever I was doing.

And so, I created this `nnn` plugin (i.e., bash script, i.e., can also be used outside of `nnn`)
named `ethunder` to make this a lot easier (*email* attachment via *Thunderbird*).

**USAGE: (1) Select a single file within `nnn` (2) invoke the plugin.** 

*You will shortly see Thunderbid open up in composition mode with a new
outgoing email with your selected file as an attachment. Enter the recipient, 
a subject and message if you like, and hit send.*  

# Done. #

- - - - - - - - - 

I'm fairly new at bash scripting and made these shell scripts for my own use, so I'm
SURE they could be improved upon further. I'd WELCOME any suggestions on how to 
streamline, improve clarity, or protect against stray input errors not currently
trapped by my rudimentary case testing.

And, if you enjoy using these plugins and find them helpful in your own workflow, 
I'd be delighted to know. 
