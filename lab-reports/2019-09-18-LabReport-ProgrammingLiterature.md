# Lab Report: LAB NAME

#### YOUR NAME

## Process Description

This week's lab involved using the website Tracery to program a randomly generated body of text based on a snippet of a poem. Then, we used this program to create a Twitter bot. When we started the instruction portion of the lab, my first mistake was that I started off in Safari, and nothing worked. I tried to copy and paste the sample Tracery code, but it wouldn't even paste into the text box. I switched to Chrome right away, and it worked, so this is what I used for the rest of the exercise. Once we started creating our bodies of text, I definitely had trouble getting my text to work. I was creating my text in text editor and then copying and pasting it into Tracery, but it was consistently just showing up as ((origin)). To troubleshoot this, I tried building it directly in Tracery and then pasting it into the text editor once it worked just so I wouldn't lose it. 

I started working on the piece of text (in this case, a snippet of T.S. Eliot's "The Love Song of J. Alfred Prufrock") by simultaneously inputting the parts of speech and the origin, so the poem would develop in parts as I worked on it. For example, I would input words in a category as follows: "time":["minute","second","year","decade"], and so on. Meanwhile, I would add this section to the origin, writing: "origin":["In a #time#,"]. This way, I could see section by section if the syntax was correct, and if anything was wrong I could just get rid of and redo that one element. I ended up finishing the JSON file at home, and then once I'd worked on it for a while more, I plugged it into my twitter account. I initially had some problems with line breaks not showing up the right way in Twitter, but I got it functioning the right way after a while. After seeing what it generated, I went in and added more options for nouns and verbs beyond words that nodded towards Eliot's work. It was getting a bit repetitive, and although I liked that it had an Eliot-esque tone, I wanted a bit more variety. 

## Observations

Just as with last week's lab, it was frustrating at first to get the hang of the program and get everything to actually work. Having to use a different web browser initially threw me off, but it resolved the first issues quite quickly so it was worth it moving along. It was also frustrating to write a whole JSON file in text editor and then find that it wouldn't work in Tracery, but once I started working the other way around it began to feel more efficient. I did end up closing the wrong Tracery tab at one point and lost a good chunk of the JSON file that I had written, but it gave me another opportunity to physically write out the data which was ultimately beneficial. Writing the syntax of the JSON file felt clunky and awkward at first, but I'm actually surprised by quickly I got the hang of writing (at least very basic) syntax. Moving forward, I'm curious to play around with more complex functions and see what I can generate that way.

This exercise actually made me excited to play around with the technology more in the future. I'm not sure that I'll start creating Twitter bots necessarily, but it's interesting to input a set of parameters and then see how randomly generated text can both resemble and deconstruct its origin text. For my specific text, I tried to replce the nouns and verbs with other words that already existed in the poem. Since _Prufrock_ is so long and vividly descriptive, I felt that drawing from the existing text would elicit a sort of familiarity wiht the piece overall, while still deviating from what one would expect from this stanza. This made me think about how these randomly generated bots relate to teh concept of authorship. The words were written by T.S. Eliot, the JSON file was written by me, and the actual words displayed were generated randomly by a computer. At this point along the line, who can really be considered the "author" of one of these randomly generated bits of text?


## Analysis

The text that was generated by the bots we created makes me think of how someone in a society like that in Butler's _Speech Sounds_ may handle language. For example, if one lacked the capability to read and write language, that doesn't necessarily bar them from creating the symbols that make up written language. Suppose a non-literate person in this society was given a set of words and tasked with reordering or rearranging them. There's a chance that the strings of text they developed would resemble the text generated by a computer processing a JSON file. They may not know what the words mean, but with enough instruction and reference, they could likely draw the symbols in a way that's readable, even if it doesn't make sense.

The type of writing that the computers produce takes away the intellectual component of writing and reduces it to a systematic equation. This calls to mind a quote in _The Book_ which reflects on "comtemporary anxieties about the ways digitally mediated reading and writing shortens out attention spans and ability to engage deeply with texts" (Borsuk 59). The technology we made use of effectively severs the path between thinker and thought, as Socrates feared. Of course the contexts for these fears are very different, as the "writing" Socrates and Plato were so wary of "proved essential to the development and dissemination of knowledge in a rapidly growing world" (60). I suppose the issue with the random generation lies instead with the fact that the computers can only draw from a limited source of data to complete their "thoughts," and lack the necessary context to create a coherent idea. If someone were to take these "thoughts" seriously, they could spread that erroneous information, and, due to the accessibility of the Internet, that poses a risk of misinformation being disseminated very widely. 

I highly doubt Ælfric would approve of this exercise given what we know about his aversion to translation. In essence, the whole point of this lab was to take an existing body of text, "translate" it into JSON with the addition of parameters for its randomization, and then hand the reins over to the computer, which then controls the forms that the text takes. Though the parameters are controlled and there are only a finite number of forms that the text can take, the initial author (in this case, the person who input the data into the JSON file) hands over control of the text's precise meaning to the computer. When it comes to taking anexisting text and reworking it in this fashion, all of this "translation" happens without the initial author's consent. Ælfric agonizes over the difference between the phrasings "'And the spirit of God moved over the waters”'" and "'and the spirit of God was moved over the waters,'" while we are willfully eschewing the precision of a careful translation in favor of spontaneous, nonsensical random substitution.

Finally, in Annette Vee's writing on coding as literacy, I found the following statement particularly interesting and relevant to this activity: "I see programming as the constellation of abilities to break a complex process down into small procedures and then express—or 'write'—those procedures using the technology of code that may be 'read' by a nonhuman entity such as a computer" (Vee 22). This exercise added layers to that idea, as not only did we write procedures that were "read" by a computer, but then the computer "wrote" back material in response which we then read and interpreted. So we programmed the structure, and then the computer, in a way, programmed back to us. This brings me back to the question of authorship. Would the computer be considered an "author," or would the authorship lie in the programmer's hands?