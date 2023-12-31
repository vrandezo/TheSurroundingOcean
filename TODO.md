# Next
- Meaning rings
  - follow P5972, P5973, and P5137 and their statements
  - get synonyms and put them to the right
  - get translations and put them to the left
  - make it a ring
  - ensure what was seen stable, but add on the way
  - get item for this sense equalities and put them to the left of that
  - caches of meaning rings

Bug: L471585-S2 (doesn't have a S1 so it gets confused)
Nice to test:
L587637-S1
L304013
L643086

# Todos
- replace (1) with (space)<b>1.</b> ? (compare standard dictionaries)
- Highlight individual senses of more than one, up and down goes through them, clickable
  - Only the highlighted sense is relevant for the meaning ring and hierarchy
  - when moving to other LID, ensure that sense_id is set to the right sense, i.e. S1?
- display meaning hierarchy
  - re hierarchy, check out P279 and P6593 and their statements
  - cache meaninig hierarchy
  - ensure what is seen is stable
- It seems that when the same lemma gets at the border we can skip homophones eg honey the noun
  - Solve by putting >= instead of >
  - increase the limit from 10 considerably for speed up
- display image
- on keyboard navigation, when navigating to an empty field, what happens? (eg no etymon but press z)
- add Wikipedia links to senses
- use item for this sense for senses for alternative glosses in language
- Show antonym as a link at the end of the sense
- Show links to other dictionaries
- Show link to Wiktionary
- Use Wikifunctions for transliterations
- allow for navigation by keyboard
- add README, LICENSE, CODE OF CONDUCT etc.
- add IPA, syllabilization? next to audio button?
- navigate with keyboard through lists
- figure out different lemmas with other language codes
- deal with overflows
- animate navigation
- gray out the edges?
- add language selector
  - ensure languages work
  - Test right to left languages
- search for a lexeme?
- display help on keypress
- display something to display help
- add about
- show placeholders and loading signs
- deal better with more than one audio
- audit all awaits if they are really necessary
- add get_entities that takes and returns a list
