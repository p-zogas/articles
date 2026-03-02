# Why LLMs have trouble with style guides and what to do about it

In 2019 I wrote [Guide to content strategy](https://www.designsystems.com/guide-to-content-strategy-in-design-systems/ "Guide to content strategy") for Figma's [DesignSystems.com](https://www.designsystems.com/ "DesignSystems.com"). My goal was to give content designers some clear first steps for incorporating language guidance into design system components in order to make it easier to scale their work.

Now, at the beginning of 2026, design teams are working even closer to code and racing to get their design system components hooked into Figma, v0, Cursor, or whatever else they're using. They're after high quality protoypes and fast iteration cycles, along with the ability to reduce time-to-production by increasing automation. For content designers, it seems like a similar transition should be easier. LLMs are made of language, and all of the artifacts for content standards and goverance are language. Should be pretty easy to just point some models at your style guides, glossaries, and brand guidelines and expect solid outcomes, right?

That hasn't been my experience. It works to give a chatbot access to your docs and ask it to draft content or use it as a souped-up spelling and grammar check. But as things scale up--either in terms of a product's complexity or the scope of your documentation--efficiacy decreases pretty rapidly. And for automated writing you can trust, it's not there yet.

I'm going to use the first section of this piece to explain why this is, and in the second I'll outline a few solutions.

## Why LLMs are having trouble

### Style guides are written for humans

Content teams at tech companies use style guides because they're useful ways to organize rules for writing and because the people working on those teams have always used them. The people who created content function came from publishing, journalism, teaching, and writing--a fields where the ability to follow and create style guides is bullet point #1 in job postings.

Open up any style guide, and you'll see a lot introductory material, preambles to sections, and wordy explanations in a long document that's likely kept on Google Drive, Notion, or Confluence. People know what to skim and learn how to navigate whatever guides they use often, but the norms and structures of style guides make them less useful for LLMs.

### LLMs need more examples and fewer guidelines

Try asking an LLM why it chose to include or exclude a comma in a sentence. It will probably answer in terms of clarity or simplicity or readability. It won't tell you that it made a decision based on the relationship of independent and dependent clauses or the presence of a coordinating conjunction. That's because LLMs are following patterns found in many, many sentences rather than writing a sentence in reference to a rule.

LLMs are pattern-matching machines more than they are rule-following machines. 

### How to look for things is just as important as what you're looking for

* Context windows
* Recency bias

## What you can do about it

### Get your guidelines into files--and a file structure--that LLMs prefer

### Rewrite your guidelines to focus on examples, block lists, canonical strings, and personas

### Always be testing your outputs

### Have a plan for routing
