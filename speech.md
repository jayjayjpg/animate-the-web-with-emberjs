# The Speech

# Introduction

Present yourself
Hi folks, my name is Jessica Jordan and I'm a front-end developer working at Leadfeeder. Leadfeeder offers a SaaS tool for sales management, but - more interesting for most of you - 
I also have the honor to work with several other great developers on Ember applications.
As you can assume I'm a big fan of Ember and building things on the web, but there is also another passion that I share with maybe a few more of you in the audience: Animations. Cartoons? 


Storytelling?
Why animations in the first place?

And this is what I want to talk about today for the next 25mins. In my talk you will learn more about 

- what animations are (mechanics, definitions)
- how we bring them to the web today
- how Ember can help us with creating our own animations along an example of our own animation/animated component


But before we get started, let's have a look what kind of animations I will be talking about.
Today I will not be talking about how get that spinner button animation rotating correctly.
I also won't illustrate how we create meaningful user interactions by the means of SVG-based animations. But in fact, Jen will be giving an awesome talk about that tomorrow.
Unfortunately, you won't learn anything new about ember-liquidfire today either.

(Sarah Drasner on Functional Animation - JSCONF.Asia 2016: https://www.youtube.com/watch?v=HaD5z2KqcGk)

All of these examples round up animations in a category??? called informative UX (Sarah Drasner quote, Complex Responsive Animations, CSS Conf 2015), that we a as UI-driven web developers are most familiar with: Enhancing our user's experience  
But after writing that 101st css3 keyframe, after adding that 53rd bootstrap collapsible ---- crossed ----- materialize collapsible ---- crossed ----- Semantic UI collapsible
to your website you might wonder: are there any other things I can do with animations on the web?

(Yes)

Storytelling is the keyword. What we have seen again and again in motion picture on the TV or on the cinema screen is the use of animations for evolving a narrative whose purpose
might be educational or simply for pure entertainment. 
Since I was little I was a big fan of animated stories - or let's call them cartoons - and tonight I want to show you how we can tell these stories on the web.

But first let's have a closer look into what an animation as I described it earlier is:


We can use animations 
So let's get right into having a look what we mean by talking about web animations tonight:



# Body

 - Animation - What + Why?
  Definition of Animation: 


Why bring the animations to the web? Already several years ago "Reinventing comics" author soundso declared that soon when the technologies arrive, we will be able to
narrate stories on the web using our infinite canvas, tapping on mobile devices whenever and wherever we go. In her keynote "Storytelling on the Shoulder Of Giants" 
award-winning cartoonist and - as of this time - probably one of the most well-versed web developers in the topics of web-driven storytelling Rachel Nabors describes
her epiphany moment as follows: "It took 5 years and a few specs, until I realized the infinite canvas was right there in front of me, all the time. It was my browser.
It started exploding with HTML5, APIs for web audios, speech recognition, CSS animations specifically....I started putting in animations everywhere again. I started
illustrating again. I started telling stories the way I like to tell stories again." (full video and article: https://medium.com/panel-frame/storytelling-on-the-shoulders-of-giants-a57a850b935d#.j9l1czgww )


 - Animations On The Web - Tools and APIs
When you are a developer there is one tool that comes quickly to your mind: Yes exactly: It's Flash.
It was the go-to tool for designers with an approachable GUI to create narrative animations and also for developers to create fully flexible pieces of art by the means
of Flash's own proprietary script language. It was widely installed on desktop computers back in the early 2000s (this is when I just started using computers) and also
websites were creating and delivering big chunks of their multimedia content using Flash, just to name flash animations or the multimedia player on Youtube starting from 2005.
Due to browser coverage issues the big Flash era slowly came to an end with people becoming less and less interested in creating their animations in Flash and
a new kid entered the web animations scene: HTML5

The HTML5 spec offered a range of different APIs for developers to create and deliver diverse pieces of multimedia content: Audio, Video and Animations. In general, the 
term HTML5 animations is often used loosely to describe all parts of animations that are based on open-web standards. Anything that can be delivered in modern browsers
using native APIs or by enhancement of CSS / JS libraries can be referred to as a HTML5-based animation.
And what's so special about them, you may ask - why should I care about HTML5 animations at all?

As I said earlier, HTML5 animations may describe animated narration based on open web-standards. Open web-standards come with several benefits
- Open to anyone to use
- Accessibility - outreach to the user on all devices / browsers
- Reliability - since it is a dedicated API that will take years to mature across several browsers, it gives functionality you create based on it today
a good foundation to still work for a good time in the future - out of the box - no installation / update of any dependencies required

Which is all great!

Tools that we own so far, APIs that are available

CSS and hardware acceleration explained on an example

In the end we will realize that our life as a developer who wants to tell animated stories on the web in the year 2017 is already full of endless possibilities. Finally the choice is up to you
considering all the key aspects you are looking for in the tools that you are using.
In the end, I want to show you how this could actually look like. Let's see how we can leverage the combined powers of Ember and the web animations api to create our own
web animation component.
So....

 - Animations w/ Ember & WAAPI 
 
...this is how our animation component could look like. I already started drawing out a character standing on the panel. To give you a direction on where this practical example is going
let's summarise the features we would like to have for our comic component:

 - show a moving comic character in the front using a sequence of predefined images
 - ability to create several layers of animation in our component easily
 - add playback control for our sequence panel, giving us the power to manipulate the sequence with DOM events


So first all, let's create an animation layer including our comic character. As we earlier layed out, the base of every traditional frame-by-frame animations 


- Ember Object Model and how it helps to create reusable components

- Sprite Sheet Creation and Usage

- Keyframe Effects

- Group Effects

- Playback Control with Actions
- DOM events can be tied into the playback control


# Conclusion

Many tools, lots of fun to be had animating things on the web. 
We had a look at animations and where they come from
How open web standards help us to create great, reliable and accessible animations
How Ember Components help us to have the best from the world of open web APIs and the JS web app conventions


