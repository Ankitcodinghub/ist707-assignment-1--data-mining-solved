# ist707-assignment-1--data-mining-solved
**TO GET THIS SOLUTION VISIT:** [IST707 Assignment 1- Data Mining Solved](https://www.ankitcodinghub.com/product/ist707-assignment-1-data-mining-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95999&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;IST707 Assignment 1- Data Mining Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Introduction

Squabble is an interesting word game in existence, and it has a few special features that make this game the preferred one in the race. The rules are easy, it gives players six chances to guess a randomly selected five-letter word. You can enter a total of six words, meaning you can enter five burner words from which you can learn hints about the letters and their placements. Each letter in your guess is labeled with respect to a mystery word as a correct letter, a used letter, or an unused letter. For instance, if the mystery word was “ADULT” but your guess was “AGENT”, then the labelling would be as follows: A correct, G unused, E unused, N unused, and T correct. That information can inform the next guess. Each subsequent guess helps narrow down what the mystery word could be. Although much thought was put into these game rules, our tools will to be less constrained to broaden the possibilities. For example, both length of word and number of guesses will be arbitrary. Along with lifting these numerical constraints, we are going to lift textual constraints in our tools to allow different letters other than A-Z. In particular, the tools will be able to deal with characters other than A-Z allowing for more variants for a Squabble-esque game. We retain the idea of labelling a words’ letters according to a mystery word.

The main class, WordLL, will be a non-graphical text-based utility. Simple interfaces for WordLL are provided in WordLLExamples. Below is an example run of WordLLExamples in action where bold words are guesses entered by keyboard and lines starting with “Word:” show a history of results. Note that letters are decorated/surrounded with either “-“, ”+”, or “!” which correspond to unused, used, and correct. In the original Squabble game, colours indicate this information: unused letters are grey(-), used are yellow(+), and correct are green(!).

enter a word (XX to stop):BOOK Word: -B- -O- -O- -K-

enter a word (XX tostop):LONDON Word: +L+ -O- -N- +D+ -O- -N- Word: -B- -O- -O- -K-

enter a word (XX tostop):SHELF Word: -S- -H- -E- !L! -F- Word: +L+ -O- -N- +D+ -O- -N- Word: -B- -O- -O- -K-

enter a word (XX tostop):ADULT You got it!

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
<pre>Word: !A! !D! !U! !L! !T!
Word: -S- -H- -E- !L! -F-
Word: +L+ -O- -N- +D+ -O- -N-
Word: -B- -O- -O- -K-
</pre>
enter a word (XX to stop):XX Provided files

The following is a list of files provided to you for this assignment. Do no not alter LinearNode.java. The other two files are provided to help you understand the requirements of the assignment and are not to be submitted.

<ul>
<li>LinearNode.java (from the notes)</li>
<li>TestWordLL.java (some tests to check your code which may differ from Gradescope’s
tests)
</li>
<li>WordLLExamples.java (a collection of uses for your finished code)</li>
<li>words (a text file with many words)
Classes to Implement

For this assignment, you must implement four Java classes: Letter, Word, WordLL, and ExtendedLetter. Follow the guidelines for each class below.

In all these classes, you can implement more private (helper) methods, if you want to, but you may not implement more public methods. You may not add instance variables other than the ones specified below nor change the variable types or accessibility (i.e. making a variable public when it should be private). Penalties will be applied if you implement additional instance

variables or change the variable types or modifiers from what is described here. Letter.java

This class represents a single letter that will be used in the game. Each game letter also has an accompanying integer label which indicates whether it is used, unused, or correct with respect to the mystery word.

The class must have the following private variables, and constants:

<ul>
<li>letter (char)</li>
<li>label (int)</li>
</ul>
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Computer Science Fundamentals II CS 1027

Assignment 2

• UNSET, UNUSED, USED, CORRECT (int) (constants that have unique values; these are the possible values for the “label” instance variable)

The class must have the following public methods:

<ul>
<li>public Letter(char c) [constructor]</li>
<li>Initialize label to UNSET and set the value of instance variable letter to c</li>
<li>public boolean equals(Object otherObject)</li>
<li>First checks whether otherObject is of the class Letter, and if not the value false is
returned. If otherObject is of the class Letter, then the “letter” attributes of otherObject and this object are compared: If they are the same the value true is returned, otherwise false is returned.
</li>
<li>public String decorator()</li>
<li>Returns “+” (if the “label” attribute is USED), “-“ (if the “label” attribute is UNUSED), “!(if
the “label” attribute is CORRECT), or “ “ (if the “label” attribute is UNSET; note this is a

space).
</li>
<li>public String toSt”ring()</li>
<li>an overridden method that gives a representation of letter &amp; label which uses the helper
method decorator. The String returned is of the form “dCd”, where C is the “letter”

attribute of this object and d is the String returned by the decorator() method.
</li>
<li>from the Introduction, we can see some examples of Letter.toString():  “+A+”,
“+C+”, “-C-”, “!E!”, “-P-”, “-T-”

 A, C are letters that are USED

 P, T are letters that are UNUSED

 E in the fourth location is CORRECT
</li>
<li>public void setUnused()</li>
<li>used to change the value of attribute “label” to UNUSED</li>
<li>public void setUsed()</li>
<li>used to change the value of attribute “label” to USED</li>
<li>public void setCorrect()</li>
<li>used to change the value of attribute “label” to CORRECT</li>
<li>public boolean isUnused()</li>
<li>returns true if the attribute “label” is set to UNUSED</li>
<li>otherwise returns false</li>
<li>public static Letter[] fromString(String s)</li>
<li>Produces an array of objects of the class Letter from the string s given as parameter.
For each character in s a Letter object is created and stored in the array. The Letter
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Computer Science Fundamentals II CS 1027

Assignment 2

objects are stored in the array in the same order in which the corresponding characters appear in s.

Word.java

This class represents a word in the game that is comprised of any number of letters. Each letter is represented by a Letter object. The Letter objects are stored in a linked list formed by objects of the class LinearNode. Each node in the linked list stores an object of the class Letter. The most important instance method of this class is labelWord which labels Letter objects with respect to a mystery word. This is the trickiest method of this assignment.

The class must have the following private variables:

• firstLetter (LinearNode&lt;Letter&gt;): A reference to the first node in the linked list

representing the word corresponding to this object. The class must have the following public methods:

• public Word(Letter[ ] letters) [constructor]

• Initialize the Word object so the Letter objects in array “letters” is stored within its

linked structure. Instance variable firstLetter must point to the first node of the linked list.

For example, the invocation to the constructor passing as parameter an array of Letter objects corresponding to guess “BOOK” in page 1 would create the following linked list:

</div>
</div>
<div class="layoutArea">
<div class="column">
firstLetter

</div>
<div class="column">
Object of class LinearNode

Object of class Letter

</div>
</div>
<div class="layoutArea">
<div class="column">
‘B’

UN

</div>
</div>
<div class="layoutArea">
<div class="column">
‘O’

US

</div>
</div>
<div class="layoutArea">
<div class="column">
‘O’ UN

</div>
<div class="column">
SET

</div>
</div>
<div class="layoutArea">
<div class="column">
‘K’

U

</div>
</div>
<div class="layoutArea">
<div class="column">
SET

</div>
</div>
<div class="layoutArea">
<div class="column">
SET

</div>
</div>
<div class="layoutArea">
<div class="column">
N

</div>
</div>
<div class="layoutArea">
<div class="column">
SE

</div>
<div class="column">
T

</div>
</div>
<div class="layoutArea">
<div class="column">
<ul>
<li>public String toString()</li>
<li>Creates a String of the form: “Word: L1 L2 L3 … Lk”, where each Li is the string
produced by invoking the toSting method on each Letter object of this Word.
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
<ul>
<li>from the Introduction, we can see examples of the output of this toString() method:  “Word: +A+ -C- -C- -E- -P- -T-”

 “Word: -B- -O- -O- -K-”</li>
<li>public boolean labelWord(Word mystery)</li>
<li>takes a mystery word as a parameter and updates each of Letters’ “label” attribute
contained in this Word object with respect to the mystery word
</li>
<li>returns true if this word is identical in content to the mystery word</li>
<li>To understand how the “label” attribute of the Letter objects stored in the linked list
of a Word object are updated, consider an example. Suppose that the mystery word is “APPLE” and that this object stores Letter objects corresponding to the word “BOOK”, then the “label” attributes of the Letter objects would be updated as follows:

 label for Letter object corresponding to ‘B’ is UNUSED  label for Letter object corresponding to ‘O’ is UNUSED  label for Letter object corresponding to ‘O’ is UNUSED  label for Letter object corresponding to ‘K’ is UNUSED

WordLL.java

This class is a central repository for information about a WordLL game: It stores a mystery word and all word guesses tried so far. It keeps a history of the past word guesses in a linked structure. Its name is a bit of play on words—Word-Linked-List.

The class must have the following private variables:

<ul>
<li>mysteryWord (Word)</li>
<li>history (LinearNode&lt;Word&gt;)</li>
</ul>
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
Computer Science Fundamentals II CS 1027

Assignment 2

</div>
</div>
<div class="layoutArea">
<div class="column">
mysteryWord history

</div>
</div>
<div class="layoutArea">
<div class="column">
Object of class

Object of class

</div>
</div>
<div class="layoutArea">
<div class="column">
LinearNode

Word

</div>
</div>
<div class="layoutArea">
<div class="column">
Object of class

</div>
<div class="column">
LinearNode

</div>
<div class="column">
Object of class Letter

</div>
</div>
<div class="layoutArea">
<div class="column">
The class must have the following public methods:

<ul>
<li>public WordLL(Word mystery) [constructor]</li>
<li>Initialize an empty history</li>
<li>set the mysteryWord attribute to the parameter mystery</li>
<li>public boolean tryWord(Word guess)</li>
<li>takes a Word as an argument to test against this games’ mystery word</li>
<li>updates the label of all the letters contained within Word guess (using labelWord)
and adds Word guess to the front the of history (you must create a node of the class LinearNode, store the Word guess object in it and then link this node to the front of the linked list pointed by history)
</li>
<li>returns true if the word represented by guess is identical to the word represented by mysteryWord, otherwise returns false</li>
<li>public String toString()</li>
<li>Creates a String representation of the past guesses with the most recent guess
first. From the Introduction, we can see examples of the strings produced by this method toString() after every guess. For instance after the third guess in the example of page 1 this is what results of invoking method toString():
</li>
</ul>
 “Word: -S- -H- -E- !L! -F- Word: +L+ -O- -N- +D+ -O- -N- Word: -B- -O- -O- -K-”

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
Note the end of line “\n” after each word. ExtendedLetter.java

This class is a subclass of Letter and extends the functionality. Instead of relying on a single char to represent the content of a Letter object, objects of this class will use a String instance variable and will further introduce the concept of being related to other ExtendedLetter objects. This class adds more features to broaden the notion of a letter that will be used in the game.

The class must have the following private variables, and constants:

<ul>
<li>content (String)</li>
<li>family (int)</li>
<li>related (boolean)</li>
<li>SINGLETON (int) constant equal to -1
The class must have the following public methods:
</li>
<li>public ExtendedLetter(String s) [constructor]</li>
<li>Initialize instance variables of the superclass
 super(c) where c is an arbitrary char (it doesn’t matter which since it will not be used)
</li>
<li>Initialize the instance variables as follows:

 content is set to the String parameter s  related is set to false

 family is set to SINGLETON</li>
<li>public ExtendedLetter(String s, int fam) [constructor]</li>
<li>Initialize instance variables of the superclass
 super(c) where c is an arbitrary char (it doesn’t matter which since it will not be used)
</li>
<li>Initialize the instance variables as follows:
<ul>
<li> &nbsp;content is set to the String parameter s</li>
<li> &nbsp;related is set to false</li>
<li> &nbsp;family is set to the int parameter fam; this is a positive number which
indicates that any ExtendedLetter object with the same value in instance

variable family will be consider related to this ExtendedLetter object
</li>
</ul>
</li>
<li>public boolean equals(Object other)</li>
<li>return false if the parameter other is not an instanceOf ExtendedLetter</li>
<li>otherwise</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="layoutArea">
<div class="column">
<ul>
<li> &nbsp;it will set the instance variable related of this object to true if the family instance variable of other is the same as this.family.</li>
<li> &nbsp;return true if the instance variable content of other is equal to the instance variable content of this object;</li>
<li> &nbsp;otherwise it returns false</li>
<li>public String toString()</li>
<li>an overridden method that gives a String representation of this ExtendedLetter
object
</li>
<li>If this ExtendedLetter object is unused (its label instance variable has value
UNUSED) and its instance variable related has value true, return the string “.A.” where A is equal to this.content. For example, if this.content is “%” and this.related is true, this method would return “.%.”.
</li>
<li>Otherwise, this method should return a string “+A+”, “!A!”,“-A-”, or “ A ” depending of the value returned by method decorator() from the superclass, where A is equal to this.content.</li>
<li>public static Letter[] fromStrings(String[] content,int[] codes)</li>
<li>Creates an array letters of Letter objects of the same size as the size of the array
content received as parameter. This array letters will be returned by the method

after storing in it the following information:
</li>
<li>If parameter codes is null then the i-th entry of array letters will store an
ExtendedLetter object created with the constructor ExtendedLetter(content[i]).
</li>
<li>If codes is not null, then the i-th entry of array letters will store an ExtendedLetter
object created with the constructor ExtendedLetter(content[i],codes[i]). To Run the Program

If you are running the program from the terminal, place all files in the same directory, compile them with javac and run the program by typing java WordLLExamples.

If you are using Eclipse, put the file called words in the root folder of your project (not inside the src folder) and run the WordLLExamples class.
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 9">
<div class="layoutArea">
<div class="column">
There are two modalities of the program. If in the main method of WordLLExamples you invoke method playEnglish, the program will play Squabble with words; if you invoke method playCards you will have to guess four Euchre cards.

Marking Notes Functional Specifications

<ul>
<li>Does the program behave according to specifications?</li>
<li>Does it produce the correct output and pass all tests?</li>
<li>Are the classes implemented properly?</li>
<li>Does the code run properly on Gradescope (even if it runs on Eclipse, it is up to you to
ensure it works on Gradescope to get the test marks)
</li>
<li>Does the program produces compilation or run-time errors on Gradescope?</li>
<li>Does the program fail to follow the instructions, (i.e. changing variable types, etc.)
Non-Functional Specifications
</li>
</ul>
<ul>
<li>Are there comments throughout the code (Javadocs or other comments)?</li>
<li>Are the variables and methods given appropriate, meaningful names?</li>
<li>Is the code clean and readable with proper indenting and white-space?</li>
<li>Is the code consistent regarding formatting and naming conventions?</li>
<li>Submission errors (i.e. missing files, too many files, etc.) will receive a penalty of 5% • Including a “package” line at the top of a file will receive a penalty of 5%
Remember you must do all the work on your own. Do not copy or even look at the work of another student. All submitted code will be run through similarity-detection software.
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 10">
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
</div>
