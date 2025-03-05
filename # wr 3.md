# Notes 3

## echo
*# Notes 3

## echo
* **definition**:
 * used for displaying text on screen.
* **Usage**:
 * 'echo' + 'option' + 'string to print'
* **example**:
  * `echo "Hello, World!"` - prints "Hello, World!" to the screen.
  * `echo -e "Hello\tWorld"` - prints "Hello    World" with a horizontal tab.
  * `echo -e "This is line 1\nThis is line 2"` - prints two lines of text with a single echo command.
  * `echo "hello world"` - display/print a line of text
  * `echo -e "hello\tworld"` - Display a line of text with a horizontal tab
  * `echo -e "this is line 1\nthis is line 2"` - Display 2 lines of text with a single echo command
## date
 * **Definition**: 
     * displays or sets the system date and time.
* **Usage**: 
     * date [+FORMAT] [MMDDhhmm[[CC]YY][.ss]]
* **Example**: 
    * date '+%Y-%m-%d %H:%M:%S'
## free
* **definition**:
   * displays the amount of free and used memory in the system. 
* **usage**:
    * free [-h| -m| -g| -t]
* **example**:
    * free -h 
## uname
*  **definition**: 
    * displays system information. 
* **Usage**:
    * uname [-a |-r| -s |-n|-v|-m|-p|-i|-o]
* **example**:
    * uname -a 
## history
* **definition**:
    * shows the history of commands entered in the terminal. 
* **usage** 
    * history [-c][number]
* **example**: 
    * history 10 
## man
* **Definition** 
   * displays the manual page for a given command. 
* **Usage** 
   * man [command] 
* **Example**: 
   * man echo
## apt
* **Definition**:
    * package manager for debian-based distributions.
* **Usage**: 
    * sudo apt [install|remove|update|search][package]
* **Example**: 
    * sudo apt install figlet
## snap
* **Definition**: 
   * package manager to install and manage snap packages.
* **Usage**: 
  * snap [install|remove|refresh| list| find][package]
* **Example**: 
   * sudo snap install vscode --classic 
## flatpak
* **Definition**: 
   * system for building, distributing, and running sanboxed desktop applications on Linux.
* **Usage**: 
    * flatpak [install | remove| update | list |search][remove application]
* **Example**: 
   * flatpak install flathub org.mozilla.firefox 
  
