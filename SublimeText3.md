# Cheat sheet for using sublime text 3:
[Reference](https://www.youtube.com/watch?v=_JFIeY46sIU "Tuts 1,2,3 etc")

### Basics
* Insert word in several places: **Click+ctrl** in all places - adding several cursors 
* Changing many words at once (find & replace): Highlighting a word, will show it in several places. You can just press **ctrl-d** and it will add
highlighting to the next instance of the word, continuously. 
* Add same text on beginning of multiple lines: press **shift** key & click **right** mouse button and drag.
* Add at end: Same as above, **OR** highlight the lines you want, and press **ctrl+shift+l** each line becomes editable. 
* Wrapping selection in element: **alt+shift+w** (To do on all lines - need item above first, making each line editable (don't select all lines normal way))
* To move a whole line up or down, above/ below other lines, press **ctrl+shift+arrow** and it moves :) 
* To duplicate a line **ctrl+shift+d** 
* To delete a line **ctrl+shift+k**
* Indentation: 
	- List items 'li' out of line indentation - press **ctrl+'[ or ']'** do go left or right 
	- But can do many lines: highlight all: go to **Edit>Line>Reindent** - can do a WHOLE page
	- When pasting in HTML - intelligent pasting: **ctrl+shift+V** 

### Working on Projects 
* Can import a whole project by opening sublime text and then looking for the project folder and dragging and dropping into sublime text 
* **ctrl+P** to find the file that you want to edit from your project 
* Now, to go to a specific function (in js for eg)/ selector/ class (in html or css) : press **@** and then type name
* Now, looking for a specific search result press **#** 
* Jump to a specific line: press **colon (:)**
* Note, we don't need to open a file with ctrl P, can use it even in open files to go and use the above three (function, search, line no)
* BEFORE SAVING: right-click and select 'show unsaved changes' just to make sure you're happy with ur changes  (then press **escape** to continue out of it and go press save)
* Can create new files or folders by right clicking on side bar where project files are!
Can add new folders that werent part of your project and then, if you want, save them together as a 
sublime project: **Select Project > Save Project as** and this will save this collection of files and folders 
as a .sublime-project folder

### Command Palette **ctrl+shift+P**

* There are a whole range of amazing things that can be done with this command palette - these are just some egs. 
* Instead of **Edit>Convert Case> Upper Case**, can just **ctrl+shift+p > conve...** till you find it 
* Reverse order of a bunch of lines: **ctrl+shift+p > rever...** then select **Permute Lines: Reverse** 
* Reverse order of a bunch of lines: **ctrl+shift+p > sort...** 
* Encode special characters (char escaping for security): **ctrl+shift+p > encode...** 
* Set syntax: **ctrl+shift+p > set Sy...(enter for set syntax) > html>  ** 

### Tut 5: Package Managers (Installing community created addons)
* Before being able install the packages, we need to install the package manager. We are looking for 
[package control](https://packagecontrol.io/installation "This link may change with time")

Eg: color highlighter for css - first
