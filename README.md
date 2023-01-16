# nnn-plugs
Home-crafted nnn plugins created for my own use. Happy to share under the Open Unlicense

I often want to email others (or myself!) files/attachments - sometimes entire directories - 
containing sensitive info such as account numbers, passwords, etc. Before doing so, I want 
to compress larger files and then password protect (i.e., robustly encrypt) the files.

nnn is an outstanding file manager! Being able to accomplish this compression & encryption
easily within nnn prompted me to craft a couple of fairly simple plugin scripts...

1. arcenc - Archive Encryption using tar archival tools & gpg encryption
2. arcdec - Archive Decryption, also using tar and gpg

Dependencies ... well, you need to have tar and gpg installed, which I suspect is not 
unusual for most Linux installations.

I'm fairly new at bash scripting and made these shell scripts for my own use, so I'm
SURE they could be improved upon further. I'd WELCOME any suggestions on how to 
streamline, improve clarity, or protect again stray errors that are not currently
trapped by my simple case testing.

And, if you enjoy using these plugins and find them helpful in your own workflow, 
I'd be delighted to know. 
