# MARC Excavations
## Disaster Maps
### March 6th 2019

I started digging the MARC record with a very literal digging. I looked inside the folder of corpora we were using for the example (animals) and decided to search for [the dinosaurs list](https://github.com/dariusk/corpora/blob/master/data/animals/dinosaurs.json). I excavated the Visual Materials and then the Maps. I feel like Maps are one of the first visualizations system made and I love seeing how they interpret the actual territory of a place. Also what kind of legends and visual code they use. This first excavation wasn't very useful, I realized the list of dinosaurs was too large so the code was running very slowly. Also, the most recurrent found word was 'dinosaur', 'fossils' and 'mammals'. So I went back to the JSON and deleted those that weren't actually a dinosaur species, which I wanted to find. The only map object with a species of dinosaur was a [Khaan](https://vignette.wikia.nocookie.net/dino/images/f/fb/3235657_orig.png/revision/latest?cb=20150912163902). Which was still something cool to find. I felt like Archeologist. With the 'cleaned' version of the JSON file I run the code again, it was taking even more to find things and I stopped it before I got any results.

At this point I decided that I should be looking for a smaller list of things to get more and faster results. In my stream of consciousness and remembering about our fellow dinosaurs, I remembered why they disappeared. And that led me to think about natural disasters. These kind of phenomena weren't such a big deal when I was growing up, until 2010 when I experienced the first big earthquake in my country (8.8 in the Richter scale) followed by a Tsunami that destroyed many coastal towns.

After this year, I'm not sure if my awareness of natural disasters grew bigger or the amount of natural disasters worldwide has increased. Many big earthquakes and tsunamis followed from that year (Japan, Haiti China) and hurricanes and floods were a daily news. So I asked myself, how are does these natural disasters appear in the Library of Congress. And specially, are they mapped in some way? Can natural disasters be drawn in a map?

So I used the [Environmental Hazards](https://github.com/dariusk/corpora/blob/master/data/geography/environmental_hazards.json) list and shrinked it to more general hazards that could be easier to find among the Maps records. I then uploaded to the [Glitch](https://disaster-maps.glitch.me/) sketch to see first, which ones I could find in maps and the occurrence through the years. To make it more legible I transformed the results into an Emoji that represent the nature of the hazard.

##### Lava = 🌋, Flood = 💧, Drought = 🍂, Mudflow = 💩, Tornado = 🌪, Thunderstorm = ⚡️

This is how it looks:

<p align="center">
  <img src="https://github.com/karihigh/s2_artistsinthearchive/blob/master/disastermaps.png?raw=true" align="middle" width="100%" style="border: 1px solid black">
</p>

What I would like to do next is add a tooltip to each object so that I can read the title and eventually link them to the actual object in the Library of Congress website. I should also add a year scale for the x axis so it is easier to get a better glance to the data through the years. Also, this definitely doesn't answer my initial question (if natural disaster have increased in time) because the amount of records always increase. And because this is just the search of a word that describes a natural-disaster in the Maps of the Library of Congress, not the actual facts.
What I can conclude, is that 💧 floods 💧 are the most recurrent thing to Map and thunderstorms aren't (only 1 object found). I would love to take a look at the maps to see what are they telling about natural disasters.
