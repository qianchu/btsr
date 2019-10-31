In this folder, you will find the data and guidelines for Bilingual Token-level Sense Retrieval Task (BTSR)

    1. guideline.en-zh: The guideline for Chinese
    2. guideline.en-es: The guideline for Spanish
    3. btsr.en-zh: the test data for en-zh btsr
    4. btsr.en-es: the test data for en-es btsr
    5. btsr_candidates_20k.en-zh.en: With English as the target language, the 20k English candidates to search from for en-zh btsr test set.
    6. btsr_candidates_20k.en-zh.zh: With Chinese as the target language, the 20k Chinese candidates to search from for en-zh btsr test set. 
    7. btsr_candidates_20k.en-es.en: With English as the target language, the 20k English candidates to search from for en-es btsr test set.
    8. btsr_candidates_20k.en-es.es: With Spanish as the target language, the 20k Spanish candidates to search from for en-es btsr test set. 
    9. readme.MD (this document)


For btsr_en-zh and btsr_en-es, each line of the file contains the Chinese/Spanish test case followed by ' ||| ' symbol and then the corresponding English test case:

    <Spanish/Chinese test case> ||| <English test case>

The candidate files (btsr_candidates_20k....) only contain the test cases in the target language. 


A test case specifies a word a context. For a test case, the format is the following:

    [test word lemma]::[position of the test word in the sentence] |&| [the sentence containing the test word]






 