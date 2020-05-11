# NER Annotation Suite Documentation

This repository is reserved for the documentation of the [NER Annotation Suite](http://christianbudhi.com/projects/ner-annotation-suite/about). Each section is maintained as a separate markdown file and referenced in the contents.json. A section will only be enabled in the application if an entry is added in the details dict **and** its key is added to the sections list.


## content.json interface
``` typescript
// main table of contents object
interface TableOfContents {
    // list of sections to enable in the application
    sections: string[], 

    // dictionary of section details
    details: { [sectionTitle: string]: ContentInfo } 
}

// Information required for section page
interface ContentInfo {
    // section title to display in table of contents
    title: string; 
    
    // reference to markdown file
    url: string; 

    // reference to subsection to show on table of contents
    sectionIds: string[]; 
}
```