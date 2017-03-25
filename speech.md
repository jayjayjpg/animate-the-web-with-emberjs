# The Speech

# Introduction

Present yourself
Hi folks, my name is Jessica Jordan and I'm a front-end developer who just in the beginning of the year joined the dev team at Leadfeeder. Leadfeeder offers a web tool to leverage 
web analytics data for sales teams and I have the pleasure to work on ambitious web apps together with other talented Ember developers.
Besides my joy for my new project, I'm deeply in love with my hometown Berlin - here you can see the tall Alexander Tower
which can be seen from almost anywhere in the city centre - and enjoy checking out the diverse
vegetarian cuisine in my free-time, I like to draw a lot and also mingle with other web enthusiasts in the Berlin tech scene.
I'm one of the co-organizers and oftentimes also co-learners of learning groups and workshops under the umbrella of OpenTechSchool
Berlin - an organization that aims to bring free knowledge about technology of all kinds to people.
Also just recently I bumped into Clemens and Joschka who are some other """"lost""" Ember souls in Berlin and we 
decided to revive the EmberJS Berlin meetup. So if you are ever in town, please join us - we are a very friendly meetup group
and the stickers we sneak from the EmberJS Munich meetup to hand out are just adorable! 

Besides of all these things, there's another big interest of mine / adoration / I don't know, that I want to share in more detail with you today: And these are Cartoons! Animated Comics??? Animations have made up a huge part of my childhood, with me getting fully 
emerged in stories and worlds so different from ours, that the producers of these shows decided to actually ditch the live acting and draw it down  :-) 

If we think about cartoons and take it to a more abstract, higher level perspective, we will realize that those are not much
else than hand drawn motion picture - or let's animations on the TV. What is also important to not is, that not everything
that is animated on the TV is an actual cartoon - as there is another important component to it to make it call like so.

And we may call this component "Storytelling". We will see that the really interesting and fascinating part of cartoons is the story
that is conveyed in them and that is transported through an animated narrative. These 
kind of animations can be educational, purely entertaining or even both. The animation therefore is valuable on its own, 
but still in the bigger picture of narration just a meands to an end - finally it is a message that is about to transported
and the animation is its deliverer..... should arrive at our viewers.????

The interesting thing is now that if we as developers think about animations, there are many different things that might cross our mind 
instinctively. What might happen is that we think about that edgy hover effect our UX lead asked us to implement last week,
it might be that we were thinking back at our amazement when we created our first Ember app with Liquid-fire powered page transitions.
Also, we might think about an ambitious SVG based data visualization to improve the usability of a data-heavy interface we are creating.
In fact if you are interested in the latter, I would like to highly recommend you Jen Weber's talk on SVG animations and interactions
in Ember to explore this in greater depth tomorrow afternoon.

All of these examples of assisting our app's overall user experience through interaction-driven animations 
may be categorized under the term of Informative UX  which I blatanlty caught up on Sarah Drasner's talk on animations at JSConf.Asia 2016) 
(Sarah Drasner on Functional Animation - JSCONF.Asia 2016: https://www.youtube.com/watch?v=HaD5z2KqcGk)


But although these are all great and relevant topics to almost anyone here in the room, I in fact won't be talking about any of these.
Instead I will be coming back to one of my favorite topics from earlier: Storytelling driven-animations. And for this, I would like to in 
the upcoming 25 mins explore with you how traditional animations are defined and created and how we can bring these kind
of animations to the web today and to what extent these tools and methods differ from each other / outweigh each other. 
Finally I will also show you on two more concrete examples how we can merge the best from the world of open Web APis and Ember
to create our own animations - and easily present them on the web to our readers and viewers.



# Body

Let's have a quick look how an animation is actually defined - so far one of the more general descriptions of
animations describes them as ....
The frequence in which the images are displayed are crucial for the animation emerging. In fact, there is not much to 
a display of several images in succession if it wasn't to our visual perception to have a non-perfect resolution for sequential
perception. A really old study by Max Wertheimer (1912) shows that already a lag in the display of two different lines of smaller than 200ms
will for most people lead to the perception of a fluent motion with 60ms to have been declared as the optimal lag
interval - other studies claim this sweet spot for animation to 
be somewhere around 30 - 100 

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


