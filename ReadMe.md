In this project, I am making Question-Answer System by finetunig DistilBert model of Huggingface on BoolQ dataset provided by HuggingFace.

BoolQ is a question answering dataset for yes/no questions containing 15942 examples. These questions are naturally occurring ---they are generated in unprompted and unconstrained settings. Each example is a triplet of (question, passage, answer), with the title of the page as optional additional context.

I got accuracy of 63% by finetuning. we will get more better results by hyperparameter tuning.