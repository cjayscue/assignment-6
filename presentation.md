% Information Retrieval Models
% Christiana Ayscue & Sanjana Krishnan
% 28, November 2016

#Hey There!

<img src="https://upload.wikimedia.org/wikipedia/commons/b/ba/Round_hay_bale_at_dawn02.jpg">

<aside class="notes">
Hey guys!  My name is Christiana Ayscue.  And my name is Sanjana Krishnan.  And we are going to be telling you about something that we do multiple times a day.
</aside>

# Search
<img src="https://ladywithatruck.files.wordpress.com/2015/05/stuff.jpg">
<aside class="notes">
Search for stuff.
</aside> 


# What do we Search for?

Some Examples

> - Music
> - Text
> - Images
> - Audio

 
 <aside class="notes">
Some common examples of data that we search for all the time are music, text, images, and audio.
</aside> 

# What applications do we use to find what we are looking for?

> - Web Search
> - Desktop Search
> - Peer-to-peer search

<aside class="notes">
What applications do we use to find what we are looking for?  We can use web search engines such as Google, desktop search on our laptops, 
or peer-to-peer search, which simply means to ask another human being a question.
</aside> 


#Goal

<img src="http://img.aws.livestrongcdn.com/ls-article-image-400/cme/cme_public_images/www_livestrong_com/photos.demandstudios.com/getty/article/117/203/78457028_XS.jpg">

<aside class="notes">
The goal here is pretty simple: to match information seekers with the information they seek.
It sounds like an easy process, but is it really?
</aside>

#Information Use

<img src="http://infoseeking.org/img/intent2.jpg">

<aside class="notes">
The first thing to think about, is that that people experience information needs when they percieve gaps in their knowledge.
</aside>


# Finding what we want


<img src ="https://media.giphy.com/media/xaMg6NGwH2fFS/giphy.gif">
 
<aside class="notes">
As human beings, the way we search for information is not static.   
</aside>

# Berry Picking Model

This represents how we progress during our searches...

<img src="http://searchuserinterfaces.com/book/images/berrypicking.png">

<aside class="notes">
Instead, we tend to search in the manner that this represented in this image. As we discover new or useful information during our search we 
our query is going to evolve and shift.
</aside>


# Basics

<aside class="notes">
In a nutshell, we've shared with you all the basics of search.  Now we are going to take things to another, slightly more technical level.
</aside>

# Information Retrieval

<aside class="notes">
A big piece of the search puzzle involves Information Retrieval.  What is this you may ask?  Well, according to SILS Professor Jaime Arguello, it is the science and practice 
of
</aside>

# D&E
Developing & Evalutating

<aside class="notes">
developing and evaluating systems that match information seekers with the info this seek.  In other words, IR is a means to find the info or data that you want.
</aside>

#IR Models


<aside class="notes">
In the world of IR, there are a variety of information retrieval models.  However, we are only going to focus in on three important ones today.
</aside>

#IR Models
Those 3 are

> - Boolean Model
> - Vector Space Model
> - Probalistic Model


<aside class="notes">
Those three are the Boolean Model, the Vector Space Model, and the Probalistic Model.
</aside>


#Boolean
Exact Match

<aside class="notes">
First, let's check out the Boolean Model. The Boolean model returns what is called an exact match. 
Retrieval is therefore based on whether or not the documents contain the query terms.
</aside>

#Logical Operators

> - AND
> - OR
> - NOT

<aside class="notes">
The logical operators AND, OR, and NOT are used when creating queries (aka searches) and information returned is either relevant or non-relevant.
</aside>

#Boolean PROs 
<img src="http://pix.iemoji.com/images/emoji/apple/ios-9/256/smiling-face-with-smiling-eyes.png">

<aside class="notes">
The advantages to this model are that users understand why a document was retrieved, users can control how specific the queries are, and it is easy and fast for the system to process.

</aside>

#Boolean CONs

<img src="http://www.clipartkid.com/images/124/crying-emoji-face-KS8xJS-clipart.png">

<aside class="notes">
On the flipside, the cons of this model are that users take full responsibility on query formulations, Boolean queries get very complicated if the information 
needs are precise, and there is no relevance score to refer to.  For the unexperienced searcher, using a Boolean query may not be very helpful.
</aside>

# Vector Space Model

<img src="http://blog.christianperone.com/wp-content/uploads/2013/09/vector_space.png">


<aside class="notes">
Our next model is the Vector space model.  This model assumes that the degree of matching between a query and retrieved documents can be used to rank-order documents.  
This rank-ordering corresponds to how well a document satisfying a user’s information needs.
</aside>

#Vector Space Explained
<img src="http://www.visitbawbaw.com.au/uploads/best-match-recruitment-2.jpg?d=201408140836">

<aside class="notes">
The vector space model is considered a "best match" model.
</aside>

#Vector Space


<img src="http://fox.cs.vt.edu/talks/1995/KY95/RR-vs-cos.GIF">
<aside class="notes">
This is a bit technical, but given a query, the vector space model scores each document based on the cosine of the angle between the two vectors.
</aside>


#Term Weight
<aside class="notes">
With IR models, term weight plays an important role.  Assuming that some words are more representative than other words,
if a term is more heavily weighted than it is a more important query term overall.
</aside>

#PROs 

<img src="http://pix.iemoji.com/images/emoji/apple/ios-9/256/smiling-face-with-smiling-eyes.png">

<aside class="notes">
Some positive points about the vector space model include that it is a simple model based on linear algebra, it allows ranking documents according to their possible relevance
and it allows partial matching
</aside>

#CONs

<img src="http://www.clipartkid.com/images/124/crying-emoji-face-KS8xJS-clipart.png">

<aside class="notes">
A couple of downsides of this IR model are that search keywords must precisely match document terms, and the
order in which the terms appear in the document is lost in the vector space representation.
</aside>

#Final Model
Probalistic Model

<aside class="notes">
Our third and final IR model is the Probablistic Model
</aside>

#Best Match
<img src="https://upload.wikimedia.org/wikipedia/commons/f/fb/Pagerank_copia.jpg">

<aside class="notes">
Similar to the vector space model, the probalistic model is also known as a best match model.
</aside>

#Probabilistic Model

<img src="https://pi.tedcdn.com/r/pf.tedcdn.com/images/playlists/hated_math_1200x627.jpg">

<aside class="notes">
As explained by Wikipedia, probabilistic models treat the process of document retrieval as a probabilistic inference. 
Similarities are computed as probabilities that a document is relevant for a given query. 
</aside>

#Ever wondered?

> - How
> - Google
> - Works

<aside class="notes">
have you ever wondered how google actually works?
</aside>


#Page Rank Algorithm

<aside class="notes">
Google uses this probabilistic model and came up with their own PageRank algorithm.
</aside>

#Quote from Bruce Clay, Inc
PageRank (PR) is a calculation, famously invented by Google founders Larry Page and Sergey Brin, 
which evaluates the quality and quantity of links to a webpage to determine a relative score of that page’s importance and authority on a 0 to 10 scale.

<aside class="notes">
A writer for Bruce Clay, Inc, Chelsea Adams stated that "PageRank (PR) is a calculation, famously invented by Google founders Larry Page and Sergey Brin, 
which evaluates the quality and quantity of links to a webpage to determine a relative score of that page’s importance and authority on a 0 to 10 scale.""
</aside>

#Yay for YouTube

<aside class="notes">
This brief video will explain the details of how Google operates.
</aside>

#Video



#Google is kind of 
**popular**

<aside class="notes">
Google has done very well for themselves.  For many of us, Google is our go-to search engine.  For them to be as successful as they are
the had to have done some things right.
</aside>

#Room for
**improvement**

<aside class="notes">
But there is always room for improvement, even if you are Google and presume to have most, if not all, of the answers.
</aside>

#Other 
options

<aside class="notes">
More importantly, Google is not the only option for a search engine.  
</aside>

#Cool Ones

<img src="http://www.disneyclips.com/imagesnewb/images/clipdonstamp.gif">

<aside class="notes">
There are actually some really cool ones out there such as  Dogpile that pulls in and ‘curates’ results from various different engines including Google, Yandex and Yahoo, 
but removes all the ads, DuckDuckGo which doesn’t retain its users’ data, so it won’t track you or manipulate results based on your behaviour, or Giphy 
that communicates entirely in GIFs
</aside>


#Wrap-up
<aside class="notes">
So how is this information useful in our lives?  Well, there is a great deal of uncertainty at all steps of the information retrieval process.
This uncertainty affects the queries because the the user may not always know how to aptly describe what they are looking for.  It also affects what is
retrieved because the retrieval system is not able to think like a human being and only responds as a machine.
</aside>

#The more informed the better...

<aside class="notes">
The more understanding we have about the information retrieval process and the IR models themselves, the better searchers we can become.
For anyone that is pursuing a career in information science or information retrieval, this understanding can lead to better design and therefore 
more relevant and accurate results.
</aside>


#Source/Resources
<aside class="notes">
For anyone that is interested in learning a little bit more, check out these links:
</aside>

* <a href= "https://ils.unc.edu/courses/2016_fall/inls201_001/">Foundations of Information Science</a>
* <a href= "https://en.wikipedia.org/wiki/Information_retrieval">Information Retrieval</a>
* <a href="http://www.inf.ed.ac.uk/teaching/courses/tts/pdf/vector.pdf" >More on Vectors</a>
* <a href="https://searchenginewatch.com/2016/02/25/say-goodbye-to-google-14-alternative-search-engines/">Say Goodbye to Google</a>


#Thank you

<img src="https://m.popkey.co/04a13b/AVrJJ.gif">
<aside class="notes">
Thank you for listening, guys!
</aside>
