# Next

# Bug
- get_entity seems not working well with redirects, try L6798, see L6799 for example
 - index.html?lid=L1083187-S3 - problem with redirects

# Todos
- think about behaviour of navi button (show on tap?) (nikki)
- cancel overlays with close button or tap on background (nikki)
- highlight seems to persist on mobile after tap (nikki)
- lexemes with several senses have unneccessary mdash outside focus
- Show antonym as a link at the end of the sense
 - maybe other special relations?
- navigate with keyboard through search results
- navigate with keyboard through lists
 - press shift + z, q, etc. highlight the possible result, and go only letting go shift
- keyboard navigation for the meaning switches
- etymon also P5425 (has Han characters)
- prevent keyboard or click events when not ready
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
- Show links to other dictionaries
- Use Wikifunctions for transliterations e.g. of Hangul or Harigana or Greek or Cyrillic
- navigation animation from lists takes always the whole list instead of only the single entry (inline is not animatable)
- deal better with more than one audio
- what happens when loaded with invalid lid
- allow to swipe on mobile
- add get_entities that takes and returns a list
- use get_entities that gets more than one entity at once
