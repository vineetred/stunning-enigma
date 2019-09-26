# stunning-enigma

## Vision:

To reduce misinformation online.

## Specifics:

A web application, where, given a link to a Facebook/Instagram/Twitter post, we output a prediction on whether the news in that post is real or fake.

Input : A valid url to a post.
Output: Boolean, True or False.

## Method:

- Data collection done using Facebook Graph API to extract the post, who shared it, who liked it, and how many overall likes it recieved. We train the classifier using this data to predict whether or not the news is fake or real.
- Instead of analysing user behavior, we use the contents of newspapers/social media articles to train a classifier to distinguish between real and fake data(Supervised Learning).
- Find websites which only distribute fake news and websites that are proven to be trust-worthy. Use this information to create datasets of just fake and real news. Use these datasets in unsupervised learning to find features of fake news which don't need to be manually crafted. Use these features alone or in tandem with supervised learning features to see if there is a boost in overall accuracy.

## Papers
- https://www.pnas.org/content/116/7/2521
- https://www.ncbi.nlm.nih.gov/pubmed/29935897
- https://arxiv.org/pdf/1704.07506.pdf
- http://www.public.asu.edu/~skai2/files/aaai_2019_unsupervised.pdf
- http://delivery.acm.org/10.1145/3140000/3132877/p797-ruchansky.pdf
- http://openaccess.thecvf.com/content_ECCV_2018/papers/Jacob_Huh_Fighting_Fake_News_ECCV_2018_paper.pdf
- https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8397048
- http://delivery.acm.org/10.1145/3160000/3159677/p637-wu.pdf
- https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8397049
