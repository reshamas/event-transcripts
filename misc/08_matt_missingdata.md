

```text
## Upcoming Events
Join our Meetup group for more events!
https://www.meetup.com/data-umbrella

Matt Brems:  Data Science with Missing Data

## Key Links
- Transcript:  https://github.com/data-umbrella/event-transcripts/blob/main/2020/08-matt-brems-missing-data.md
- Meetup Event:  https://www.meetup.com/data-umbrella/events/271243174/
- Video:  https://youtu.be/LJKYXq3WHTw
- Slides:  https://github.com/matthewbrems/missing_data_short_version/blob/master/missing_data_slides.pdf
- GitHub repo:  https://github.com/matthewbrems/missing_data_short_version

## Agenda
00:00 Ty gives the introduction
04:24 Ty welcomes the audience
05:40 About the speaker
06:07 About Data Umbrella
06:49 About the cosponsor PyLadies NYC
07:15 About General Assembly
10:20 Matt gives introductory words
10:54 Matt's biography
11:08 Agenda of the talk
11:38 Part 1: How big of a problem is missing data?
12:28 Matt gives an overview of the notebooks.
13:48 What is the realistic approach for us: Good, fast, cheap?
16:50 Part 2: Strategies for doing data science with missing data
16:58 Avoiding missing data
18:29 Decrease burden on your respondent
20:02 Improve accessibility
21:33 Ignoring missing data
23:30 Before "accounting for" missing data, let's shift our mindset
25:03 How to account for missing data
25:34 What's the difference: Unit vs. Item Missingness
26:49 The unit missingness notebook
30:26 Weighting class adjustments to tackle bias due to missingness
32:54 Pass weights into scikit-learn (sklearn) 
34:08 Use weights for your model
34:42 Decreased bias but increased variance
36:27 Be aware of assumptions.
38:23 Pulling the pieces together in one workflow ...
39:23 Scenario 1: Missing Completely at Random (MCAR)
40:45 Scenario 2: Missing at Random (MAR)
42:33 Scenario 3: Not Missing at Random (NMAR)
43:42 How do we account for item nonresponse?
43:58 Deductive Imputation
45:20 Mean/Median/Mode Imputation
46:22 Mean Imputation
47:25 Why is underestimating variance a bad thing?
50:39 Mode Imputation
51:02 Single Regression Imputation
51:42 Proper Imputation
52:04 The way to properly impute missing data
53:40 Rubin's Rules
54:08 The item missingness notebook
54:15 How do we account for item nonresponse?
54:24 Pattern Submodel Approach
57:00 Final words
 
## Event
If you’ve never heard of the “good, fast, cheap” dilemma, it goes something like this: You can have something good and fast, but it won’t be cheap. You can have something good and cheap, but it won’t be fast. You can have something fast and cheap, but it won’t be good. In short, you can pick two of the three but you can’t have all three.

If you’ve done a data science problem before, I can all but guarantee that you’ve run into missing data. How do we handle it? Well, we can avoid, ignore, or try to account for missing data. The problem is, none of these strategies are good, fast, and cheap.

We’ll walk through advantages and disadvantages of various approaches and cover practical recommendations for integrating best missing data practices into your workflow!

## About the Speaker

Matt currently is a global instructor for GA's Data Science Immersive program across the United States. Matt is a recovering politico, having worked as a data scientist for a political consulting firm through the 2016 election. Prior to his work in politics, he earned his Master's degree in statistics from The Ohio State University and his undergraduate degree at Franklin College in Indiana. Matt is passionate about putting the revolutionary power of machine learning into the hands of as many people as possible. When he's not teaching, he's volunteering with Statistics Without Borders, thinking about how to be a better teacher, falling asleep to Netflix, and/or cuddling with his pug.

LinkedIn: https://www.linkedin.com/in/matthewbrems/
Twitter: https://twitter.com/matthewbrems


```
