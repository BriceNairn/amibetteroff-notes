# 4 — UI/UX
## Designing the UI


After nailing down the calculator fundamentals I moved on to designing the UI.
The page was exploding all over the screen,

I got started by throwing 10 divs into a new HTML file and started iterating on my nested div structure.

> I threw 10 divs into a new HTML file and got started with hosting it with Live Server.

> *IMG*
￼
A screenshot of early progress.

> *IMG*
￼
Where I had got to after a few hours.
 



— Starting a new html file
- Using Live Server to view immediate iterations over site development
- Laying down the page divs
- Slow process of going back to the first photo-type site and integrating the page layout there.



> *IMG*


— The Chart
- stacked bar charts
- floating labels

￼
￼
Learning how CSS handles bar charts


— Payment Integrations
- Stripe Payment Links
- Stripe payment tables

> *IMG*

— Mobile Optimisation
- Challenges:
- elements overflowing off the screen
- re-ordering page elements so they would make sense on mobile

> *IMG*

After getting 85% the way there, a functional calculator, a layout that worked in desktop and in mobile 90% of the time,

So much more time was spent on refinement
Getting features work work exactly as intended
Re-touching every section of the page
Each section has been through a minimum of 4 revisions

Revising text
Font weights
Table formatting

> *IMG*

The Detail: Mention how you "customised every aspect until it was perfect." That’s not a "flex"; it’s the obsession of a creator.



## The last 10%
Hitting the Wall and Overcoming it

— CSS Styling
- Pulse
    - Pulse breaking everything CSS
    - Pulse going off each time I pressed the breakdown table buttons
    - Redesigning a lot of the functional logic
    - (It’s a dark magic and I still only loosely grasp how it works)
- Breakdown Table number transition
- Mobile button resizing


The Last 10% and Hitting the Wall.
Everything up until this point had felt fast and exciting, and realistically I could have stopped and shipped here and everything would have been fine.. but in my tenacious and furious drive for perfection I would not let myself accept less.

  > In hindsight shipping now would have been the right move, with delaying final polish for a later update.

After researching the UI and UX design philosophy and asking Gemini how I could best design my site to provide the best value and successfully convert donations for a free tool.  Gemini was talking about heuristics and creating perceived work and that I needed to implement a calculator “pulse”, display message ticks all over the screen that the calculator was looking up tax brackets & calculating the medicare levy, and I was already struggling with the stripe payment table and how it kept orientating vertically on a tablet which was driving me insane.

  > How I initially interpreted Gemini’s answer wasn’t it.

My initial interpretation of how to implement a pulse was to blur the entire screen after a user clicked a calculate button, but after a more of a conversation with Gemini I learned that my initial and dated first impression of what a pulse was, was based on dated sites that I remember stumbling across years ago.


I was already frustrated that the stripe payment table kept orientating vertically on a tablet which looked all out of shape and bad.

This was incredibly frustrating, as everything up until now had a solution, everything could be worked on, iterated and perfected, but because this was an imported script page element from stripe I realised that the only way to get this to work how I wanted, would to be to rebuild the entire donate section from scratch and create a whole lot of payment links.

  > Ugh!

At this point I had burned myself out completely, all the excitement had worn off and I had just realised that I was staring anther 50+ hours of work in the face. I’m not ashamed to say that I just said fuck it, I started browsing Facebook marketplace and immediately pounced on a listing for a MacBook Pro 13” mid 2012 which had been listed for A$80 6 hours ago.

  > So broken, yet still working, my first MacBook! - I’m writing this blog on it, and it feels good!

I took another 3 days off to go outside and touch grass. I went out and saw a free public live event, an improv comedy show, interviewed for a job and looked up how to reinstall MacOS without http support.

And right about when news was circulating that Iran and USA were throwing missiles around the Middle East I had enough of being outside and was ready to escape back into the gruelling grind of banging out the last 10%.

  > Respect for cleanly developed sites, that final level of polish is so much work!


> *IMG*


￼
Early prototype / version, showing an early implementation	of the stacked bar chart, breakdown table and copy outdated copy.

￼
Optimising pay period buttons for mobile, previously the rounded pill styles were clipping the button container border.

 


