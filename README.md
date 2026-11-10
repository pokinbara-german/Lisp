# Description
This is simple text parser in MULISP-85 (also tasted on Microsoft MULISP-86) from my student times.\
It can also trim spaces inside texts and fully recursive (does not use imperative features of language).

This is just a basic parsing concept. Result of this program can be used in further text processing.

# Using
1. You need muLisp85+ interpreter.\
can be found here: [Mega.nz](https://mega.nz/file/gbgzBQaA#mtFxZgQdelzT3y0Quo4cWKdNmV7qFawXH60X6c5syrk)\
or here (this is diskete image file): [Archive.org](https://archive.org/details/microsoft-mulisp_202301)
2. You need DosBOX. Probably you don't have MSDOS on your computer right now and don't want to run anything from the Internet on your own computer.\
can be found here: [dosbox.com](https://www.dosbox.com/download.php?main=1)
3. Rename your MULISP distro to something simple like `mulisp`
4. Run DosBox and type something like `mount c ~/Downloads/mulisp` to mount it to DosBox.
5. Add this programm to your MULISP distro directory.
6. Now you can run command `mulisp l2sl.lsp`\
This will run whole file with auto-tests. If test was successful it will show `$ T` if not `$ NIL`.\
Last `NIL` is always there because it is the end of execution (special cool way of MULISP to say `Goodbye!`).
8. Now you can try it by yourself `(main "My unparsed text string!!!")`


```text
                  _      _           
                 | |    (_)          
  _ __ ___  _   _| |     _ ___ _ __  
 | '_ ` _ \| | | | |    | / __| '_ \ 
 | | | | | | |_| | |____| \__ \ |_) |
 |_| |_| |_|\__,_|______|_|___/ .__/ 
                              | |    
                              |_|       
```
