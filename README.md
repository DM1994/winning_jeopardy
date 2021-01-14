# winning_jeopardy
Analysing data to find the best way to win jeopardy
Original dataset downloaded from here: reddit.com/r/datasets/comments/1uyd0t/200000_jeopardy_questions_in_a_json_file/
Data consists of 252,583 questions from the game show.
According to source, data measures:
"
'category' : the question category, e.g. "HISTORY"
'value' : $ value of the question as string, e.g. "$200"
Note: This is "None" for Final Jeopardy! and Tiebreaker questions
'question' : text of question
Note: This sometimes contains hyperlinks and other things messy text such as when there's a picture or video question
'answer' : text of answer
'round' : one of "Jeopardy!","Double Jeopardy!","Final Jeopardy!" or "Tiebreaker"
Note: Tiebreaker questions do happen but they're very rare (like once every 20 years)
'show_number' : string of show number, e.g '4680'
'air_date' : the show air date in format YYYY-MM-DD
"
