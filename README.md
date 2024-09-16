# BUSA90059 - Data Analytics for Decision Making
## Assessment 2
[Andrew Ferris](agferris@student.unimelb.edu.au)

## Gender Diversity and Corporate Board Governance

#### Background
The representation of women in the corporate boardroom has long been a subject of contention, introspection and reform. Historically, women have been notably underrepresented. In the US, as of 2007, women held a mere 14.8 per cent of Fortune 500 board seats. This pattern mirrors global trends, with female representation in director roles even lower in countries like Japan and hovering around 8–10 per cent in Europe, Australia and Canada. Disconcertingly, many firms that do appoint female directors often stop at a tokenistic single appointment, as evidenced by studies showing that a majority of firms with female directors usually have just one. 

Yet, the winds of change are palpable. Legislative initiatives across various nations advocate for gender parity. Norway, for instance, legislated a pioneering and stringent mandate in 2008, requiring listed companies to have 40 per cent of their director seats occupied by women or face dissolution. Similarly, Spain seeks to reach a 40 per cent threshold by 2015. These proactive measures are anchored in the belief that a diversified board is not only morally right but can also influence company governance significantly. 

Several arguments underpin the need for gender diversification in boardrooms. One compelling narrative is the sheer wastage of potential talent. In the UK, even though women represent about 30 per cent of corporate managers, they account for a paltry 6 per cent of non-executive director positions. Moreover, the exclusion of women often perceived as not being a part of the entrenched 'old boys club', poses a question about the genuine independence of board decisions. But, while the moral and ethical arguments for gender parity are universally acknowledged, there is a nascent yet burgeoning inquiry into how gender dynamics affect tangible aspects of corporate governance. One such critical facet is director compensation. As more women break through the proverbial 'glass ceiling', questions arise: Do gender-diverse boards approach director compensation differently than their less diverse counterparts? Are there discernible pay disparities between male and female directors? And, if such disparities exist, what might be the underlying drivers? 

In light of these considerations, we embarked on a comprehensive study, focusing on the bustling corporate entities listed on the Siliconia Stock Exchange (SSE). By examining the top 200 companies on the SSE, we aim to unveil if gender diversity merely amounts to symbolic tokenism or if it has discernible effects on corporate board governance. Our study is inspired by seminal works like Adams & Ferreira (2009), which delved into the impacts of gender diversity on governance and performance. They found that women, interestingly, showcased better attendance behaviors compared to their male counterparts. The study also revealed that women often held roles in crucial monitoring-related committees like audit and governance, though they were underrepresented in compensation committees. 

#### Main Aims of the Study

- Is there any evidence of a gender pay gap among the directors? 
- Are there any firm-level factors that affect the total compensation of directors? 
- Is there any evidence of higher director compensation for firms with higher percentages of female board members? 
- Are there any non-linear effects? 
- What is the most suitable model based on the data given? 
- Are there any limitations of your regression model and possible improvements?

#### Data Decriptions

We collect director-level and firm-level data on the top 200 companies listed on the Siliconia Stock Exchange over the past 10 years. The key outcome variable is the total compensation for each director (measured in thousands of dollars), which is the sum of the annual retainer, the number of board meetings times Board Meeting Fee, and the value of all stock-based compensation (including options that are priced Black-Scholes formula). 

The following firm, board, and director characteristics are also collected: 

Firm-level data: 
- Log(sales) of the company: natural logarithm of sales (in millions of dollars) 
- Stock performance: the firm’s average monthly stock returns (in percentage) 
- Volatility: the standard deviation of the firm’s monthly stock returns (in percentage).

Board-level data:
- Board size: number of directors on the board 
- Fraction of independent directors on the board 
- Fraction of female directors on the board.

Director-level data: 
- Gender dummy = 1 if the director is female 
- Age: age of the director  
- Tenure: the number of years the director has served on the firm’s board 
- Number of other directorships held elsewhere 
- Retired dummy = 1 if the director retired from his/her primary occupation.

The entire data set contains information on 1,756 directors from these 200 companies. 

#### Original Journal Article

The original journal article is contained in the repository [here]().