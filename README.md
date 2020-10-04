# QADiscourse
Discourse Relations as QA Pairs

This repository contains code and data accompanying the EMNLP 2020 paper: "QADiscourse - Discourse Relations as QA Pairs:
Representation, Crowdsourcing and Baselines"



# QADiscourse Dataset

All data is presented in a .tsv format, with each row corresponding to one QA pair:
    
    0. **qasrl_id** Same sentence IDs that are used by QASRL and QAMR.
    1. **sentence** Tokenized sentence.
    2. **worker_id** Anonymized worker ID.
    3. **full_question** Full question where we joined the question start with the auxiliary or _ if no auxiliary was added and the question body. Not preprocessed.
    4. **full_answer** Answer to the question.
    5. **question_start** Question Prefix.
    6. **question_aux** Auxiliary or _ if none.
    7. **question_body** Question body.
    8. **answer** Answer.
    9. **untokenized sentence** Same sentence as in 1. but untokenized.
    10. **target indices for untok sent** Target indices extracted for a specific sentence using heuristics, for the untokenized sentence.