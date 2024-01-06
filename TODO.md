# Next
- display image or icon P2910

Nice to test:
L5619-S1
L587637-S1
L304013
L643086

# Todos
- change the cursor when it can click, highlight the clickable area
- add Wikipedia links to senses
- deal with overflows
 - when lists remove senses
- show loading signs and throbbers when not ready
 - prevent keyboard or click events when not ready
- animate navigation
- search for a lexeme?
- add language selector
  - ensure languages work
  - Test right to left languages
- display help on keypress
- display something to display help
- add about
- add README, LICENSE, CODE OF CONDUCT etc.
- navigate with keyboard through lists
- add IPA, syllabilization? next to audio button?
- figure out different lemmas with other language codes (eg en-US and en-GB or different alphabets)
- Show link to Wiktionary
- L16666 shows self as hyper and hypo
- start at L1191593 then go to etymon dog, and I can't go back anymore
- Meaning hierarchy
  - re hierarchy, check out P279 and P31 in addition to P6593 and their statements
  - cache meaninig hierarchy
  - ensure what is seen is stable
- Meaning rings
  - P6271 (demonym)
  - ensure what was seen stable, but add on the way
  - caches of meaning rings
  - store the sense ID when moving away from a lexeme and coming back
- It seems that when the same lemma gets at the border we might skip homophones eg honey the noun
  - Solve by putting >= instead of >
  - increase the limit from 10 considerably for speed up
- on keyboard navigation, when navigating to an empty field, what happens? (eg no etymon but press z)
- use item for this sense for senses for alternative glosses in language
- Show antonym as a link at the end of the sense
- Show links to other dictionaries
- Use Wikifunctions for transliterations
- deal better with more than one audio
- audit all awaits if they are really necessary
- get_entity seems not working well with redirects, try L6798, see L6799 for example
- add get_entities that takes and returns a list
- what happens when loaded with invalid lid
- press navigation button to a field that doesn't exist (e.g. to etymon when there is none)
