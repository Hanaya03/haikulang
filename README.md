# haikulang
Final project for CS420 Advanced Programming Languages. A programming language that follows the haiku poem structure. To continue the haiku motif, the language uses keywords that are nature themed as most haikus are centered around nature.

**HOW TO RUN**
1. Ensure you have the latest version of python installed. Minimum version of 3.10 required. You can find the download [here](https://www.python.org/downloads/)
2. Go to the folder where you downloaded the haikulang.py file or to the 'source code' folder where you pulled the repo
3. Run the command 
```console
py haikulang /path/to/your/file.haiku
```

**SYNTAX**
Every line must consist of a poem, where a poem is a set of 3 stanzas seperated by '...' or '-'. The '...' indicates the end of a command, while the '-' will continue the command in the next stanza. If a command ends within a stanza, the programmer must place a '.' to seperate the commands. Stanzas must consist of words seperated by spaces, and the total number of syllables in the 1st and 3rd stanzas must be 5 syllables long, while the 2nd stanza must have 7 syllables.
```
Winter's biting cold... winds howl 'hello world'... I stay warm in bed...
```
Blossoms/Born - instantiates a variable
```
The willows blossom...
```
Like - variable assignment
```
willows like tall, joyful plants...
```
With - if statment
Then - end if. Must follow a 'with' or 'but' statement.
```
with willows under tall plants... we howl 'true' then
```
But- else statement. Must follow a 'with' statement. May precede another with statement
```
with seas under skies... winds howl 'true' but the fish- howl 'false' until then...
```
Seasons pass - while statment
Seasons end - end while statement. Must come after a while statement
```
seasons pass, willows- under monkeys. The trees all- howl 'true'. Seasons ends...
```
Rain pours - for statement. The word after the statement becomes the variable that's tracked. That variable must then be followed by a condition
 ```
 The rain pours, willows- like naught. Willows under bright- healthy, lovely sun...
```
Conditionals
- and - equation operator
- under - less than operator
- underneath - less than or equal to operator
- over - greater than operator
- above - greater than or equal to operator

Arithmetic
- Summation - Performed by placing multiple variables or positive, neutral, or negative keywords after a 'like', 'seasons pass', or 'seasons end' keyword
- Seed/Breed - multiplication
- kill - division
- spare - modulo