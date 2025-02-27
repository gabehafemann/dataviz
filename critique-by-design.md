| [home page](https://gabehafemann.github.io/dataviz/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) | | [GIS files](GIS-Samples) |

# Critiquing Redfin Data by Redesign


## Step one: the visualization

For the critique by design project, I chose to look at housing affordability data from Redfin. Before I came back to school, I worked in housing policy and food security advocacy, advocating for things like SNAP funding expansion and the introduction of state- and federal-level Renter Tax Credits. I opted for a dataset I already had a connection to. Specifically, I chose to redesign the mortgage affordability data visualization because it's conveying really staggering information: that people need to be making more than $100,000 annually to reasonably afford the national median mortgage. That's even assuming, either generously or naively, that people can scrape together a 20% down payment despite the skyrocketing costs.

I'm looking at this graph from Redfin 
![image](https://github.com/user-attachments/assets/df81f53b-168e-4839-ae86-15dee1557eec)
Available from this link: https://www.redfin.com/news/homebuyer-income-afford-home-record-high/


which was assembled using Redfin analysis of this data from the Fed: https://fred.stlouisfed.org/series/MSPUS


## Step two: the critique

Overall, my impression is that the design of the original data visualization is clean and for the most part pretty clear, but misses some opportunities to raelly show the context and what the implications are. I think it kind of does what it intends to do, but could be punchier. The timeline is also ambiguous until you look pretty closely which isn't very helpful.


## Step three: Sketch a solution

With that in mind, I kept the line chart and added more descriptive labels and another line of data (with data from the Fed) for context.

![20250213_003403](https://github.com/user-attachments/assets/f22c8508-0161-4fc1-bf77-3a864994c036)


## Step four: Test the solution

When I talked to my classmates about it (three folks -- a Master of Arts Management student and two Master of Information Systems Management students), they gave some really helpful insights.

First, I asked them to tell me what they think is going on in the graph. Unanimously, they articulated that people need to make more money to buy houses.

When I asked what's working, they told me that the text is confusing. It made more sense in context with some discussion, but the header and labelling wasn't illustrative on their own. Plus it's chaotic to look at.

I lucked out that my group was students not in the policy program. One groupmate wondered if I'd made a mistake because the lines never touched, which I think highlights the need for the complementary data points.

We workshopped things I could say to more succinctly describe the data. Folks suggested I use language like "income needed to comfortably afford" or "reasonably afford" the median mortgage. Someone also suggested i get more journalistic with the title, something like: "income required to buy a house grossly outpacing income."


- Who do you think is the intended audience for this?
- homebuyers who are trying to assess the landscape

Results: 

- include another couple of ways to index the dates on the graph
- clean up the title and labels such that it's more intelligble period
- leverage subtitles to clarify the 30% threshold rather than putting it in the label
- maybe include a trendline for the median mortgage payment? might be distracting because the scale is so much lower
- keep the shading between the income where median mortgage doesn't exceed 30% of income and actual median income, maybe include a parenthetical/bracket or arrow situation
- change top line label to "income where median mortgage is affordable"
- "income required to afford median mortgage"



Synthesis: 

_What patterns in the feedback emerge?  What did you learn from the feedback?  Based on this feedback, come up with what design changes you think might make the most sense in your final redesign._

- I learned from the feedback that my approach was generally effective, but needed some stylistic tweaks and less text to really sing.
- For the redesign, I think honing the text, adding a subtitle (similar to the original) and giving the lines pithier labels are going to be key. We also talked about retitling it and adding at least one more increment mark on the x-axis. 


## Step five: build the solution

_Include and describe your final solution here. It's also a good idea to summarize your thoughts on the process overall. When you're done with the assignment, this page should all the items mentioned in the assignment page on Canvas(a link or screenshot of the original data visualization, documentation explaining your process, a summary of your wireframes and user feedback, your final, redesigned data visualization, etc.)._

## References
_List any references you used here._

## AI acknowledgements
_If you used AI to help you complete this assignment (within the parameters of the instruction and course guidelines), detail your use of AI for this assignment here._

