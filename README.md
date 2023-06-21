# Topics: Confidence Intervals

## 1.	For each of the following statements, indicate whether it is True/False. If false, explain why.

### I.	The sample size of the survey should at least be a fixed percentage of the population size in order to produce representative results.\
Ans: False:
False sample size is not depend on the fixed percentage of popultion size sample size total depend upon number of as per central limit theorem more the number of obsevation in sample it tends to the normal distributionand it depennds on the other factor like confidance interval


### II.	The sampling frame is a list of every item that appears in a survey sample, including those that did not respond to questions.\
Ans: False
It is used to create the sample by selecting a subset of the population to be included in the survey. The sampling frame should ideally be complete and accurate, but it does not include those who did not respond to the survey questions.

### III.	Larger surveys convey a more accurate impression of the population than smaller surveys.\
Ans:  True


## 2.	PC Magazine asked all of its readers to participate in a survey of their satisfaction with different brands of electronics. In the 2004 survey, which was included in an issue of the magazine that year, more than 9000 readers rated the products on a scale from 1 to 10. The magazine reported that the average rating assigned by 225 readers to a Kodak compact digital camera was 7.5. For this product, identify the following:

### A.	The population –>
All the readers of PC Magazine
### B.	The parameter of interest –>\
Population size,Average,Raiting Scale,Sample Size\
### C.	The sampling frame ->\
9000 all readers responded to that survey\
### D.	The sample size –>\
225 readers\
### E.	The sampling design –>\
Rating given or Response\
### F.	Any potential sources of bias or other problems with the survey or sample -> \
Here the data selection process not biased but the data cosidered only among the readers of this Magazine and actually we need the data from all people of diiferent electronic gadget users.

## 3.	For each of the following statements, indicate whether it is True/False. If false, explain why.

### I.	If the 95% confidence interval for the average purchase of customers at a department store is $50 to $110, then $100 is a plausible value for the population mean at this level of confidence.
Ans:  True

### II.	If the 95% confidence interval for the number of moviegoers who purchase concessions is 30% to 45%, this means that fewer than half of all movie goers purchase concessions.\
Ans: False:  A 95% confidence interval means that we can be 95% confident that the true population proportion falls within the interval. Therefore, we cannot infer that fewer than half of all moviegoers purchase concessions based on this confidence interval alone\
### III.	The 95% Confidence-Interval for μ only applies if the sample data are nearly normally distributed.\
Ans: False: for 95% confidance interval we have to assume that sample size will be more as per the centrl limt theorem if sample size is not much more and data is not distributed then we consider as a t statistical test

## 4.	What are the chances that  ?

A.	¼ 
B.	½ 
C.	¾ 
D.	1
Ans: B (This is only an assumption, because if we consider more than 50% for sample mean to be greater than the probability of getting a lower value gets overshadowed because sample mean has an equal chance to be lesser than population mean)

## 5.	In January 2005, a company that monitors Internet traffic (WebSideStory) reported that its sampling revealed that the Mozilla Firefox browser launched in 2004 had grabbed a 4.6% share of the market.

### I.	If the sample were based on 2,000 users, could Microsoft conclude that Mozilla has a less than 5% share of the market? \
Ans: No \
As the p Value > alpha for 95% confidence we failed to reject null hypothesis
Ho: > 5% null hypothesis

### II. WebSideStory claims that its sample includes all the daily Internet users. If that’s the case, then can Microsoft conclude that Mozilla has a less than 5% share of the market?\
Ans: Yes



## 6.	A book publisher monitors the size of shipments of its textbooks to university bookstores. For a sample of texts used at various schools, the 95% confidence interval for the size of the shipment was 250 ± 45 books. Which, if any, of the following interpretations of this interval are correct?

### A.	All shipments are between 205 and 295 books. +>\
Incorrect
95% of the time the size of the shipment will be around 250 +/- 45 books

### B.	95% of shipments are between 205 and 295 books. => Correct

### C.	The procedure that produced this interval generates ranges that hold the population mean for 95% of samples. => Correct

### D.	If we get another sample, then we can be 95% sure that the mean of this second sample is between 205 and 295. => Correct

### E.	We can be 95% confident that the range 160 to 340 holds the population mean. => Incorrect: as we increase the range +/- 1 sigma the % of confidence increases for a normal distribution it will be 97.5% that the mean will lie in between 160 to 340 (-3 sigma to +3 sigma)


## 7.	Which is shorter: a 95% z-interval or a 95% t-interval for μ if we know that σ =s?

A.	The z-interval is shorter\
B.	The t-interval is shorter\
C.	Both are equal\
D.	We cannot say\
Ans: the T interval is shorter This is because the t-distribution has fatter tails than the standard normal distribution, and so the t-interval will be more conservative than the z-interval.

# Questions 8 and 9 are based on the following: To prepare a report on the economy, analysts need to estimate the percentage of businesses that plan to hire additional employees in the next 60 days.

## 8.	How many randomly selected employers (minimum number) must we contact in order to guarantee a margin of error of no more than 4% (at 95% confidence)?

A.	600\
B.	400\
C.	550\
D.	1000\
Ans: A
Error=z/((p*q)/sqrt(n))
n=(Error)^2(p*q)/z

phat=0.5

q=0.5

CI=0.95

alpha=1-CI

z_value=stats.norm.ppf(alpha/2)

z_value

n=(((z_value)**2)*0.5*0.5/(0.04)**2)

round(n)

## 9.	Suppose we want the above margin of error to be based on a 98% confidence level. What sample size (minimum) must we now use?

A.	1000\
B.	757\
C.	848\
D.	543\
Ans: C

phat=0.5

q=0.5

CI=0.98

alpha2=1-CI

z_value2=stats.norm.ppf((alpha2)/2)

z_value2

n=(((z_value2)**2)*0.5*0.5/(0.04)**2)

round(n)
