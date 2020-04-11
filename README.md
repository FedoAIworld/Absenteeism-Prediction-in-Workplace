# Absenteeism_Prediction_in_Workplace
# Introduction
Absenteeism is the term given when an employee is habitually and frequently absent from work. This excludes paid leave and occasions where an employer has granted an employee time off.

This task will address Absenteeism at a company during work time.

Problem: Business environment nowadays is more competitive than it used to be. This lead to increased pressure in the workplace. Therefore, it is reasonable to expect that unachievable business goals and an elevated risk of unemployment can raise people's stress levels. Often, the continuous presence of such factors becomes detrimental to a person's health. Sometimes this may result in minor illness which of course is not desired. However, it may happen that the employee develops a long-term condition. An example being depression.

# Looking at predicting absenteeism from work.
We would like to know whether or not an employee can be expected to be missing for a specific number of hours in a given work day.
Having such information in advance can improve our decision-making. How? by re-organizing the work process in a way that will allow us to avoid a lack of productivity and increase the quality of work generated in our firm.

Logically here come some additional questions based on what information should we predict whether an employee is expected to be absent or not.
How would we measure absenteeism?
Should we rather think about trying to predict excessive absenteeism?
Just remember that as a whole the purpose of the business task will be to explore whether a person presenting certain characteristics is expected to be away from work at some point in time or not.
In other words, we want to know for how many working hours an employee could be away from work based on information such as how far they live from their workplace? How many children and pets they have? Do they have higher education? and so on.

# Visualization and insight
# Age vs Probability

![](Tableau_visaulization/Age vs Probability.png)

From the figure, we can clearly see that employees with age 40 years and below absent from work for more three hours.
For instance, there's a 59 percent chance that an employee who is 28 years will be absent from work for more than three hours.

# Reason vs Probability

![](Tableau_visaulization/Reasons vs Probability.png)

We can see all reasons contain data for both values 0 and 1 except for reason 2.
None of the employees (from our 40 observations) were away from work. For this reason, it is removed from the analysis since it provides less information on our dataset.
If a person is supposed to be absent due to a reason from Group 1 as marked by the dots associated with the value of 1 the probability that she will be excessively absent is above 50 percent.
Hence such an individual is expected to be away from work for more than three hours whereas when we look at a Reason 3 we must consider the very few observations of people who had specified this reason for excessive absence as well as the fact that the probabilities have been distributed both in the lower and upper parts of the vertical line.
That's why we could say that.
Similarly, to reason 2 this class doesn't tell us much about what to expect from individuals being absent because of a reason from Group 3.
Finally reason 4 leads us to an opposite conclusion compared to reason one.
The people who are absent because of reason 4 absence exhibit a probability below 50 percent to be excessively absent.
And now if we want to extend our analysis by adding a qualitative interpretation of the results what should we say for groups 1 and 4? Do our numerical inferences match any business logic and can they have a more intuitive explanation?
The reasons included in group 1 without disrespecting all other reasons the ones we have here represent very serious diseases. That's why the numbers tell us that the expected probability of an individual to be excessively absent because of a reason from this class is higher than 50 percent.
How about group 4?
It represents what we've called less-serious reasons for absence a dental appointment, physiotherapy, a medical consultation and others.
When you think of it is quite probable that none of these could be serious enough to require that a person is absent from their workplace for an entire day. That's why the numbers show that people who have to be absent for such a reason are not expected to be excessively absent as you can see the probability values are all below the mark of 50 percent.

# Transportation Expense and Children

![](Tableau_visaulization/Transportation Expense and Children.png)

We would like to see the probability that a person will be excessively absent from work in relation to the transportation expense they must cover each month as well as to the number of children they have.
Although loosely we could say that there is a positive correlation. Perhaps if we were given a data set containing more observations this correlation would have been stronger.
Then we could say with certainty that the higher the transportation expenses of a person the higher the chance they will be away from work excessively good.
Looking at the data further, it turns out people with no children don't exhibit a high probability for excessive absence. Also aside from one small exception none of them have high transportation expenses.
Perhaps there is nothing that would induce these people live further away from their working place.
We have a lot more data in this case (1 child) the probability that this group is expected to be excessively absent varies across observations. However, most of the data is clustered around the average transportation expense spending between $220 and $240 a month.
What about people with two children?
If we disregard the values clustered around the centre the distribution is similar. Thus we could say that our data is about people who don't generally spend more than $240 on transportation. Only 5 observations lay beyond this cut-off line.
Just one individual has 3 children. In other words, this category can't really affect the analysis of the 40 observations we have. Therefore, it is excluded from the analysis.
