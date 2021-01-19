# memotioin-analysis
memotion analysis using cnn-bilstm architecture
# Introduction
In the last few years, the growing ubiquity of Internet memes on social media platforms such as Facebook, Instagram, and Twitter has become a topic of immense interest. Memes, one of the most typed English words (Sonnad, 2018) in recent times.
Memes are often derived from our prior social and cultural experiences such as TV series or a popular cartoon character (think: One Does Not Simply - a now immensely popular meme taken from the movie Lord of the Rings). These digital constructs are so deeply ingrained in our Internet culture that to understand the opinion of a community, we need to understand the type of memes it shares. 
(Gal et al., 2016) aptly describes them as performative acts, which involve a conscious decision to either support or reject an ongoing social discourse. Online Hate - A brutal Job: The prevalence of hate speech in online social media is a nightmare and a great societal responsibility for many social media companies. However, the latest entrant Internet memes (Williams et al., 2016) has doubled the challenge. When malicious users upload something offensive to torment or disturb people, it traditionally has to be seen and flagged by at least one human, either an user or a paid worker. Even today, companies like Facebook and Twitter rely extensively on outside human contractors from start-ups like CrowdFlower, or companies in the Philippines.
But with the growing volume of multimodal social media, it is becoming impossible to scale. The detection of offensive content on online social media is an ongoing struggle. OffenseEval (Zampieri et al., 2019) is a shared task which is being organized since the last two years at SemEval.
# proposed method
Our main aim is to provide emotion for a given meme. So,
here we are using multi-channel CNN model to capture the
features of sentences, to capture the sequence of the sentences we are using Bi-directional LSTM and passing it through a dense neural
network to provide the output.


![method architecture](https://github.com/manideepvvs356/memotioin-analysis/blob/master/cnn_bilstm.PNG)



 This is project is developed by [vvs manideep](),[sumanth pola]() and [dattu burle]() 
 This is done under the guidance of [Dr.Vipul Mishra]() professor at bennett university.

