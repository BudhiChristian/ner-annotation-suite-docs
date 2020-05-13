# Getting Started

An important part of Natural Language Processing is knowing and processing your data set. This application allows you to process your data once you know what you want to extract out of it. 

On the start off the annotation process you will be brought to a setup page, which will help you load your data into the application and manage options before you begin the process. Entity tags can also be setup on this page.

## Selecting a Data Input Type

Currently the NER Annotation Suite supports two input types: 
1. On the fly data input
2. Preloaded data in the form of a txt file

### On the Fly Data Input (Start Empty)

By selecting "Start Empty" for input type, your session will start off with a blank slate. Once you begin annotation you will have the ability to add data on the fly using the panel on the left. 

![sentence queue reference][sentence-queue]
This panel will appear during the training stage

### Preloaded Data (TXT File)

By selecting "TXT File" for input type, you will be prompted to select a file from your local machine and sentence delimiter. This option will begin your session with any sentences present in the text file you provided, parsed by the sentence delimiter you choose.

![sentence text input][sentence-txt-input]

After uploading your file and selecting a delimiter, click the "Parse Text" button and the application will attempt to extract the sentences in your file and tell you how many it has found. It is important to note that in order to continue, you must click parse text so that your sentences may register with the application. 

Additional sentences may be added once you begin annotation using the same panel referenced in the "On the Fly Data Input" section.




[sentence-queue]: https://christian-budhi-hosting.s3.amazonaws.com/ner-annotation-suite/ner_sentence_input.PNG

[sentence-txt-input]: https://christian-budhi-hosting.s3.amazonaws.com/ner-annotation-suite/ner_text_input.PNG