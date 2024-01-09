# Next
- internationalize help overlay

# Bug
- get_entity seems not working well with redirects, try L6798, see L6799 for example
 - index.html?lid=L1083187-S3 - problem with redirects

# Todos
- navigate with keyboard through search results
- navigate with keyboard through lists
- speed up page
 - audit all awaits if they are really necessary
 - order animation and awaits better
 - add get_entities that takes and returns a list
 - use get_entities that gets more than one entity at once
- etymon also P5425 (has Han characters)
- prevent keyboard or click events when not ready
- underlined senses loose highlight when out of center and being hovered
- add IPA, syllabilization? next to audio button?
- fix right to left languages
- Meaning hierarchy
  - check out P279 transitively
  - check out P31 as well
  - ensure what is seen is stable
  - going down, currently aribtrary limit of 50
- images
 - deal with images that have too much height?
 - add icon P2910 to image,  would add: 3 on Lexeme / 20 on Senses / 5,000 on items 
 - maybe make it cream and brown for an inactive sense?
- Meaning rings
  - P6271 (demonym)
  - ensure what was seen stable, but add on the way
  - caches of meaning rings
- store the sense ID when moving away from a lexeme and coming back
- It seems that when the same lemma gets at the border we might skip homophones eg honey the noun
  - Solve by putting >= instead of >
  - increase the limit from 10 considerably for speed up
- on keyboard navigation, when navigating to an empty field, what happens? (eg no etymon but press z)
- Show antonym as a link at the end of the sense
 - maybe other special relations?
- Show links to other dictionaries
- Use Wikifunctions for transliterations e.g. of Hangul or Harigana or Greek or Cyrillic
- deal better with more than one audio
- what happens when loaded with invalid lid
