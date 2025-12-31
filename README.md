![images/logo.png](images/logo.png)

> [!WARNING]
> DO NOT USE FOR **ANY** PURPOSE UNTIL THIS WARNING IS GONE!
> THE WARNING MEANS ZAPT-Interface is INCOMPLETE!

# an (at least made for) at-boot interface

run it at boot, mostly suited for ~~an~~ ***my*** Arch Linux installation (of course, to my preferences) but i'm sure it'll work for the majority of people

# depenencies

## required

- python (running the program)
- pytermgui (for the cool tui stuff)
- rich (for colours and bold fonts (✪o✪))

## optional

- network manager (wifi, ethernet configuration)
- blueman (bluetooth configuration)

# how to install

## method 1: manually

- clone repo `git clone https://github.com/therealzakie/zaptInterface.git && cd zaptInterface`
- add script path to `$PATH` directory list via your shell's config `export $PATH:{whatever the script directory is}`
- restart your terminal window or run `source {your shell config}`
- run `zapt`

<!--
 _______________________________________
/ that you are digging into the source  \
| code, i can see! coming soon so wait, |
\ the install script is.                /
 ---------------------------------------
        \
         \
          \         ____
           \     _.' :  `._
             .-.'`.  ;   .'`.-.
    __      / : ___\ ;  /___ ; \      __
  ,'_ ""--.:__;".-.";: :".-.":__;.--"" _`,
  :' `.t""--.. '<@.`;_  ',@>` ..--""j.' `;
       `:-.._J '-.-'L__ `-- ' L_..-;'
         "-.__ ;  .-"  "-.  : __.-"
             L ' /.------.\ ' J
              "-.   "--"   .-"
             __.l"-:_JL_;-";.__
          .-j/'.;  ;""""  / .'\"-.
        .' /:`. "-.:     .-" .';  `.
     .-"  / ;  "-. "-..-" .-"  :    "-.
  .+"-.  : :      "-.__.-"      ;-._   \
  ; \  `.; ;                    : : "+. ;
  :  ;   ; ;                    : ;  : \:
 : `."-; ;  ;                  :  ;   ,/;
  ;    -: ;  :                ;  : .-"'  :
  :\     \  : ;             : \.-"      :
   ;`.    \  ; :            ;.'_..--  / ;
   :  "-.  "-:  ;          :/."      .'  :
     \       .-`.\        /t-""  ":-+.   :
      `.  .-"    `l    __/ /`. :  ; ; \  ;
        \   .-" .-"-.-"  .' .'j \  /   ;/
         \ / .-"   /.     .'.' ;_:'    ;
          :-""-.`./-.'     /    `.___.'
                \ `t  ._  /
                 "-.t-._:'

 ## method 2: install script

- clone repo `git clone https://github.com/therealzakie/zaptInterface.git && cd zaptInterface`
- run script `./install`
- the script **should** add the script to your PATH by appending a line in your shell config file, or if not possible, it will instead add it to /usr/bin/.

-->