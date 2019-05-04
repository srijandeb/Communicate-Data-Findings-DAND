# Communicate-Data-Findings-DAND

# What Is PISA?
The Program for International Student Assessment (PISA) is a system of international assessments that allows countries to compare outcomes of learning as students near the end of compulsory schooling. PISA core assessments measure the performance of 15-year-old students in mathematics, science, and reading literacy every 3 years. Coordinated by the Organization for Economic Cooperation and Development (OECD), PISA was first implemented in 2000 in 32 countries. It has since grown to 65 education systems in 2012.

## What PISA Measures
PISA’s goal is to assess students’ preparation for the challenges of life as young adults. PISA assesses the application of knowledge in mathematics, science, and reading literacy to problems within a reallife context (OECD 1999). PISA does not focus explicitly on curricular outcomes and uses the term “literacy” in each subject area to indicate its broad focus on the application of knowledge and skills. For example, when assessing mathematics, PISA examines how well 15-year-old students can understand, use, and reflect on mathematics for a variety of real-life problems and settings that they may not encounter in the classroom. Scores on the PISA scales represent skill levels along a continuum of literacy skills.

Each PISA data collection cycle assesses one of the three core subject areas in depth (considered the major subject area), although all three core subjects are assessed in each cycle (the other two subjects are considered minor subject areas for that assessment year). Assessing all three subjects every 3 years allows countries to have a consistent source of achievement data in each of the three subjects, while rotating one area as the primary focus over the years. Mathematics was the major subject area in 2012, as it was in 2003, since each subject is a major subject area once every three cycles. In 2012, mathematics, science, and reading literacy were assessed primarily through a paper-and-pencil assessment, and problem solving was administered via a computer-based assessment. In addition to these core assessments, education systems could participate in optional paper-based financial literacy and computer-based mathematics and reading assessments. The United States participated in these optional assessments. Visit www.nces.ed.gov/surveys/pisa for more information on the PISA assessments, including information on how the assessments were designed and examples of PISA questions.

# Introduction to the PISA 2012 dataset
PISA is a survey of students' skills and knowledge as they approach the end of compulsory education. It is not a conventional school test. Rather than examining how well students have learned the school curriculum, it looks at how well prepared they are for life beyond school.

Around 510,000 students in 65 economies took part in the PISA 2012 assessment of reading, mathematics and science representing about 28 million 15-year-olds globally. Of those economies, 44 took part in an assessment of creative problem solving and 18 in an assessment of financial literacy.

# Assumptions and steps taken during data exploration

After looking throughout the Dataset Dictionary to find out what each of these columns represents, a number of leads to be explored have been considered:

We are interested in finding out how students from individual countries perform in Math, Reading and Science literacy.

For that, we will check the average world and country-wide distribution of Math, Reading and Science literacy scores, individually.
Considering that we can see the countries' average literacy patters in different subjects, we are also curious about from which countries do the "geniuses" stem, meaning which countries have students with exceptionally high literacy scores.

For that, we will check the distrbution of exceptional scores in Math, Reading and Science literacy, grouped by country.
Lastly, we would like to find out whether students whose parents have different cultural backgrounds will report any changes in average scores, compared with students raised in a homogenous family background.

For that, we will compare the distribution of mean scores in each subject across both students with homogenous family background (parents born in same country) and students with heterogenous family background (parents born in two different countries).

# Summary of your main findings
After investigating the dataset and visualizations, we have found out the key summaries:

How do students from individual countries perform in Math, Reading and Science literacy?

* We have found the literacy trends for each country in part, along with countries with high deviations in scores compared to the norm. The results can be explored in Visualisation 4 and 8.
What are the countries from which "geniuses" stem, meaning which countries have students with exceptionally high literacy scores?

* Generally, we have seen Asian countries as being the world leaders at educating students who perform exceptionally, not only in each different subject individually, but also at multiple subjects simultaneously. Singapore and China are examples of this.
Do students whose parents have different cultural backgrounds report any changes in average scores, compared with students raised in a homogenous family background?

* We have discovered that students whose parents are from two different cultural backgrounds report, on average, slightly higher performance (scores) in all three measured subjects.

# Key Insights used for your presentation deck

From all the visualizations, I have pointed out the Key insights which are mentioned below:

* Math Score, Reading Score and Science Score - all cases the highest frequency range is between 300-600, genius students i.e greater than 600 marks lies under 50000 benchmark and poor quality students i.e. below 300 score lies under 20000 benchmark
* Maximum Students lies between 400-500 score range which means the PISA data is very much balanced
* Oceania and Asian countries, in particular China and Singapore, seem to be the places where exceptional students are most likely to stem from
* Singapore is the clear leader in excellency, since it manages to reach within the top 3 countries with most exceptional students in all three areas of study
* Korea and Australia also have a respectable number of excellent students in both Math and Science
* Besides Asia and Oceania, a number of European and North American countries also make the podium: Canada is present in all three of the above distributions, while Poland, Czech Republic and Switzerland appear to be educating Math-bright students
* Most countries seem to achieve, in different subjects, rankings which are close to each other, with 80% of countries reaching rankings within 10 places higher/lower across all the subjects. The remaining 20% of countries with large deviations will be analyzed further on, as we would like to find out in what subjects are they deviating and how large is the difference
* From the top ranking of countries, we can clearly see that it was no coincidence that exceptional students come from Asian countries, in particular China and Singapore, as these are the countries which are 1st, 2nd or 3rd place across all subjects. Another country which impressed was Poland, with 3 exceptional students in Mathematics. Here, it can be seen that this is no coincidence either, as Poland occupies a spot in the top 10 placements in Reading and Science, and 11th in Mathematics
* The box-and-wiskers plot allows us to see the outliers in scores for each country in part. For example, we find out that, even though a number of Singapore's students managed to achieve outstanding results in the field of Mathematics, that is not to be considered "out of ordinary" (or, with other words, as outliers) in the country's perspective, however the outstanding results received in Science can be indeed considered to be slightly out of regular bounds, since we can notice the Singapore's outliers in the plot
* Other such findings can be performed by picking a country of interest and checking its score distribution, rankings and outlier distribution accordingly
* Singapore leads in the world ranking of multi-talented outstanding results, being the only one country present in all three possible combination of two talents. Coupled together with previous findings of Singapore's on-average and above-average student results, we can determine that its country is world-leader in providing multidisciplinary high-quality education, across all measured disciplines.
* China is once again present in the rankings, together with (South) Korea, determining that, as said about Singapore, such countries have a very high quality of education in the measured fields. The connection between all previous visualizations of scores determine that such outstanding results are not simple coincidence, but only slightly-higher than average results compared with these countries' mean of scores.
* There were no students who have managed to reach scores above 800 in all three subjects simultaneously, which is why there is no further visualization on this matter.






