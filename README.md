# Pulsar Neighborhood web site mirror

Note: this is forked from the original [Pulsar Neighborhood repo](https://github.com/pulsar-neighborhood/pulsar-neighborhood.github.io).

Welcome to the home for the [Pulsar Neighborhood site](https://pulsar-neighborhood.io). This is the source behind the magic. As an open community we welcome all ideas and contributions, whether it is a new feature on the site or content you would like to see.

## About the site's framework

Pulsar Neighborhood was created on the [Hugo framework](https://gohugo.io/). It uses bootstrap components to create the wondrous experience that is. There is a mix of core Hugo functions, good ideas from seasoned Hugo experts, as well as the odd idea found out in the wild. We try to follow the best practices of Hugo when it comes to the site's folder structure and naming. If you are familiar with the framework, then this site is [hopefully] very easy to get started with.

If you see something about the site's design that could be a little better please [make a suggestion](https://github.com/compuguy/pulsar-neighborhood.github.io/issues) or PR that great idea right in to the project.

The site has 4 content types: article, guide, video, and spotlight. Articles are the most common and represent a blog post or some other written story about Pulsar. Guides are step by step instructions on how to achieve some goal using Pulsar. Videos are a brief about what is covered and a YouTube link. Spotlight is a special type used for the community spotlight section of the site.

## "I love the spotlight" - said no software engineer, ever

 Don't sweat this. It's less about you and more about what you've done with Pulsar. If you've got something to share but don't feel like writing it all out let's put it in the spotlight. [Open a spotlight issue](https://github.com/compuguy/pulsar-neighborhood.github.io/issues/new?assignees=&labels=&template=community-member-spotlight.md&title=Check%20my%20Pulsar%20skillz) and give us a sentence or two about the cool things you've done. Share a link if it's something public.

## Contributing ideas and content

It can be a simple idea, a written article, or a half though-out step by step guide. However far along the content is, the community is here to help make it a pulitzer candidate.  Your options...

### Opening an issue (simplest)

When you [open an issue](https://github.com/compuguy/pulsar-neighborhood.github.io/issues/new/choose) in the repo you are asked to choose from a template. Use this to choose the type of content the best fits your idea. Paste your markdown within the "content" area of the new issue or simply type out a few lines of idea. There are a few additional areas of interest like title, author info, image, etc. All of this is optional. A content moderator will guide you through getting everything right.

### Running the site locally

If you're feeling adventurous (and have a basic understanding of Hugo) you could fork the repo and develop your idea locally. Then open a pull request to suggest the idea in the main site. Below are commands you can use to get content started:

Create a new article:

```bash
hugo new articles/my-really-great-idea.md
```

Create a new guide:

```bash
hugo new guides/my-step-by-step-guide.md
```

Create a new video:

```bash
hugo new videos/my-cool-video.md
```

## Content formatting examples

As you write content for the community use the below markdown examples to take things to the next level. Spoiler - no one likes a wall of text and everyone loves reading code.

Guide steps [[Markdown](content/examples/guide.md)] [[Live](https://www.pulsar-neighborhood.io/examples/guide/)] - use this to get a step by step guide started

Tabs [[Markdown](content/examples/tabs.md)] [[Live](https://www.pulsar-neighborhood.io/examples/tabs/)] - share your code in multiple runtimes

Code Snippets [[Markdown](content/examples/code-snippet.md)] [[Live](https://www.pulsar-neighborhood.io/examples/code-snippet/)] - include snippets throughout your content, maybe even highlight a line and comment on it

Blockquote [[Markdown](content/examples/blockquote.md)] [[Live](https://www.pulsar-neighborhood.io/examples/blockquote/)] - make a statement

Information Callout [[Markdown](content/examples/info-callout.md)] [[Live](https://www.pulsar-neighborhood.io/examples/info-callou/)] - include a call out box with further info about a topic

Warning Callout [[Markdown](content/examples/warn-callout.md)] [[Live](https://www.pulsar-neighborhood.io/examples/warn-callout/)] - include a call out box with fair warning about something

Danger Callout [[Markdown](content/examples/danger-callout.md)] [[Live](https://www.pulsar-neighborhood.io/examples/danger-callout/)] - include a call out box that warns of dragons or ill-tempered creatures ahead

Success Callout [[Markdown](content/examples/success-callout.md)] [[Live](https://www.pulsar-neighborhood.io/examples/success-callout/)] - include a call out box declaring a win

Table [[Markdown](content/examples/table.md)] [[Live](https://www.pulsar-neighborhood.io/examples/table/)] - markdown tables aren't the best, use this to go a little further
