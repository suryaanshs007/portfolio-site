# Suryaansh S — Portfolio

A personal portfolio site built around a backend and systems theme, with a terminal inspired UI and a few touches that nod to my Arch Linux setup.

## About

I'm a CS undergrad at Manipal Institute of Technology, Bangalore, currently exploring backend development, machine learning fundamentals, and Linux internals. This site is where I showcase a few of the things I've built so far, including CloudSentinel (an AWS based anomaly detection system) and OdinRecipes (a hand built recipe site from The Odin Project).

## Tech Stack

- **HTML, CSS, and vanilla JavaScript**: no framework, no build step
- **Tailwind CSS** (via CDN) for styling
- **Google Stitch** for the initial wireframe and visual design direction
- **Claude (equipped with a "frontend-design skill")** for refining the design, fixing bugs, and adding interactive features like the scroll triggered ray animation and the 3D spinning Arch logo. (Link to Claude skill used: <a href="https://github.com/anthropics/claude-code/blob/main/plugins/frontend-design/skills/frontend-design/SKILL.md?plain=1" target="_blank" rel="noreferrer noopener">https://github.com/anthropics/claude-code/blob/main/plugins/frontend-design/skills/frontend-design/SKILL.md?plain=1</a>)
- **Hermes Agent** An incredible, open-source agentic AI tool that comes with unique features like skill-rewrite and self-authoring, allowing models (running as the 
hermes agent) to grow increasing smart with every task, I used the built-in "popular-web-designs" skill and instructed hermes to use the Linear Website's color palette. 
(Link to this product: <a href="https://hermes-agent.nousresearch.com/" target="_blank" rel="noreferrer noopener">https://hermes-agent.nousresearch.com/</a>) 
- **Vercel** for hosting and deployment

## The Hermes Agent (my thoughts and more details):

Hermes Agent, developed by Nous Research is an incredible AI agent tool, the fact that
it is open source and is being built and maintained by a
bunch of passionate CS nerds is just proof of how quickly we can adapt
and ride this agentic AI tide. i was genuinely gobsmacked
by how this thing works, it puts Open Claw in the ground,
if you haven't tried this, please do. The skill-rewrite
and self-authoring works so well, it almost feels like sorcery.

Even whilst using underpowered models like Laguna M.1 and
Kimi K2.6, the hermes agent can correct and learn with time, 
literally adapting to your personality and your preferences, getting 
smarter with time, capping it's own SOUL.md and user memories to a certain character 
limit to keep things fresh and happening, instead of clogging itself 
and getting overwhelmed like Open Claw. It knows just how you work, 
I was able to give it claude's memories of me and it immediately 
modified it, adding only the most relevant things and cutting off unnecessary 
information, my design choices, tech stack, and everything else, it knows 
exactly what you'd want with a single memory import from any other AI provider and 
will only get more customised as you work with it. I was able to redesign my entire site 
exactly to my liking with one of its buit-in skills and the knowledge it had acquired 
so far of my preferences, a full redesign with a single prompt, using a model much inferior to
something like Sonnet 4.8, (yes i did a comparison, sonnet's work was garbage for the exact same prompt and skill).
All using a free API key, 0 bills. 

literal sorcery. 


## Design Notes

The visual identity leans into a terminal and OS aesthetic, dark background, monospace accents, and a violet color scheme that matches the Arch Linux brand color. Project cards alternate left and right as you scroll, connected by a glowing curved path that traces from the "currently learning" section all the way down to the contact terminal.

## Status

Actively maintained. This is a living site, it'll get updated as new projects get built and existing skills get sharper.
### Link: <a href="https://suryaanshs-portfolio.vercel.app/" target="_blank" rel="noopener noreferrer">https://suryaanshs-portfolio.vercel.app/</a>
