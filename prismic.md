# Prismic editor guidelines

## REVIEWERS

* All lists must be rendered using either numbered or unnumbered list attribute from text editor. Do NOT use in-text “-” character ! 
* All uploaded images must integrate alternative attribute.
* All images must integrate and fill “alt” field. This will be automatically added if image has alternative attribute. If not, you’ll need to add alternative attribute on image in gallery and re-insert it into document, or add the alt attribute by yourself on document’s image.
* Do not keep empty lines at end of text.
* Documents images must be resized.

## STRUCTURE

### Custom types

* Custom type’s name should be written in english, using human case
* Custom type’s App ID should be written in english, using kebab-case
* UID is mandatory, at top of custom type, downcase, using kebab-case
* Fields names should be written in english, downcase, using human case
* Fields API IDs should be written in english, downcase, using snake_case
* Fields placeholders are not mandatory
* It can contains meta fields, which needed to be named “meta title” (`meta_title`) and “meta description” (`meta_description`)

### Contents

* Image alts fields are mandatory
* Image dimensions needed to be uploaded in Prismic gallery and be resized
* Tags are not mandatory but can be added for research purposes
* Title of page has to be named “page title” (`page_title`), even if there is only one title on the content
* Always prefix general content fields with “page ” (`page_`)
