# CaseLaw_NLP
###Extractive and Abstractive Methods for Case Law Summarization

The scope of this project is to produce automated summarization of Case Law by utilizing extractive and abstractive NLP models. <a href=https://en.wikipedia.org/wiki/Case_law>Case law</a> is a collection of legal decisions that are used to determine legal precedents for future cases. 

The <a href="https://case.law/">Caselaw Access Project</a>, compiled by Harvard Law School, is a corpus of three hundered years worth of Case law documentation in the United States. Cases from North Carolina were used as <a href=https://case.law/bulk/download/>source data</a> for this project.

Summarization methods include extractive summarization using <a href=https://radimrehurek.com/gensim/summarization/summariser.html>gensim's summarizer function</a> and abstractive summarization using a base Seq2seq model, <a href=https://arxiv.org/abs/1903.10318>BERTSUM</a>, and an implementation of <a href=https://openai.com/blog/better-language-models/>GPT-2</a>.

A full project description can be found in <a href=https://github.com/hlandman/CaseLaw_NLP/blob/master/NLP_CaseLaw.ipynb>this notebook</a>. 
