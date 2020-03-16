# Search-Engine-

INTRODUCTION
-----------------------
This is a full retrieval engine that will provide you all the relevant documents that you will ever want to find.

Don't worry - you will get a perfect results in a minimium time if you will follow our instructions.



INFO
-----------------------
Project name: @OODLE 
-----------------------


java versiom 1.8.0_131

After each indexing and ranking process the following files will be save to the disk:
* dictionary - holds the all information about the unique term in the corpus
(name, number of docs that contains the term, numer of appereance in all the corpus, path to the final posting file) 
* docs posting - holds the all information about the docs
(name, number of unique entities, number of unique terms, size of doc, amount of the most frequency term)
* terms posting - holds the all information about the terms in the corpus
(name, list of the documents that the term exist in with the quantity the term appears in it)
* stop words - holds all the stop words that given to us.
* Entities posting - holds all the entities that found in the corpus
(string of entity, list of docs that the entity appear on them and number of appereance in the doc)
* optional file - doc that represent the top five entities that created when you want to display your results after the ranking.
(string of entities, rank of the entity)


OPERATING INSTRUCTIONS:
-----------------------
1. Run the jar file
2. Click on the 'upload directory' button and set a path to the directory that your corpus at.
3. Click on the 'save directory' button and set a path to the directory where you want all the posting files will be save.
4. The choose box is responsible to decide in which type of retrival the engine will use.
   if you select the choose box, this means that the search engine will execute the process by stemming the terms.   
5. Press 'start' in order to run the processing of the corpus.
   if the running succsess a window with some information about the current indexing process will appear.
6. Pressing 'upload dictionary' button load your dictionary to the memory.
7. Pressing 'display dictionary' button shows all the unique terms in the corpus and their number of appereance in all the cporpus.
8. Pressing 'Insert Query' button to open a new window that handling with queries.
9. You can write query by yourself, and after click on 'Run Your query' in order to start ranking your query.
10. You can browse file with amount of queries, and after click on 'Run your selection' in order to start ranking your queries.
!! Pay attention that you need to browse file in specific format
11. Pressing 'choose path to treceval' in order to select the folder that the results.txt file will be saved, you cannot run query without enter this path.
12. You can try to improve your results by clicking on semantic function : 'online semantic'/'offline semantic' checkboxes and then run your selection that compile according the checks.
you can be impressed from both semantic function but cannot chose them together.
13. after all, you can display the ranking results by clicking on 'display results' button. first, you see a table that contains of - query id and 'review' button to the query ranking. 
if you press on the button you will see another table that contains of - id of relevant doc, his ranking and 'entities' button. 
and last - if you press on the button you will see another table with the entities results - name of entity and her score, sorting by ASC.



Enjoy your searching ! 


© Eden Mizrahi & Yarden Schwartz
