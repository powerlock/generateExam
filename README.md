# generateExam

Goal: read the chemistry question bank and extract questions to generate random questions according to its levels 

## need to fix:
When the paragraph starts with a new page while there are blanks in previous page, the first question can't be extracted.
temporarily fixed with skiping the question while the current_question is not none.

## to-do:
Categorize questions to three types: multiple choices, short answer, and true or false questions.
Create three different classes and choose questions bases upon classes.