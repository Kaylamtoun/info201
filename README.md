# info201
# Assignment 1: Protests
In recent years the United States has experienced a surge of protests, in support of Black Lives Matter, gender equity, and other social or political issues.

In this assignment, you will work with data from [Count Love](https://countlove.org/), data that is often [cited](https://www.nytimes.com/2020/08/28/us/black-lives-matter-protest.html) by the _New York Times_ when reporting on US demonstrations.

## Learning objectives
By completing the assignment, you will demonstrate the following skills:

- Use of **version control** for managing your code
- Declaring document rendering using **markdown** syntax
- Foundation programming skills in R
- Critical think about data.

## The Assignment
**Instructions and grading**. Assignment instructions, and grading information,
are available in this file: [analysis.R](analysis.R).

**Eight assignment parts**. The file [analysis.R](analysis.R) consists of eight parts.

* Parts 1-6 require you to code in R.
* Part 7 prompts you to critically think about the Count Love dataset.
* Part 8 prompts you to consider your learning.

**Coding and reflection prompts**. You will find two kinds of prompts in [analysis.R](analysis.R):

* *Coding prompts*, which prompt you to write R code in [analysis.R](analysis.R).
* *Reflection prompts*, which prompt you to write responses below
in this file (`README.md`).

**Formatting Your Responses and Reflections**.

* When formatting your written
responses and reflections below, please *retain* all
reflection prompt IDs (e.g., (R.1a), (R.2a), etc.).
* To write clearly,
use markdown code - for example, use **bold**, _italics_, and `code` appropriately; include images or links (if useful); and so forth.

**Getting started**. To get started, we suggest that you open [analysis.R](analysis.R) in RStudio
and open this file in Atom. Or, you might find it more convenient to open
both files in RStudio and flip back and forth with the tabs.

Key point: In [analysis.R](analysis.R), write R code; in this file below,
write in English.

**Questions?** As always, please post on Teams or ask your Instructor or Teaching Assistant.

:computer: Good coding!
   :writing_hand: Good critical thinking!
      :smile: Good-luck!

(_Updated: January 15, 2022, David Hendry_)

Answer Below:

## Your Responses and Reflections
* **(R.1a)** **Count Love** is an online resource that takes into record the thousands of protests that occurred in the United States starting from January 2017 to as recent as January 2021. Count love extracts information on protests/demonstrations that occur in different states and even further to each city. The creators of Count Love do constant research going thru newspapers and television sites to update the data on the website.

#### Social Movements
* **(Article #1)** [**Black Lives Matter May Be the Largest Movement in U.S. History** by _The New York Times_](https://www.nytimes.com/interactive/2020/07/03/us/george-floyd-protests-crowd-size.html)
* **(Article #2)** [**We Cannot Fight Anti-Asian Hate Without Dismantling Asian Stereotypes** by _The New York Times_](https://www.nytimes.com/2021/06/15/learning/we-cannot-fight-anti-asian-hate-without-dismantling-asian-stereotypes.html)

#### Part 2: Attendees
* **(R.2a)** The mean is the average of all data combined. The median represents the middle number of the data. The difference between the mean and the median tells me that the data is skewed to the right. This is because the mean of the dataset is approximately **644** and the median of the dataset is **100**. The data has an uneven frequency because the mean is larger than the median.

#### Part 3: Locations
* **(R.3a)** The total number of protests in Washington according to the Count Love data is **1,375**. This data does not surprise me because especially with the recent uprising of the Black Lives Matter movement and Stop Asian Hate there have been more demonstrations and protests in my community. Most recently in 2020 and 2021 I planned and participated in a Black Lives Matter and Stop Asian Hate protest at my old High School.
I think with more people realizing the oppression and hate minorities receive there would be more protests occurring. Here are the articles about the two demonstrations I helped plan and participated in. [**Seattle rally Saturday calls for end to anti-Asian hate crimes and violence** by _The Seattle Times_](https://www.seattletimes.com/seattle-news/seattle-rally-saturday-calls-for-end-to-anti-asian-hate-crimes-and-violence/) [**Calling to reforms to police and education, Seattle students flood the streets to protest** by _The Seattle Times_](https://www.seattletimes.com/seattle-news/education/calling-for-reforms-to-police-and-education-seattle-students-flood-the-streets-to-protest/)


* **(R.3a)** I think the sapply() function in R is powerful because it takes in data and returns a vector.

* **(R.3b)** While looking at the States table, I noticed that some of the state’s abbreviations are capitalized while some are not. For example for the state of **Idaho** it is **iD** instead of **ID**. A way I would change my analysis would be to filter out the state abbreviations that are not capitalized to ensure everything is the same.

#### Part 4: Dates
* **(R.4a)** The change in the number of protests does not surprise me because with everyone becoming more aware of protests and social media being a way to share information quickly people would more likely participate. Also from **2019** to **2020** The world drastically changed such as our world going through a pandemic in 2019 to the 2020 presidential election, which created an uprising among people living in the United States. These events would ultimately result in more protests.

#### Part 5: Protest Purpose
* **(R.5a)** The words that occur most with the `high_level_table` are **Immigration** and **Civil Rights.** The picture that is painted about the U.S. reflects on what U.S. protesters care for and want to advocate for.

#### Part 7: Critical Thinking
**(R7.a)**

* **Goals**: Count Love was started in 2016, by Tommy Leung and Nathan Perkins. The goal of Count love is to provide factual data and information about protests that occur in the U.S. Count Love aims to make data accessible to citizens, journalists, politicians, and more. Count love provides a way of communication between people and U.S. elected officials.
* **Human Values**: The data on Count Love aims to help amplify the voices of protestors while also providing a reliable and easy to navigate data sources. Count Love makes finding factual information about protests or demonstrations easy for the everyday citizen.  
* **Data sources**: The protest data on Count Love derives from the local newspaper and television sites using key words to review articles. To ensure the data is credible, Count Love creators group similar articles together and use a method called Bayesian Filtering that generates a score that helps them decide to keep or reject an article. Count Love uses tools, heuristics, and machine learning techniques in their article review process.
* **Direct stakeholders**: The direct stakeholders are everyday citizens, students, researchers, and much more. The skills that are needed are a simple background on protests and the motivation in using Count Love is to find data about protests in the U.S. Count Love does not make money.
* **Indirect stakeholders**: The indirect stakeholders of Count Love could be the actual protestors themselves. Even though Count Love does not take into account names or personal information they still have an approximate of how many protestors attend. Some protestors want to make it loud and clear they are demonstrating while others may want to keep it private.

* **Benefits and harms**: The potential benefits of Count Love is educating and collecting valuable information about protests. Cities, towns, or counties officials might want to review protest data to see what people are protesting and advocating for and listen to the voices. Count Love is also an important resource because users may see a trend in where protests occur so they might want to participate as well.  The potential harm of Count Love is not having the most up to date and accurate information, though Count Love uses sorting systems to make sure articles and information about protests are reliable and credible there can always be mistakes or missing information.

* **Summary on power**: Count Love uses and resists **power** to amplify protestors’ voices and collect all data about protests in the U.S.  To make Count Love even more stronger it would be beneficial for the Count Love creators to connect with users, get feedback, and also even witness the protest first hand. Allowing protestors to be involved with Count Love would make it an even more powerful resource resulting in Count Love being a power for good.

#### Part 8: Your Learning
* **(R.8a)** What I found most challenging was creating the function. The most interesting thing I learned was the data about protests in Washington state, it made me more curious to find out if there are more protests in bigger cities in Washington such as Seattle compared to other cities or towns. I think it would be valuable to learn about how long a protest persists. For example, during the Black Lives Matter movement, there were protests going on everywhere happening for a different duration of time. Finding out how long or how many days a protest persists would be valuable and add more to the Count Love data set.
