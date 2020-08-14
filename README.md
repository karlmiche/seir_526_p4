## P4 App

### love&order

* New tech you plan on using

* Name of app
love&order

My background includes poetry! If you think about it, poetry is a type of data visualization that follows a reliable algorithm (certain number of syllables, constrained amount of lines, matching consonants or 
sounds). The new tech I plan on incorporating is GSAP (a javascript animation library).

3. What is your goal with this project?

By now, I know I am interested in machine learning, data visualization, APIs that manipulate or classify data, and interactive frontend development. To challenge myself, I'd like to learn to use the Green Sock Animation Platform with React for a truly beautiful frontend experience, and to create a Python backend to challenge myself in terms of manipulating data. 

For love&order, I'd like to: have users search for news articles as a text source with a simple news API, filter selected article text through the Google Natural Language API, classify different syntactical parts of speech, and then categorically rearrange the parts of speech according to different poetic structures (you've got options! Haiku? We can make one. A villanelle? Sure.)

5. Who is the user for your app?

I think the 24-hour news cycle is nuts, and I'm totally guilty of participating in unhealthy news consumption (thank you, clinical OCD). I'd like to make this app to help people process the news in a different way, but also as a callback to things that were important to me in the past. The user is me, but also those who are interested in interactive frontend experiences.

1. How do you plan on learning/implementing this new technology?

Taking the first day to read documentation/take notes on documentation without diving into building anything. From project three, I learned that we were successful because we took a lot of time to learn and plan, and let the project drive itself from our plans. I also plan on using articles, youtube tutorials, and anything I can get my hands on in terms of learning how to accomplish these goals.

7. Any potential roadblocks you think you might run into?

I am imagining combining Python and React to be a potential roadblock that I hope to avoid by spending a lot of the first day reviewing resources. This is just something I haven't done before. In terms of using GSAP, I am also anticipating that incorporating GSAP with React might be a challenge, since GSAP involves DOM manipulation, and I haven't really spent much time animating elements.

## Intended Pseudocode/Under the Hood (So Far)

// grab words from news articles with news API
https://newsapi.org/

// categorize each word with google nlp - in Python this time
https://cloud.google.com/natural-language

// count syllables in each word
https://stackoverflow.com/questions/46759492/syllable-count-in-python

// group words by part of speech and number of syllables

// make a string of words that is a certain number of syllables long organized by part of speech
    // if this type of word, add to array
    // until array is this many syllables

// return a set number of arrays as lines 

// stringify arrays

// style words as they appear on the page with animation through GSAP 

// style components of the page with GSAP in an interactive and beautiful way

## User Flow
A user can select from a list of poem options what they'd like to see, and then search for a news topic. They then select an article. Once an article and a poem type have been selected, a poem is generated for the user.

## Sources So Far
* https://blog.miguelgrinberg.com/post/how-to-create-a-react--flask-project
* https://greensock.com/gsap/

### Possible effects with GSAP/Websites with effects I like
* https://codepen.io/natewiley/pen/xGyZXp
* https://codepen.io/SergioDaroca/pen/dNPpNe?editors=0010

* Breakdown individual tasks and what you plan on working on day by day (in a Trello board or some other project planning tool/format). 

## Planning/Notion
https://www.notion.so/love-order-4c67be4a09924cb4bb7f05025815fef6

## Wireframes
Potential layout page:
![](https://i.imgur.com/P1qvvzy.jpg)