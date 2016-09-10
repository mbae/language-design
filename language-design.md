_Fill in each this file with your responses, placing each response after its
corresponding question._

---

**Question**

Pick three quotes from the readings about language design. Good candidates 
are:

   + Something you agreed with / resonates with your own experience
   + Something you disagree with
   + Something that is interesting, a new idea or perspective you'd like to remember
   + Something you didn't understand

For each quote, describe what it was about the quote that led you pick it.

**Response**

> If one person does all the work, then growth will be slow. But if one lets the
> users help do the work, growth can be quick. If many persons work side by side,
> and the best work is added with care and good taste, a great deal can be added
> in a short time.
[[Steele, 1998]](https://www.cs.virginia.edu/~evans/cs655/readings/steele.pdf)

We picked this quote because it seemed important to computer science software
development. We agree that this is a very important way to develop big projects,
but Matthew points out that if many people are all working on the same thing
it can also get chaotic. Therefore it is important to have a structure like 
Steele talks about Java development having where it is a mix of one person and
many people working together.

> These preconceived biases arise because programming languages are
> as much social constructs as they are technical ones. A
> programming language, like a spoken language, is defined
> not just by syntax and semantics, but also by the people who
> use it and what they have written. Research shows that the
> community and libraries, rather than the technical features,
> are most important in determining the languages people choose.
> Scientists, for instance, use Python for the good libraries for
> scientific computing.
[[Yang and Rabkin, 2015]](https://modelviewculture.com/pieces/c-is-manly-python-is-for-n00bs-how-false-stereotypes-turn-into-technical-truths)

We picked this quote because it is important to consider the social constructs
around programming languages. The author of this quote makes the argument that
the languages people learn are based on their environments and situations rather
than technical features. Daniel makes a point that libraries adds technical
features, and we both think it is a bit contradictory. Matthew points out that
the community can also contribute to technical features of languages. Overall,
we agree with the idea that there are other factors besides technical features
that influence which programming languages we learn and use.

> They created a "placebo languages" called Randomo, whose syntax was randomly
> generated, to use in trials alongside Quorum and Perl.
[[Pavlus, 2012]](https://www.fastcodesign.com/1665735/why-arent-computer-programming-languages-designed-better)
We really did not understand what it meant ot have syntax that was randomly
generated.  Does this mean that commands are random collections of letters of
length zero to infinity and where you place braces, semicolons, and other such
syntax also a randomly determined? For instance in many languages you need curly
braces for multi line if statements but not 1 line if statements.  In randomo
was it randomly determined after how many lines in an if statement you would need
to use curly braces?  Without a definition for random we both find the paper very
unconvincing. Some 
google searching revealed a definition of Randomo says it is:
> A programming language based largely on the syntactical structure of Quorum. 
> With the exception of braces, the lexical rule for variable names, and a few 
> operators (e.g., addition, subtraction, multiplication, division), many of the
> keywords and symbols were chosen randomly from the ASCII table. 
[[Stefik, 20000]](https://ecs.victoria.ac.nz/foswiki/pub/Events/PLATEAU/Program/plateau2011-stefik.pdf)
However if based on this definition Randomo is based off of Quorum, which the
study did show that people liked better than perl.  So it is quite misleading
to say that people liked a randomly generated langauge better than perl when in
reality it is based off a not random language that people liked better.

---

**Question**

How would you know a well-designed language? What are the symptoms? How would
you know a poorly designed language? What are the symptoms?

**Response**

One noticeable characteristic of a well-designed langauge is that it makes space
for growth. User are able to grow the language themselves, following the bazaar
metaphor in the reading from Steele. Another similar idea is that users are
able to build things in the language that looks like things that are built into
the language to give them a sense ownership. If the language is inflexible, it
makes it hard for the user to make things. Furthermore, if it's built large and
without collaboration, it is likely designed in a way that is not what the users
would like.


---

**Question**

How do the themes of _Growing a Language_ relate to the "sound lab" we did this week?

**Response**

The big theme from _Growing a Language_ is to let languages be growable
and let users be able to contribute. In one sense, the theme is apparent in the
sound lab because we are using Python, a very growable language. But at the same
time, the API that was given to us was inflexible because the design
decisions already made. As a result, the API itself was not as growable or
accessible to the users. For example, the reverse function did not just reverse
a sound and save it, it also played the sound and the reversed sound which was
not necessarily what we wanted to do.

---
 
**Question**


In what way is an API a language? 

**Response**

An API has many language characteristics talked about in the articles.  It is
growable in the way Steele states that langauges should be and often one can use
an API to build more APIs.  Moreover, often communities develop APIs together
and certain communities like certain APIs and not others in the same way certain
communities like particular languages but not others in the way talked about in
Yang and Rabkin's article.


---

**Question**

What does the post on grayscale tell us about the process of API design?

**Response**

The post on grayscale tells us that the community contributes to the process
of API design. In the post, users were able to vote on which naming to use
for grayscale. It also shows that people in the community have varied (and
sometimes strong) opinions on things as simple as naming a function for 
grayscale. We also were rather surprised that the rgb function won by so many
votes since we both thought that black was by far the clearest naming choice.
This reveals that different communities have different shared ideas that make
some choices clearer to members of the community but not to outsiders.  We
suspect that in the community using the rgb function is pretty common so to them
it would seem natural to use this for a function that does not really change red
green or blue colors but rather shades of black and white.

---

**Question**

The Yang and Rabkin article talks mainly about general-purpose languages. In 
what ways do the themes apply to the study and creation of DSLs?

**Response**
One thing we believe is that DSLs are just as susceptible as general-purpose
programming languages to the biases and stereotypes people impose. DSLs, by
design, are not as big and popular as other languages such as Java and Python.
Because of this, they might be perceived as inferior due to biases from the
larger languages' communites. In addition, communities for DSLs are generally 
much smaller and can make DSLs seem weak socially.

We are both curious how DSLs fit into the world. To what extent are they
academic/research topics, and to what extent are they currently used tools in
the world? And in considering the DSLs that are out there being used, to whom
are they given to? We believe that DSLs are available both in high-end academia
as well as precollege. For example, Scratch is a DSL (probably) that is used
in primary to secondary school. Because of this polarization, we believe the
topics in the article apply to DSLs.


---

**Question**

The Pavlus article mentions the researchers' comments that people preferred
"natural-language replacements for some of the more abstruse syntax". In other 
words, people found it easier to work with code that looks more like a human language (e.g.,
English). Consider the following quote by William R. Cook, one of the creators
of AppleScript:


> The experiment in designing a language that resembled natural languages (English
> and Japanese) was not successful. It was assumed that scripts should be
> presented in “natural language” so that average people could read and write
> them. … In the end the syntactic variations and flexibility did more to confuse
> programmers than to help them out. It is not clear whether it is easier for
> novice users to work with a scripting language that resembles natural language,
> with all its special cases and idiosyncrasies. The main problem is that
> AppleScript only appears to be a natural language: in fact, it is an artificial
> language, like any other programming language. … even small changes to the
> script may introduce subtle syntactic errors that baffle users. It is easy to
> read AppleScript, but quite hard to write it.
[[Cook 2007, page 1-20]](https://dl.acm.org/citation.cfm?doid=1238844.1238845)

Are these two experiences of natural languages at odds with one another? Would
you choose to include natural language in the design of a DSL? If so, how might
you do so? If not, why not?

**Response**

We think that this shows that there is a balance to be struck between natural
language design and regular scripting language syntax.  It is also important
to know the audience of the language.  If they are experienced programmers it
is probably easier for them if your programming language looks more like what
they are used to and has the less natural syntax of Java or C, but if they are
less experienced it would feel more natural to the user to use a more natural
language type of syntax and grammer.

For us, it depends on the DSL whether or not we would include natural language
in the design. We think Python is a good example of a general-purpose language
where there is a good balance of natural language. The syntax is straightforward,
and there isn't too much natural language that obscures the language.


---

**Question**

Briefly describe how you split up the work for this assignment.

**Response**

We each read the articles on our own.  Then we discussed the question together
before typing up anything.  Then we typed the question up, taking turns on who
was typing by about every question.  The person who wasn't typing was watching
for grammar and spelling mistakes and adding ideas.

---
