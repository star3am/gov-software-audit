# Software Audit of SA Government Departments

How much does our government spend on proprietary software? I haven't found an audit anywhere so I decided to conduct one myself. 

## Why do I care; Why should you?

My estimate is that we are spending over R10 billion of public funds annually on proprietary software, the large majority of it to overseas companies through their local partners. That's essentially a pot of money that leaks out of the South African economy. Why not use open source software instead supported by local companies? There are lots of good reasons to using open source software most of which I won't mention but the ones I think are important for government are:

* No vendor lock-in - software is often like a monopoly, once you've bought into it, the cost of moving to another system can be prohibitively expensive. Knowing this, vendors can maintain high prices with little fear of competition
* Software quality - bugs are quick to fix - anyone can clone a repository, make the fix and send a pull request. The fix benefits everyone and doesn't require a long version update cycle.
* Reduction of redundancy - Department A needs some software, Department B needs the same software - why do they both have to purchase their own software?
* You want a feature? - You don't need to wait for the next version of the software and hope that your must-have feature is included.
* Free? - nope - that's not at all true and should not at all be a reason to choose open source software.

Apart from the above - my biggest argument for moving government to open source systems is economic. An additional 10 billion rand annually injected into the local software development industry will create a bundle of jobs and stimulate economic activity which is being lost to software imports.

## Arguments against going open source

* *You'll need to re-train all of government* - hey, you have R10 billion to spend - spend some on training
* *Open source software sucks* - you think so? Spend R10 billion tuning it to be just so
* *You can never move government wholesale* - one step in front of the other
* *There is no open source equivalent to X package* - let's talk - are you sure you looked carefully enough?
* *What about support* - Pay for it - I'm sure there are tons of companies willing to provide it.

## I geddit - what's next?

A strong quantitative economic argument for why open source software is good is the only way to convince decision makers. To achieve this, I am gathering information by submitting [PAIA](http://www.sahrc.org.za/home/index.php?ipkContentID=25&ipkMenuID=45) requests to government departments requesting information on software licences. What software are they using? How many licences do they have? How much are they paying?

PAIA is tedious but defines a process through which members of the public can access information held by government (with exceptions). A PAIA request costs R35 and can take anywhere between 30 days - 1 million years to process. 

Once I receive the data, I enter it into the csv file in this repository ready for analysis. 

## Sounds like an awesome idea - how can I help?

I am targeting government at national, regional and local level. It's great that we have PAIA but it isn't as easy as sending an email. You often have to send a couple. Sometimes you deal with public servants who like to test your resolve. Also, in practice, government departments have no real obligation to give you the data. In principle you can take them to court but in practice that's not really going to happen. 

That said, I can't do it alone but I do feel that it is a worthwhile goal. If nothing else, a database of software used by government may be useful outside of this project. Also - learning about PAIA is quite useful - just because information is not available on a government website doesn't mean that you can get access to it. It's a useful tool in your toolbox if you need to research a particular topic.

If you're willing to help - contact me, clone the repository and get cracking. Send pull requests and I'll merge your additions into the database (and credit you appropriately).
