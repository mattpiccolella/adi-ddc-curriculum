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

