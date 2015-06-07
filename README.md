# MemoryTests2015
Memory tests for class demonstrations of working memory capacity and principles of memory encoding, consolidation, and retrieval

# How to use
The working memory test is coded in six separate files, which are to be run in sequence using RStudio. They were last tested and functional on 2015-06-07 in RStudio version 0.98.1103. To get responses, the code is set up to work with Google forms. Each test is coupled to a separate form, where students can enter their responses. It is recommended that any new user of this code should set up their own google forms and replace the url:s in the code. Similarly, the code can be easily customised by changing the words, translating the text from Swedish to other languages, etc, if desired. 

The recall test requires picture stimuli for presentation as well as a Google form set up to ask about the same stimuli. For testing, I have used pictures from the International Affective Picture System (http://csea.phhp.ufl.edu/media.html#topmedia). These pictures are not in the public domain. 

The rationale, procedure, and results of these tests will be described in a short scientific communication.

# Data
The subfolder Data contains deidentified results from the memory tests when tried with 11 medical students. There are 4 separate files for the working memory tests with 5, 7, 9, and 11 items. Results from the recall test are in a separate file. This latter file has 30 columns named Q1-Q30, indicating whether answers were correct, and then 4 columns giving the fraction of correct answers for pictures that were shown ("seen"), shown only once ("unconsolidated"), shown twice ("consolidated"), or not shown ("unseen"). The students gave implied consent by participating in the demonstration, which was not a course requirement. Ethical review was not required since data could not be linked to individials.
