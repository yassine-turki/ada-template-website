# Data Story
<p style="font-size: 8px;">Warning message. Angelina is a fictitious character created for the sake of the project.</p>


<style>
    figure {
        counter-increment: figure;
    }
    figcaption:before {
        content: "Figure " counter(figure) ": ";
        font-weight: bold;
    }
</style>


### Introduction

(some AI generated photo?)
My names is Angelina, I am 21 years old and I just finished a school of theater in Paris. Theater has always been my passion, but the problem is the very low and unreliable salary. My dream now is to work in the movie industry where I will be able to continue acting, while earning a sufficient income.  
A friend of mine told me: “Movies are made by men for men. Women are just here to add sexyness”. 

It struck me, as I never could imagine such a strong statement could be true. In this era of fake news, I could not let my dreams be ruined by a few words so I decided to take the matter in my own hands. I decided to pursue a class at EPFL called ADA, and do my own analysis of all the movie industry. Then, and only then, I will be able to determine whether my friend was right or not. 

### Starting from the beginning

I went on the internet and downloaded the information of all movies from wikipedia. At first glance I wanted to see the ratio of actresses and actors. I found out that there are 2 times more actors than actresses. I was a little disoriented. But since I am in Paris, I checked the ratio in France which was of [OSKAR...]. I also took the opportunity to look at various countries. Figure [OSKAR...] shows the ratio of actors vs actresses by world region. 
…

I was disappointed to see that women are much less present than men. But I did not lose hope, and figured that perhaps there was a great evolution of women in films. So I looked at the evolution of the percentage of women in films (<a href="#fig1">Figure 1</a>) globally but also by regions (figure…OSKAR)


<figure id="fig1">
    <iframe src="Mean_Ratio_and_Count_by_Movie_Release_Date.html" width="800" height="600" frameborder="0"></iframe>
    <figcaption style="text-align: center; margin-top: 4px;">
        Ratio of actresses and number of movies by year
    </figcaption>
</figure>

The proportion of women in films increases very slightly from the 60s. In 1960 there were 31% actresses in films, while in 2011 there are 35%. In France, the ratio of actresses is constant, but slithly higher than the global average.  

One thing I learned from ADA is that valuable information can be hidden in the data so I decided to dig further and look at the evolution of actresses in film by movie genre. <a href="#fig2">Figure 2</a> shows the list of genre with the highest and lowest gender ratio.

<figure id="fig2">
    <iframe src="top_genres.html" width="900" height="600" frameborder="0"></iframe>
    <figcaption style="text-align: center; margin-top: 4px;">
        Most and least inclusive genres. 
    </figcaption>
</figure>

I find it amusing that the most "inclusive" genres (still bellow 50% of actresses in the cast) happens to be 'Kitchen sink realism'. The other genres are not much better: "Adult", or even "Melodrama". Obviously, women only complain and work in the kitchen :(.  I will definitly need to see how women are represented in the film industry (will do later). On the other hand, the least inclusive genres are all those including violence or war. Woman are more tender that is true. It is sad because I loved "Spaghetti Western". 
 
Definitely, my future does not look very bright from this perspective. But with my theater background, I am sure I will be able to get good acting roles, and be as famous as Scarlett Johansson. Actually I am wondering how top actresses are represented ? Do they have actual big roles, and play in many big movies ? How long are they ‘stars’ ? Do they continue to be celebrities once they are older ? 

And so I went and explored my data. The problem was that I didn’t have a way to identify the main actors from my dataset. Nothing stops me, so I went online, found out that IMDB had a list of main roles, downloaded all the data, cleaned it, merged it, until I had a nice dataframe, one that would satisfy Maria and Bob. 

I directly looked at the distribution of main roles. I found out that men have 72% of first roles. But actually I saw before that there are much more actors than actresses. So in that sense, it is logical that there are more first role for actors. However, proportionally, I see that men still have 56% of the first roles. That means if there was the same number of actors and actresses, actors would be more likely to get the first role. Crazy. Similarly to before, perhaps there is a bit of hope in the evolution. <a href="#fig3">Figure 3</a> shows the evolution of the women having 1st, 2nd and 3rd roles. Nothing too glamorous as it remains quite constant. We can almost perceive a decrease in the share of women having first role :(. In 2012, there are only 26% of women with first role. That is not soo good for my carrer.

<figure id="fig3">
    <iframe src="percentage_evolution_of_actresses.html" width="800" height="500" frameborder="0"></iframe>
    <figcaption style="text-align: center; margin-top: 4px;">
        Evolution of the gender ratio for different roles 
    </figcaption>
</figure>
Let me investigate which genre is most welcoming for my career as an all time star. <a href="#fig4">Figure 4</a> shows the most and least inclusive genre for first roles actors/actresses. 

<figure id="fig4">
    <iframe src="first_role_genre.html" width="700" height="400" frameborder="0"></iframe>
    <figcaption style="text-align: center; margin-top: 4px;">
        Most and least inclusive genre for first role
    </figcaption>
</figure>
So either I am a feminist, or a pornstar. That's not very nice...

So clearly, women are not present in war films. But they are present in erotic movies 🙄

But then I thought : "perhaps the distribution is skewed due to the high number of 'small budget films'". "Perhaps the big films have more women actresses”. I didn’t really know why. I had this feeling. Perhaps it was just some hope. 

So I kept only the films with the highest revenue (above …OSKAR), and looked at the distribution of roles actresses/actors. Figure …OSKAR shows the share of women with roles in these movies. 

[Discussion on graph]

But if I become a star, how long will I remain a star ? (Angelina dreaming) If I start to get older, will I remain famous and loved by all my fans ? Figure [...LOLO] shows the starting career of actresses and actors and their ending career. 
[...LOLO]
But perhaps, famous actresses play longer… Let me check. 
[...LOLO]
Big films generate big revenues. So my question now is whether big films have lots of actresses, and if there is a link between the two. So I went on and once more did the analysis, and as we see
[...ALIX]
Not so much… 
But then, clinging on for hope I decided to check whether, perhaps, having a woman in the first role would lead to higher revenue for a given film. Or would it be the opposite?
[Oskar graph 1]
But does this change across countries? Perhaps there are some countries where having an actress in first role is correlated with higher revenue?
[Oskar graph 1]
And what if I did become the biggest star of my country!? How much would I earn? Is the gender wage gap between the biggest stars of cinema different across countries? Let’s see
[Oskar graph 2]
Hmmm… But to be a star, I need to make sure the country I’m in actually produces movies. Let’s see which countries produce the most movies. We’ll only look at movies that list revenue to weed out very small films.

But is there any relation between the general gender ratio of a film and the revenue generated? [...ALIX]
And is there a correlation between an actress's age and the revenue she generates?
[... ALIX]
How are women represented ? 
Okay, so the proportions of women in the movie industry could definitely be better… But now let’s see the types of roles I could have as an actress. How will people describe my roles? What type of actions will my characters perform? To find this out I need to have a way to differentiate female characters from men characters in movies. Let me look at the distribution of proportions of female characters in movies.

[... ALIX graph from docs]

Well, it is highly skewed right, but that’s no real surprise anymore based on my previous analyses… However, this gives me an idea! I’ll split films by character gender ratio and look at the descriptive adjectives and verbs used in films with more men than women and vice versa through NLP methods. A ratio of 1:2 seems like a good cutoff point. I’ll also remove words that show up for both male dominant and female dominant films at similar frequencies.

[... ALIX graphs from docs (with words)]

Ah, well that’s not super encouraging either… It seems films with mostly women characters are characterized by love, marriage, pregnancy and sexuality… While movies with mostly men revolve around violence, power struggles, and crime. 
Ok let’s try a different approach to see the topics of movies with a large proportion of actresses. I’ll run sentiment analysis on a variety of topics for our movies with the same split on gender ratio

[... ALIX other graph]

[START OF ALESSANDRO's PARAGRAPH]
Ok we see similar trends as the word cloud, but for the most part the variations are not as drastic as they could be. Running some hypothesis tests, all the variations are statistically significant. [ALESSANDRO]

## Delving into the Language of Film

Up to now, I’ve focused on the tangible aspects of representation: the ratio of actors to actresses, how main roles are distributed, and how these patterns evolve over time or differ by region. But there’s another dimension to consider—*how* stories are told. Do movies featuring more actresses differ thematically and emotionally from those dominated by actors? To answer this, I turned to the actual summaries of the films.

### Text Preprocessing and Thematic Categories

First, I needed to prepare the textual data. I took all the movie summaries and performed several preprocessing steps:  
- Converted all text to lowercase  
- Lemmatized words (reducing them to their dictionary form)  
- Removed extremely common and extremely rare words, ensuring that only meaningful, distinctive terms remained

This cleaned dataset allowed me to compare films on a more even linguistic footing.

To quantify the narrative content, I defined a series of **categories**—themes like love, violence, family, happiness, sadness, career, and so on. Each category corresponded to a set of seed words that captured its essence. I then used a language model to embed these words into a vector space. By computing the centroid of these embeddings, I obtained a semantic “center” for each category.

### Identifying Category-Related Words

From each category’s centroid, I selected the 100 words in the entire corpus most similar to that centroid (based on cosine similarity). These 100 words effectively broaden the category from a handful of seed terms to a richer semantic field. For instance, the “violence” category might include words like *“attack,” “battle,” “murder,” “gunfight,”* and so forth.

After determining these sets of 100 words per category, I counted how frequently they appeared in each film’s summary. Dividing by the total number of words in the summary gave me a normalized “score” representing how strongly each category was represented in that movie’s narrative.

### Splitting the Dataset and Statistical Testing

Since my ultimate goal was to see whether narratives differ in films featuring more women than men, I split the dataset into two subsets:  
1. **Female-Dominant Films**: Movies with a higher proportion of actresses  
2. **Male-Dominant Films**: Movies with a higher proportion of actors

By comparing average category scores between these two subsets, I could detect meaningful thematic shifts. To ensure that any observed differences were not due to chance, I ran **statistical tests** (e.g., Mann-Whitney U tests) to verify the significance of these differences. Many categories showed statistically significant variations, reinforcing the idea that gender composition does correlate with narrative themes.

### Visualizing the Results

#### 1. Category Embedding Visualization

Before diving into comparisons, let me show you how the categories were formed. Below is a 3D scatter plot of the embedded words, with each category’s 100 words highlighted in a distinct color cluster.

**Figure: 3D Visualization of Category Clusters**  
<figure id="fig6">
    <iframe src="centroids_top_words_plot_3d.html" width="800" height="500" frameborder="0"></iframe>
    <figcaption style="text-align: center; margin-top: 4px;">
        Evolution of the gender ratio for different roles 
    </figcaption>
</figure>

[END OF ALESSANDRO's PARAGRAPH (for now)]

[START OF YASSINE's PARAGRAPH]
Giving a voice to women: looking at directors
I’ve focused all my energy on researching actors so far, but what if I looked at directors instead? What if I ever want to direct a movie? What are my chances? 
I’ll first look at general gender ratio across directors
[...YASSINE]
Ouch… Ok but has it improved over the years? [...YASSINE]
And are there some countries with higher proportions of female directors? Should I really move countries? [...YASSINE]
And what about the number of movies per director? Does that change across genders? [...YASSINE]
And what about the casting choices of Directors?  Female directors hire more females than male directors? What about taking a first, second, or third role? Do we have a bias? [...YASSINE]

Looking at other societal issues : what’s been done ?
