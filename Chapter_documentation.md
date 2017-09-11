# The Essential Documentation

Defining and starting a new software project is a routinary task for a software engineer.
We carve new ideas all the time into software programs.
And we organise these software programs following well-defined structures.

Of course, we know the technology and how projects should be structured for them.
And if we do not know the technology, we know the exact keywords to look for in a web search.

This is not the case for those people not experienced with software engineering practices.
The lack of terminology, the lack of contacts, the lack of experience are a high entry barrier for newcomers.

You're starting a software project.
You are maybe building a product for your business or a cool startup.
Or maybe you're designing a library to share to the scientific community.
Or you're perhaps doing it just for the fun.

## Describe your project

### Choose a Project Name

The first thing that your project needs is a name.
Without a name, you cannot create a first directory in your disk to store your source files.
Without a name, you cannot tell people how to search for your project.
A name give your project an identity, a way to refer to it and to differentiate it from other projects.

#### What is a good name?

Naming is hard.
Donald Knuth, one of the biggest minds ever in computer science said that choosing a good name is one of the two most difficult tasks in computer programming (for the curious reader, the other one is cache invalidation).
Indeed, choosing a good name requires understanding the nature of what we are naming.

Good names do not always take the same form but they have something in common: in one way or another they are easy to remember.
Some names, like Google, are easy to remember because they are cachy.
Some other names, like Python or apache, are good because they relate to an existing idea or concept.
Some others, like Ubuntu, use cachy words in foreign languages.
However, there are actually no strict rules to get a good name.

#### Some Ideas

In general, I use two main approaches to chose a name: acronyms and fantasy names.

Acronyms are useful when you want to reflect some idea in the name directly.
For example, a project whose long name is "Can be an acronym" can be transformed in the acronym CaBAnA (Can Be An Acronym).
Acronyms are good if you want to embed specific words or affiliations inside the name.
They are also handy when you miss the inspiration for a better fantasy name.

A different alternative to name your project is to use a fantasy name.
We call fantasy names those names that are not necessarily forged like the acronyms.
Instead, a fantasy name is taken or inspired from existing concepts.
Some examples of this are the Apache Spark platform, or the Oracle SQL database.

Fantasy names can have also have a metaphore.
Good metaphores relate easily to the project and, if we know it, it helps in remembering it.
Typical metaphorical names are inspired in mythology, books.

Finally, sometimes you will need to adjust your name to the technology conventions or limitations.
For example, some tools require special casing: start with uppercase or lowercase, spaces allowed or forbidden, underscores or not, etc.

#### About Bad Names

As there exist good names, there exist also bad ones.
Again, there are no strong rules that say if a name is good or bad, but I like to follow some guidelines.
First, I avoid long project names.
Long names are harder to remember, to type, to web-search than short names. 
Second, I avoid acronyms with too many consonants because they may turn difficult to pronounce.
And a name that we cannot pronounce, we cannot promote with the parole.

### Explain What does your Project do

People will arrive to your project's main page because they are looking for similar stuff. Or maybe because somebody linked you. And sometimes even for random.
Most of the people that will arrive to your project's page will have something in common: they do not know your project.

And people now knowing your project will ask the following questions as soon as they arrive to your site: What is it? What is it useful for? Why should I use it?
Most of the people will abandon your site if they do not find any of these explanations.

Another point of consideration when explaining what your code is about: write for newbies. Most people will be users of your code. And users don't want to understand in detail what happens inside your code, they want to understand what can they use it for. Give examples of usage, tell the user if he's the right person for your code.

Of course this does not mean that you don't have to do a technical documentation of the internals of your project. You need technical documentation, but it is not a friendly way to welcome new users.

## Add Installation Instructions

### Platform

### Dependencies

### Build, Compile

### Verify your Installation

## Explain How to Use Your project

### Document the API

### Extension Points

### Add Examples