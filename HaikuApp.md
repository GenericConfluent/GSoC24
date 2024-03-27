# Personal Info
**Full name**: Matthew Curtis Power
**Timezone**: UTC-06:00
**Email address**: m13power@gmail.com
**IRC username** (oftc.net): GenericConfluent
**Trac username** (dev.haiku-os.org): GenericConfluent
**Gerrit changes submitted** (review.haiku-os.org): IN PROGRESS
**GitHub**: https://github.com/GenericConfluent
**Emergency contact**: ibi.curtis@gmail.com

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
I may go on a walk. I could also end up going camping for a couple days aswell,
though I don't expect this to take time away from GSoC so much as 

#### Are you using Google Summer of Code to fullfill a university requirement ...
Nope. I just really want to write code this summer and the prospect of being
paid for it doesn't hurt either.

#### How and when did you first hear about Haiku?
When I was looking through the org list. I ignored any orgs that were
looking for people with web/python abilities since I much more enjoy low level
high level languages. Also: "Haiku is a fast, efficient, easy to use and lean
open source operating system". Maybe it's because I'm a fanatic member of the
rust cult and "blazingly fast" has been burned into my mind but... if that's
how you describe your project say no more, where can I sign up to work on it?

#### Did you also apply to other GSoC organizations? If so, which is your order of preference? 
Looking into Waycrate. Though I'm more inclined to work on Haiku so I may just
not submit my application.

1. Haiku
2. Waycrate

#### Estimated last day of classes/exams: 
26 April 2024

#### Estimated first day of classes: 
3 September 2024

# Introduce yourself. 
Well, my name is Matthew and I'm just a normal everyday person. It's nice to meet
you. Code has interested me since I was a wee little lad and so after a year or
two of having no clue where to start I eventually started jumping around between
Python, Javascript, and C++. I've been writing code for... about eight years now
I guess? Time really flies. As for how long I've been writing good code for, I'm
not fully convinced I've even started.

My problem is that I have next to no experience working on larger projects and 
in formal/semi-formal environments since all the stuff I do is little toy hobby
project where timelines don't matter. On the topic of hobbies I like programming,
piano, and regular exercise. Sometimes I do small competitive programming contests
for fun with my friends or stuff like game jams and whatnot. I did GMTK last year
and it was a really neat expereince.

Back in around eigth grade I decided I would try to write an OS for my raspberry pi
and didn't get very far (well makes sense I had a very limited understanding of computer
architecture at that point and of embedded programming generally). Because of that 
I have kindof always wanted to do work relating to an OS.

Additionally graphics programming has always really piqued my interest so I've been
itching to do a deep dive on it. (Partially because of how bad my experience has been
running the Wayland with the proprietary NVIDIA drivers.)

Other things to know: Don't think I can live without nvim and I use Arch BTW. (I'm sorry.) 

# Expectations from Mentors. (What do you expect Haiku's mentors to help you with?)
Guidance. I learned this when I was younger but nothing slows down progress more
than not knowing what you don't know. I really need somebody who can tell me where I
can find good information, and what it is that I don't know. Since I think that will
help me learn, improve, and ultimately deliver my project much better.

# Main
**Title**: Multiple monitors output in app\_server
**Description**: See https://www.haiku-os.org/community/gsoc/2024/ideas
**Goals**: 
- Update all Accelerant drivers and the app server so they support multi-monitor.
- If there is time, update the Screen utility so that the monitors can be repositioned
relative to eachother

## Timeline:
Community bonding period (May/June)
- Scour the web for useful documentation on the hardware
- Read through the 214 files that make up the accelerant drivers.
- See what the respective Linux drivers look like for inspiration.
- Update BScreen
- radeon
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
- Or give my secondary project a try.

# Secondary
Title: Write a virtiofs driver

## Description
While I was figuring out how I wanted to work I realized there isn't a neovim
port for Haiku and building it seems to be a pain. Since was running Haiku with
QEMU and libvirt I figured I would just use virtiofs to mount my local copy of the
on the VM so I could build and test the app\_server on Haiku but not need
to rewrite a separate configuration for vim. Unfortunately that didn't work because
as far as I can tell there is no virtiofs driver on Haiku. This project would 
seek to remedy that.

Goals:
- Allow Haiku users to mount host directories to their guest VM through virtiofs.

## Timeline
Community bonding period (May/June)
- Gather all the relevant information online.
- Check the linux driver for inspiration.


First month of coding (June/July)
TBD

Second month of coding (July/August)
TBD

Third month of coding (August/September)
TBD
