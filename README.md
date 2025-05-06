# comp442-6421-assignment-1-lexical-analyzer-solved
**TO GET THIS SOLUTION VISIT:** [COMP442_6421 Assignment 1-Lexical Analyzer Solved](https://www.ankitcodinghub.com/product/comp442_6421-assignment-1-lexical-analyzer-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96191&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP442_6421 Assignment 1-Lexical Analyzer Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Assignment 1, Lexical Analyzer

</div>
</div>
<div class="layoutArea">
<div class="column">
This assignment is about the design and implementation of a scanner for a programming language whose lexical specifications are given below. The scanner identifies and outputs tokens (valid words and punctuation) in the source program. Its output is a token that can thereafter be used by the syntactic analyzer to verify that the program is syntactically valid. When called, the lexical analyzer should extract the next token from the source program. The syntax of the language will be specified later in assignment #2. The assignment includes two grading source files used by the marker. These files should be used as- is and not be altered in any way. Completeness of testing is a major grading topic. You are responsible for providing appropriate test cases that test for a wide variety of valid and invalid cases in addition to what is in the grading source files provided.

Atomic lexical elements of the language

id ::= letter alphanum* alphanum ::= letter | digit | _ integer ::= nonzero digit* | 0

float ::= integer fraction [e[+|−] integer] fraction ::= .digit* nonzero | .0

letter ::= a..z |A..Z digit ::= 0..9

nonzero ::= 1..9

Operators, punctuation and reserved words

</div>
</div>
<div class="layoutArea">
<div class="column">
== + | &lt;&gt; – &amp; &lt; * ! &gt;/

&lt;= = &gt;=

Comments

</div>
<div class="column">
( ; if public read

) , then private write

{ . else func return }:integervar self

[ :: float struct inherits ] -&gt; void while let

impl

</div>
</div>
<div class="layoutArea">
<div class="column">
• Block comments start with /* and end with */ and may span over multiple lines. • Inline comments start with // and end with the end of the line they appear in.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Work to submit Document

You must provide a short document that includes the following sections:

Section1. Lexicalspecifications:Identifythelexicalspecification,expressedasregularexpressions,that you used in the design of the lexical analyzer. Highlight any changes that you may have applied to the original lexical specifications and justify your changes.

Section 2. Finite state automaton: Finite state machine diagram describing the operation of your lexical analyzer.

Section 3. Design: Give a brief overview of the overall structure of your solution, as well as a brief description of the role of each component of your implementation.

Section 4. Use of tools: Identify all the tools/libraries/techniques that you have used in your analysis or implementation and justify why you have used these particular ones as opposed to others.

Implementation

• Lexical analyzer: Write a lexical analyzer that recognizes the above-mentioned tokens. It should be a

function that returns a token data structure containing the information about the next token identified in the source program file. The token data structure should contain information such as (1) the token type (2) the lexeme of the token and (3) the location of the token in the source code. When lexical errors are found, an error token should be produced, whose type is the specific error type, its lexeme is the erroneous character stream, and its location is where the error was found in the source code. When a token is identified from a file named, for example, originalfilename, it should be printed out into a file named originalfilename.outlextokens that lists the token stream that corresponds to the original program. When lexical errors are found, error messages should be printed out in a file named originalfilename.outlexerrors.

• Test cases: Include many test cases that test a wide variety of valid and invalid cases. Test cases are included in files that are read by the implementation. Your test files must include the test files provided with the assignment, which should not have been altered. Samples of expected output files are also given with the assignment as guidance.

• Driver: Include a driver that extracts the tokens from all your test files. For each test file, the corresponding outlexerrors and outlextokens files should be generated.

Selected examples

0123 [Invalid number:0123] OR [integer:0][integer:123]

01.23 [Invalid number:01.23] OR [integer:0][float:1.23]

12.340 [Invalid number:12.340] OR [float:12.34][integer:0]

012.340 [Invalid number:012.340] OR [integer:0][float:12.34][integer:0] 12.34e01 [Invalid number:12.34e01] OR [12.34e0][integer:1] 12345.6789e-123 [float:12345.6789e-123]

12345 [integer:12345]

abc [id:abc]

abc1 [id:abc1]

abc_1 [id:abc_1]

abc1_ [id:abc1_]

_abc1 [Invalid identifier:_abc1]

1abc [Invalid identifier:1abc] OR [integer:1][id:abc] _1abc [Invalid identifier:_1abc] OR

[Invalid identifier:_][integer:1][id:abc]

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Assignment submission requirements and procedure

<ul>
<li>Each submitted assignment should contain four components: (1) the source code, (2) a group of test files, (3) a brief report, and (4) an executable named lexdriver, that extracts the tokens from all your test files. For each test file, the corresponding outlexerrors and outlextokens files should be generated.</li>
<li>The assignment statement provides test files (.src) and their corresponding output files.</li>
<li>The source code should be separated into modules using a comprehensible coding style.</li>
<li>The assignment should be submitted through moodle in a file named: “A#_student-id” (e.g.
A1_1234567, for Assignment #1, student ID 1234567) and the report must in a PDF format.
</li>
<li>You may use any language you want in the project and assignments but the only fully supported language</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
during the lab is Java.

<ul>
<li>You have to submit your assignment before midnight on the due date on moodle.</li>
<li>The file submitted must be a .zip file</li>
</ul>
</div>
</div>
</div>
