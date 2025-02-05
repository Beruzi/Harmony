# Harmony
My attempt at creating music recomendation software to streamline the process and accurately cater to your taste.

------
## Thoughts
In the past I've been extremely frustrated with the quality of songs recomended to me by popular platforms like Apple Music and Spotify. While the latter is better, I still find myself annoyed with whatever their algorithms deam "similar" to a song or playlist. I've gained a rather rudimentary understanding of how these algorithms work after some internet browsing... there are *two* primary ways of recomending songs:
- Content Filtering
- Collaborative Filtering

Now for the record, I believe that both spotify and apple music use a combination of both -- in fact, that's probably the 'best' way to recommend songs. However, I do not like and will be attempting to develop my own method.

##### Collaborative Filtering 
This is when algorithms look at multiple users and find overlapping songs between them -- basically crowdsourcing. It then concludes that any songs that are not found in the intersection between the two are worth recommending to the party that lacks that song. While this strategy my yield some good results, I think its a poor way to quantify *my* taste... I like, many others, might thing there music taste is superior. Or a less egostitical measure, different people might like songs for different reasons: lyricism, tempo, common instruments, etc. 

##### Content Filtering
This is the more objective way to measure how similar one song is to another. You compare the actual songs and their qualities to one another... tempo, harmony, instruments, key, etc. This is what I'll be focusing on. 

## Plans
This project will also serve as my first real Machine Learning Project (sorry fantasy football projector). I intend on building off the knowledge and skills I've accumatlated in the ML space from my undergrad research with something a little more personally motivated. I imagine I'll need to pick up domain knowledge on audio and audio processing. If the model I intend on training becomes too computationally demanding, I will reach out to my University's High Performance Computing Lab and see if I can get access to that. 

