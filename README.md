# NGSA-Dataset

A structured, open dataset of NGSA past papers (paper 1 question and answers), compiled for educational and non-commercial use. Includes multiple choice questions, answers, and metadata in JSON format for easy integration.

## Why I Created This

I wanted this data for a personal project, but couldn’t find it on the Ministry of Education’s website, so I built it myself. I'm sharing it so others (teachers, developers, students) can benefit too.

## File Structure

```

ngsa-dataset/
├── README.md
├── LICENSE
└── data/
    ├── english/
    │   ├── ngsa-english-dataset-qa-2021.json
    │   ├── ngsa-english-dataset-qa-2022.json
    │   └── ...
    └── math/
        ├── ngsa-mathematics-dataset-qa-2010-unfinished.json
        └── ...

```
**NOTE:**
- Files labeled with ```filename-unfinished``` contain question numbers and correct answer data only. The question text and answer option labels have not yet been added.
- Files labeled with ```filename-un``` contain question numbers, correct answer data, option labels, and question texts. The instruction text, context, and meta have not yet been added.
- Files labeled with ```filename-tests``` contain test metadata such as the subject, level, paper type, and a list of references (question_ids) that point to the individual questions.
- Files labeled with ```filename-qa``` contain the individual questions for each subject range

## License

This dataset is licensed under the Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0). You may use, share, and adapt the data for non-commercial purposes, provided you give credit to:

- Ezra Minty - [Compiler of the NGSA Paper 1 Dataset](https://github.com/xbze3)

Full license details: [ https://creativecommons.org/licenses/by-nc/4.0/ ] 
