# TextRank
TextRank implementation for automated document summarization approaches based on 
Sarkar.D., Text analytics with Python: A practical real-world approach to gaining actionable insights from your data (2016). Apress Berkely, CA, USA.

TextRank text summarization includes the following steps:
1. Tokenize text.
2. Notmalize text.
3. Choose N number of sentences to be in the final summary.
4. Make document-word feature matrix.
5. Build the document similarity matrix.
6. Use these similarity matrix as weights and sentences as nodes for the Pagerank algorithm.
7. Get the score per sentence and rank sentences based on these scores.
8. Return N top sentences for the topic.
