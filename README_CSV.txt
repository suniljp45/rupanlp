NLP PRACTICALS - CSV VERSION WITH CHANGE COMMENTS

For each CSV-based program, look for lines beginning with:
    # CHANGE HERE

Those comments show exactly what to customize for the CSV file you receive.

GENERAL STEPS
1. Put the CSV file in the same folder as the Python program.
2. In pd.read_csv(...), change the filename to your CSV filename.
3. Print df.columns to see the exact CSV column headers.
4. Change TEXT_COLUMN and, where needed, LABEL_COLUMN / CATEGORY_COLUMN to select
   the correct columns. By default, df.columns[0] selects the first CSV column and
   df.columns[1] selects the second. If you prefer, set them to exact header names,
   for example: TEXT_COLUMN = "ReviewText".
5. Do not change the other variable names or algorithm code unless your assignment asks.

COLUMN SELECTION BY PRACTICAL
- Bag Of Words + TF-IDF: text column and optionally category/label column.
- LDA + LSA: text column.
- ML Sentiment Analysis: text/review column and sentiment/label column.
- News Classification: news/headline text column and category column.
- Word2Vec: description/text column; also update the example search word/query if desired.
- Transformer Sentiment: text/post column; language column is optional.

The remaining sample/demo programs are preserved from the prior CSV ZIP.
