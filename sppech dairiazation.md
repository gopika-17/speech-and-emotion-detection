---
license: cc-by-4.0
task_categories:
- audio-classification
language:
- bn
pretty_name: SUST BANGLA EMOTIONAL SPEECH CORPUS
size_categories:
- 1K<n<10K
---








### Downloading the data

```
from datasets import load_dataset

train = load_dataset("sustcsenlp/bn_emotion_speech_corpus",split="train")

```


### Naming Convention

Each audio file in the dataset has a unique name. There are eight parts in the file name where all the parts are connected by underscores. The order of all the parts is organized as: Gender-Speaker's serial number-Speaker's name-Unit of recording-Unit number- Emotion name- Repeating number and the File format. 

For example, the filename F_02_MONIKA_S_1_NEUTRAL_5.wav refers to:

| Symbol      | Meaning |
| ----------- | ----------- |
|      F      | Speaker Gender       |
| 02   | Speaker Number        |
|   MONIKA   | Speaker Name                     |
|  S_1    |  Sentence Number                    |
|  NEUTRAL     |  Emotion                    |
|    5  |  Take Number                    |

### Languages

This dataset contains Bangla Audio Data.

## Dataset Creation

This database was created as a part of PhD thesis project of the author Sadia Sultana. It was designed and developed by the author in the Department of Computer Science and Engineering of Shahjalal University of Science and Technology. Financial grant was supported by the university. If you use the dataset please cite SUBESCO and the corresponding academic journal publication in Plos One.







## Dataset Structure

### Data Instances

[More Information Needed]

### Data Fields

[More Information Needed]

### Data Splits

[More Information Needed]

### Curation Rationale

[More Information Needed]

### Source Data

#### Initial Data Collection and Normalization

[More Information Needed]

#### Who are the source language producers?

[More Information Needed]

### Annotations

#### Annotation process

[More Information Needed]

#### Who are the annotators?

[More Information Needed]

### Personal and Sensitive Information

[More Information Needed]

## Considerations for Using the Data

### Social Impact of Dataset

[More Information Needed]

### Discussion of Biases

[More Information Needed]

### Other Known Limitations

[More Information Needed]

## Additional Information

### Dataset Curators

[More Information Needed]

### Licensing Information

[More Information Needed]