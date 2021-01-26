## BIENVENUE SUR MA PAGE WIKIDATA

### EXCERCICE 1
```sparql
Select DISTINCT ?peinture ?peintureLabel ?lieux ?lieuxLabel
where { ?peinture wdt:P170 wd:Q296. ?peinture wdt:P195 ?lieux.
SERVICE wikibase:label { bd:serviceParam wikibase:language "[AUTO_LANGUAGE],en".}
}
```
# EXCERCICE 2
```sparql
select DISTINCT ?peinture ?peintureLabel ?img 
where {
 ?peinture wdt:P170 wd:Q296.
 ?peinture wdt:P18 ?img.
SERVICE wikibase:label { #pour récuéprer les labels
bd:serviceParam wikibase:language "fr,en"}
}
```
file:///C:/Users/alyko/Documents/DA.html

Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/AlyKONATE/AlyWIKI/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
