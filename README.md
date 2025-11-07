## What is a Bash shell scripting.

A Bash shell scripting banner maker is simply a script written in Bash (the Bourne Again Shell) that displays a custom banner — often ASCII art, text, or colorful info — when you open your terminal (like Termux or Linux terminal).


__TYPE NAME__ :
- Here type your name which you want to show in your terminal.

```
#### Display ########################

echo -e "\e[0;37m" 
clear
echo
echo -e " \e[1;32m  ░██████╗░██╗░░░██╗██╗░░░░░██╗░░░░░  ██╗░░██╗██╗░░██╗░█████╗░███╗░░██╗ \e[0m"
echo -e " \e[1;32m  ██╔════╝░██║░░░██║██║░░░░░██║░░░░░  ██║░██╔╝██║░░██║██╔══██╗████╗░██║ \e[0m"
echo -e " \e[1;32m  ██║░░██╗░██║░░░██║██║░░░░░██║░░░░░  █████═╝░███████║███████║██╔██╗██║ \e[0m"
echo -e " \e[1;32m  ██║░░╚██╗██║░░░██║██║░░░░░██║░░░░░  ██╔═██╗░██╔══██║██╔══██║██║╚████║ \e[0m"
echo -e " \e[1;32m  ╚██████╔╝╚██████╔╝███████╗███████╗  ██║░╚██╗██║░░██║██║░░██║██║░╚███║ \e[0m"
echo -e " \e[1;32m  ░╚═════╝░░╚═════╝░╚══════╝╚══════╝ ╚═╝░░╚═╝╚═╝░░╚═╝╚═╝░░╚═╝╚═╝░░╚══╝  \e[0m"
echo
```
