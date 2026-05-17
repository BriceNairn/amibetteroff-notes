# Compliance, Accessibility & Legal Liability
## The ‘Oh Shit’ moment



Legal Liability for financial calculator sites

From the start legal liability wasn’t really on my radar, for me I was doing a simple tax calculation and showing the remaining net income and super contribution.

It wasn’t until I had largely finished my calculator and UI/UX that I looked up whether this project was going to get me into legal trouble.

From my research, I was okay since I wasn’t selling nor providing personalised financial advice, but early iterations of my calculator were stating which outcome was ‘better’ and I later found out that they way the outcome was worded could be perceived as persuasive and lead to problems if someone followed that advice and things didn’t work out for them.

  > Generalised financial advice is okay to share on the internet.

This kicked off a review of all of my calculator outputs, and the phrasing around the key outputs.

I later learned that any language if found to be persuasive or favouring an outcome could lead to liability.

  > Initially my top summary KPI read “Contract/Permanent is Better”

I also learned that a single disclaimer on the foot of the site would not necessarily be enough to defend myself from a claim, and that it should be present when inputting values into the calculator and when looking at outputs.


To also address legal liability I added multiple disclaimers about what the tax calculations were and what they weren’t. Explicitly stating that the tax figures were calculated using simplified tax and medicare methods.


Generalised Financial Advice
I have not sold nor provided financial advice advocating for action.

Generalised advice is okay,
I just had to be careful about how I used language in my results summary.

I could get into trouble if a user of my site made financial decisions based on the result of my calculator if I performed an incorrect calculation, or used persuasive language influencing or advocating for either outcome.

To also address legal liability I also went about adding multiple disclaimers about what the tax calculations were and weren’t, stating that the tax figures were calculated using simplified tax and medicare methods and placing (estimates or est.) next to important number values.

In general though, as this is a free tool and I’m not selling a service, and the advice is generalised and based on simplified tax brackets provided by the ATO the legal liability is low. 

I figured that I was okay as I was:
- not selling financial advice
- not advocating for either decision a user may or may not take
- putting visible disclaimers about how the tax calculations have been simplified and may not match individual circumstances
- providing a basic calculator, providing insight into the inputs users enter through logic in JS


	> I had expectations of liability around finance related resources but had no idea about web accessibility.



Accessibility
I was blind-sided by the liability I was creating by not making my site accessible for vision or motor impaired users.



for my website isn’t fully compliant in being accessible for vision impaired and could open myself to legal liability on the grounds of discrimination of disabled people.



This immediately put the brakes on launching the site early until I understood where my short-comings were.



-ARIA (Accessible Rich Internet Applications) is a set of HTML attributes that enables the developer to communicate the role, state and property of UI elements to users using a screen reader.

Motor disabled users also need to be able to fully navigate the site using just the TAB key.

Thankfully there are free ways to test and evaluate and measure your sites accessibility.
The one I chose was Google Lighthouse.




— Working around financial information
- generally okay if you’re providing estimates
- being neutral 
- not pushing advice
- general advice
- not advocating for an outcome
    - Wording and perceived interpretations matter
- Providing estimate disclaimers where a user will be seeing a result

— Accessibility
- Legal liability for discriminating against vision impaired people by not being accessible dev challenge
- Googles websites to review and rank accessibility

— Disclaimers
- Writing effective disclaimers
- & making sure they are on the page near calculated values

— Reworking language to be more matter of fact and less 
- Also balancing to try stay on brand
- throwing (estimated) or (est.) on all important numbers

— Privacy by Design
- Data sovereignty and why I don’t track any salary information entered on my site
    - OPTUS and the rising risk of data breaches
- 




## Review
### Google Lighthouse

> *IMG*
