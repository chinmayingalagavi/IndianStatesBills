# IndianStatesBills
Dataset of legislature passed by Indian States from 1962.

I scraped the Parliament of India Digital Library for all available copies of its periodical "Journal of Parliamentary Information". In each edition, one of the appendices carries the list of bills passed by state legislative houses. I used the OpenAI API to parse these documents and created a CSV. 

I couldn't find any public dataset with a list of bills passed by Indian states, so I created this for my Economic History paper. Note that the first edition with such a list is from 1962.

No guarantee of accuracy. A few entries are definitely missing. Some because they are missing from the library, and some because the AI parsing was not perfect. But from my inspection it is >98% credible.

The passing body, either 'Legislature', 'Legislative Assembly', or 'Legislative Council', is taken directly from the data. It seems to use 'Legislature' for states with unicameral legislatures, and specifies the house for bicameral legislatures. However this format is not consistent, and I have seen editions of the document use 'Legislature' for years in states that I know for a fact had bicameral legislatures.
