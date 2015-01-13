# How to Write Curriculum

So, you want to write curriculum for the ADI High School Teaching Program? Well, you've come to the right place!

Our curriculum generally consists of two parts:

1. A guide that walks through the content and exercises, with which students can follow along during class and refer to after class.
2. Slides for the instructor to read from as they go teach featuring the essentials on which the lessons will focus.

ADI has general guidelines for creating both of these; these will be outlined here.

## Writing Markdown
[Markdown](http://daringfireball.net/projects/markdown/), as stated on its website, "is a text-to-HTML conversion tool for web writers." It's an easy way for ADI to write awesome tutorials for a wide range of subjects. It has awesome features, like:

**Lists**

1. Item
2. Item
3. Item

**Headings**

# Heading
## Heading
### Heading

**Block Quotes**
> "'You miss 100% of the shots you don't take' - Wayne Gretzky" - Michael Scott

And, perhaps most importantly, **Code Segments**

This can be either inline, which is used for referring to code mid-sentence.

For example, say I wanted to mention the `Arrays.sort()` method in Java when talking about Quicksort.

We can also do blocks. This is huge for our curriculum because it represents the place where students will model all of their code off of:

```
function toCelsius(fahrenheit) {
    return (5/9) * (fahrenheit-32);
}
document.getElementById("demo").innerHTML = toCelsius(32);
```

More features of the Markdown language are available [here](https://help.github.com/articles/markdown-basics/).

Especially as some new to Markdown, it can be helpful to have text editor that shows the rendering of your Markdown in real time. For this, I recommend [Dillinger](http://dillinger.io). It's a web-based Markdown editor wherein you type on the left and see Markdown on the right.

As a reference, here is the [Intro Python tutorial](https://github.com/mjp2220/devfest-webdev/blob/master/webdev_python_curriculum.md) I wrote in Markdown for DevFest. If you want to see the Markdown for it, simply press Raw. I would recommend formatting the curriculum so it is pretty similar to this guide.

## Creating Slides
For creating slides from which to present, most people in ADI use [Slides](http://slides.com/). It's free, looks nice, and generally very easy to use. 

Try to keep the slides short and sweet. Highlight the most important parts of your curriculum. These should take much less time than the Markdown guide, as it should pull strongly from curriculum that has already been written.

Pictures of your completed webpage are good; they help students to know whether they are on the right track. So include these pretty liberally!

Also, try to keep it fun. Gifs are encouraged. Everyone likes the fun teacher :D.

For some examples, check out [my slides](https://slides.com/mattpiccolella) from last semester. They represent the general guidelines ADI Workshops uses in creating slides.

# So, how can I start?
It may seem daunting to begin writing curriculum. However, with these simple steps, you can be a master content writer!

1. Find good content online for your subject. Places like [HTML Dog](http://htmldog.com/), [Codecademy](http://codecademy.com), and [Eloquent JavaScript](http://eloquentjavascript.net/) are great places to start. Also, check out ADI's [Resources page](https://adicu.com/resources) for a more comprehensive list.
2. Outline all the sections of content you want to hit. For example, with an HTML curriculum, you would want to list things like Document Structure, Basic Tags, Images, Links, etc. (It may be a good idea to have someone review it at this point as well to make sure you're hitting all the important points.)
3. Fill in the details. Do this with code segments, interesting pieces of information, and other things.
4. Create simple exercises. For example, say you are going through JavaScript functions, create an exercise to convert pounds to kilograms. For bonus points, add solutions to your exercises!
5. Issue a [pull request](https://help.github.com/articles/using-pull-requests/). This allows for other members of the group to give feedback, suggest edits, and check for typos before the content is added to the master copy.

Once you have finished these steps, your content is ready and can be delivered to students! Woohoo!

# Common Misconceptions
There are many misconceptions about writing classroom content on technology subjects. I will address those here.

- **You do not need to know the content already to write content.** One of the best ways to learn things is to write content for it. Want to learn JavaScript? Write content on JavaScript! Many of ADI's workshops are written by someone written the content as they learn the content themselves.
- **You do not need to know Markdown like the back of your hand.** Markdown is not something you need to memorize. If you want something, say a list, google "Markdown lists"; the first result will give you what you need. Or, even more easily, use past tutorials we have written; copy and paste it to get the general structure set.
- **You do not need to know Git.** If you are having trouble with issuing a pull request, this is a great way to learn! We are all very willing to help; writing content is the way I and many others learn about collaboration with Git.
- **You are not expected to do everything yourself.** Ask for feedback often. Leave unfinished sections in your outline and have others fill in the details. Write the content and ask a partner to think of exercises. If you are adding to content in any way, that is awesome! Do as much as you can when you can.

I hope this has been helpful! Now go out there and start writing awesome curriculum for our students!

