# Story Booth
Omeka-S theme for Dartmouth College Library's Story Booth project

## Installation

Add this to your standard themes directory in Omeka-S

## Special Instructions for Items

This theme is specific to the Story Booth project and adds a basic grid system and 
UI enhancements including a specific color palette. Developed by Joshua Shaw, DLTG, 
Dartmouth Library. Based on the SpeakOut theme: [https://github.com/dartmouth-dltg/speakout](https://github.com/dartmouth-dltg/speakout)

This theme is designed to work with the RandomItems module (DLTG fork):
[https://github.com/dartmouth-dltg/omeka-s-module-RandomItemsBlock](https://github.com/dartmouth-dltg/omeka-s-module-RandomItemsBlock)

Items should have the following metadata values assigned

- Title
  - A name given to the resource.
  - Use dcterms:title
- Description
  - A concise description of the item
  - Use dcterms:description
  
 Each item should also have two media assets associated with it
 
- Image
   - Use dcterms:title
   - alt tag
- HTML transcription of the image text
   - Use dcterms:title to set the title
   - Use dcterms:type set to 'storybooth'
   - media tab:html with formatted transcription of the image text