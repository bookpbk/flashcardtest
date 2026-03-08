Create a simple HTML webpage for chinese language flashcard reviewer. 

It should 
Data Section
-be able to import excel data of 3 columns -chinese_text / pinyin / english_meaning
-pre-load the above with 10 sample vocabs. 
-save and import state of usage as some kind of memory file (maybe a json)

Review section
-has a slider that list number of vocabs to review per session (from 5 up to 30) 
-has buttons to trigger 3 review modes -> from chinese_text / from pinyin / from english_meaning 
-once trigger, show "main" cards one-by-one of the vocab being reviewed. The vocab is to be randomized from the "Data" pool, and only display according to mode selected (from chinese_text / from pinyin / from english_meaning) 
-beside the "main" card, show 3 choices of the corresponding data, 1 being the correct answer and other 2 randomly picked from other cards.
--> if in chinese_text mode, show 3 pinyin 
--> If in pinyin mode, show 3 english meaning 
--> if in english mode, show 3 texts. 

-if correct answer is picked, move on to next word
-if wrong answer is picked, show that option as red and wait for user to select another word. 

-Store the record of vocab reviewed, correct answer and date in the "state"
