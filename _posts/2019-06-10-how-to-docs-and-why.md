---
layout: post
title:  "How to Docs and Why"
author: ryan
categories: [ general-ideas, soft-skills ]
image: https://ryanhaber.s3.amazonaws.com/productbrief/content/images/neonbrand-618322-unsplash.jpg
featured: true
hidden: false
---

*tl;dr*: Nothing is worse than having to write docs - except not having them when you need them. You want not too little, but not too much.

# Why Bother?

Docs-writing sucks. That's why you don't want to do it, right? Well, that's fair enough. And even in a world where we rightly prefer working code over documenting the everloving f*@k out of things, there are some good reasons to document your work - whether as code or as an end-product.

<ul>
  <li>
    <strong>You are helping yourself.</strong>
    <br/>The better your documentation is, the fewer questions people will ask you in the future. And when they ask you questions, you will be able to send them a link instead of writing documentation. Based on this reasoning, it is a good idea <em>not</em> to document things that nobody will ever care about. You might be surprised that somebody asks about X. If that happens, answer their question and add your answer to the documentation in a place where people can find it. Also, you might have to revisit something six months or a year later. It will help you if you made good docs while you were working on it the first time.<br/>
    <br/>
  </li>
  <li>
    <strong>You are helping your future self.</strong>
    <br/>You will one day arrive at a new job or join a new team. You will hope that the people there have written good docs to help you get started. Pay it forward by writing good docs for whoever comes after you.<br/>
    <br/>
  </li>
  <li>
    <strong>You are helping your team.</strong>
    <br/>You might win the lottery one day and leave suddenly. Your team will love you if it make it easy for them by documenting your work well.<br/>
    <br/>
  </li>
  <li>
    <strong>You are helping our clients or customers.</strong>
    <br/>When our stuff is easy to use, people use it more. If it is not easy to use, we can at least explain it and make it feel easy. When we do these things, we get more sales and more renewals.</li>
</ul>

# What Makes Good Documentation?

## Quantifying the Value and Quality of Documentation

People often think that the value of docs is subjective or unquantifiable. This is rarely the case.

The value of writing is that it can be written once and shared many times, whereas in-person or real-time forms of communication need to be repeated each time a new person needs the information.

Time is money. Wasted time is wasted money and lost productivity.

If I answer a question for the external developer community and it takes me 10 minutes, and at my pay scale that is, to keep things easy, say $10, then the company pays $10 each time I answer that question. If the question comes in daily, then in the course of a working year of 240 days, the question costs the company $2400. If I write a good doc and make it easily findable at a cost of $60 one-time, I think you can see how the savings is dramatic. In my experience, a well-written, easily-findable answer eliminates the question 90% of the time. For the other 10%, you can smugly send a link and sit back while the past-you does the present-you's job for you. This scenario is simplified, but it is a real-life scenario that I live repeatedly. We all answer any number of questions over and over again because of disorganized knowledge management. This problem is not unique to our company.

Depending on the complexity of your documentation problem and your channels for interacting with your docs' users, you can gather just this sort of data and more. How long does it take to read a doc? How many times do people read the doc and then contact customer support? How often is a question asked of customer support? How easy is it to find the document in the docs repository when you know it exists? How often do internal or external search queries for relevant questions bring up the relevant doc or an irrelevant doc? What is the user behavior like when they land on a doc from a seemingly relevant search query. All of this questions can be answered objectively using modern technology. These answers, in turn, are the first data points for understanding the cost of difficult or missing documentation. They are a good first step in figuring out what needs to be documented or what docs need improvement.

The question is, then, what things should be documented?

<ul>
  <li>Document questions that are clearly or probably going to be asked.</li>
  <li>When you get asked a new question, might as well write it in a generally-applicable way if possible and quickly insert it into the best location in your documentation structure.</li>
</ul>

What should not be documented?

<ul>
  <li>Things nobody cares about</li>
  <li>Things that you are proud of but really only you care about, like how hard you worked - tell your mom or write a blog post.</li>
</ul>

> The trick is to anticipate the probable audiences for a subject matter and what they probably need to know.

So much for the value of a doc.

What about the quality of a doc? Isn't this subjective?

No. Not at all. A doc has a job to do and it is good inasmuch as it accomplishes that task. That is the absolute and completely objective standard to the quality of technical documentation. Suppose I write a document for experienced Java engineers and, out of a 100 engineers, 17 understand it. No matter how smart I think I am, I have failed. That score will save very few people any time.

There are other objective standards, too. The subject of readability, the ease and speed with which prose can be read and understood, is a very well researched topic. See [https://readable.io](https://readable.io) or [https://hemingwayapp.com](https://hemingwayapp.com) for free or low-cost readability scorers that will tell you the difficulty or ease of reading your doc and what makes it easier or harder. They typically use a set of established formulas to return a grade level, a letter grade, or a percentage score. They often give good tips for improving your particular text. Aim for a 7-9th grade reading level. This isn't dumbing anything down - this is making it so your document's user does not have to figure out what you were trying to say. This is just making yourself plain to even a teenager.

The principles and tips below will help you take your "business-ese" and easily transform it into clear text that your intended audience can understand. One caveat is that big words affect readability. Some words, like _utilize_ should almost always be replaced with _use_ because they mean the same thing and use is easier. Other times, you just have to use a bigger word like _reciprocation_. That's OK. Just be readable.

## Understand Your Audience
Good documentation is written for a specific audience. The author understands the audience and writes only those things that the audience needs to know. The author explains those things in a way that the audience can understand. Some examples include:

* Other engineers / your future self
* Educated, intelligent non-engineers: PMs, Designers, etc.
* Managers, Directors, or Executives
* External developers
* Marketing or sales team members
* External end-users

## Understand Your Audience's Needs

Audiences need different things at different times.

* **Conceptual**: Theoretical overview that explains the *What?* and *Why?*
* **Tutorial**: How-to steps that explain *How* to accomplish a task.
* **Reference**: Look-up material when your audience needs to know a fact, like a definition of a word or the parameters accepted by a method.


## Make a Matrix of Needs

Once you have made a grid of audiences and their potential needs, you can make rational decisions about which ones to document. For example, consider the subject of something technical like a data pipeline. In the follow matrix of needs, we mark spaces with X if we think we probably do not need to write the document because the audience does not likely need it. Otherwise, we comment on what the document should accomplish.

| Audience | Conceptual | Tutorial | Reference |
|----|----|----|----|
|Other engineers | Explain to other engineers what the pipeline does, how it works, and why we set it up that way, so they can get started working on the pipeline. Engineers looking at your code need to know: (a) what you did and (b) why you did it that way. <br/><br/> (a) should be clear from the code itself. Comments can help explain (b). | Help engineers set up their environment. | List of classes and methods. |
| PMs / POs | Explain to PMs / POs in a simple way what the pipeline does, how it works, and why we set it up that way. | List of unusual words and their meanings in the context. | *They can share with engineers.* |
|Executive summary | Explain in simple, common words, very briefly, what the pipeline does and why. | X | X |


## Universal Principles

### Concise

Do not use more words than you have to. If a sentence can have 10 words and you write 13 words, you have written 30% more than you need to. You ask your reader to read 30% more than they need to. Your writing feels fluffier the more you do this. If you do it a lot, it becomes harder to find answers.

Pro tip: Avoid using adjectives. Adjectives are usually unnecessary and often change. If you write, "The blue button," a UX designer will come along and change the color and your docs will be wrong.

**Example:**

I went up to the store in order to buy some organic eggs.  = 13 words

I went ~~up~~ to the store ~~in order~~ to buy ~~some organic~~ eggs.  → Remove words that do not add value for the particular audience.

I went to the store to buy eggs. = 8 words = 38% savings.  → Multiply this savings across 100 pages of documentation. &

### Complete

Try to include everything that somebody is likely to want to know. Do not include things that will not help other people with their work. If you are really proud of something, show it to your mother. The rest of us will be proud of you when we can read your docs and appreciate your work without have to read all the stuff you are proud of.

**Pro tip**: Do not create the same content twice if you can avoid it. Instead, use links and iframes to connect or display content as needed. Put related pieces of content close to each other. If related content cannot go nearby, connect them using links, iframes, or another such tool.
    
### Clear

**Clarity is objective.** If your intended audience does not understand your docs, your docs are not clear.

**Pro tips**: use a readability checker like [https://www.readable.io](https://www.readable.io) or [https://www.hemingwayapp.com](https://www.hemingwayapp.com) to help you achieve the right level for your writing. For technical documentation, aim for levels 7-9. If the only "problem" with your writing is that you have a number of large words that are necessary in the context, that's OK. You might have to use words like _application_ or _analytical_ that typically make a doc a bit harder. You do **not** have to use words like _utilize_ when a word like _use_ is just as good.

### Correct

Get someone else who understands your content to sanity check it for correctness. If your document is found by a reader to be inaccurate, they will wonder why they should read your work anymore. In some situations, inaccurate information can cause serious harm.


## Organize Your Content


### General principles:

<ul>
  <li>Keep related content close to each other.<br/>If a user only needs a bit of information in one place, then put that information in that place. If the user needs the information in more than one place, put it in one place and then link, iframe, or mention it in the other places.<br/>
    <br/>Example: <em>To log into your account you need credentials. For steps to get credentials, see Getting Credentials</em>.<br/>
    <br/>
  </li>
  <li>Avoid writing the same documentation twice.<br/>When someone updates one place, they will often forget to update the other. The two pieces of content fall out of sync and the documentation as a whole becomes less trustworthy.<br/>
    <br/>
  </li>
  <li>Make different kinds of content (conceptual, reference, etc) visually distinct. Separate them from each other when it makes sense.<br/>
    <br/>
  </li>
  <li>Use clear heading titles. Headings should answer a question. Headings for conceptual and reference content are usually nouns. Headings for tutorial (how-to) content should start with a verb.<br/>
    <br/>Bad: <em>How Do I LMGTFY?<br/>
    </em>Good: <em>Using Let Me Google That For You</em>
    <br/>
    <br/>
  </li>
  <li>Bullet points vs numbered lists:<ul>
      <li>If order does not matter, for instance, when you describe best practices that are independent of each other or when you are sharing concrete facts, then use bullet points (unordered list).</li>
      <li>If order does matter, for instance, when you list the steps of a procedure, use a numbered list (ordered list).<br/>
        <br/>
      </li>
    </ul>
  </li>
  <li>Use a table of contents for a long document or for a collection of documents.<br/>
    <br/>
  </li>
  <li>Each thing should be about one thing. You should be able to summarize every book, chapter, paragraph, and procedure in a single sentence.<br/>
    <br/>
  </li>
  <li>Use tags. Try to use existing tags instead of inventing new ones, whenever possible.</li>
</ul>

# Simple Tips That Anyone Can Do

<ul>
  <li>Write simple text. Short sentences, easy words, active-voice verbs all help readers quickly move through text.<br/>
    <br/>
  </li>
  <li>Put the documentation where it is relevant.<br/>If it is relevant to multiple things, make it a separate topic and link to it from all the places where it is relevant.<br/>
    <br/>
  </li>
  <li>Use existing standards whenever they apply.<br/>
    <br/>
  </li>
  <li>Use formatting consistently. Otherwise, the formatting loses meaning. Below are some common standards for documentation formatting.</li>
</ul>

# Common Standards for Formatting Technical Documentation

**Boldface** - use boldface to highlight exact words as they appear in the UI when a user needs them for taking action. If they are not exact words or they are not needed for action at that moment, don't use boldface.

`Monospace` - use monospace to indicate words or string as an exact match in code or other technical sources like config files.

_Italic_ - use italic to indicate that words or string is an exact match that is not in code.

Ordered lists - use for steps or other information in which the order is essential

Unordered lists - use for information in which the order doesn't matter

H1 - top-level subjects, unless there is no special format for a title, in which case, use H1 for the title of a document

<br/><br/><br/><br/>

Photo by [NeONBRAND](https://unsplash.com/@neonbrand?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/search/photos/writing?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)
