# UpliftModeling-MachineLearning

The UpliftModeling is the representative Machine learning algorithm used in direct marketing.
There are two choices which is either sending men’s email or women’s email.
LogisticRegression algorithm is used for training the model.
After training, we can figure it out the most effective way to send email to customers.

<img width="1154" alt="Screen Shot 2019-11-04 at 7 43 28 PM" src="https://user-images.githubusercontent.com/40285946/68115310-79047780-ff3b-11e9-8e3b-1f5648ef83d4.png">
<img width="718" alt="Screen Shot 2019-11-04 at 7 43 51 PM" src="https://user-images.githubusercontent.com/40285946/68115346-8de10b00-ff3b-11e9-8d80-dcf817773845.png">

Sending is_treat_list("Mens E-Mail") to top 60% uplift score, 
sending is_control_list("Womens E-Mail") to rest of low 40% uplift score
might be the efficient solution.
