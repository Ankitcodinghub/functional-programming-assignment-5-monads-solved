# functional-programming-assignment-5-monads-solved
**TO GET THIS SOLUTION VISIT:** [Functional-Programming Assignment 5-Monads Solved](https://www.ankitcodinghub.com/product/functional-programming-assignment-5-monads-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97101&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Functional-Programming Assignment 5-Monads Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Assignment 5 Monads

5.1 Submission instructions

<ol>
<li>Unzip the A5.zip folder. It should contain one file: 􏰀 Solutions.hs – for the Haskell exercises</li>
<li>Edit the first line of each of the source files as described in the comments.</li>
<li>Edit the source files with your solutions.</li>
<li>When done, zip (not rar renamed as zip!) this A5 folder and name the zip archive with the following format:
A5 ⟨FirstName⟩ ⟨LastName⟩ ⟨Group⟩

Examples of valid names:

􏰀 A5 John Doe 30432.zip

􏰀 A5 Ion Popescu 30434.zip

􏰀 A5 Gigel-Dorel Petrescu 30431.zip

Examples of invalid names:

􏰀 Solutions.zip

􏰀 A5.zip

􏰀 Solutii A5 Ion Popescu.zip
</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
145

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
5.2 Assignment exercises 5.2.1 Haskell

Exercise 5.2.1 3p

Implement a function passwords that enumerates all 8 character passwords containing digits (0 – 9) lowercase letters (a – z) and uppercase letters (A – Z) using the list applicative.

Haskell REPL

<pre>      &gt; take 5 passwords
      ["00000000","00000001","00000002","00000003","00000004"]
      &gt; take 5 (drop 10000 passwords)
      ["000002Bi","000002Bj","000002Bk","000002Bl","000002Bm"]
</pre>
Hints:

Re-read section 10.2 of Lab 10 about the list applicative.

You should consider using (some of) the following functions: replicate , sequenceA .

Exercise 5.2.2 3p

Given the following data definition data Password = Password String , implement a func- tion validatePassword :: String -&gt; Maybe Password that takes a string and returns a valid password wrapped in Just or Nothing , if the string isn’t a valid password.

A valid password should have at least 8 characters and should contain:

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰀 At least one lowercase character 􏰀 At least one uppercase character 􏰀 At least one digit

<pre>&gt; validatePassword "123"
Nothing
&gt; validatePassword "abc"
Nothing
</pre>
<pre>&gt; validatePassword "MyStr0ngPassword2"
Just (Password "MyStr0ngPassword2")
&gt; validatePassword "abcDE12"
Nothing
</pre>
<pre>&gt; validatePassword "Abcd1234"
Just (Password "Abcd1234")
</pre>
</div>
<div class="column">
Haskell REPL

</div>
</div>
<div class="layoutArea">
<div class="column">
Hints:

You should consider using (some of) the following functions: any , all , elem , notElem

Exercise 5.2.3 5p

Given the following data definition data Email = Email {username :: String, domain:: String} , write a function validateEmail :: String -&gt; Maybe Email that takes a string a returns a valid email address wrapped in Just or Nothing , if the string isn’t a valid email ad- dress.

A valid email address (jonny@example.com) should: 146

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
<ul>
<li>􏰀 &nbsp;Contain a username (the part before the “@” character) that is at least 3 characters long (johnny)</li>
<li>􏰀 &nbsp;Contain exactly one “@” character</li>
<li>􏰀 &nbsp;Contain a domain name (the part after the “@” character) that contains:
– A non-empty hostname (which can contain “.” characters) (example) – A “.” character

– A top level domain (com)

Haskell REPL

<pre>   &gt; validateEmail "johnny@example.com"
   Just (Email {username = "johnny", domain = "example.com"})
   &gt; validateEmail "johnny@.com"
   Nothing
   &gt; validateEmail "johnny.com"
   Nothing
   &gt; validateEmail "johnny@domain@.com"
   Nothing
   &gt; validateEmail "x@domain.com"
   Nothing
   validateEmail "johnny.john@domain.com"
   Just (Email {username = "johnny.john", domain = "domain.com"})
   &gt; validateEmail "johnny.john@domain.example.com"
   Just (Email {username = "johnny.john", domain = "domain.example.com"})
</pre>
Hints:

You should consider using (some of) the following functions: span , break , null

Exercise 5.2.4 4p

Complete the main function in Solutions.hs to create a Haskell program for checking whether an email and password are valid. The program should prompt the user to enter their email address and password, check if they are a valid email address and password and show a message whether the input was valid or not.

Grading:

<ul>
<li>􏰀 &nbsp;2 points for implementing the validateUser :: String -&gt; String -&gt; Maybe User function that uses validateEmail and validatePassword to validate an email ad- dress and a password</li>
<li>􏰀 &nbsp;2 points for implementing the main function</li>
</ul>
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
147

</div>
</div>
</div>
