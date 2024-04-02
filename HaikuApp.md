# Personal Info
**Full name**: Matthew Curtis Power \
**Timezone**: UTC-06:00 \
**Email address**: m13power<AT>gmail<DOT>com \
**IRC username** (oftc.net): GenericConfluent \
**Trac username** (dev.haiku-os.org): GenericConfluent \
**Gerrit changes submitted** (review.haiku-os.org): https://review.haiku-os.org/c/haiku/+/7585 \
**GitHub**: https://github.com/GenericConfluent \
**GitHub2**: https://github.com/micron-mushroom

# About Working Term
#### Will you treat Google Summer of Code as full time employment? 
Yes

#### How many hours per week will you work?
Yes

I typically spend my summer working on random hobby projects for fun. This year
I intend for that to be Haiku. I generally intend to work `[9:00, 17:00]` since
that's when most other people I know work. So my estimate for the moment is
`8h` every day five days a week. The baseline I'm expecting is `40h/week`.

#### List all obligations (and their dates) that may take time away from GSoC:
I may go on a walk or running a mountain marathon. I could also end up going 
camping for a couple of days as well, though I don't expect this to take time 
away from GSoC so much as reallocate it, since I will probably end up working 
for fun on the weekends and outside of the hours I outlined above.

#### Are you using Google Summer of Code to fullfill a university requirement ...
Nope. I just really want to write code this summer and the prospect of being
paid for it doesn't hurt either.

#### How and when did you first hear about Haiku?
When I was looking through the org list. I ignored any orgs that were
looking for people with web/python abilities since I much more enjoy low-level
high-level languages. Also: "Haiku is a fast, efficient, easy to use and lean
open source operating system". Maybe it's because I'm a fanatic member of the
Rust cult and "blazingly fast" have been burned into my mind but... if that's
how you describe your project say no more, where can I sign up to work on it?

#### Did you also apply to other GSoC organizations? If so, which is your order of preference? 
None. I thought about doing Waycrate or CCExtractor, but school cut my time
short.

#### Estimated last day of classes/exams: 
26 April 2024

#### Estimated first day of classes: 
3 September 2024

# Introduce yourself. 
Well, my name is Matthew and I'm just a normal, everyday person. It's nice to meet
you. Code has interested me since I was a wee little lad and so after a year or
two of having no clue where to start I eventually started jumping around between
Python, Javascript, and C++. I've been writing code for... about eight years now
I guess? Time really flies. As for how long I've been writing good code, I'm
not fully convinced I've even started. I'm at the point now where I don't really
think it makes sense to list the "languages" I know because the language doesn't
really matter to me, because I know how to program.

As of the time of this application I'm a first year student at the Univerity of
Alberta studying Computer Science (technically I'm in the honours program but as
the word "technically" indicates that's just a technicality).

My problem is that I have next to no experience working on larger projects and 
in formal/semi-formal environments since all the stuff I do is little hobby
projects where timelines don't matter. On the topic of hobbies, I like programming,
piano, and regular exercise. Sometimes I do small competitive programming contests
for fun with my friends or stuff like game jams and whatnot. I did GMTK last year
and it was a really neat experience. 

My other problem is that I've spent so much time on the internet that my concept 
of formal writing has been somewhat erroded. (As you may very well be able to tell.)
So I do hope you will forgive my informality throughout this application.

Back in around eighth grade I decided I would try to write an OS for my Raspberry Pi
and didn't get very far (well makes sense I had a very limited understanding of computer
architecture at that point and of embedded programming generally). Because of that 
I have since wanted to work on a proper OS.

Additionally, graphics programming has always really piqued my interest so I've been
itching to do a deep dive on it. (Partially because of how bad my experience has been
running the Wayland with the proprietary NVIDIA drivers.)

Other things to know: Don't think I can live without vim, and I use Arch BTW. (I'm sorry.) 

# Expectations from Mentors. (What do you expect Haiku's mentors to help you with?)
Guidance. I learned this when I was younger but nothing slows down progress more
than not knowing what you don't know. I really need somebody who can tell me where I
can find good information, and what it is that I don't know. Since I think that will
help me learn, improve, and ultimately deliver my project much better.

# Proposal
**Title**: Multiple monitors output in app\_server \
**Description**: See https://www.haiku-os.org/community/gsoc/2024/ideas \
**Goals**: 
- Update all Accelerant drivers and the app server so they support basic side by side multi-monitor.
- If there is time, update the Screen utility so that the monitors can be repositioned
relative to each other, select whether a screen should be an extension of the desktop or a mirror,
etc.

## Timeline:
Community bonding period (May/June)
- Scour the web for useful documentation on the hardware
- Read through the 214 files that make up the accelerant drivers.
- See what the respective Linux drivers look like for inspiration.
- Necessary app server updates (Screen, Desktop, etc)
- radeon (Good place to start since it already has some work done)
- radeon\_hd
- virtio
- framebuffer

First month of coding (June/July)
- Any remaining major work on app\_server
- skeleton
- vesa
- et6x00
- via

Second month of coding (July/August)
- s3
- matrox
- ati
- 3dfx
- neomagic

Third month of coding (August/September)
- nvidia 
- intel\_extreme
- intel\_810
- Update Screen utility.


After Google Summer of Code
- Maybe port nvim
- Writing and XMPP client also really interests me.

