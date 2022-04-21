# Annotation Project on Click-baiting YouTube titles
Annotation Project for course INFO-259 at UC Berkeley with Prof. David Bamman, Spring 2022
- [Annotation Guidelines](https://github.com/6shun/Annotation_Project/blob/main/docs/guidelines.pdf)
- [Models](https://github.com/6shun/Annotation_Project/tree/main/notebook_classifiers)
- [Model Analysis](https://github.com/6shun/Annotation_Project/blob/main/docs/Model_Analysis.pdf)


This repo is structured as following:

```
.
├── data                            
│    ├── 1_raw_data.csv                 # Raw data
│    ├── 4_annotated_data.csv           # Annotated data
│    ├── 5_adjucated.txt                # Annotated data in .txt format
│    ├── 5_individual_annotation.txt    # Annotated data with individual annotation recorded   
│    └── ap_data                        # Final data
│           └── 1 
│                ├── train.txt
│                ├── dev.txt
│                └── test.txt                  
├── doc                                 
│    ├── guidelines                     # Annotation guidelines
│    └── Model_analysis                 # Results and analysis
├── notebook_data_process               # Notesbooks for preprocessing data
│    ├── AP1_preprocess.ipynb           # Cleaning raw data for annotation
│    ├── AP2_annotate_data_to_txt.ipynb # Annotated data to txt files
│    └── Data Validator.ipynb           # Validating Data for classifiers
├── notebook_classifiers                
│    ├── LogReg.ipynb                   # Logistic Regression
│    └── BERT.ipynb                     # BERT
└── README.md
```