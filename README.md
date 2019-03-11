This repository contains an example of a VBA macro spawning a process with a spoofed parent and command line. 

Companion blog post: https://blog.christophetd.fr/building-an-office-macro-to-spoof-process-parent-and-command-line

![Demo](https://user-images.githubusercontent.com/136675/54154646-49e44780-443a-11e9-998d-ec1f54a83437.gif)

## Notes

- Tested on Windows 10
- Will likely work only on 64-bit systems
- The size of the original command line stored in [`originalCli`](https://github.com/christophetd/spoofing-office-macro/blob/master/macro.vba#L260) needs to be greater than the size of the real one stored in [`cmdStr`](https://github.com/christophetd/spoofing-office-macro/blob/master/macro.vba#L311)

## Acknowledgments & inspiration

- ["Red Teaming in the EDR age"](https://www.youtube.com/watch?v=l8nkXCOYQC4) by Will Burgess 
- https://blog.xpnsec.com/how-to-argue-like-cobalt-strike/
- https://twitter.com/subtee
