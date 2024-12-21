# On boiling the ocean

So you've got an idea. 
You know it's a great idea, and if people would just get on board it would be so awesome...

In the business world, this is called boiling the ocean. 
In business it's a problem, when learning it can be great though, so let's talk about it a bit.

## Some history

I don't know if this is true, but it is hilarious so I'm going to quote it here:

> The “boil the ocean” idiom came about during World War I. When Will Rogers was asked how the US should go about the issue of German U-boats, he simply recommended this: “Let the ocean be boiled.” A reporter asked how this could be done. In response to this, Will Rogers replies, “Man, I’m just the idea.” Source: theidioms.com

Pretty much everyone who works in tech has run into an idea like this.
When your job is to actually deliver working things to customers, boil the ocean ideas range from laughable to morale-killers.
Because of this they're often met with doubt when brought to groups of industry folk, even if those folk are friendly and looking to help people learn (which if I'm being honest is not most groups of industry folk). 

### Dunning-Kruger

Dunning-Kruger is a cognitive bias where inexperienced people think things are simpler than they are, and experienced people also, but to a lesser degree, think things are simpler than they are.
When you combine these with a boil the ocean idea, you can have people who don't know tech thinking, "oh building this app would be so simple for an app developer," and experienced people thinking, "this sounds easy, why don't you just do it yourself."

Most of the time, Dunning-Kruger is a pain in the keister, because it takes the form of some CEO telling you which database to use, but there's this magical time before you realize how hard things are where you can do things that the curmudgeonly industry vets always talk themselves out of.
This is the land of Chris Sawyer, Tarn Adams, Notch, and ConcernedApe.[^1] 

Even Tolkien spent two decades penning his Legendarium before he wrote the Lord of the Rings. 

## How to build big ideas 

If you go into places where ideas get thrown around--startup forums, tech meetups--you'll often hear ideas are easy/cheap/inconsequential, and that things like execution are what matter. 
When it comes to making money, that's kind of true I guess, but this doc's not about making a startup.

Truth is, maybe ideas are easy, but only a handful of people who have them make the ridiculous leap to actually thinking they should make their idea happen. 
I'm always reminded of what George Bernard Shaw said,

> “The reasonable man adapts himself to the world: the unreasonable one persists in trying to adapt the world to himself. Therefore all progress depends on the unreasonable man.”[^2]

And this is why it's important to understand what your motivations are in this big undertaking.

### If you're out to make money

As I said this isn't a doc on how to make a startup, but I'll say a few words about why boiling the ocean is the wrong strategy if money is your goal. 

Money, in software, is best made by startups (if you're not already an executive or something I guess), and for a startup to work you need two people: someone to build the thing, and someone to sell the thing. 
Everyone who has done one or the other thinks their thing is the most important, and they're both wrong, and it also doesn't matter since worrying about which is which is a quick way to make it so you never sell the thing in the first place. 

Not having skill in one thing or the other does not preclude you from taking on either role because they're both _hard_ to get good at (see Dunning-Kruger above). 
And having your software product fail doesn't necessarily mean you make no money (read [Money][money]).

BUT having your software product be some gigantic thing when you don't know how hard that is AND you actually _need_ the money you're trying to make is a recipe for disaster. 
So don't do that.

### If not money than what?

Well there are plenty of reasons to do things.

* Future money (learning new skills, building a portfolio, etc)

* For the sake/love of it

* To impress people

* To better humanity and/or the world

* Because it is awesome

If these, or anything else fits your case, then get on the boat friend, and let's be unreasonable together.

### Get started before you start

For the following sections I'm going to assume you've chosen to build whatever it is you want.
If instead you want to sell it, I'm going to have to ask you to look elsewhere for guidance, lest I Dunning-Kruge myself on sales.

One of the first big projects I started was building a random music generator. 
Nowadays I'm sure there's some AI-assisted music generators out there, but this was like 2001, and playing tones of any kind from a computer was pretty arcane. 

Big software projects are, usually, _systems_.
That is they are multiple software programs running in a cohesive unit to do whatever it is you're trying to do.
In a big company you would have a systems architect or two who put together system architecture.

Let me show you some system architecture:

![A very basic system architecture diagram](https://github.com/planet-nine-app/money/blob/main/docs/system_architecture.png)

I'm sure you can see why they make the big bucks.

Break your project down into parts like this. 
The specifics of the parts aren't really important. 
What's important is your ability to articulate what the parts do and how they fit into your project.

For my random music generator I had a UI where you could pick things like keys and tempos, and I had the tone generator that built the tones via math based on the UI, and I had the song generator which put the tones in order based on musical rules. 

In general the way to build your project is to just keep breaking down these boxes into smaller boxes until you hit a box that you feel you can do.
Then you do that box.
Just like eating an elephat--one bite at a time.

### I need help

Ok, here's the thing with big ideas, and really sharing things at all, when you share, you're sharing something you've thought about for months, or years, but the person you're talking to has just heard about what you're trying to tell them.
So big ideas tend to be just plain overwhelming to people when they first hear them. 
Really all ideas are kind of overwhelming when people first hear them--especially if they don't trust you to have good ideas yet.

This means if you're trying to recruit people, don't hit them with the whole idea of the back, instead focus on the first box you're trying to build. 

A lot of people make the mistake of trying to find people to commit to their project, but that's not really how things work in the (software) world. 
Life happens, and priorities shift around. 
If I had a nickel for each time someone working with me on a project disappeared because they started seeing someone new, I'd have enough nickels to rehire some of them to work on the projects for real. 

You can, and should, plan on committing all of the code and design yourself.
If you get help, great, if not the _real_ help comes with the conversations you have with people who you bring along the way. 

### No end in sight

Survivorship bias is a hell of a drug.
It gives the illusion that success is a linear process, and one that simply starts at day one and grows.
It is not.

When I was in high school, my friends and I used to call it the 99% pile.
99% of all creative endeavors: music, art, code, etc, end up thrown away either not good enough or unfinished.
Now that I'm older it's probably closer to 99.99%. 

That doesn't mean we don't try.

If your dream takes five years to build, take five years to build it.
If it's no longer your dream after three years, find another dream.

I've been working on mine for six and a half.

## Get on the boat

When I was a kid, I remember hearing that we didn't know how people got to Hawaii.
I was like, "that's dumb. Of course we know. They got there by boat."

It's what we do as humans.
You put some barrier in front of us, and we'll figure out how to go over, under, or around it to find what's out there.
We're explorers.

You had an idea, built a boat, and now the island's telling you not to go. 

Who knows where the boat's gonna take you?

Is it worth it to you to find out?



[money]: https://github.com/planet-nine-app/money


[^1]: I choose solo game developers here because though some may have knwon programming, there's sooooo much more that goes into making games that I don't think it's a huge stretch to say they had a touch of the Dunning-Kruger at the onset of their endeavors. 

[^2]: Ol' George penned Man and Superman in 1903, the same year Madame Curie was awarded the Nobel Prize for the first time. A writer friend of mine once admonished me for editing quotes to modern sensibilities of gender and race, but this quote, like the tech industry, and society in general is stupidly patriarchal, and I can't let it slide without comment.
