# Session prompts — "Better Vibes" deck

Verbatim prompts given to the coding agent during the creation and iteration of
`presentation-design.html` (later moved to `better-vibes/presentation-design.html`).

---

## 1. Initial request

> I'd like to create a presentation deck in an HTML file. I'm going to be discussing presentation design itself. Here's a rough outline: Good presentation design
> - you don't have to be a designer
> - don't have to have an awesome in-house slide template
> - you can use AI
> - think of this as a visual test harness
> - just have to care
>
> Why should I care?
> - you want to demonstrate that you care! virtue signaling is good, actually
> - or you don't want to undermine the good impression others may have of you
> - most importantly, you don't want something on your slides to distract your audience from the message
>
> background on good slide design
> - CRAP https://designlab.wisc.edu/resources/design-tips-and-tricks/crap-principles/
> - Presentation Zen
> - these are in the weights
>
> clip art round 2!!
> - psychological horror of images that are just a bit "off"
> - distraction from the content
> - undermining your point
>
> subtler antipatterns arising from AI generation
> - familiar layouts
>     - this is ok actually!
>     - don't worry about unless you want to stand out
> - excessive borders
> - redundant decoration
>     - bullets + numbers + icon + border + different accent colors for every item in a list?!
> - "navigation" - this is useful for orienting the user, but watch out for "nav" that is really just subtitles in a nav-like location
>     - purpose is: table of contents + you are here
>     - ideally consistent across the entire deck
>
> old mistakes that are starting to creep back in to AI-generated designs
> - text too small
> - too much content on a slide
>     - design for the back of the room!
>
> smaller common mistakes
> - text overlap
>     - creeps in when a design is generated with a grid, then text is edited later
> - icon misalignment
>     - icon & text can be tricky: there's not a single alignment rule, it's contextual
>
> all fixable by you
>
> here's a skill that can help remind you of some of these principles
>
> In the "familiar layouts" section I want a slide that looks like classic Claude-generated content, because it's recognizable now. This presentation should use modern design principles, with a clean layout and large typography. A subtle abstract accent element in the background should be present across slides, animating to a new position with each transition.

## 2. Retitle

> Great start. Retitle the presentation "Better Vibes: Care & Craft in your Presentation Design"

## 3. Small-print asides are an antipattern

> There are several places where you've added an explanatory sentence or subtitle in a small font; that's one of the antipatterns I'm encouraging the audience to avoid. On the slide where I talk about that principle, it'd be helpful to show the antipattern but then have the next slide be a cleaned-up version that avoids the just-seen pattern

## 4. General cleanup

> Otherwise, clean it up

## 5. Title slide typography + premise slide

> on the title slide, I want bigger font size for the "Care & Craft" subtitle. Move "you don't have to be a designer.." to its own following slide

## 6. No period after "Better Vibes"

> No period after "Better Vibes"

## 7. Don't wrap the subtitle

> Don't wrap the "Care & Craft" line

## 8. Remove accent titles

> remove accent titles such as "the premise" throughout, but keep "a talk about talks" on the title slide

## 9. One point per slide

> on the slides where three points are listed as text (such as the "you want to demonstrate that you care" slide), split those into one point per slide

## 10. Trim structure; shared heading; subtitle restrictions

> remove the second slide. remove line 05 from the next one. for the three slides outlining why you should care, keep "Why should you care?" as a heading across all of them. On the virtue-signaling one, the subtitle should only be the "virtue signaling is good, actually" text. remove the other subtitles from the other two slides in that section

## 11. References + split a line out

> Mention slide:ology and Robin Duarte in the "in the weights slide". Move the "models have read all of it" line to its own slide

## 12. Lorem ipsum for the familiar-layouts demo

> The "Leveraging Familiar Layouts for Maximum Impact" slide gets my point wrong; I would like that to be lorem ipsum text, and I'm just trying to demonstrate that everyone can clock a Claude-generated layout. I want to follow that slide with another that has the same lorem ipsum content, but laid out in a way that reduces redundant decoration. Following slides will then explain what's changed

## 13. Bigger type, shorter sentences on the clean slide

> make the font sizes much larger on slide B there, and cut down the length of each of the "sentence" elements by half

## 14. Consistent antipattern headings

> My antipattern section should have a small upper-left heading, consistently "Antipatterns: <antipattern being discussed>". refer to my original outline text to figure out the subsections ther

## 15. Familiar layouts isn't an antipattern; bigger headings

> "familiar layouts" is its own thing, not an antipattern here. "antipattern:" headings are way too small. Muted is ok, but need to be way bigger

## 16. Reorder; heading style matches h2

> Move the lorem slides to come before the antipatterns section. Use a very similar heading style to the in-page headings for the Antipatterns headings - BIG is fine up there

## 17. AI images are an antipattern

> AI images section is one of the antipatterns.

## 18. Trim the AI-images slide

> drop the h2 there, and remove the em dash & following text

## 19. One slide per section

> "if the image feels fake" is the slide to keep in that section, drop the others

## 20. Manual edits round 1

> I've manually edited a bunch of the slides.

## 21. Move the deck

> I'd like to move this HTML file to a new directory, and I'm going to add an image there

## 22. Add the image

> on the "images for the sake of images" slide add ./image-for-the-sake.jpg on the right side of the slide

## 23. Icon-alignment examples

> The "icon misalignment" slide needs some minimal visual examples of what the text mentions. keep it simple, bold

## 24. Fix the fourth example

> the fourth example of a two-line label is actually misaligned. It should be aligned to the top of the first line

## 25. Nudge alignment

> scoot it up another 5px, and do the same for the one-line

## 26. Cut a line

> and remove the "both are easy to fix" line

## 27. Nudge back

> bring the two-line one back down another 5px

## 28. Manual edits round 2

> I've made more edits

## 29. Manual edits round 3

> I removed a few more

## 30. Export + skill

> I'd like my prompts in this session exported as an MD file. Can you also distill a skill from this session, writing up design principles that I talk about and that I made?
