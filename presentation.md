% Information Retrieval Models
% Christiana Ayscue & Sanjana Krishnan
% 28, November 2016

<aside class="notes">
Hey guys!  My name is Christiana Ayscue.  And my name is Sanjana Krishnan.  And we are going to be telling you about something that we do multiple times a day.
</aside>

# Search
Search for **stuff**.

 <aside class="notes">
Search for stuff.
</aside> 


# What do we Search for?

<center><img src="/test/Data.jpg"  alt="data" border="2"></center>

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

pic of goal post

<aside class="notes">
The goal here is pretty simple: to match information seekers with the information they seek.
It sounds like an easy process, but is it really?
</aside>

#Information Use

diagram of information use

<aside class="notes">
The first thing to think about, is that that people experience information needs when they percieve gaps in their knowledge.
</aside>


# Finding what we want

static gif?

 
<aside class="notes">
As human beings, the way we search for information is not static.   
</aside>

# Berry Picking Model

This represents how we progress during our searches...

berry picking model pic

<aside class="notes">
Instead, we tend to search in the manner that this represented in this image. As we discover new or useful information during our search we 
our query is going to evolve and shift.
</aside>


# Basics

**Basics**

<aside class="notes">
In a nutshell, we've shared with you all the basics of search.  Now we are going to take things to another, slightly more technical level.
</aside>

# Information Retrieval

**IR**

<aside class="notes">
A big piece of the search puzzle involves Information Retrieval.  What is this you may ask?  Well, according to SILS Professor Jaime Arguello, it is the science and practice 
of
</aside>

# Developing/Evaluating

Developing & Evaluating

<aside class="notes">
developing and evaluating systems that match information seekers with the info this seek.  In other words, IR is a means to find the info or data that you want.
</aside>

#IR Models

IR Models

<aside class="notes">
In the world of IR, there are a variety of information retrieval models.  However, we are only going to focus in on three important ones today.
</aside>

#IR Models
Those three are

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
happy face pic

<aside class="notes">
The advantages to this model are that users understand why a document was retrieved, users can control how specific the queries are, and it is easy and fast for the system to process.

</aside>

#Boolean CONs

sad face pic

<aside class="notes">
On the flipside, the cons of this model are that users take full responsibility on query formulations, Boolean queries get very complicated if the information 
needs are precise, and there is no relevance score to refer to.  For the unexperienced searcher, using a Boolean query may not be very helpful.
</aside>

# Vector Space Model
vector space pic


<aside class="notes">
Our next model is the Vector space model.  This model assumes that the degree of matching between a query and retrieved documents can be used to rank-order documents.  
This rank-ordering corresponds to how well a document satisfying a user’s information needs.
</aside>

#Vector Space Explained
Best Match

<aside class="notes">
The vector space model is considered a "best match" model.
</aside>

#Vector Sapce

picture of vector space

<aside class="notes">
This is a bit technical, but given a query, the vector space model scores each document based on the cosine of the angle between the two vectors.
</aside>


#Term Weight
<aside class="notes">
With IR models, term weight plays an important role.  Assuming that some words are more representative than other words,
if a term is more heavily weighted than it is a more important query term overall.
</aside>

#PROs 
happy face pic

<aside class="notes">
Some positive points about the vector space model include that it is a simple model based on linear algebra, it allows ranking documents according to their possible relevance
and it allows partial matching
</aside>

#CONs

sad face pic

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

<aside class="notes">
Similar to the vector space model, the probalistic model is also known as a best match model.
</aside>

#Probablistic Model
pic with bubbles

<aside class="notes">
Our third and final IR model is the Probablistic Model
</aside>


#Probabilistic Model

mathy pic

<aside class="notes">
As explained by Wikipedia, probabilistic models treat the process of document retrieval as a probabilistic inference. 
Similarities are computed as probabilities that a document is relevant for a given query. 
</aside>

#Ever wondered?

> -How
> -Google
> -Works

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

#Video

<aside class="notes">
This brief video will explain the details of how Google operates.
</aside>

#Video
llkjlkj


#Google is kind of 
popular

<aside class="notes">
Google has done very well for themselves.  For many of us, Google is our go-to search engine.  For them to be as successful as they are
the had to have done some things right.
</aside>

#Room for
improvement

<aside class="notes">
But there is always room for improvement, even if you are Google and presume to have most, if not all, of the answers.
</aside>

#Other 
options

<aside class="notes">
More importantly, Google is not the only option for a search engine.  
</aside>

#Cool Ones

pics

<aside class="notes">
There are actually some really cool ones out there such as  Dogpile that pulls in and ‘curates’ results from various different engines including Google, Yandex and Yahoo, 
but removes all the ads, DuckDuckGo which doesn’t retain its users’ data, so it won’t track you or manipulate results based on your behaviour, or Giphy 
that communicates entirely in GIFs
</aside>


#Wrap-up/relevance to my life
<aside class="notes">
how is this relevant to my life?
</aside>


#Source/Resources

Ron
Wikipedia
http://www.inf.ed.ac.uk/teaching/courses/tts/pdf/vector.pdf
https://searchenginewatch.com/2016/02/25/say-goodbye-to-google-14-alternative-search-engines/