# Winning Jeopardy Game

Jeopardy is a popular TV show in the US where participants answer questions to win money. It's been running for a few decades, and is a major force in popular culture.

Let's say we want to compete on Jeopardy, and we're looking for any edge we can get to win. In this project, we'll work with a dataset of Jeopardy questions to figure out some patterns in the questions that could help us win.

The dataset is named jeopardy.csv, and contains 20000 rows from the beginning of a full dataset of Jeopardy questions, which we can download <a href="https://www.reddit.com/r/datasets/comments/1uyd0t/200000_jeopardy_questions_in_a_json_file">here</a>.

As you can see, each row in the dataset represents a single question on a single episode of Jeopardy. Here are explanations of each column:
<ul>
<li>Number -- the Jeopardy episode number of the show this question was in.
<li>Date -- the date the episode aired.
<li>Round -- the round of Jeopardy that the question was asked in. Jeopardy has several rounds as each episode progresses.
<li>Category -- the category of the question.
<li>Value -- the number of dollars answering the question correctly is worth.
<li>Question -- the text of the question.
<li>Answer -- the text of the answer.
</ul>
