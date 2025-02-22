# master-thesis-2024
This is my MS Thesis named "Conspiracy Theories vs Critical  Thinking Using an Ensemble of  Transformers and Large Language  Models".

This thesis contributes to the PAN at CLEF 2024 Oppositional Thinking Analysis shared task, focusing on automatically differentiating between conspiratorial and critical thinking narratives. 

The task includes binary classification to identify texts as conspiratorial or critical and span-level detection to recognize narrative elements like Agents, Facilitators, Victims, Campaigners, Objectives, and Negative Effects. Two multilingual datasets, in English and Spanish, with 5,000 annotated Telegram comments each, presented challenges such as class imbalances and complexities in detecting partially overlapping spans.

For the binary classification task, a Soft Voting ensemble of fine-tuned Transformer models, enhanced with data augmentation techniques like back-translation, achieved F1-macro scores of 0.8917 for English and 0.8293 for Spanish. 

The span-detection task emphasized precise tokenization and synonym replacement to maintain token alignment, crucial for detecting narrative spans. Great emphasis was placed on data preprocessing that further improved model robustness, achieving a span F1 score of 0.6279 for English and 0.6129 for Spanish, which secured the best performance in the shared task for both languages and set a new state-of-the-art.

Additionally, experiments using Large Language Models (LLMs) significantly improved these results. By first employing zero-shot and few-shot learning techniques, and then fine-tuned LLMs enhanced cross-lingual understanding and narrative detection. These improvements underscore the effectiveness of LLMs in handling complex multilingual datasets, setting new performance benchmarks for both languages.

This thesis contributes to the field of narrative analysis, offering insights that may inform future research on improving narrative detection across other domains and highlighting the role of automated systems in combating misinformation in digital spaces.
