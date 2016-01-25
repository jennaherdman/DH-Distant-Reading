
#What is text analysis?

As a student of both English literature and Digital Humanities, one of my core goals has been to develop knowledge of different tools which help these two academic concentrations complement and enhance one another. Luckily, several tools already exist which offer us the means for a distant-reading approach to texts, allowing us to look at the patterns and differences of several texts at the same time. Some scholars are developing databases which allow you to look at over a million books. 

In this blog, I will introduce you to some useful tools for beginning text analysis, which will serve to break down the practical, housekeeping purposes. I will also delve into the methods of drawing relevant meaning from these tools, and apply them directly to my own research to demonstrate how the tools can diversify and richen classic literary criticism. This last step, the application of the tools to analysis, is very meaningful and something which I have found some tools lack - if we have the data, what are the possibilities of what we can do with it? Can distant-reading text analysis articulate something that traditional means of scholarship does not? 

Not only is this a cool way of approaching literary studies, but it is also a user-friendly way for non-academics to approach literature in dynamic and accessible ways. This approach, in my opinion, is a potential, inclusive future for literature studies, and text analysis and visualization is a way to get there. 

If you would like to read my blog applying these methods to my MRP research on vampire literature, please click here: -linky- 

Further reading:
* [The instability of gender](http://tedunderwood.com/2016/01/09/the-instability-of-gender/)
* [A dataset for distant-reading literature in English, 1700-1922](http://tedunderwood.com/2015/08/07/a-dataset-for-distant-reading-literature-in-english-1700-1922/)
* [A quantitative literary history of 2,958 Nineteenth-Century British Novels](http://litlab.stanford.edu/LiteraryLabPamphlet4.pdf)
* [How not to read a million books](http://people.brandeis.edu/~unsworth/hownot2read.html)

#Tool Tutorial

*David Copperfield* by Charles Dickens is one of my favourite books, and one of Charles Dickens’s masterpieces. For the tool tutorial section of this blog, I am going to suggest that you follow along using the easy, step-by-step instructions I lay out. If you’d like to use a different text, of course, be my guest. 

Here are a few facts about Dickens which makes his texts so ripe for analysis: 
* 1. They’re damn long. A former professor of mine put it perfectly: Dickens write “in excess.” 
* 2. They’re wordy. 
* 3. They’re repetitive - because Dickens wrote in serial instalments, he had to keep reminding his readers of the nearly a THOUSAND characters peppered through his fifteen novels. So if you’re annoyed at how each minor character is pretty flat except for the tick which characterizes them, it’s done partly to help the reader keep track of all the minor characters who reappear throughout the text (re: the Micawbers). 

All of these traits make Dickens ripe for text analysis. 

![David cover](https://github.com/jennaherdman/DH-Distant-Reading/blob/master/screenshots/9780141343822.jpg?raw=true)

##Step 1: Preparing the Text

You can download a (free!) copy of [David Copperfield](http://www.gutenberg.org/ebooks/766-) from Project Gutenberg  They also have oodles of other texts for your legal and easy download. What I’ve done is click on the file that says “Plain Text UFT-8”, then selected “all” and copy-pasted the entire book into a blank TextEdit file. This takes about five seconds. Let’s name it “David Copperfield - Text Analysis” and save it in a safe place. 

Now, it’s time to cleanse our document so that all that remains are the actual words we want to analyze - none of this administrative business. Check out this screenshot of my “David” file: 

![screenshot 1](https://github.com/jennaherdman/DH-Distant-Reading/blob/master/screenshots/text%20analysis%20tutorial%20screenshot%201.png?raw=true)

So, all of this has to go. Especially if your text comes from gutenberg, be sure to cleanse it of the disclaimers and info at the beginning and end of the book that the site has added. If you’re using “David,” then the first words should be some classic authorial manifesto about being the hero of his own life, and the last words in the document should involve point upward. 

Depending on how vigilant you are, feel free to go through and delete the chapter headings and such, though arguably they are part of the text. I’m not really decided yet how I feel about the chapter headings myself. Must consider. 

Okay. We now have a nice, clean Dickens novel waiting to be analyzed. Beautiful. 

##Step 2: Welcome to WordCounter

Firstly, I’d like to give credit to Matthew S Carroll and his blog “DataBasic: A suite of data tools for the beginner” for introducing me to the first two tools I’m going to show you. If you’re interested, check out [this post](https://medium.com/3-to-read/databasic-a-suite-of-data-tools-for-the-beginner-5165651e46a5#.drg8uolnq-) and the website, “Medium.”  Mr. Carroll approaches these tools with the purposes of the journalist in mind and comes up with some really interesting potential for analysis. 

Our first two tools, WordCounter and SameDiff, are produced by some excellent folks at DataBasic who have designed some easy and accessible tools for beginners, especially in the classroom, to get comfortable with data analysis. The tools offer some basic options for text analysis. Importantly, in my opinion, they also open our eyes to what sorts of things you can look for when we move on to more complicated tools, opening up the potential for finding meaning in these exercises. 

So, let’s copy-paste our “David” into [Word Counter](http://beta.databasic.io/en/wordcounter/-).

![screenshot 2](https://github.com/jennaherdman/DH-Distant-Reading/blob/master/screenshots/text%20analysis%20screenshot%202.png?raw=true)
*Keep doing you, Agnes. RIP Dora.*

You’ll notice the box “ignore stopwords” and be sure to keep it checked. This will keep those pesky “ands” and “buts” out of your analysis. 

WordCounter can show us some interesting things. For example, in the novel, “Agnes” used 316 times while “Dora” was used 510 times. The two romantic rivals for David’s heart. This is interesting since Agnes appears so much earlier in the novel and (spoiler) ends up marrying David while Dora dies quite soon after their marriage. Sharon Marcus has written about the connections between the two women and the negotiations of their relationship through David. I would be interested to read about how many times the women mention each other in dialogue as opposed to how David does. 

**Note:** WordCounter is very similar to another tool I will introduce to you, Voyant. Also, on my machine especially, WordCounter has been unreliable, perhaps because the program has recently been released to the public and is (as it should be!) receiving a lot of traffic. I will do a brief explanation to Voyant in Step 4. 

##Step 3: Welcome to SameDiff!

SameDiff is the second tool from DataBasic that I’m going to introduce to you. It compares two different texts and outlines in a user-friendly way the words that are used in both texts vs. the words that only appear in one text. 

Of course, for this tool we’ll need a second text. How about *Jane Eyre* by Charlotte Bronte, another favourite of mine. Though the two novels contain notable similarities - bilgunsromans, orphans, first-person narration, etc., they are different enough in literary thought and in character and content that we might be able to pull out some neat information. Let us download [*Jane Eyre*](http://www.gutenberg.org/ebooks/1260-) from gutenberg like we did with “David” and clean up the text quickly - be sure to slice out the prefaces as well. They’re interesting, but not relevant for this specific purpose. 

Get to [SameDiff](http://beta.databasic.io/en/samediff/#upload-) and upload your two files for comparison. What you’ll get are three columns of words in varying sizes. 

![screenshot 3](https://github.com/jennaherdman/DH-Distant-Reading/blob/master/screenshots/text%20analysis%20screenshot%204.png?raw=true)
*If only Jane had a Peggotty like David did.*

If you hover over a specific word in the central column, you can see how many times a word was used in each novel. For example, “dear” was used 414 times in “David” and 183 times in “Jane.” In general, though, SameDiff doesn’t tell us much about these particular novels. The word frequencies are dominated by names and places. However, what this tool has done is given us a useful introduction to the possibilities of text analysis. 

Interestingly, it also offers a quick segway into the idea of a corpus creating a text. Instead of close-reading “David” in chronological order, with each word coming in front of the other, these tools present a new form of text which we analyze separately from the novel in its original form. For those of us interested in the developing nature of texts and archives this is an important point. 

###WordCounter and SameDiff 

####Advantages
* great for beginners 
* visually appealing 
* exciting new tools 

####Disadvantages 
* very basic and simple 
* unreliable functionality 
* can only really look at one or two texts at once

##Step 4: Welcome to Voyant

Voyant is a useful tool for visualizing and sorting through words. It’s base functions are similar to WordCounter, though less visually appealing, but it has many more options for text manipulation. First of all, let’s go to the [Voyant website](http://voyant-tools.org). 

Upload your David document into Voyant by choosing *Upload* then *Add* and select the relevant document. If you have multiple documents in your corpus, just keep selecting *Add* until they are all there. Then, select *Reveal.*

![screenshot 12](https://github.com/jennaherdman/DH-Distant-Reading/blob/master/screenshots/text%20analysis%20screenshot%2012.png?raw=true)

Now, you’ll notice that the word cloud under the word “Cirrus” is not particularly helpful. This is because we need to edit out the stop words. Stop words are words like “and”, “the”, “to” and so forth. To generate the analysis and exclude the stop words, click on the little box to the top left of the word cloud, labeled “options: Cirrus.” A box will pop up. Under “Stop Words List” select “English (Taporware) and check the box that says “Apply Stop Words Globally.” Then press OK. 

![screenshot 14](https://github.com/jennaherdman/DH-Distant-Reading/blob/master/screenshots/text%20analysis%20screenshot%2014.png?raw=true)

The new word cloud is far more interesting for purposes of basic analysis. “Mr”, “little”, “aunt”, and “peggotty” are some of the most commonly used words. You will also notice “eyes”, “face”, “head” and “mind” are frequently used. This tool can help raise questions about the frequency of these words and what significance they have without having to look at the individual context of each word - though this is possible with Voyant under the Corpus Reader heading. 

If you click on a specific word in the Cirrus area, another window will open called Word Trends. These allow you to see the relative frequencies across the text or the corpus. Choosing a specific point on the graph lets you see the keyword in context. 

![screenshot 13](https://github.com/jennaherdman/DH-Distant-Reading/blob/master/screenshots/text%20analysis%20screenshot%2013.png?raw=true)

In this example, I’ve chosen the word “Traddles.” One of the neat things about the novel is how characters re-appear variously throughout the bildungsroman. Traddles is a particularly interesting character for where he comes back. Putting a bunch of these graphs together, we could map the influences and core figures throughout David’s life. This tool thus maps plot as well as language. 

Once you’ve mastered the basic functions of Voyant, you can expand on your visualizations to warp the data using [different tools](http://docs.voyant-tools.org/tools/). 

 To access these tools, click the little disk symbol in the top right corner of the page. If you hover over it, it will say: “Click here to generate a URL to access this corpus again.” After you click it, a box will appear with some different options. Select the option that says: “a URL for a different tool/skin and current data.” A second box will appear allowing you to choose the Tool which you would like to use. Copy the URL and post it into a new window. I will demonstrate some of the tools that I found the most pertinent for this kind of research.

**Knots:** A series of twisted lines which shows you an active visualization of certain terms and their intersections throughout the text. Knots isn’t as specific as it is just neat to watch. [Read more about Knots here](http://docs.voyant-tools.org/tools/knots/). 

As you will notice, the tool will have chosen a few terms to focus on for your Knots visualization. You can tailor the words you want (perhaps drawing on the Cirrus word cloud from the original Voyant page). Click on the existing coloured terms at the top to delete them from the visualization or press “Clear Terms” in the tool bar. Add a term by searching it in the dropdown menu. A set of options will come up - click on the proper one, and then press “enter” on your keyboard. These instructions seem very specific, but this is because the program can be fickle. 

![screenshot 16](https://github.com/jennaherdman/DH-Distant-Reading/blob/master/screenshots/text%20analysis%20screenshot%2016.png?raw=true)

As you can see, I’ve chosen a selection of minor characters to compare. The Knots demonstrate the interactions of these characters throughout the novel, clustering them together. Some observations can be drawn from these squiggles: 

* Dora (dark blue) is very separate from the mother (pink). This makes sense as the mother dies young, however, Dora and the mother are consistently compared in literary analysis due to their status as “child-wives.”
* Peggotty (purple), little Em’ly (light green) and Steerforth (light blue) are the most central characters according to this visualization 

Of course, this tool is dependent on the words which you choose to enter. However, from what we have here, there are many interesting observations which can be drawn. When done properly, this visualization can represent the plot of the novel through the interactions of the characters based on language. 

**Bubblelines**

Bubble lines is similar to Knots in term of usability. However, it arranges the information in a more linear fashion. Export the relevant URL as you would have with Knots. 

As with Knots, de-select and select the relevant terms. I’ve chosen three of the young male figures who come in and out of David’s life. I would recommend checking the box “Separate Lines for Terms,” which will place each word on its own line and make it a bit easier to distinguish between them. 

![screenshot 17](https://github.com/jennaherdman/DH-Distant-Reading/blob/master/screenshots/text%20analysis%20screenshot%2017.png?raw=true)

So here, we have yet another visualization which tells us something about the plot of the novel. There are infinite possibilities for possible terms to compare here - another possibility might be the use of a certain set of words or locations. 

For more information about Voyant and the options for analysis, [select here](http://docs.voyant-tools.org/start/). 

###Voyant

####Advantages
* relatively simple to use, at least with the basic tools
* allows visualizations
* does not need to be downloaded or hosted
* can analyze multiple texts in a corpus

####Disadvantages 
* will sometimes freeze your computer 
* interface is a bit confusing at first


##Step 5: Welcome to Antconc

Antconc is a separate application which you have to download onto your machine - a deceptively simple phrase. 

I would also like to acknowledge this tutorial by Heather Froehlich, “Corpus Analysis with Antconc” published on “The Programming Historian.” It’s a super useful and detailed tool tutorial which has helped me understand the tool and offers discussions of what can be done using Antconc. My tutorial here is a simplified application of the uses Froehlich discusses, but I would recommend checking hers out as well. [Check it out here](http://programminghistorian.org/lessons/corpus-analysis-with-antconc). 

Download [Antconc](http://www.laurenceanthony.net/software/antconc/) in accordance with your machine’s version. Be sure to give the appropriate permissions for your computer to access it. 

When the window opens, you have some different options for tools to analyze your texts. They are: 

* **Concordance:** A keyword in context search function. This will find patterns in the language. This is a good way to start looking for patterns in the language structures. 
* **Concordance Plot:** Simple visualization of the above. 
* **File View:** Full-file view of the results. 
* **Clusters/N-Grams:** Picks out word patterns according to frequency. 
* *Collocates:** Words which are likely to appear in patterns, as opposed to definitely appear in patterns. 
* **Word List:** All the words. 
* **Keyword List:** Comparisons. 

 Firstly, get your texts into Antconc using File - Open. I’ll put in the David text we’ve been working with to start. 

###Antconc Lesson 1: Concordances

Reminder: concordances help us look for patterns in the language using a keyword search. Select the “David” text on the left under “Corpus Files,” and put in a search term. I’m going to try the word “love” and see what we come up with. 

![screenshot 5](https://github.com/jennaherdman/DH-Distant-Reading/blob/master/screenshots/text%20analysis%20screenshot%205.png?raw=true)

As you will see, we have 264 hits of the word “love.” Now, if I were writing a paper on the use of the word “love” in this novel I would do some research into the idea of love as a construct or term in Victorian literature. I could study the use of love as a verb vs. love as a noun. I could even, if I chose, use Antconc to analyze all of Dickens’s books and see how the use of the word “love” varies or is similar between the collection of them. Do certain texts use love in different contexts than others? 

Now, with the Concordance tool, we can also change the way we view this data. Look at the heading “Kwic Sort.” This tool lets you expand the specific view of the words which you are viewing to the left or to the right. You can click on a specific word and navigate to “File View” to see the explicit context of the word. 

![screenshot 6](https://github.com/jennaherdman/DH-Distant-Reading/blob/master/screenshots/text%20analysis%20screenshot%206.png?raw=true)

Phrases: We can also search for a phrase or a set of key words by typing the phrase into the search bar. Say, for example, “love and truth,” which only appears six times, but each time in reference to Agnes. 

Concordance Plots: If you click the tab next to “Concordances,” it will visualize in a simple fashion the frequencies under which your keyword appears most often. Let’s try this with the word “Uriah.” Uriah Heep, the cadaverous ginger who haunts Mr. Wickfield through his character tick of humble, discreetly patronizing servitude. When running “Uriah” through Concordance Plot, we see a resurgence of his reappearances in the novel. It’s fun to play with this tool by running different characters names through and comparing them. 

![screenshot 7](https://github.com/jennaherdman/DH-Distant-Reading/blob/master/screenshots/text%20analysis%20screenshot%207.png?raw=true)

![screenshot 8](https://github.com/jennaherdman/DH-Distant-Reading/blob/master/screenshots/text%20analysis%20image%208%20.png?raw=true)

![screenshot 9](https://github.com/jennaherdman/DH-Distant-Reading/blob/master/screenshots/text%20analysis%20screenshot%209.png?raw=true)

Here, we have a simple, yet fascinating visualization of the periods in David’s life when each character reappears and is most important. Another interesting visualization I ran is “Emily” vs. “Little Em’ly” who are the same person by different names. 

###Antconc Lesson 2: Collocates

Collocates are lists of words which accompany your keyword. They are statistically more probable to be connected together (such as “maiden” and “voyage”). 

So, click on the Collocates tab. Choose a word to search - I’m going to try with “Uriah” again, just because I detest/pity him. A tutorial for Antconc for Newcastle University suggests removing tags from the text. Do this by clicking Global Settlings -> Tag Settings and check Hide Tags -> Apply. 

Like with the Concordances, you specify the number of words on either side that you would like to be considered using the Window Span. I’ll choose 3L and 3R. 

Now, the Collocates tool will rank the words in order of their relevance as a collocate to the keyword. These may have a low frequency, but this is dependent on not only what appears next to the keyword, but also what doesn’t appear next to other words in the text. You can also sort them by frequency. 

![screenshot 10](https://github.com/jennaherdman/DH-Distant-Reading/blob/master/screenshots/text%20analysis%20screenshot%2010.png?raw=true)

This tutorial has gone into detail on the possible uses and analyses of these tools, as well as explaining them. Of course, there are still many other things Antconc can be used for. However, I hope this can serve as a useful beginner’s tool that will pique the interest and inspire confidence in the reader’s conception of their ability to do text analysis. 

###Antconc

####Advantages
* offers tools for looking at patterns of words
* concordances and collocates are especially useful

####Disadvantages 
* not the best interface
* takes a while to learn
* visualizations are very basic


#Conclusions

In this tutorial, we have explored: 

* how to prepare a text for analysis 
* how to use WordCounter and SameDiff
* how to use some basic functions of Voyant
* how to use some basic functions of Antconc 
* the potentials for text analysis using these tools 

This blog has outlined some of the basics of text analysis. Now, even with more advanced tools, tools like Antconc are not in themselves enough. We still need to use our knowledge of the corpus and assumptions and hypotheses about the texts and the use of language within them in order to draw true analysis from this information. The tools themselves only let us get to that point in a newer and simpler way.  

In terms of disadvantages, the tools are not always easy to learn or to find value in. As I explained, the analysis depends on extenuating knowledge and perhaps just creates research questions, not answers. However, it is undeniable that distant-reading is a new way of approaching literature, which in itself is worth studying and improving on. 

Which tool would I recommend? Both Voyant and Antconc have positives and negatives. They’re not the simplest to use, and often it can be hard to draw obvious meaning from the visualizations or concordances. From my own research, I would advise familiarizing yourself with both.

Visualizations are, in my opinion, more important than simple tools for analysis. They make research accessible to wider audiences who don’t always want to sift through large quantities of text. It is the job of the researcher to present these visualizations in ways which not only complement their analysis, but make the analysis easily readable and enjoyable for the non-academic or inexperienced reader. 

##Examples for future analysis
* Compare Dickens to other authors of his day. How do his diction and word patterns differ from Austen? Or the Bronte sisters?
* Does Dickens’s style change over the course of his long writing career? 
* How has literature’s portrayal of a certain construct or theme evolved in terms of the language and structure over time? For example, have the collocates associated with red-haired characters improved since the days of Uriah Heep?

**Reminder:** To see these tools applied to my own research into vampire texts of the nineteenth century, [please follow this link](LINK). Thank you! 





