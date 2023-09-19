| [home page](https://cfrias1.github.io/portfolio/) | [visualizing debt](visualizing-government-debt.md) | [critique by design](critique-by-design.md) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Assignment 3 & 4: Critique by Design
## Step one: find a data visualization
The below data visualization is a table that I created in my job as a financial analyst/consultant for Arizona's Child Care Subsidy program; it's meant to show the YTD expenses, last communicated "planned" amount in a formal infrastructure plan document, the current forecast, and how the current forecast is spread out among the various fund sources for the initiatives undertaken using COVID relief funds. It has been in use and consistently updated/edited for the past 2 or so years.
![Arizona's Department of Economic Security's Division of Child Care Infrastructure Plan Table](https://github.com/cfrias1/portfolio/assets/144168691/e5b485de-7797-4866-b663-13a947b466d5)

## Step two: critique the data visualization
### Usefullness: 6/10
The audience for this visualization are those who come from a programmatic background, not a finance one, so a the sheer number of numbers presented here are a bit overwhelming. However, the purpose of the table is to show the financial progress of these various initiatives and knowing how much we're planning on spending on time sensitive grants is incredibly important to division leadership so a routinely updated table that's meant to communicate this is very useful. The reason why it's rated a 6, however, and not higher, is it's easy to get bogged down in it, which diminishes it's usefullness.
### Completeness: 6/10
There's a ton of information here, which helps its completeness. The reason why it's rated a 6, however, and not higher, is that it's a lot to look at and doesn't do a great job at communicating key takeaways, i.e. what categories are at risk of not spending, who's doing well, etc and there's no overt showing of what the key expiration dates are. 
### Perceptability: 3/10
While in a familiar format, a table, again it's a lot of information that very quickly/easily overwhelms the viewer. Plus, the color choices, while originally were meant to help distinguish the columns, are probably distracting/disorienting and do more harm than good. I think the fact that it's a table, and not a chart, causes the audience to do extra steps in their mind to interpret the data, which diminishes the perceptability rating.
### Truthfullness: 9/10
It's a table of numbers; there isn't any strong message or skew to portray meaning, it's meant to just show this is what it is.
### Intuitiveness: 4/10
Similar to my comments on perceptability, the table has a lot of information that quickly overwhelms and disorients the reader. So while it's a familiar format, it's information is not extremely intuitive.
### Aesthetics: 3/10
It's ugly, I'll admit it. It originally took this form because I needed an overview look in a spreadsheet that connected to various other tabs that went into more detail on this data; so when I had to routinely share this with a larger audience, I just used what I already had instead of trying to adapt into something more aesthetically pleasing.
### Engagement: 4/10
If one can past their initial overwhelmed feeling, I think the fact that there's so much information here can inspire some to dive deeper/want to discuss lines that look odd to them. It's just really hard to find what you're supposed to be looking for.
### Overall Observations
I think the table is overall okay, though that may be my own personal bias speaking given that some variation of it has been in use for 2 or so years. I think it's more effective to a financially minded audience, who wants the exact numbers for various things and see how it perfectly adds up. I think it's less effective to those more programmatically minded, as often they might only care about one or two of these lines and it's difficult to one, find their line and two, immediately understand what you're meant to take away from it. Overall, given the purpose of this visualization, adding a second visualization might be more beneficial to appease both interests.
### Primary Audience
The primary audience for this tool is government programmatic staff/leadership, internal department financial/data partners, state stakeholders who are invested in child care, and political bodies - the governor's office and legislature - who can make decisions on how these funds are spent. It's moderately effective; some audiences appreciate the detailed outbreak, as usually this table would be included with a document that has summaries on what all of these initiatives are exactly and some actually need the full complete numbers for the work they do, but others would be immediately overwhelmed by it (which sometimes is the point - show how much we're doing and overwhelm to avoid excessive questioning).  
### Final thoughts on design critique methodology
Overall, Few's method was fine. I felt a lot of the categories, such as perceptibility, intuitiveness, and aesthetics, had a lot of overlapping elements so it was difficult to try and distinguish between the three. But I think the foundation is there and it's important to consider all these elements when designing/critiquing a data visualization - just potentially format it different. Also, the number scaling is probably unnecessary; instead of 0-10 you honestly could just have "Needs a ton of work", "Is Adequate", and "Does pretty well" and you have the gist of it.

## Step three: sketch out a solution
So, understanding that I likely would need to keep the table in some capacity as that level of detail is needed for some audience members, I decided that I'd try to create a supplemental visual that would convey the high level spending progress. That way someone could, at a glance, see what initiatives still had a bit to go. I would try to combine categories while still keeping the main CRRSA vs ARPA distinction.
![Sketch](https://github.com/cfrias1/portfolio/assets/144168691/007b34aa-a25b-4152-854b-7ca5b1346c6c)

## Step four: Test the solution
### Feeback #1: student, mid-20s

Can you tell me what you think this is?
> Spending progress for DCC bc that's the title

Can you describe to me what this is telling you?
> Some things are more spent than others

Is there anything you find surprising or confusing?
> I don't know what those acronyms mean

Who do you think is the intended audience for this?
> Someone who knows what those acroynms mean, your boss?

### Feedback #2: student, mid-20s

Can you tell me what you think this is?
> Government spending percentage - I recognize the ARPA acroynmn

Can you describe to me what this is telling you?
> That you're trying to track expenses of things that have expiration dates

Is there anything you find surprising or confusing?
> The red color/0% are pretty aggressive - is that bad?

Who do you think is the intended audience for this?
> Someone in government, probably

## Step five: Build your solution
So, my sketch might have been too ambitious for Flourish, I couldn't get the CRRSA data to be side-by-side with ARPA. Also, I dumbly didn't anticipate how percentage spending might be good to show an even level field between the initiatives but on that same note, it doesn't capture the potential danger of not meeting spending targets. For example, some of the smaller initiatives are only 30% or so completed but not meeting their spending targets would only result in a loss of like $200k; whereas other large initiatives could be 90% complete but that remaining 10% is $5M. Percentages didn't capture that so I kept the proportions but shifted to abbreviated figures, i.e. $5M. Overall, I'm a bit bummed that I couldn't create a visualization that could convey everything the table did in a better way but also feel a little vindicated that I've been presenting a shoddy table all this partly because an alternative isn't super clear/easy.
<div class="flourish-embed flourish-chart" data-src="visualisation/15073095"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
<div class="flourish-embed flourish-chart" data-src="visualisation/15074098"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
