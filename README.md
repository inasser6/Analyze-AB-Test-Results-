
# Analyze A/B Test Results
A/B tests are very commonly performed by data analysts and data scientists. It is important that you get some practice working with the difficulties of these.

For this project, we will be working to understand the results of an A/B test run by an e-commerce website. The company has developed a new web page in order to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product. Your goal is to work through this notebook to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.

The data and the Jupyter Notebook, which are all of the files you need to complete the project, are provided for you in a downloadable zip file in the resources tab (as well as under "Supporting Materials" below). Note that portions of the notebook reference back to quizzes that are linked in this lesson to ensure you are on the right track.

# Part I - Probability:
* in the control group, what is the probability they converted?
* in the treatment group, what is the probability they converted?
* What is the probability that an individual received the new page?
# Part II - A/B Test:
  Notice that because of the time stamp associated with each event, you could technically run a hypothesis test continuously as each observation was observed.
However, then the hard question is do you stop as soon as one page is considered significantly better than another or does it need to happen consistently for a certain amount of time? How long do you run to render a decision that neither page is better than another?
These questions are the difficult parts associated with A/B tests in general.
# Part III - A regression approach:
In this final part, you will see that the result you achieved in the A/B test in Part II above can also be achieved by performing regression.

