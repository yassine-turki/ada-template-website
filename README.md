# Data Story
<p style="font-size: 8px;">Warning message. Angelina is a fictitious character created for the sake of the project.</p>

### Introduction

(some AI generated photo?)
My name is Angelina, I am 21 years old and I just finished a school of theater in Paris. Theater has always been my passion, but the problem is the very low and unreliable salary. My dream now is to work in the movie industry where I will be able to continue acting, while earning a sufficient income.  
A friend of mine told me: “Movies are made by men for men. Women are just here to add sexyness”. 

It struck me, as I never could imagine such a strong statement could be true. In this era of fake news, I could not let my dreams be ruined by a few words so I decided to take the matter in my own hands. I decided to pursue a class at EPFL called ADA, and do my own analysis of all the movie industry. Then, and only then, I will be able to determine whether my friend was right or not. 

## Starting from the beginning

I went on the internet and downloaded the information of all movies from wikipedia. At first glance I wanted to see the ratio of actresses and actors. I found out that there are [...] more men than women. I was a little disoriented. But since I am in Paris, I checked the ratio in France. I also took the opportunity to look at various countries. Figure … shows the ratio of actors vs actresses by world region. 
…

I was disappointed to see that women are much less present than men. But I did not lose hope, and figured that perhaps there was a great evolution of women in films. So I looked at the evolution of the percentage of women in films (figure…) globally but also by regions (figure…)

…
The proportion of women in films globally increased a tiny bit by the end of the 20th century. In France, it increased by …, while in …, it only increased by ….
One thing I learned from ADA is that valuable information can be hidden in the data so I decided to dig further and look at the evolution of actresses in film by movie genre. Figure … shows the share of women in the movie industry by genre, and figure… shows the evolution of women in those genres. 

…

Looking at [movie genre] definitely does not seem very attractive as they are only [share of women]. However, [movie genre] seems already a bit more favorable for women. It’s not really my type though. 

Definitely, my future does not look very bright from this perspective. But with my theater background, I am sure I will be able to get good acting roles, and be as famous as Scarlett Johansson. Actually I am wondering how top actresses are represented ? Do they have actual big roles, and play in many big movies ? How long are they ‘stars’ ? Do they continue to be celebrities once they are older ? 

And so I went and explored my data. The problem was that I didn’t have a way to identify the main actors from my dataset. Nothing stops me, so I went online, found out that IMDB had a list of main roles, downloaded all the data, cleaned it, merged it, until I had a nice dataframe, one that would satisfy Maria and Bob. 

I directly looked at the distribution of main roles. I found out that men have [...] more first roles than women. But actually I saw before that there are much more actors than actresses. But even proportionally, I see that men still have [...] more first roles than women. Crazy. Figure … shows the evolution of the women having 1st, 2nd and 3rd roles. and figure … analyses the evolution by genre. 

…

Clearly, women are not present in war films. But they are present in erotic movies 🙄
We can also see that…

But then I thought : “perhaps the big films have more women actresses”. I didn’t really know why. I had this feeling. Perhaps it was just some hope. 

So I kept only the films with the highest revenue (above …), and looked at the distribution of 1st roles among actresses/actors. Figure … shows the share of women with 1st roles in these movies. 

[Discussion on graph]

But if I become a star, how long will I remain a star ? (Angelina dreaming) If I start to get older, will I remain famous and loved by all my fans ? Figure [...] shows the starting career of actresses and actors and their ending career. 
[...]
But perhaps, famous actresses play longer… Let me check. 
[...]
Big films generate big revenues. So my question now is whether big films have lots of actresses, and if there is a link between the two. So I went on and once more did the analysis, and as we see
[...]
Not so much… 
But then, clinging on for hope I decided to check whether, perhaps, having a woman in the first role would lead to higher revenue for a given film. Or would it be the opposite?
[Oskar graph 1]
But does this change across countries? Perhaps there are some countries where having an actress in first role is correlated with higher revenue?
[Oskar graph 1]
And what if I did become the biggest star of my country!? How much would I earn? Is the gender wage gap between the biggest stars of cinema different across countries? Let’s see
[Oskar graph 2]
Hmmm… But to be a star, I need to make sure the country I’m in actually produces movies. Let’s see which countries produce the most movies. We’ll only look at movies that list revenue to weed out very small films.
