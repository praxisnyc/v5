# praxis v5

> commons as root, all focus on mesa

https://praxis.nyc/v5
https://delicious-cloche-a58.notion.site/mesa-1f47efa0c20e4855a4928e37a53a4abd

## TODO, technical

- [x] move other terms to glossary data folder
- [ ] discuss capitalization
- [ ] rethink popover template
- [ ] create [indigenous glossary](https://gohugo.io/templates/data-templates/) slide with loop
- [ ] add more terms to glossary
- [ ] redesign initial page 
- [ ] slide rethinking
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
- [ ] consulting
- [ ] sketch remaining pitch images
- [ ] referance images for drawings
- [ ] references for brand and slides
- [ ] start working on brand
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


````
cd ~/Documents/praxis/v5
git pull
open -a "sublime text" .
open http://localhost:1313/v5/
hugo server -D

```