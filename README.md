# DH-Workshop-Notes

Notes for coding DH workshop
### Nov 19

#### As of now, learned basic construct of the command line.
Computational analysis may be able to track word frequency significantly faster, but it may not be able to accurately pick up on context of the word itself. Computer may miss certain word complexity and nuances.
- Voyant
- AntConc
- NVivo

*“I believe that the time is ripe for significantly better documentation of programs and that we can best achieve this by considering programs to be works of literature ... the practitioner of literature programming can be regarded as an essayist, whose main concern is with exposition and excellence of style.”*  
Donald Knuth, Literate programming (1984), p. 9

**Python**

Benefits
- Generally more readable
- Easier to see problems in the code
- Processes data quickly

Constraints
- Automates certain functions which can limit what it can do
- Programmer friendly vs machine friendly

Observations
- Have to imput in code functions (while analyzing text) for the program that our brains would automatically do. Ex: I ignored words like 'the' and 'and' , but I would have to explicitly write this in the command line. 
- stopwords - words to be excluded
- io means input/output. input a file to generate an output
- Humans can separate strands of text, computer needs command line specification
- for loop - run the function until the requirements are met
- Note that computers 'think' in binary terms. Yes or no, never maybe and always objective
- Flow chart activity - yes or no, process of buying chocolate ice cream, the conditions that can be answered with yes or no to meet the requirements to buy ice cream

### Nov 26

#### Jupyter Notebook

Textual slicing
- 0= 1st letter
- 1= 2nd letter
- 3= 3rd letter
- so forth...

Grouping words
- same as slicing 
- 0= 1st word/sentence depending on what you want to pull

Camparison operators
- used to compare two numbers or variables
  - |==| Equal to
  - |!=| Not equal to
  - |<| Less than
  - |>| Greater than
  - |<=| Less than or equal to
  - |>=| Greater than or equal to

Boolean Operatora
- 3 key boolean operators:
  - and, or, and not
  - true or false
  - true and true
  - false or false
  - not false

for loop
- for (item you would like to iterate action)
  - perform action

### Dec 3
#### Python 2 functions
 Functions are blocks of reuseable code
 - there are many functions such as "print()" or "len()" which were designed to perform specific tasks when called. 
 - If there is a task you will need to repeat multiple times at various points, you can write a function 

#### Wrangling Text Data
- can use pre-written code: Natural Language Toolkit
- Create process data
  - Stopword lists 
    - ignore specific words
      - that are irrelevant, for example
      - modify stopwords and punctuation lists like any other list
        - to add multiple elements to a list at once, we use extend() rather that append()
  - Tokenizing
    - splitting up a larger body of text into smaller lines or words
    - various tokenization functions are built into the NLTK library
      - can break down parts of speech
        - good for literary analysis
  
- prewritten code
  - pre-written code is like pre-prepared meals/having ingredients ready to go
- Pandas: pre-written code for tabular data
  - python package for exploring, cleaning, and processing tabular data

