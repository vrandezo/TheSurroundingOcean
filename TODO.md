# Next
- Meaning rings
  - P6271 (demonym)
  - ensure what was seen stable, but add on the way
  - caches of meaning rings
  - store the sense ID when moving away from a lexeme and coming back

Nice to test:
L5619-S1
L587637-S1
L304013
L643086

# Todos
- add P5238 to the etymons
- display meaning hierarchy
  - re hierarchy, check out P279 and P6593 and their statements
  - cache meaninig hierarchy
  - ensure what is seen is stable
- It seems that when the same lemma gets at the border we can skip homophones eg honey the noun
  - Solve by putting >= instead of >
  - increase the limit from 10 considerably for speed up
- display image or icon P2910
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
- show loading signs and throbbers when not ready
 - prevent keyboard or click events when not ready
- deal better with more than one audio
- audit all awaits if they are really necessary
- get_entity seems not working well with redirects, try L6798, see L6799 for example
- add get_entities that takes and returns a list
