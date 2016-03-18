# answerbag-dataset

This data covers 187,234 "professionally-researched" question-answer pairs from
answerbag.com as of late 2015.  This is a recrawl based on the [answerbag
dataset][] distributed by Alessandro Moschitti, which did not include the full
set of questions originally.

Both questions and answers are given as tuples of the form `(qid, text)` in the
respective files, ordered by the field `qid`.  Both files are gzip'ed and tab-delimited.

[answerbag dataset]: http://disi.unitn.it/moschitti/Teaching-slides/NLP-IR/qa.tar.gz
