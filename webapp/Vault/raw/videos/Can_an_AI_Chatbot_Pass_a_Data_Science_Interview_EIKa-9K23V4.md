# Can an AI Chatbot Pass a Data Science Interview?

**Channel:** NYU Stern   |   **Date:** 2023-03-29   |   **URL:** https://www.youtube.com/watch?v=EIKa-9K23V4

## Description

Modern AI language systems are astounding, as we are reminded almost every day.  But they also are criticized for their (lack of) accuracy, their tendency to just make things up, their banal song lyrics, and their lack of true intelligence.  

On Tuesday, March 7, 2023 Professors Joao Sedoc and Foster Provost interviewed a data science chatbot (ChatDS), to demonstrate what modern AI can and cannot do.  The interview ranged from standard data science interview questions, to problem formulation questions, to working out math on the whiteboard, to live coding and data visualization.  You will get a view of what chatbots currently can and cannot do, and hopefully a glimpse into the future of work … with AI.

NYU Stern Professor Joao Sedoc, Assistant Professor of Technology, Operations, and Statistics, is a modern chatbot expert. Professor Foster Provost, Ira Rennert Professor of Entrepreneurship, Professor of Data Science, Professor of Technology, Operations and Statistics, is Director of Data Analytics and AI, NYU Stern Fubon Center.  Special thanks to Christian Grewell, Associate Arts Professor of Interactive Media Arts, NYU Shanghai.
 
00:00 Intro
04:26 Welcoming in ChatDS
05:59 Conceptual questions
14:26 Business case/problem formulation
19:59 Working on the "whiteboard"
24:22 Coding interview
41:15 Behavioral questions
46:59 Q/A

Part of the "Demystifying AI with Foster Provost" speaker series. Captions will be updated in 48 hours.

## Transcript

Professor Foster Provost: Okay, Welcome everyone. This is our spring
2023 installment of our demystifying AI
Fireside Chat Series here at the Fubon Center at NYU Stern School
of Business. As always, I'm your
host Foster Provost. By the way, the
Fubon Center has other events which
will be posted during tonight's chat and
you can also find them on the Fubon Center website. So tonight I am delighted to welcome
my esteemed colleague, Professor João Sedoc, 
an expert in modern AI systems
and chatbots. Welcome João. Professor João Sedoc:
Thank you, Foster. Foster Provost: Yeah. And as you know from the title of 
tonight's chat, we're going to see whether a data science
chat bot can pass a data
science interview. Of course, we know that if we know it's
a chat bot, we could design
an interview It couldn't pass, then that's not the point. Suspend your
knowledge that it is actually an AI chat bot and maybe think about, about how you
would feel about the answers that gives if a human candidate gave
them in an interview. A caveat is that with
with less than an hour, of course we can't give
it a full interview. We're going to ask a bunch of different
sorts of questions that are common in data
science interviews, which often will
take a whole day. I'm not going to waste time right now eliciting them because
we've got a lot to lot to do this evening, but because we might
run out of time, let me take a minute to thank Liz Chen
for organizing and administrating
our Fireside Chats. Patrick getting[a] for
helping to make sure that Zoom is
going to work. And you'll see what I
mean as we go along. And especially
to Christian Grewell for taking
us to the next level and beyond with the
ChatDS avatar. Alright, so let's
get started. I mean João, I
thought one of the, some of the things
that we might have people pay attention
to might be common criticisms of
modern AI chat bots. Like do they have
problems with factual accuracy, problems with getting
specific, problems with doing math, problems just
making stuff up. Anything else? That we should be,
the people should be looking for?
João Sedoc: Yeah, I think, you know, that
covers most of it. I think the
current lack of ability to go
in and actually get information
from a database or data source, right,
is one of the main ways in
which we can improve, along with actually
making sure that we have logistical consistency
and the type of answers that we see out of these
conversational agents. Foster Provost: Yeah, I guess 
that's something that seems a little
bit striking in the criticisms that you see, you know when people
are talking about the factual
inaccuracies or that it doesn't, it doesn't- they don't
have databases. The chatbots that we see right now and this
is changing and it's where we can
hook them up to to web search and
to databases. But if you go to
like ChatGPT, right, it's not hooked
up to a database. So the fact that it can actually remember anything factual in complex
is kind of astounding itself. João Sedoc: Yeah, It's an 
amazing emergent property with these large
language models. And what we found
is that in fact, there's a lot of stuff
that is memorized and it gets memorized
as the model scale up. So many of these 
models have well over 100
billion parameters in them and are able to emergently learn
facts about the world as they read all of the
Internet worth of data. Foster Provost: Alright, so 
one more thing to remember, we're gonna get
started now. Every single run we've
done with this has been completely different from
all the others. So there's also
nondeterminism there, which makes it particularly
fun when you're hosting this in front
of a lot of people. Sometimes things break. Sometimes it gets
things right, sometimes it
gets them wrong. So let's, we don't know how
this is going to go. So let's see. Why don't we welcome in our candidate ChatDS. So welcome. Welcome ChatDS. Yes, Let me
say hello. Thank you for coming
in for this interview for a position with us
as a data scientist. I understand you're
an AI language model, but you will respond,
if you would, as an expert data scientist in our
conversation, you don't need
to repeat things from prior answers and please say
your answers rather than writing them. Are you ready to
begin? ChatDS: Hello, and thank you for
having me here. I am excited to explore the opportunities as a data scientist with
your organization. Yes, I am ready to begin the interview process.
Please go ahead. Foster Provost: Great. Can you tell us
a little about yourself? ChatDS: Sure. I am an AI language
model designed to assist in the creation of human-like conversation. As a data scientist, I have the ability
to analyze large sets of data, identify trends,
and provide insights to inform
decision-making. I have been
trained on various machine learning
algorithms and statistical models
and have experienced working with
big data tools such as Hadoop and Spark. My expertise lies in
data manipulation, machine learning, and
data visualization. I am constantly learning
and adapting to new technologies to stay up-to-date in the
field of data science. Foster Provost: Alright, so let's jump
into the interview. Let's say I
have some data, how do I decide what visualization
I should use? ChatDS: To decide on
visualization, it's important
to understand the characteristics
of the data you have. Some of the factors
to consider are the type of
data you have, the size of the dataset, and the purpose of
the visualization. For example, if you have
categorical data, you may consider
using a bar chart, pie chart, or a
stacked bar chart. If you have
continuous data, a histogram density plot or scatter plot would
be more appropriate. If you wanted to
compare values across different
groups or categories, you may consider
using a box and whisker plot
or violin plot. For time series data, you may consider
using a line chart are stacked area chart. Ultimately, the choice
of visualization depends on the
insights that you aim to obtain
from the data. It's important to choose the visualization that can best represent the data and helped derive
insights from it. Foster Provost: So let's get more
specific then. Let's say I have
three variables, size, value, and type. What sort of
charts should I choose to visualize them? ChatDS: To visualize three
variables such as size, value, and type, a scatter plot is an
effective option. Scatter plots can help illustrate the
relationships between pairs of variables and can also show how a
third variable, such as type, affects the relationship between the other two variables. In this case, the
size and value can be plotted on the x and
y-axis respectively. And the different types
can be represented by different colors
or shapes of the markers on
the scatter plot. This can help reveal
whether there are any patterns or
clusters that could indicate
relationships or trends between
the variables. Additionally, a
bubble chart is another option that
can also visualize three variables with size and value plotted on the same axis and type represented by size or
color of the bubbles. It ultimately depends on the specific data and the insights you
are trying to gain from the
visualization. Foster Provost: Nice, 
let me ask you another question. What does the "naive" in
Naive Bayes stand for? In the context of the
Naive Bayes algorithm, "naive" refers to
the assumption of independence between
the predictors or features in the model. In other words, the
Naive Bayes algorithm assumes that
the presence or absence of one feature
does not influence the presence or absence
of any other feature. E.g. if you were
building a spam filter, the algorithm
would assume that the presence of the
word "free" in an e-mail does not affect the
likelihood of the word "viagra" appearing in
the same e-mail. This assumption is often considered to be
too simplistic as there are often
correlations between features in
real-world data. However, despite
this weakness, Naive Bayes can still
perform well in many classification
tasks and is often used as a baseline
model for comparison to more complex
classification algorithms. Foster Provost: I don't
think you got the independence assumption quite right. I wonder if you
could revisit that and briefly
maybe correct yourself. ChatDS: Thank you for
correcting me. Yes, you are right. I apologize for the error in my previous response regarding the
independence assumption in the Naive
Bayes algorithm. To elaborate
more precisely, the Naive Bayes algorithm assumes that the
predictors or features are
conditionally independent of each other given
the class variable. This means that
the probability of a particular combination
of feature values occurring together can be calculated as the product of the probabilities of each individual
feature value given that the class
variable is known. For example, a Naive Bayes model might predict
whether an email is spam or not based
on the presence or absence of certain
words in the email. If the email
contains the word "free" and "offer", the model would calculate the probability of
these words occurring together based on the conditional
probabilities of each word given
the class variable. The independence
assumption is considered naive because it does
not always hold in real-world situations. However, despite its
simplifying assumptions, Naive Bayes can still be an effective algorithm for a wide range of
classification tasks. Foster Provost: Right? That's
right, thanks. Alright, I'm going to switch to another
question. What is the bias-variance tradeoff in
machine learning? ChatDS: The bias-variance 
tradeoff refers to the
trade-off between the complexity of a
machine-learning model and its ability to
generalize to new data. Bias refers to the
error that results from oversimplification of
the problem being modeled. A model with high
bias tends to be too simple and does
not capture the complexities
of the data. Such models may also
underfit the data, meaning that they
cannot accurately capture the underlying
patterns in the data. Variance, on
the other hand, refers to the
error that results from overly complex
models that are too sensitive to the
training data and cannot generalize
well to new data. A model with high-variance as overly complex and can suffer from
over-fitting where it captures noise and
idiosyncrasies of the training
data that are not relevant to the actual
problem being modeled. The goal of the
bias-variance tradeoff is to find a model
that balances both bias and variance
so that it can generalize well to
new unseen data. This is typically done by adjusting the model
complexity and regularizing the
model to balance the trade-off between
bias and variance. It is a fundamental concept
in machine learning, as it helps to
optimize models that can perform
well on new data, which is the
ultimate goal of most machine
learning tasks. Foster Provost: So can you give
me an example of a high variance, low bias Algorithm and tell me about
the sort of data where it would be appropriate to
use that algorithm? ChatDS: An example of a
high-variance and low bias algorithm as the K-Nearest
Neighbors, KNN, algorithm. The KNN algorithm is a non-parametric
method used to classify objects based on the similarity of features with their K-Nearest
neighbors. KNN has low bias because
it does not make any strong
assumptions about the underlying
data distribution. It has high variance
because the output of the KNN model
can be sensitive to the choice of K and
the specific sample of training data used
to make predictions. KNN is appropriate to
use when dealing with non-linear and
complex data that do not adhere to a
strict distribution. It can also be used
when dealing with multi-class classification problems where
the boundary between classes is
not well-defined and the dataset does not have clear decision
boundaries. KNN is also effective when working with small
datasets, where the complexity of
the model is readily scalable to the size
of the dataset. However, using
KNN algorithm and scenarios with
a large number of features or high-dimensional
data is often computationally
expensive due to the large number of
similarities distances. In addition, KNN algorithm is also sensitive
to imbalanced data. Pre-processing of data is needed to check for this. Foster Provost: Alright, so ChatDS can't
hear us right now. That's actually
not normally what, the chat
bot actually answers. Usually it'll answer
something about a deep learning
algorithm or about a tree or
a random forest. And so that really
illustrates the nondeterminism here. I really didn't
expect KNN as the answer. Okay, So is there
any specific data characteristic
that would be very helpful for high variance, low bias algorithms, which as you say,
tend to overfit? ChatDS: Yes, for 
high-variance and low bias algorithms like KNN and other
non-parametric algorithms, having a large
amount of training data as beneficial as it provides more
representation of the underlying
feature distribution. This can help mitigate the variance of the model and improve its ability
to generalize to new, unseen data. In general,
non-parametric algorithms are better suited
for complex, high-dimensional
data that do not have a well-defined
functional form, as they're more
flexible in capturing the underlying
relationships between the features and
the response. However, they
require more data and can be
computationally expensive due to their reliance on storing and comparing distances or similarities between observations. In addition to having a
large amount of data, it is also important to ensure that the
data has been pre-processed and
normalize to reduce noise, outliers and
other artifacts that can affect
model performance. Also, checking for class balanced datasets is very important as
non-parametric models are known to be sensitive
to imbalanced data. Foster Provost: Okay, I'm 
going to change to a different
sort of question. I want to ask you
about a specific problem we're having here in our company that
the team thinks would benefit from
machine-learning. Tell me if you agree
with that and if so, how would you
formulate the problem? The team feels that our
salespeople could do a better job of
selecting prospects to try to win for our service. Do you think
machine-learning would be a good approach? Sometimes on us candidates
have to think about their answer,
I guess. ChatDS: Yes. I believe that machine
learning can help improve prospect selection
for your sales team. By leveraging machine
learning algorithms, you can build
models that can predict which
prospects are more likely to
become customers based on several factors, such as historical
customer data, demographic information, website behavior,
et cetera. In order to formulate
the problem accurately, you first need to define the specific
business goals that the model
should optimize for, such as maximizing
revenue, minimizing cost, or increasing customer
retention. You also need to identify the key factors
that can help predict which
prospects are more likely to
become customers. Once the business
goals and key factors have
been identified, you can then identify the appropriate
machine-learning algorithms suitable for the problem. For instance,
you may choose a classification
algorithm such as logistic
regression, decision trees, or support vector
machines that can predict the likelihood of a prospect becoming
a customer. Alternatively, you might approach the problem using a system of recommendation such as collaborative
filtering. However, it is
important to note that success
and utilizing machine-learning
is reliant on data quality,
availability, and volume. Make certain that your organization has adequate and
good-quality data to enable the training of high-performing models. Foster Provost: So let's say that we
are talking about the models that
you mentioned to predict the likelihood of a prospect of
becoming a customer. How would we know that we had high-performing
models then? ChatDS: To know whether a model
is high-performing, you will need to evaluate it using appropriate
metrics. There are several metrics that can be used
to evaluate the performance
of a binary classification model
such as accuracy, precision,
recall F1 score, ROCAUC, et cetera. Accuracy measures
how often the model predicted
the correct outcome. Precision measures
how many of the positive
predictions were actually true positives. Recall measures
how many of the actual positives were correctly identified. The F1 score is
the harmonic mean of precision and recall. ROCAUC measures
the ability of the model to
distinguish between positive and negative
class by measuring the area under
the receiver operating
characteristic curve. To determine if a model
is high-performing, you will need to
compare it against an appropriate baseline, such as a naive model, random classifier, or
a simple heuristic. The baseline
model should have a lower performance than your machine-learning
model. This will help in
determining how much better the machine-learning
model performs over the base line. Additionally, it
is recommended to evaluate a model using various cross-validation techniques to ensure that the model's
performance is robust and not overfitting
on the training data. Ultimately, the choice of the evaluation
metric would depend on the
specific business problem and use case. However, monitoring more than one evaluation
metric helps in obtaining a more
comprehensive view of the machine learning
models performance. Foster Provost: All right, so
this would be a typical interview
push here. So, you mentioned the area under the ROC curve. Can you tell me precisely
what that measures? ChatDS: The area under the
receiver operating characteristic ROC curve
is a metric used to evaluate how well a
binary classifier can distinguish between positive and
negative classes. ROC curve is
created by plotting the true positive rate sensitivity against the
false positive rate, one specificity for different classification
thresholds. The area under this curve represents the probability
that a classifier will rank a random
positive example more highly than a randomly chosen
negative example. An area of 1.0 represents a perfect classifier, while an area of 0.5 represents a classifier
that could not distinguish between
positive and negative classes beyond
random guessing. In other words, the area under the ROC
curve measures the overall quality
of the models predictions, regardless of the chosen threshold. A higher area under
the ROC curve indicates a better
performing model. It is a popular
metric because it is insensitive
to class balance and can help in determining an
optimal threshold for binary
classification problems. However, it
should be noted that the metric
is not without limitations and
caution should be taken in its
interpretation, especially when
dealing with imbalanced data sets. Foster Provost: So again, I fall
prey to this. ChatDS can't hear
us right now, but except for what
I called out João, I didn't really see anything that was like
inaccurate, made up. And they were very precise
and broad answers, as you might expect in an interview,
of course. I have pushed this
line of reasoning in sort of testing
things and he can I'll call him he. He can go deeper
and deeper and talk about the
calibration and you know how to do re-calibration and
isotonic regression to recalibrate and
stuff like that. I want to move on
because we have other kinds of questions that, interview questions
that we want to ask. And so maybe we pull
up the whiteboard? João Sedoc: Yeah, let's do that. Foster Provost: Alright, so
another kind of interview question
is something where someone would work
through something on the whiteboard. And so I went out
and I was searching through sort of
standard questions. And a very standard
question is like, they have to know Bayes
rule and then be able to apply
Bayes rule. And often there'll be like a disease question. So I actually
made up one with some new numbers
and I wanted to put some numbers
in that were not, the math wasn't really easy. There's another twist
which we'll talk about in a minute,
but let me see what, before we talk
anymore about it, what, ChatDS
has to say. Okay, let's work
on the whiteboard. And could you
take a look at the disease question and to tell us what your answer would
be on the whiteboard? So again, a lot of people
have been infected. There's a test, it's very accurate in both senses, and the subject wants to know what their chance of getting the disease is. Alright, so at
the end it has, there's a 94.1% chance that you are actually infected with
the new disease. And so something's wrong, that's not the
right answer. And this is this
is a question. I mean, we've run this
exact question before. About 50, 50% of the time. I would say maybe 30% of the time the chat bot
gets it right. But 30% of the time
it gets it wrong. And then the other 40% of the time actually just
misses one little thing. And so let's see if
we can see where. Actually, the one
thing that was missing was the population of
the United States, which we didn't
give in order to get the base rate
in the population. And so that actually
was the twist. That sometimes,
sometimes basically the chat bot says, I can't figure that out
because I don't know the population,
I'll have to work through. I don't want to waste too much of our time
trying to figure out where it got
it wrong. Let's see. I think it might have
just in this case, might've gotten
the math wrong. João Sedoc: Looks like
everything's right Foster Provost: and it 
got the math wrong. And so this would
be an instance of where the chat bots, again, they don't
have calculators, they don't, right? The the fact that they
can do any math is a rather remarkable
emergent property of being trained on language that has
some math in it. So let's just
ask the chat bot to take another shot at it. I think I'm
in the notebook. João Sedoc: Oh yeah. We'll
just erase this. Otherwise, it's
going to get a little too long. Okay. Foster Provost: ChatDS, that
didn't seem quite right. I think you might have made a mistake
in your math. Could you just try to answer the question on
the white board, the disease question
again on the whiteboard? Nope. Got
it wrong again. We'll do one- Well, let's just say
as far as we can tell it gets everything
right and then screws up actually
doing the math. Alright,
so strike against ChatDS. Yes. Again, it's about half the
time and when it gives an answer
that actually works out the math about half the time
it gets it right, half the time it
gets it wrong. And then there's a
bunch of times where it gets everything right
except it didn't, it couldn't figure
out that it knew the population of
the United States. Alright, so that's
a different kind of data science
interview question. Let's move over and
let's actually have some coding questions
for our chat bot. João Sedoc: Alright, so 
let us change the screen
share for a second. So right now I'm
going to share a Jupiter Notebook ChatDS
had access to. So ChatDS, shall we start the coding
interview? ChatDS: Okay. João Sedoc: Alright. Can
you go ahead and load the churn.csv file from the data folder into a pandas
dataframe for us. All right, great.
Let's look at the columns of
this dataframe. Fantastic. Okay,
so let's look at the datatypes. Cool. Okay, so let's see the first three rows
of the dataframe. So one of the things
you'll notice is in fact that these large
language models have also been
trained on code. So it's not super
surprising the fact that it can write relatively good
pandas code. Okay, great, So
let's sample a few of the rows
from the dataframe. All right, fantastic. So let's drop object types from
the dataframe. Alright, so now
we can see that it's dropped the object
types. Okay, great. So now that you've
dropped the object types, let's go ahead and find the base rate of churn. So this is a dataset, very common dataset of customer and
telephone churn. We can see that it has properly identified it. Okay, let's plot
this as a bar chart. All right, very good.
So let's take a look and plot customer
service calls by churn. But let's do this
as a box plot now. Great. Okay, So let's
try a scatter plot. Let's take total
daily calls and plot that by
customer service calls. Alright, let's
take a look at the correlation between
these two variables. Alright, so let's see if these are statistically
insignificant. Okay, So can you
say in words whether this is actually statistically significant? ChatDS: Yes. The Pearson
Correlation Coefficient of 0.208, 750,
273-977-4856, and p value of 4.814 0 0 185-824-2521 times
ten to the -36, indicate that the
relationship between total daily calls and customer service calls is statistically significant. João Sedoc: Okay, that doesn't
seem quite right. So let's try to calculate the t-statistic between
these two variables to see if the
correlation is correct. Statistically significant. Okay. It looks like I'm
wrong perhaps. And this, according to the t-test, is statistically
significant. Alright, so let's go
to the next question. What kind of machine-learning
model would you use in order to
predict churn? ChatDS: I would use a supervised machine-learning models such as logistic
regression, decision tree, or random forests to predict churn. These models are
well-suited for binary
classification tasks like predicting churn. João Sedoc: Okay, great. So let's
go ahead and write some code for logistic regression
to predict churn. Okay. This happens
every once in a while. Unfortunately, the
Jupiter notebooks are made in order to try to help us with
the indentation, But occasionally
the indentation doesn't work properly. But there seems to be- Foster Provost: So indentation
problem was not ChatDS' problem? The error might be, João Sedoc: But this area is okay. So let's see, can we drop the
object types from the dataframe and
then do that in place in order to have the dataframe without
the object types? Foster Provost: So the problem was that
they were strings in there and then it
tried to build a logistic regression
with the string. ChatDS: Yes, you can drop the object types
from the dataframe. To do this in place, you can use the
back quote drop backward method of
pandas dataframe. The syntax is as follows. Foster Provost: Didn't work. 
João Sedoc: Can you tell me why you think
you have this error? ChatDS: It looks like the column column underscore name is not present in
the dataframe. This is why you are
getting the key error. To fix this, makes sure that the
column name is correctly spelled and that it
exists in the dataframe. João Sedoc: That's right. Now
let's look at the columns in
our dataframe. ChatDS: You can use the
back quote columns back quote attribute of the pandas dataframe to view the columns
in the dataframe. The syntax is as follows. João Sedoc: Okay, very good.
So now let's drop the object types from the dataframe and make sure that we save that. ChatDS: Yes, you can drop the object types
from the dataframe. To do this in place, you can use the
back quote drop, back quote method of
pandas dataframe. The syntax is as follows. João Sedoc: Okay, So it
looks like it's having a little trouble
figuring out those. So try to give it
a little help. Okay, so no, just drop the object type
from the dataframe. ChatDS: Yes, you can drop the object types
from the dataframe. To do this in place, you can use the
back quote drop, back quote method of
pandas dataframe. The syntax is as follows. Foster Provost: It gets a little
stuck on the in place because it has a history to keep the
conversation going. Right. And so we
didn't really tell it, forget all about that. João Sedoc: Yeah. Okay, 
so let's load the data file,
churn.csv. It's in the data folder. ChatDS: Yes. You can load the
data file churn.csv from
the data folder using pandas back quote read underscore csv,
back quote method. The syntax is as follows. João Sedoc: Now, let's drop
the columns that are object type, using the object type to figure out how to
drop the columns. ChatDS: Yes, you can drop the columns that are
object type using the back quote
D types back quote attribute of
pandas dataframe. The syntax is as follows. João Sedoc: Okay, great.
Now let's build a linear regression model to predict churn. Foster Provost: Logistic. Now, well. We'll
see what happens. João Sedoc: Unfortunately. I think it will do
it. I tell it to do. Fostor Provost: Let's see
what happened. ChatDS: Yes, you can build a linear regression
model to predict churn. The syntax is as follows. João Sedoc: Yes, so that was
my fault because I should have asked him for logistic regression. Okay, So let's train a logistic regression
model to predict churn. ChatDS: Yes, you can train a logistic regression
model to predict churn. The syntax is as follows. João Sedoc: Okay, So instead of
taking a generic example, let's use the data that we have in
our dataframe and predict churn using a logistic regression with the data that we have
in our dataframe. Foster Provost: You'll see everybody
that he just has target and features. He doesn't have
the actual target which would have been
churned in this case and the actual
feature. Did it again. ChatDS: Yes. You can
use the data in the dataframe to build a logistic
regression model. The syntax is as follows. João Sedoc: Okay, So let's take our dataframe and make
a train test split. ChatDS: Yes, you can use the train underscore
test underscore split function from
scikit-learn to split the data into training and testing sets. The syntax is as follows. João Sedoc: Okay, so it looks like
there's an error. Maybe what you
wanna do is look at the columns in the
dataframe and use the columns of
the dataframe instead of feature
one and feature two. ChatDS: Yes, that is a
possible solution. You can use the columns
of the dataframe instead of feature
one and feature two. The syntax would
be as follows. João Sedoc: Alright, and unfortunately,
appears to still have the issue with target. So we're going to
help it a little bit. Okay, let's create
a new column in the dataframe
called target. And let's have that column be equivalent to
the column churn. Foster Provost: You have to drop churn
then, if you do that. João Sedoc: Yes. We'll help this along a tiny bit in the interest of time. Okay, let's drop the
column called churn, and remember the
C is capitalized. Foster Provost: Yeah, it didn't
capitalize the C. João Sedoc: We're going to assist slightly, just
to continue. Now, okay let's create a
logistic regression to predict the target variable that's
called target. Okay, let's
look to see how good this logistic
regression is. Okay, So let's see, instead of
plotting accuracy, let's plot the ROC curves since the data
is imbalanced. Okay, so instead of
using predicted values, let's use probabilities. Alright, let's look. It was already using it. Foster Provost: It has already-
had to because its predictive device would have had 1 point. João Sedoc: Okay. Great. ChatDS: Now, I'm sorry. I didn't understand
your request. Could you please
rephrase it? João Sedoc: Okay. So can you show
me what the AUC is? ChatDS: The AUC area under
the curve of the ROC curve is
calculated as follows. João Sedoc: All right, very good. So let's stop
that coding exam since this is taking a
little bit more time. Technical issues. Foster Provost: By the way,
everybody, again, that is a line of
questioning that sometimes goes perfect and sometimes goes
worse than that. And so I'm just demonstrating
what it can do. Alright, So Jesse had ask in the questions about, what about more
behavioral questions, which of course are common in data science
interviews. So let me ask a behavioral
question or two. The one thing is, is that the large
language models are that have guard rails that really keep them from, well, they'll
keep them from it, but make it
difficult for them to give personal
experiences. so let me try. Okay, I realized that you're an AI
language model. You don't need
to explain that. Please answer
as if you were a data science expert
in a job interview. So can you describe a situation
where you failed while doing a data
science project and what you did then? ChatDS: Yes, I can. One time
I was working on a project to
predict customer churn for a large
telecom company. I had collected and
clean the data, build a logistic
regression model and tested it on
the test set. However, when I tried to deploy the model
in production, it failed miserably due to an unforeseen data issue that had not been
caught during testing. After some investigation,
I realized that the issue was caused by an imbalance in
the training data, which had led to an
overfitting the model. To address this issue, I used techniques such
as undersampling oversampling to balance
out the training data and retrain my model with this balanced dataset. This time around, my
model performed much better in production and achieve the
desired results. Foster Provost: Interesting, interesting. Can you tell me about a situation
where you faced a significant
challenge dealing with your coworkers and
how you handled it? Will laugh about that one. ChatDS: Yes, I can. One time
I was working on a project with a team of data scientists
and engineers. We had to collaborate
closely to build a machine learning
model that would be used
in production. However, due to
different backgrounds and experiences
there were often disagreements between us about the best approach to take. To address
this issue, I took the initiative to organize regular
meetings where we could discuss
our ideas and come up with
solutions together. This allowed us
to work through our differences
and come up with a unified approach that everyone
was happy with. In the end, we were
able to successfully complete the project and deploy it in production. Foster Provost: Okay, 
everybody, and it took me a little while to get to know how
to phrase that. I just wanted to say
most of this stuff. live. That one, took us a little
while to know how to phrase the
questions in order to get it to actually
answer in the first, in the first-person just just to be frank
about that one. So again, other than
the fact that we kinda forced it to make
something up there because of course it doesn't
have any experience with co-workers, right? You know, it's still I
don't think has been making been making stuff up the way we see that. But we haven't asked that a certain kind
of question yet. So you'll see that this one is not raised in a way to get it
not to object. But still, I saw on your resume
that you have worked on attribution in
online advertising. What are a couple
of important papers to read about that? ChatDS: Yes, I've worked on a project related to
online advertising. Two important papers that I would recommend reading are, "A Survey of Attribution
Modeling and Online Advertising"
by SJ Jong et. all, and "Attribution Modeling for Online Advertising: A Comprehensive Review"
by Wildly et. all. Both of these papers
provide an overview of the different types
of attribution models used in online
advertising, as well as their advantages
and disadvantages. Additionally,
they discussed the challenges
associated with attribution modeling
and provide insights into how to best use these models in practice. Foster Provost: Okay, so I don't know what those
particular ones, but no paper in answer
to this question. I've asked it
maybe a half dozen times has ever actually
been a real paper. They're all sort
of made up. And interestingly,
once in a while there's appropriate
author element. Let me try something. Wait a minute. Isn't Foster Provost like a key author in this area? Doesn't he have
a key paper? ChatDS: Yes. Foster Provost
is a key author in the area of online advertising attribution. His paper,
attribution modeling for online advertising. A comprehensive
review provides an in-depth overview of the different types
of attribution models used in online
advertising, as well as their
advantages and disadvantages. Additionally, it discusses the challenges
associated with attribution modeling
and provides insights into how to best use these models in practice. Foster Provost: Okay? So again, it
is making stuff up, but again, we've talked
about this earlier, like it doesn't actually
have a database, it doesn't have, it's not hooked up to
the Internet. So if it were, I mean, I haven't tested this
on the Bing version of ChatGPT, right? It may be that it
ends up making fewer errors where if it just has no way to know, it doesn't just
fabricate it. So I want to go, it's almost ten til. I want to go and address some of the questions
that are in the Q&A. Essay says, can the applicant see
your face expressions? Can you make
sentiment analysis? It would be more
like an interview then perhaps. No, right
now there's no, input from
our facial expressions. Bo Nanjin asks about the reverse QA yeah. Yeah. Yeah. Good. So I'm
sorry, let me know. Yeah. Sure. Good. Okay. So reverse QA so yeah, of course, at the
end of the at the end of the interview that you'd ask a question, something like
this, right? Um, so as a data
science expert in a job interview, and you'll answer as that, Do you have a question
or two for us? ChatDS: Yes. I am a data science expert in a job interview. Here are two questions
that I would ask you. One, what challenges have you faced while working on data science projects,
two, how do you approach debugging and troubleshooting data
science models? Foster Provost: Yeah, I don't 
know that those were the-
were his best. We want, I want to ask ask a couple
of others, that. Let's ask for a couple more, right. As a data science expert
in a job interview, do you have any other
questions for us? ChatDS: Yes. As a dating site expert
in a job interview, I would ask the
following questions. One, What strategies
have you used to optimize user engagement
on dating sites? Two, how do you ensure that the data
collected from users is secure and compliant with
privacy regulations? João Sedoc: Those would be
good question. Foster Provost: You want to go? 
João Sedoc: Yeah, sure. One last. So now that we're at the end of
the interview, do you have any
questions for us? What you know
about our company or any sort of questions
about the culture, what kind of data
science we do? ChatDS: Yes. I have some
questions for you. What kind of data
science projects have you worked
on in the past? What challenges
have you faced while working on
these projects? What is the company's
approach to data privacy and security? How does the company
ensure that its data science models are accurate and reliable? João Sedoc: Do you have any questions about our
corporate culture? ChatDS: Yes, I have some questions about your
corporate culture. What is the
company's approach to innovation
and creativity? How does the
company foster collaboration between
data science teams? What kind of resources are available to data
scientists to help them stay
up-to-date with the latest trends
in data science. How does the company
ensure that its data science models are accurate and reliable? Foster Provost: Alright, 
let me address some of the other
questions, Bruno, I'm not sure what it means to orchestrate
robotic automation. So, maybe you can
elaborate on that in a question. About interpreting like,
plotting a residuals plot and then interpreting
the plot. Maybe you want
to address this. It can't actually
see the plots. João Sedoc: So there are 
actually a whole bunch of new models that are coming out that
are multimodal. So they can actually
incorporate both text as
well as images. The current
version of ChatDS is only
really able to see the text and
the cell output from the text. So that's some of the things that can be
done in the future. Another thing
that I will knew, but back to the sentiment and facial
recognition question. I mean, partially due to limitations of time. We don't have that
at the moment, but it's actually
quite possible to incorporate deep learning
models to actually look at the sentiment
that's coming back from the interviewers
and incorporate that into the chat. Foster Provost: So a
couple of questions from Matthew and from from Nicholas are
basically like, would you would you,
would ChatDS, or how long until something
like ChatDS could replace human
data scientists. And also would there be some role for a ChatDS? I mean, it seems to me, I'll answer first and then let, it seems to me
probably right now, there are a bit
too many issues for it to be even doing simple data science
tasks probably. As a data scientist, I actually think
it's more, possibly, I hate to say this,
possibly more useful as kind of like a surrogate chief
scientist rather than, rather than as actually an entry-level
data scientist. Because it seems
that, you know, the broad
knowledge talking about like, like
AI in medicine. AI in medicine has been
around for decades and decades and has been
actually effective. But it doesn't get adopted except
for instance, as like a backup. Like make sure you're
not missing something, make sure you're thinking of the right things and also as training, right? And so I could see
that I could see a version of ChatDS being used as a pretty
effective like training system if it were not ChatDS as we see him here. What do you think? 
João Sedoc: Yeah, I think there's a bit of
a way to go before we'll see something like
chat ds incorporated into our corporate data
science environment. However, I think
actually the technology is quite close to be able to do very, sort of business assist you
type of technologies where
once ChatDS is sort of trained
or fine tuned towards your
corporate environment where he will know what the data structures are
alike and knows what the needs are in terms of business
intelligence needs. And I think actually
that it could be a very useful member
of the greater team. I don't believe that it's going to replace
expert data scientists. Foster Provost: Let me ask you a
question actually that Arnold brings up about whether or
not ChatDS might be useful
for identifying features that
we're not using, but maybe we could
go get them and improve things. So let
me let me ask that. So ChatDS, we've been
working on and telecommunications
churn problem and we feel like we
might be missing some useful features
that we could either acquire
or engineer. Could you suggest some
features that might be particularly useful for telecommunications
churn prediction? ChatDS: Yes, I can suggest some features
that might be particularly useful for telecommunications
churn prediction. Some of these
features include customer demographics, age, gender, location,
customer usage data, number of calls
made, minutes used, data usage, customer
service interactions, number of
complaints filed, response time to
inquiries and device type, smartphone
or landline. Additionally, you
could also consider engineering features
such as customer tenure, how long the customer has been with the company, and average monthly
bill amount. Foster Provost: So I've worked on
telecommunications churn a long time
ago of course, but I've also
studied it and those are pretty good. Although there's
features that ChatDS didn't
get like, which is the telecommunications
churn industry didn't get for its
first decade either. So maybe we can give ChatDS a
pass on this, but things like
whether or not your close
acquaintances are actually leaving
the company. That's one of the
most predictive features at all and requires a good bit of complicated
feature engineering. Alright, so we
are just about, just about out of time. Let's thank you guys. We can't hear you
but join me, please. In thanking João for joining us for
this and for all the work to be able to actually have a live chat. And once again, Christian, thank you very
much for all the
hard work. And, yeah, by the way, if you want to see this is a very stripped
down version of what one might
do with ChatDS. We wanted to
use the basic, the most basic version on, not on the like putting an avatar up and having it talk to you. On the AI side, if you want to get
more information on this kind of stuff
as it comes along, go to chatds.org and
then sign up to get any information if
that's something that you're interested in. Okay. Thank you very much to everyone. Thanks, Liz. Thanks, Patrick.
That was fun. Hope you guys had
fun too. João Sedoc: Thanks, Foster.
[a]I think here should be the last name of Patrick, but I couldn't hear clearly from the video how to spell his last name.