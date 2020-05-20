# Annotating Data
This guide will show you how to use the annotation suite to prepare your data for training a named entity recognition model after you've finished setting up.

## General Information

The main page of the NER Annotation Suite is comprised of three parts: the sentence queue panel, the entity tag panel, and the main annotator panel. Each of these sections will help you annotate and monitor your data and tags.

![Annotation Suite View][annotationScreen]
*Sample view of an annotation session*

Brief summary of each panel:
- **Setence Queue Panel (left)** - This panel will let you view the current and upcoming items to annotate and also add more items to the queue. 
- **Entity Tag Panel (right)** - This panel will let you view, edit, and delete the tags you will use to annotate your data.
- **Annotator Panel (center)** - This panel will be the main hub you will use to annotate your data.

## Setence Queue Panel

The sentence queue panel, to the left, is comprised of two parts: the sentence queue view, and the sentence input controls.

![Sentence Queue Panel][sentence-queue]
*sentence queue panel view - empty*

### Sentence Queue View

If sentences are ready to be annotated, a list of the next ten sentences will be display on the bottom section of the sentence queue panel. Any remaining sentences will be indicated at the bottom. The sentence at the top will be the sentence currently being staged for annotation.

Hover over the sentences to view them completely.

### Sentence Input Controls

Additional sentences can be added to the queue by entering the text into the text box and clicking the plus button. Sentences will be added to the end of the queue and cannot be empty or already exist in the training set.

## Entity Tag Panel

The entity tag panel, to the right, will allow you to create, edit, and remove the entity tags used for annotating your data.

![Entity Tag Panel][add-tags]
*entity tag panel view*

### Adding An Entity Tag

An entity tag can be added to the list by inputing the name on the bottom section of the entity tag panel and clicking add. The display color can also be changed by clicking the palette icon and selecting a color. This color will be the highlight color used to display tagged entities in you sentence.

### Editing An Entity Tag

![Entity Tag Edit][edit-tags]

By clicking the pencil icon of an entity tag, a popup will appear (displayed above) that will allow you to edit the tag's name and color. In order for you change to take effect you must click 'save'; otherwise, click the x icon to cancel. 

Editing an entity tag's name and/or color will propagate changes to existing entities in data that has already been tagged.

### Removing An Entity Tag

You can remove an entity tag by click simply clicking the trash can item on the entity tag item. This operation will not remove entities with this tag on already tagged sentences.

## Annotator Panel

documatation in progress

[sentence-queue]: https://christian-budhi-hosting.s3.amazonaws.com/ner-annotation-suite/ner_sentence_input.PNG

[annotationScreen]: https://christian-budhi-hosting.s3.amazonaws.com/portfolio/ner-annotation-suite.PNG

[add-tags]: https://christian-budhi-hosting.s3.amazonaws.com/ner-annotation-suite/entity_tag_panel.PNG

[edit-tags]: https://christian-budhi-hosting.s3.amazonaws.com/ner-annotation-suite/entity_tag_edit.PNG