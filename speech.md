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
perception. A study from the twenties by Max Wertheimer (1912) shows that already a lag in the display of two different lines of smaller than 200ms
will for most people lead to the perception of a fluent motion with 60ms to have been declared as the optimal lag
interval - other studies claim this sweet spot for animation to 
be somewhere around 30 - 100ms.


Traditional animations in motion picture works on the concept of frame-by-frame animations. This involves us to show the sequence of images
- oftentimes summarized in one single piece of medium which we would nowadays describe as a spritesheet - in succession and the necessary 
frequence to create the optical illusion of an animated motion.


Why bring the animations to the web? Already several years ago "Reinventing comics" author soundso declared that soon when the technologies arrive, we will be able to
narrate stories on the web using our infinite canvas, tapping on mobile devices whenever and wherever we go. In her keynote "Storytelling on the Shoulder Of Giants" 
award-winning cartoonist and - as of this time - probably one of the most influential developers in the scope of animated narration
on the web Rachel Nabors describes
her epiphany moment as follows: "It took 5 years and a few specs, until I realized the infinite canvas was right there in front of me, all the time. It was my browser.
It started exploding with HTML5, APIs for web audios, speech recognition, CSS animations specifically....I started putting in animations everywhere again. I started
illustrating again. I started telling stories the way I like to tell stories again." (full video and article: https://medium.com/panel-frame/storytelling-on-the-shoulders-of-giants-a57a850b935d#.j9l1czgww )


This sounds empowering, so let's have a look what these APIs are about.

 - Animations On The Web - Tools and APIs
We have not quite arrived in the present time yet, but will take a look at the immediate past
of web development. If you as a developer or also just as plain user of the internet try to remember which 
- I have to blatantly say that - single tool has already been there 20 years ago and has been heavily used until about roughly
5 years ago to create videos, games, animations and deliver this multimedia content. Yes that's right I didn't want to believe that number
either, but it's the truth: The Macomedia Flash as we know it has accompanied us in our quest to bring 
multimedia content to the web for twenty years since its 1.0 release in 1996 (share this if you still remember the days of
Macromedia Flash).
For the longest time being it was THE go-to platform for developers to create their animations based on the properiatery standard
ActionScript and for designers with little to no programming experience to create animations and also for developers to create fully flexible pieces of art by the means
. To its most popular time it has been widely installed on desktop computers back in the early 2000s (this is when I just started using computers)
websites were creating and delivering big chunks of their multimedia content using Flash, just to name flash animations or the multimedia player on Youtube starting from 2005.
Due to different various developments around the platform browser coverage drastically decreased over time and the adoption of 
Flash based technologies on webstes started to slow down. It seemed The Flash era slowly came to an end, but not without
forging the way for a new star on the multimedia horizon: 

???? Somehow come to the conclusion that also
propietariness of the technology to a large part finally killed Flash ?????


The HTML5 spec.

which suddenly offered a wide range of open Web APIs for developers to create and deliver diverse pieces of multimedia content: Audio, Video and Animations. In general, the 
term HTML5 animations is often used loosely to describe all parts of animations that are based on open-web standards. Anything that can be delivered in modern browsers
using native APIs or by enhancement of CSS / JS libraries can be referred to as a HTML5-based animation.
There are dozens of animation-specific JavaScript libraries out there that will help you with creating 
your own aninamtions on the web and they have a lot of value on its own. But in the upcoming demos 
I want to show you how powerful APIs can be that we get to use from our browser right out of the box.


???? This is mixing the term 'HTML5 animations' which summarizes all the native Web APIs and vendor libraries.
Decide with which one to go and stick with it for the description of advantages.????

I believe that open web standards - so any browser spec or open-sourced JavaScript / CSS3 library - will shape the
future of how we create animations that are meant to be for the web or other media. The main reasons I believe
this to come true is the fact that finally open web standards empower us as developers to use them to the full extent
giving us a clear understanding of how they should work by their thorough specification / open source documentation and empowering us to follow
the process of future development of these by being able to follow the public draft process. The openness around these 
web standards give us a clear idea of what is going currently and how the path ahead looks like.
We also realize that with specifications being meticuously crafted as native web features over years a solid foundation for
our development process is made - (year long maturation of API as solid foundation for using of features) it creates a reliability for us to implement content today that will still work years from now
on - and if there are breaking changes we will know in advance due to the open specification process giving us time
to make our app's changes in considerable advance.
With the specs being directly implemented as part of the browsers API and open-source libraries doing nothing more than
just relying on these native features we have the possibility to reach our user anywhere where there is a browser present -
which is basically everywhere, anytime on any device. 

Last but not least, with the recent specs something amazing happened to our developer experience. Let's see how this looked like
for cartoonist and most likely one of the most influential web animations experts Rachel Nabors who describes her transition
from animating in traditional media to make the leap to the web.

???? Rachel Nabors Quote ?????

If we understand that open web standards increase the approachability to be used by people outside of the developer community as well
and actually engage them to join the "cult", we have made a big step in the direction of developer experience. By providing
story tellers with tools to keep on narrating their tales on the modern web.
Rachel is really enthusiastic when she speaks  about her transition and admires the possibilities of the Endless Canvas. Let's
see for ourselves in the same named native Web API:


HTML5 "Endless Canvas" API

HTML5 Canvas has been around for a while and is a low-level API that is not based on the DOM API directly, but allows us to 
draw animations on a flat canvas that doesn't know anything about the DOM but instead only renders our specifications in flat 
layers. HTML5 Canvas comes with its own HTML element that can just be dropped into our HTML template, with width and height parameters defining
its dimensions.

Once we have a reference  to the canvas ???? ELEMENT|DOM ELEMENT ???? we gain access to the context object which provides us
with several methods for setting drawing colors and even for drawing full images. The context object is essential
for creating our animations and in case that you support browsers older than ????? IE 9 ???? you should
consider getting started with the html-5-canvas-polyfill, which is ultimately a JavaScript library that - once added 
to your project - will fill the gaps between the spec and the current's browser functionality by providing missing features
with its own native implementation - so you can safely use features from the future today.


Let's see how we can leverage its power in an Ember component. Let's imagine we are all great artists and have already a spritesheet
prepared with the frames that 
If we would like to draw our image down to the canvas we have to make a few more preparations 



### On the conclusion:
We can see that the HTML5 Canvas API will render the Canvas Element and nothing more. This means we have a great advantage on performance -
we are able to animate many objects onto the canvas without feeling a drastic change in our overall's web performance - since
in contrast to DOM elements having to be created and rerendered when moved across the page, we can save all this potential memory usages
by actually only changing things in the view layer. Which is great!


Tools that we own so far, APIs that are available


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


