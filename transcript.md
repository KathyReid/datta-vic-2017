# Controlling the Future - BuzzConf Nights August 2016

## Presentation checklist

* CogniToys dino powered up and ready
* NinjaSphere powered up and ready

## Welcome to country

I wish to begin by acknowledging the Wurundjeri people, the traditional owners of the land on which we are gathered today. We pay our respects to the local people for allowing us to have our gathering on their land and to their Elders; past, present and future.

Thanks everyone for coming today, and a huge thanks to Ben and Rick for convening an event as amazing as Buzzconf Nights.

## Audio impaired

If there are any hearing impaired members of the audience, let me know and I can provide you with a transcript of the presentation to follow along to.

## Kathy Reid

My name is Kathy Reid, and I work as an independent digital consultant. I engage with different organisations to do different pieces of work such as analysis, technical white papers, I run hackathons and work with technical communities. You can find me online @KathyReid.

## License

This presentation is licensed under Creative Commons universal - you're free to share and re-use this presentation. Please use it to do awesome things.



# Overview

SLIDE: Ursula from the Little Mermaid

So, hi! I'm a control *enthusiast*. I like controlling things. This talk though won't be about world domination, so if you were here for *that* controlling the future talk, well let's talk later :D *evil fingers*

SLIDE: Overview of topics covered

What we *are* here to talk about today is the future of user interfaces. I'm going to spend a couple of minutes going retro, so we can appreciate just how far we've come in a short period of time. Then, we're going to explore some of the newer user interface approaches that are emerging, such as;

* conversational user interfaces and speech recognition - and I'm going to let you play with Dino here - a toy which uses speech recognition to keep children entertained and learning.

* we'll talk about the rise of natural user interfaces - things like gesture control - everyone remember Minority Report, where Tom Cruise was controlling things on screen like this *demonstrates gesture control*? I've also got my Ninja Sphere here and will show you how that works.

* we're also going to chat a little bit about emotional user interfaces, and neural interfaces, and how they're developing. Who wants to control your devices with the POWER OF YOUR MIND???!!! :-)

* we're going to explore some of the different characteristics, commonalities and differences in user interface development, and do some thinking around what it will mean to control your environment in the future.

## Questions

I'd love to hear your questions, however I think for the ease of microphones and audio, do write them down or remember them, and I'd be delighted to respond to them at the end of the talk.


# History

So, to see where we're going, let's spend a brief moment going back, BACK IN TIME!

SLIDE: Punch cards

Some of you may be seasoned enough to remember punch cards - anyone? With punch cards you literally had to punch holes into these cards, then load a bunch of them into a computer which was about the size of a house, and wait to see if you had a syntax error, then repeat the process when you realised you'd missed a semicolon. *sigh*

Then came these

SLIDE: Old fashioned keyboards

Then came these

SLIDE: Macintosh mouse

And then we had graphics input devices

SLIDE: Wacom graphics tablet

And we saw advancing in entertainment and gaming technology as well

SLIDE: Nintendo WiiMote

And then we had touch screen devices themselves, such as phones and tablets

SLIDE: ASUS Transformer Trio

This is actually the device I'm using today

So basically the input devices themselves have got incrementally more useful and more sophisticated, we have wireless, we have bluetooth, we have less cords - which is great.

# Trends and the drivers for user interface paradigm shifts

But there's a number of key trends which are driving changes in user interface paradigms - paradigm shifts as opposed to incremental changes. Let's have a look at them.

## Mobile

SLIDE: Lego chains

Firstly, we're not chained to our desks anymore. We work mobile. We have laptops, smartphones, wearables - and if you saw my talk at BuzzConf festival last year, you'll know that soon we'll all have implantables as well!

So we need user interfaces that move with us.

Secondly, we don't want to carry a range of user input devices with us - we're mobile. We're commuting in trains, we're hot desking even if the organisations we work for have actual offices, we're working from coffee shops. We need the user interface to fit where we're working - or playing from - right now.

SLIDE: infra red keyboard

A keyboard that goes where you go!

## Contexts

Another key trend is that we're leading active, on-the-go lifestyles, with our time sliced into ever-thinner wedges. 'Always-on' devices, and work habits mean that the boundaries between work and personal time are blurring.

Twenty years ago you might have got up in the morning, caught a train or bus to work, been at work for 9am, lunched at 1pm, then finished at 5pm, and commuted home. The *context boundaries* - the boundary between what was work context and what was a home context - were very clear.

SLIDE: Slices of different context

In today's society we're *context-switching* freqently. When we wake in the morning - which is usually with the assistance of a mobile device - the first thing we do is check the device for notifications. We might quickly respond to a few work emails to get them out of the way - context switching to work. Then as we're commuting we're in a different context again - where we might do some low value 'quick and easy tasks' on the train. At work we might have the luxury of real deep thinking time - where we don't want notifications or interruptions. At home of an evening we're in a relaxed context, where socialisation with our families is a priority.

So the key theme that I'm drawing out here is that our user interfaces need to change and adapt to the *context* that we're existing in. If we're on a crowded, noisy train, we don't want to use a voice interface - because it's really difficult to do so - it's frustrating - and that means friction - the arch enemy of user interface design.

A researcher called HABER had a well thought through way of categorising these contexts;

* intimate space
* personal space
* social space
* public space

User interfaces need to know which context they're operating in.

SLIDE: If I have time on HABER's levels of context

## Ubiquitous computing

SLIDE: LIFX - technology is all around us

The third key trend that I'd like to explore is *ubiquitous computing*. Just as we're mobile, and exploring all of our different contexts, computing technology is all around us, largely due to the internet of things. Our lights - with things like LIFX - our homes - thanks to things like Nest and Amazon Echo - and even our vehicles - have much more embedded and interconnected technology.

SLIDE: Tesla Model S - vehicle technology

Combine this with both mobility and context-switching, and suddenly we have user interfaces all around us. We plan our day and our journeys on our mobile device. We swipe on with our Myki on the bus or the train. We get coffee or fast food by ordering from a touch screen. Our buildings increasingly have technology, such as proximity sensors and beacons. We're surrounded by user interfaces - it's not just computing that's ubiquitous, user interfaces are ubiquitous too.

## Key areas of user interface development

So, now that we've explored some of the overall trends that are shaping user interface technology, let's take a look at some of the emerging technologies in this space.

### Speech recognition and voice control

Without a doubt, one of the hottest technologies to emerge in this space has been speech recognition and voice control. This technology has been around for decades now, but was has been held back by a number of challenges. There are about a million words in the English language - give or take a few thousand. Now try imagining first capturing those words - perhaps in a busy cafe or where there's lots of background noise. like an open plan office. Then you need to account for intonation or accent or _emphasis on the wrong syllable_. The permutations and combinations quickly multiply into a very complex problem set.

The way that speech recognition on mobile devices - Siri, Cortana, Google Now and so on aim to address this issue is by reducing the *problem space*. You know how there are a limited number of commands that you can issue to Google Now - you might ask about the weather or ask Google to add pasta sauce to your shopping list, or ask a 'who was' question. Right - so you're not using the million or so words in the English language - you're using a much smaller subset that's easier to predict - particularly if you factor in *context* - such as being geographically in a shopping centre, or near a train station.

So, we're going to see the rise of speech recognition and voice commands, but for a few years they're still going to be limited in their vocabulary and what you can do with them.

However, even with a limited vocabulary there are lots of possibilities for how speech recognition and voice commands will be incorporated into technology.

#### Cognitoys Dino

SLIDE: Cognitoys Dino

One of those is *toys*. We're now starting to see toys, such as the Elemental Path Cognitoys Dino, use voice recognition combined with things like artificial intelligence to provide both a learning and entertainment experience.

DEMONSTRATION of the Cognitoys Dino

So what I'd like to do now is give you a run through of the Dino - which uses voice recognition and the IBM Watson platform to answer questions, tell jokes and help craft stories.

* How old are you?
* Do you have any brothers and sisters?
* What is a computer?

(let the audience have a play with it)

### Conversational UI

So, did you see some of the patterns that were emerging as we interacted with Dino? That's called a *conversational UI* - and you might have used one of these with tools like Slack or IRC in the past. Again, using a limited vocabulary, you're able to interact in some ways with *bots* or programs just as if you were interacting with a human.

If we combine this with other trends - such as self service touch screens and kiosks in places like airports and fast food restaurants, then you can see a natural progression - you won't just have to touch for your order, you can place it as you would going through drive through - except the agent on the other side of the microphone won't be a human, they'll be an Ordering Bot :D

### Implications for consideration

Of course, having listening devices around you can be a little unnerving. And there's some machine ethics issues here - and I know machine ethics is one of Paul's favourite topics.

SLIDE: Mirrored drives

* For instance, with the CogniToys dino, what happens if the child who's using it divulges private or sensitive information? What if that information indicates they're being abused? What obligation does the platform provider hold?

* How do you balance privacy with safety and security considerations? Is it feasible to think that national security agencies may want to capture or hold on to some of these conversations - for instance if the platform identifies the user as being from a particular ethnic group?

* And there's a fair body of research around the types of voices we want to interact with - as humans we prefer female voices to male voices. But will having conversational UIs with predominantly female voices further condition us as a society into believing that women are to serve, rather than to be served?

* And what happens if you have a speech impediment - such as stuttering - or difficulties with language. Are you going to be marginalised because you don't have a mainstream voice? How will standards such as WCAG and WAI-ARIA respond to these challenges?

I'll leave you to ponder these philosophical reflections.

## Gesture control and other natural user interfaces

SLIDE: Gesture control

The next emerging type of user interface technology that we're starting to see is in the field of gesture control and *natural user interfaces*. Most of you will have used gestures such as flick, pinch, zoom, tap and double tap to use table and smart phone applications, and natural user interfaces are really an extension to this - gestures without a touch screen.

Has anyone seen Minority Report - where the character played by Tom Cruise is using gestures like swipe and pinch and zoom, as part of the user interface? That's the sort of thing we're talking about here.

And it's closer than you might think.

### LEAP Motion and Kinect

SLIDE: LEAP Motion

Technologies like LEAP Motion and Kinect map gestures in real time, using a variety of technologies such as Bluetooth sensing, infra red and cameras which can sense depth of field. For instance, by disrupting an infra red field, and tracking movements over time, the devices can infer movement.

### Project Soli

SLIDE: Project Soli

One of the most exciting advances I've seen in recent months has been Project Soli by Google. Instead of using infra red or depth of field cameras, Project Soli is using radar to detect and map gestures. The benefit of this is that radar has very high positional accuracy, providing greater degrees of precision for very minor, small gestures. This is still in R&D, so I wouldn't expect to see a production release for a couple of years.

### Ninja Sphere

SLIDE: Ninja Sphere

But it's not only the giants like Google who've been experimenting with gesture control. Some of you in the room may have been early adopters of the Ninja Sphere - a gesture based device that allowed room automation at the flick of a hand.

DEMONSTRATION OF NINJA SPHERE - if we can get it working at BuzzConf Nights

### Implications for consideration

Of course, gesture based interfaces come with their own set of considerations.

* What if the user has limited mobility? What if they only have a limited range of movement?

SLIDE: Elderly woman using device

* As our population ages, we're seeing the rise of chronic, age-related conditions. For instance, in Type 2 diabetes, one of the complications that can be experienced is peripheral neuropathy - where there's a loss of sensation in fingers and toes. If our devices need to be controlled by micro-gestures, and micro-gestures are more difficult for people with these sorts of conditions, are we creating barriers to technology? We already have a fairly significant digital divide between the digital haves and the digital have-nots. Do natural user interfaces so natural after all?

Again, I'll leave you to ponder these questions.

## Emotional and social interfaces

Perhaps one of the most fascinating areas of user interface evolution is what we're observing in the emotional and social interface space - this where peoples' emotional expressions, their social cues, and indeed their thoughts are being used as sensors or inputs.

### Emotiv

SLIDE: Emotiv

Emotive is a research and consumer grade EEG - electroencephalograph - it's a wearable for your brain, and allows you to monitor, assess and research your brain's activities. It's really aimed at the research market for organisations who are doing neural research, but there's nothing to stop makers or hackers buying one and exploring it.

The Emotiv is being developed as a neural control tool, and there's even a drone you can get which is thought-controlled.

So yes, very soon you'll be able to control your environment with the power of your mind!

SLIDE: Affectiva

Another product in this space is an MIT-spinoff called Affectiva. Affectiva analyses the facial expression of a user based on a photo or video image, showing things like key emotions or the user's level of engagement with what they're watching or viewing.

Immediately you can see the implications this has for things like digital signage and advertising, or if you're more altruistic, the implications for example in student engagement in education, and identifying students who might be at risk because Affectiva has identified that they're emotionally disengaged.

### Considerations and implications

Of course, here's some key considerations to keep in mind with these technologies also. Imagine that your cloud service is keeping data on the cognitive and neural patterns of your user base and is able to categorise or filter them in a meaningful way. Could this be manipulated at all? I'm not keen on giving the government census my name and address for them to keep, so the thought of giving a for profit company my, well, thoughts, is a little scary.

And just as we've built ad blockers to filter out banners and sliders and other distractions from what we're really trying to achieve - advertising is really about disrupting the user experience - will we start to see things that block our emotions or faces from facial recognition technologies.

Well, the answer is yes, and here's an example from a collection called CV Dazzle by Adam Harvey

SLIDE: Facial recognition disrupting makeup

### When UIs collide

Another point to ponder is what happens when user interfaces collide? For instance if you have a facial recognition user interface that can identify your emotions, will a voice based user interface change to better calibrate to your mood? For instance, if you're upset or angry, will the voice interface use a more soothing tone?

## Wearable interfaces

One of the last types of interface I'm going to speak briefly about is wearable technology. There's a couple of technologies you might have heard about - or might have seen - that are breaking new ground by embedding user interfaces into wearable fabric - into clothes.

### Lilypad and Arduino wearables

SLIDE: Arduino Lilypad

For those of you of the open hardware persuasion, you may have experimented with technology like Arduino Lilypad - small electronic devices intended to be sewn into fabric using conductive thread - and controlled by a range of sensors such as accelerometers, light sensors and temperature sensors.

### Project Jacquard

SLIDE: Project Jacquard

One of the most interesting advances in this space is from Google again - where they've taken a step forward, but not just sewing hardware components into fabric, but by weaving conductive material into the fabric itself, so that you can use gestures on the fabric to control devices.

Pretty amazing stuff, hey?

## Next steps and considerations

So, we've covered a huge range of advances and considerations in user interfaces and what the future may look like for interacting with devices, machines, bots, our environment - and indeed, each other.

So to finish up, I'd like to again pose some questions and threads for further consideration.

### Too many user interfaces and having to learn them all

SLIDE: Keyboard chaos

For instance, with so many different user interfaces - touch screens everywhere, elevators that talk to you, and pretty soon - robots that take your order or provide customer service - how many different user interfaces will you have to learn to use?

There's a real paradox here - one of the key principles of user interface design and interaction design is to reduce the friction for the user - to enable them to do what they want to do quicker, easier, cheaper - and with more delight - to actually *enjoy* using whatever device they're using. But by having so many different devices, with different user interfaces, it's actually making it harder at a macro scale for people - we're overloading people with different interfaces.

Just to underscore the point - we're not *replacing* one type of user interface with another. Conversational UIs and touch screens and even wearable technologies are not going to replace keyboards and mice and game controllers - at least not in the short term. We'll be using emerging user interfaces *in addition* to the ones that already exist.

So how, as an industry are we going to respond to that?  

Is everyone familiar with BootStrap - a web based user interface framework? Right, so I think what we're going to see is the emergence of a multimodal user interface and interaction pattern - something akin to BootStrap for gestures and microgestures, conversational UI standards, and even some emerging design standards for things like wearable interfaces. What we need to do is stop inventing interaction languages, because it's causing a Tower of Babel type effect at a macro scale.

I think we're also going to see the rise of *interaction families* that are aligned with brands. Interaction families will have a personality or flavour - for instance a corporate with a focus on efficiency may have an interaction family which is spartan, quick, with a minimum of movement or sound. A more social or fun brand may have an interaction family which focuses on lots of verbal interaction or fun gestures.

### Accessibility and usability

SLIDE: Walking stick

We also have to be mindful of digital inclusion and the digital divide. We have a multicultural, aging population, with varying degrees of physical ability and varying capabilities with other senses such as sight, touch and hearing. As we build new and emerging user interfaces, we need to think carefully about who is being advantaged and disadvantaged by those interfaces.

It's called *human* computer interaction, not *English-speaking-rich-able-bodied-computer-interaction*.

Our social policy makers will need to step in where there isn't a commercial imperative to consider these issues.

## Conclusion

So, in conclusion there are three trends that are driving user interface evolutions;

* mobility
* context switching
* ubiquitous computing

and we're seeing the emergence of new types of user interfaces in;

* speech recognition and conversational UIs
* gesture control and natural user interfaces
* emotional and cognitive user interfaces
* and fabric and wearable based interfaces

Like any advances we need to carefully consider their implications. *How* we harness these technologies will shape the future we want to see. Use your control wisely.

Thank you very much.

END TRANSCRIPT

# References

* Boehm, J. (2012). Natural user interface sensors for human body measurement. International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, 39, 531–536.
Braga, M. (n.d.). Here’s What’s Holding Back Your Universal Translator | Motherboard. Retrieved August 7, 2016, from http://motherboard.vice.com/read/heres-whats-holding-back-your-universal-translator

* Brownlee, J. (n.d.). Conversational Interfaces, Explained | Co.Design | business + design. Retrieved August 7, 2016, from http://www.fastcodesign.com/3058546/conversational-interfaces-explained

* Brumitt, B., & Cadiz, J. J. (2001). Let there be light" examining interfaces for homes of the future. In Human Computer Interaction. INTERACT’01. IFIP TC. 13 International Conference on Human Computer Interaction. IOS Press, Amsterdam, Netherlands; 2001; xxvii+ 897 pp (pp. 375–82).

* David W. Cearley. (n.d.). The Evolving User Interface From Graphical UI to Environmental UI - Gartner Research ID G00138271. Retrieved August 3, 2016, from https://www.gartner.com/doc/490171/evolving-user-interface-graphical-ui

* Delimarschi, D., Swartzendruber, G., & Kagdi, H. (2014). Enabling integrated development environments with natural user interface interactions. In Proceedings of the 22nd International Conference on Program Comprehension (pp. 126–129). ACM.

* Haber, J., Greening, M., Castellano, L., & Wheaton, P. (n.d.). Proxemic Conversational UI: Moving beyond simple conversation.

* Harris, R. A. (2004). Voice interaction design: crafting the new conversational speech systems. Elsevier.

* Jackie Fenn, Alexander Linden, Steve Cramoysan, Toby Bell, & Bern Elliot. (n.d.). Hype Cycle for Human-Computer Interaction, 2005 Gartner Research ID G00128069. Retrieved August 3, 2016, from https://www.gartner.com/doc/481880?ref=ddisp

* Jain, J., Lund, A., & Wixon, D. (2011). The future of natural user interfaces. In CHI ’11 Extended Abstracts on Human Factors in Computing Systems (pp. 211–214). Vancouver, BC, Canada: ACM.

* Koskela, T., & Väänänen-Vainio-Mattila, K. (2004). Evolution towards smart home environments: empirical evaluation of three user interfaces. Personal and Ubiquitous Computing, 8(3–4), 234–240.

* Lee, E. J., Nass, C., & Brave, S. (2000). Can computer-generated speech have gender?: an experimental test of gender stereotype. In CHI’00 extended abstracts on Human factors in computing systems (pp. 289–290). ACM.

* Nass, C., Moon, Y., & Green, N. (1997). Are Machines Gender Neutral? Gender‐Stereotypic Responses to Computers With Voices. Journal of Applied Social Psychology, 27(10), 864–876.

* Picard, R. W., Wexelblat, A., & Clifford I Nass, C. I. N. I. (2002). Future interfaces: social and emotional. In CHI’02 Extended Abstracts on Human Factors in Computing Systems (pp. 698–699). ACM.

* Steinberg, G. (2012). Natural user interfaces. In ACM SIGCHI Conference on Human Factors in Computing Systems.

* Štolfa, T. (n.d.). The Future of Conversational UI Belongs to Hybrid Interfaces — The Layer — Medium. Retrieved August 7, 2016, from https://medium.com/the-layer/the-future-of-conversational-ui-belongs-to-hybrid-interfaces-8a228de0bdb5#.613h0diz3

* The evolution of the interface, from text through touch | Ars Technica. (n.d.). Retrieved August 4, 2016, from http://arstechnica.com/gadgets/2015/04/the-evolution-of-the-interface-from-text-through-touch/
