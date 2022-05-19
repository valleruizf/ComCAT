# ComCAT

ComCAT is a Catalan corpus annotated with negation.

The data consists of 222 comments in response to news articles published from January to March 2022 on the online version of the Catalan newspaper Ara. The news articles cover four topics: the Catalan independentist process, violence against women, climate change and housing. 

The corpus is divided in four directories according to these topics. In each of them, the comments are compiled in raw text (txt) in the same order in which they appear on the web after removing duplicates. The name of each file consists of the publishing date of the article to which the comment belongs (year-month-date format), followed by the comment number.

Only those comments containing at least one negative particle are annotated. The annotations for each comment are in Brat stand-off format (.ann) in the same directory as the raw text.

This collection also contains the configuration files needed to create the annotations in the text and visualize them. 
- annotation.conf includes the definition of tags, attributes, values and relations.
- kb_shortcuts.conf contains the keyboard shortcuts that can be used for quick type selection in annotation.
- tools.conf brings together the tools needed to visualize the text, such as the tokenizer, and to annotate.
- visual.conf defines the visual configurations of tags: possible abbreviated or complete labels, colours and arrows. 

To visualize the annotations, download this collection and import it to the "data" directory of Brat.

This corpus is part of a double BA final project, in which the guidelines followed to annotate negation can be found.
