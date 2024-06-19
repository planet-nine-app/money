### Overview

As I've moved from private sector development to open source projects, I've found a number of people who are coming the other direction, and could use a little guidance on how to bridge the gap from open source to sellable products.
There are a million resources out on the web for non-devs who want to start businesses, but not a lot is written for developers on how to turn their projects into things that make money so that's what this repo is for. 

Please note I'm not a business guru or anything, just someone who's played on both the business and development side of the court, and since I like writing things, and putting them somewhere without ads, I make READMEs of what I know. 

Without further ado...

### So you want (or need) to make money

If you hop into any entrepreneurial forum, you'll find lots of people trying to figure out how to start.
Pretty much everyone is given the same advice: find a problem to solve.
If that's not enough guidance, the second piece of advice is: solve a problem you have so you'll be your first customer.

In general, if you've put enough time into building and maintaining something then you've already completed these first two steps. 
Congratulations! You're ahead of like 90% of the field.

Now if you were trying to figure out what to build, there'd be a lot of stuff to do, but you've already got something so we can skip all of that. 
But I do want to say one thing to just set expectations.
Most of everything that gets created will not get huge.
Some people consider this failure, but I don't know.
If your measure of success is whether you create a giant corporation or not, I'd love to hear why you started with open source software.
Regardless of how well your product does, there's always things to learn, and often that experience translates into greater future money.

That said, let's start making it happen.

### The company

You are no longer just an individual with a GitHub account and a project, you are a business. 
The specific laws for being a business will vary from country to country, so before you start making money be sure to understand your tax responsibilities, and other governmental things. 

Again, make sure you're aware of your legal responsibilities in your jurisdiction.
Find the minimal investment necessary to make yourself a business entity (in many places this is $0).
And now _you_ are the CEO/CTO/Principal Architect/whatever of that company. 
You can have many titles, and you can and should change them based on context.
Your company doesn't need to _do_ anything other than keep working on that sweet project of yours (or not tbh). 
Believe me when I say there are many many companies, and people who gave themselves those titles, who are much less deserving than you.

Now there are a bunch of things you can do to give your company more of a presence like a website, and domain business suite, and whatever.
Do that stuff if you're interested, but don't feel obligated. 

You have bigger fish to fry.

### The product

The product is what you sell.
Since you have an open source project or two, _those_ aren't the product, because _those_ aren't meant to be sold.
So you need to figure out what to sell.

Remember that whole solving a problem thing from above?
Here's where it matters.
As I'm sure you're aware, there are few things in the world more challenging than getting people to care about your pet project.

_That is *NOT* because your project sucks._

That is because people live busy lives, and if things don't resonate immediately, we shift our focus to something else.
If you're lucky folks may take a moment to shit on your idea if you were foolish enough to post it on Reddit or something. 

Your job isn't to convince people who don't care that they should. 
Your job is to find the people with the problem you're solving, and let them pay you for solving it. 
This is called market research, and if you have any success at it you can add marketing to your resume.

For example, if I may use one of my own projects, [Sessionless] is a protocol for sending asymmetrically signed messages between devices.
This solves a problem in a few different spaces, but I'll talk about gaming since that's one that many will be familiar with.
After talking to game devs, I found out that games often have a need to store some state on a server in order to verify that the client hasn't been tampered with.
So we've created [Continuebee] as a barebones self-hostable solution for this problem.
Now Continuebee is also FOSS[^1], so it's not monetizing (yet), but it certainly could.
Just throw a different license on it, set up a website for payments, and now you have a SaaS company.

So here are your steps:

* Find where your potential users hang out
* Ask them questions about how they would like their problem solved (don't try to convince them that your solution solves their problem yet)
* Incorporate their feedback into a loose wrapper around your open source project
* Give it a strong name, and start selling

### Selling

It is very hard to describe to people whose work gets critiqued for a living, how to change their mentality for sales.
There's a reason why the classic tech startup duo is a sales person and a dev. 
They are typically not overlapping skillsets.
Depending on your goals it might be worth trying to find someone to help you with sales (just don't let them strongarm you into some giant equity slice of your pie). 

If you're gonna go at it alone, here's what you need to know. 
And remember to brace yourself, most people will not care to hear what you're selling. 

* Anyone who shows any interest at all in what you're selling is a lead, make sure you get contact info to follow up with them at least.
* Just like most people won't care, the ones who do won't care about all the things your product does, or can do, or will do. 
Find the parts that resonate with them, and focus their attention toward the sale.
* Your website will never rank on any search engine, nor will anyone find it through search. 
If you're not getting out there and meeting people somehow, they won't find you.
* There's no need to sell to the whole world.
Finding local events and meetups often works better than jumping into forums and discords.
* Networking is waaaay more effective than advertising. 
* I was going to link here to Alec Baldwin's Always Be Closing speech from Glengarry Glen Ross, but it contains language we're no longer cool with. 
If you don't mind that, it's easily searchable.

But I tell you what.
Once you've made that first sale of something _you_ made to someone with the problem _you_ solved, you won't need these points anymore.

[Sessionless]: https://www.github.com/planet-nine-app/sessionless
[Continuebee]: https://www.github.com/planet-nine-app/continuebee

[^1]: Sessionless is part of The Stack, and The Stack will spawn ideas for "products" in different verticals. 
Continue bee is one such product. 
I have no plans to monetize any of these products until such time as we've figured out a way for _everyone_ who has contributed to benefit from that, and should that happen it'll happen in a flat way instead of the American top-down way. 

However, should anyone want to develop a product that uses The Stack they are more than welcome to. 
If you do, and you'd like to help figure out monetization that benefits us all, I'll help you make that product (if you want).
