---
layout: page
title: PLT 2016
subtitle: AAAI 2016 Fall Symposium on Privacy and Language Technologies
---

## Why Now? 

The time is ripe for a discussion of the relationship between language technologies and privacy. Computing applications are increasing their reliance on natural language, with technologies such as online social media, search engines, and spoken dialog systems enabling the collection of large amounts of language data for advertising, text mining, and other purposes. Simultaneously, there is a timely opportunity for language technologies to help people understand and protect their privacy by simplifying information they must understand (e.g., privacy policies or other legal documents) or helping them to reflect on the content they share (e.g., social media posts).


## Purpose and Topics

The purpose of this workshop is to jump-start the creation of a community of researchers interested in the intersection between language technologies and privacy. Our goal is to bring together researchers who work in either language technologies or in privacy but have an interest in both areas, as these two groups will benefit greatly from a forum to interact.

This workshop will invite original research contributions and position papers on the intersection of privacy and language technologies. Topics of interest include, but are not limited to, the following:

* Analysis of privacy policies and related legal documents

* Semantics of privacy practices and regulations

* Privacy for users of online social media

* Language-sourced ontologies and knowledge bases for privacy

* Privacy in dialogue systems

* Privacy in speech and spoken language processing

* User studies of privacy-supportive language technologies

* Anonymization and identifiability in linguistic resources

* Privacy-preserving methods of text mining

The symposium’s interests include both language technologies for privacy and privacy for language technologies, with the recognition that the two are co-dependent.

## Other Venues on the Topic

To our knowledge, this will be the first event dedicated to the intersection between language technologies and privacy. The most similar event will have been the TA-COS (Text Analytics for Cybersecurity and Online Safety) Workshop at LREC (held in Portorož, Slovenia) in May 2016. However, TA-COS’ accepted papers skewed heavily toward online safety. The proposed symposium will address a wider topic area at a location that will engage more North American participants. 


## Format

We envision a mixture of activities during the symposium to include oral presentations, a poster session, and roundtable discussions. One roundtable discussion will address the next steps for this research community, and others will address topics similar to those listed above. We will also explore the possibility of having 1-2 invited speakers. 


## Organizing Committee

Shomir Wilson (lead organizer) – shomir@cs.cmu.edu

Institute for Software Research; Carnegie Mellon University; 5000 Forbes Ave.;
Pittsburgh, PA 15213
Dr. Shomir Wilson is a Project Scientist at the Institute for Software Research in Carnegie Mellon University’s School of Computer Science. Previously he has been an NSF International Research Fellow at the University of Edinburgh. The focus of his current work is the Usable Privacy Policy Project (www.usableprivacy.org), an NSF-funded effort to use crowdsourcing, machine learning, and natural language processing to make websites’ privacy policies understandable and actionable for Internet users. His recent publications include conference papers in ACL, CSCW, Ubicomp, and WWW.

Fei Liu – feiliu@cs.ucf.edu

Department of Computer Science; University of Central Florida; 4000 Central Florida Blvd.; Orlando, FL 32816
Dr. Fei Liu is an Assistant Professor in the Department of Computer Science at the University of Central Florida. Previously she has been a Postdoctoral Fellow in the School of Computer Science at Carnegie Mellon University and a Senior Research Scientist at Bosch Research in Palo Alto, California. Her research interests are in natural language processing and machine learning, with special emphasis on automatic text summarization and social media. She has published over twenty peer reviewed articles, and she serves as a referee for leading journals and conferences.

Alessandro Oltramari – aoltrama@andrew.cmu.edu

Collaborative Innovation Center; Carnegie Mellon University; 5000 Forbes Ave.;
Pittsburgh, PA 15213
Dr. Alessandro Oltramari is a Research Associate with CyLab at Carnegie Mellon University. He previously held a research position at the Laboratory for Applied Ontology (ISTC-CNR) in Trento from 2000 to 2010, and he was a Visiting Research Associate at Princeton University (Cognitive Science Laboratory) in 2005 and 2006. His current research deals with integrating ontologies and cognitive architectures for high-level reasoning in knowledge-intensive tasks. He has published more than sixty articles in refereed conferences, books, symposia, workshops, and journals. From 2004 to 2010, he co- organized the annual workshop on Ontologies and Lexical Resources. In 2014 and 2015 he was appointed General Co-Chair of the International Conference on Semantic Technologies for Intelligence, Defense and Security. In 2014 he was appointed Area Co-Chair of COLING 2014 (Lexical Semantics and Ontologies). 


<!--
You can write regular [markdown](http://markdowntutorial.com/) here and Jekyll will automatically convert it to a nice webpage.  I strongly encourage you to [take 5 minutes to learn how to write in markdown](http://markdowntutorial.com/) - it'll teach you how to transform regular text into bold/italics/headings/tables/etc.

**Here is some bold text**

## Here is a secondary heading

Here's a useless table:
 
| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |
 

How about a yummy crepe?

![Crepe](http://lafenicegelato.com/wp-content/uploads/2014/09/crepes-with-chocolate.jpg)

Here's a code chunk:

~~~
x <- 5 + 10
print(x)
~~~

And here is some code with syntax highlighting

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```
-->

<!--
<div class="posts-list">
  {% for post in paginator.posts %}
  <article class="post-preview">
    <a href="{{ post.url | prepend: site.baseurl }}">
	  <h2 class="post-title">{{ post.title }}</h2>
	
	  {% if post.subtitle %}
	  <h3 class="post-subtitle">
	    {{ post.subtitle }}
	  </h3>
	  {% endif %}  
    </a>

    <p class="post-meta">
      Posted on {{ post.date | date: "%B %-d, %Y" }}
    </p>
  
    <div class="post-entry">
      {{ post.content | truncatewords: 50 | strip_html | xml_escape}}
	  <a href="{{ post.url | prepend: site.baseurl }}" class="post-read-more">[Read&nbsp;More]</a>
    </div>
  
   </article>
  {% endfor %}
</div>
-->

<!--
{% if paginator.total_pages > 1 %}
<ul class="pager main-pager">
  {% if paginator.previous_page %}
  <li class="previous">
    <a href="{{ paginator.previous_page_path | prepend: site.baseurl | replace: '//', '/' }}">&larr; Newer Posts</a>
  </li>
  {% endif %}
  {% if paginator.next_page %}
  <li class="next">
    <a href="{{ paginator.next_page_path | prepend: site.baseurl | replace: '//', '/' }}">Older Posts &rarr;</a>
  </li>
  {% endif %}
</ul>
{% endif %}
-->
