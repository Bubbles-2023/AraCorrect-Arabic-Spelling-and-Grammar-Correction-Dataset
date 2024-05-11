# AraCorrect-Arabic-Spelling-and-Grammar-Correction-Dataset
# Arabic Grammatical Error Correction Dataset

This repository provides a dataset for training and evaluating models that correct grammatical and spelling errors in Arabic text. It addresses the limitations of existing datasets by offering a larger, more diverse set of examples with a wider range of error types.

## Key Features

* **Main Dataset (AGEC):**
    * Open access, published in 2022
    * 13,333,929 records (sentences) for AGEC (Arabic Grammatical Error Correction)
    * Two splits:
        * Train: 11,833,758 records
        * Validation: 1,500,171 records
    * Access link: [AGEC dataset link] (replace with actual link)
* **Modified Dataset (Enhanced AGEC):**
    * Approximately 2,000,000 records
    * Enriched with additional errors mimicking real-world scenarios
    * Contains 1,999,878 sentences and 49,785,900 words

* **Error Types:**
    * A noise injection technique was employed to introduce additional errors into the AGEC dataset. (Details on the technique can be provided here, if applicable)
    * Errors were meticulously designed to reflect the most frequent grammatical and spelling mistakes encountered in everyday Arabic text, following these approximate injection rates:
        * Spelling Errors: 10% (e.g., typos, missing letters, extra characters)
        * Grammar Errors: 12% (e.g., mismatched gender, number, person, case, tense, word order, extra or missing words)
        * Segmentation Errors: 12% (e.g., incorrect word boundaries)
        * Dots: 15% (e.g., accidental keystrokes from neighboring keys)
    * Injections were randomized across all sentences, ensuring a diverse distribution of errors.


## Motivation

The NLP (Natural Language Processing) domain, particularly transformer models, thrives on large datasets. However, the commonly used QALB 2014 dataset only offers a limited size of 20,430 sentences. This restricts the ability of models to generalize effectively on real-world Arabic text, which often contains diverse and nuanced errors.

## Addressing the Need for More Data

To enhance the capabilities of Arabic grammatical error correction models, we introduce this dataset. By providing a more comprehensive and varied set of examples, we aim to:

* Improve model accuracy on various error types
* Enhance model robustness in handling complex real-world scenarios
* Foster advancements in Arabic NLP research

## Dataset Creation

* **Main Dataset (AGEC):** This publicly available dataset serves as the foundation for our work.
* **Modified Dataset (Enhanced AGEC):**
    * A noise injection technique was employed to introduce additional errors into the AGEC dataset. (Details on the technique can be provided here, if applicable)
    * Errors were meticulously designed to reflect the most frequent grammatical and spelling mistakes encountered in everyday Arabic text.
    * Injections were randomized across all sentences, ensuring a diverse distribution of errors.

## Dataset Statistics

| Feature        | AGEC Dataset                 | Enhanced AGEC Dataset               |
|----------------|------------------------------|--------------------------------------|
| Sentences      | 13,333,929                    | 1,999,878                             |
| Train Split     | 11,833,758                    | - (subset of Enhanced AGEC)         |
| Validation Split | 1,500,171                    | - (subset of Enhanced AGEC)         |
| Words           | Not provided                  | 49,785,900                             |
| Error Types     | Limited to AGEC errors        | Spelling, Grammar, Segmentation, Dots |
| Access Link     | [AGEC dataset link]          | Provided within the repository        |

## Benefits of Using This Dataset

* **Larger Scale:** Significantly more training data for improved model performance
* **Diverse Error Coverage:** Enhanced representation of real-world Arabic errors
* **Publicly Accessible:** Freely available for research and experimentation

## Future Work

We plan to expand this dataset further by:

* Incorporating human-annotated errors for higher quality
* Including different error severity levels
* Exploring additional error types specific to Arabic dialects

## Contribution

We believe this enhanced AGEC dataset offers a valuable resource for the NLP community, fostering the development of more robust and accurate Arabic grammatical error correction models. We encourage researchers and developers to utilize this dataset in their work.

## How to Use the Dataset

(Provide instructions on file format, data separation, etc., if applicable)

## License

(Specify a license for the dataset, e.g., MIT License)

