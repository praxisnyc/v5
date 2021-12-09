# praxis v5


https://praxis.nyc/v5
https://delicious-cloche-a58.notion.site/mesa-1f47efa0c20e4855a4928e37a53a4abd

## TODO

- [ ] slides, language swap
- [ ] design `post-list`
- [ ] switch `category-post` for `post-list`
- [ ] other articles on same category (on `single`)
- [ ] different headers for different categories on `single`
- [ ] what do we do with orphan articles? find category for it
- [ ] categories on footer
- [ ] redesign initial page 
- [ ] language, persistent
	```
	on load
	text + slug
	get slug from glossary.yaml
	get if any dangerous character
	if yes, text
	if no, continue
	check parent lang=
	check if we HAVE term in this language
	if yes, do popover
	if no, just text
	```


## TODO, communications

- [X] hugo on josh's computer
- [X] hugo-figma integration
- [ ] glossary
	- [ ] add more terms
	- [ ] define glossary types, create slideshow
	- [ ] be updated of changes
- [x] consulting
- [ ] sketch remaining pitch images
- [x] referance images for drawings
- [x] start working on brand
- [ ] review illustration assets
- [ ] revisit image/animatic script
- [ ] design screens based on script and brand

## Script for map

- elder care
	- food delivery
	- medication/nursing * problem area
	- transportation
	- social connection
	- patient profiles
	- timeline/calendar

## advanced project navigation

- app borders signal hierarchy
- easy way to flip things to you or others in the group (affordance needed)
- pinning stacks for arguments (cards, timelines, etc)
- borders as wayfinding ACROSS apps/projects
- borders as multidirectional viewing
- borders as panels, windows
- poker table (slides repeat for each person)
- cartoon physics pin group (you can minimize it and expand it again without losing position)

## bugsbunny picnic

- borders as affordance
- shared destiny (internal consistency)
- groups as proposals, with arguments stacked inside it
- arguments can be:
	- cards
	- image/animated crops
	- groups
- tucked-in objects (kinda personal)

## timeline recall

- possibility to add chapters
- skip to next chapter

## font selection criteria

- international (accents, languages)
- open license or a very liberal license
- a lot of weights
- readability (from far away? from low definition projectors?)
- titles and long text


````
cd ~/Documents/praxis/v5
git pull
open -a "sublime text" .
open http://localhost:1313/v5/
hugo server -D

```