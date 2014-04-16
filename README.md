## Description
This c++ project allows you to easily convert any plain-text into ASCII art and vice-versa.

## Usage
Since this is a C++ project you need to compile <b>main.cpp</b> to generate an executable. I've done so below using g++:
```
g++ main.cpp -o main.exe
```
## Examples
### Convert Plain-Text Into ASCII Art
To convert plain-text into ASCII art and <b>print output in terminal</b>:
```
./main.exe display font.txt "My Sentence" "#" "."

```
To convert plain-text into ASCII art and <b>save output in a .txt file</b>:
```
./main.exe display font.txt "My Sentence" "#" "." > output.txt

```
Command Arguments:
<ul>
	<li>display: Specifies that we are turning plain-text into ASCII art.</li>
	<li>font.txt: Required file that determines ASCII shapes.</li>
	<li>"My Sentence": Any string you want to generate ASCII art from.</li>
	<li>"#": The character you choose as the foreground character.</li>
	<li>".": The character you choose as the background character.</li>
</ul>
### Convert ASCII Art into Plain-Text:
To convert ASCII art into plain-text and <b>print output in terminal</b>:
```
./main.exe read font.txt input.txt

```
Command Arguments:
<ul>
	<li>read: Specifies that we are turning ASCII art into plain-text.</li>
	<li>font.txt: Required file that determines ASCII shapes.</li>
	<li>input.txt: Your ASCII file that you want converted into plain-text.</li>
</ul>
## Contributors
Devon Bernard
* dwbcoding@gmail.com
* [LinkedIn](https://www.linkedin.com/in/devonbernard)
* [@DBCoding](https://www.twitter.com/DBCoding)
