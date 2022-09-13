# A Machine Learning Approach to Classify Anti-social Bengali Comments on Social Media
 This repository is based on my research paper titled "A Machine Learning Approach to Classify Anti-social Bengali Comments on Social Media". The paper is accepted by IEEE. You can found this paper in the following link: https://ieeexplore.ieee.org/document/9836407.<br>

 Here, you can found the basic coding part of the research. 
 We have collected 7000+ bengali comments from social media. Please see the dataset folder.

 ### Problem statement of this research
 - **Comments:** Collect preprocessed comments from social  media
 - **Annotation:** Annotated the comments as social or anti-social
- **Building Model** Using the data, build a ML model
- **Classification** Model can classify the new comments 

 ### Dataset annotation example
 - “আর ভারতে যাইয়া পুজোর উদ্বোধন করে আসো"<br>
(Travel to India to inaugurate Puja.)<br>
-Although no obscene words are used in this sentence, it offends a community's religious emotions. So, it is an anti-social comment.

- “হিরো কনডম সবসময় এক নাম্বার"<br>
(Hero condom is always number one.)<br>
-Here no slang word is used or no one is dehumanized. So, it is not an anti-social comment.

- "মা হিসেবে আপনি জাতির গর্ব কারণ আপনার সন্তানকে আপনি অনেকগুলা বাবা উপহার দিয়েছেন"<br>
(As a mother you are the pride of the nation because          you have given many fathers to your child.)<br>
-In this scenario, an individual character such as a mother was questioned, which is not socially acceptable. Hence this is termed as anti-social.

- “এটা ই যেন শেষ আন্দোলন হয়"<br>
(Hope it will be the last movement.)<br>
-It yearned for the end of a movement indicating peace. which is socially acceptable.


 ### Contribution of this research
 - Comments on social media were analysed based on socially acceptable or not rather than sentiment analysis.
 - Made a dataset containing 2000 Bengali comments collected from popular social media.
- Applied 5 traditional and modern machine learning algorithms and compared the performance of the models based on these algorithms
- Built N-Gram (uni-gram, bi-gram, and tri-gram) language models.


