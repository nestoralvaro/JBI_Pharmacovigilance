The file 1548_CrowdFlower.ods contains all the annotations we retrieved from Crowdflower. These 1548 tweets include the 899 tweets that we used to train our models and also the tweets that were left out in our experiments.

The annotated fields are:
"Tweet ID": Indicates the ID of the tweet. This unique identifier can be used to retrieve the tweet (some tweets could have been removed).
"_golden": True when the tweet was one of the 100 tweets composing the gold standard.
"is_the_tweet_text_in_the_english_language": True when the tweet is written in English.
"the_text_is_about_the_drugs_of_interest": True when the tweet is about any of the drugs of interest*.
"genre_in_which_the_drug_is_mentioned_": To categorize the tweet as belonging in any of the available genres**.
"sentiment_of_the_author_about_the_drug": The available options were "Positive", "Neutral" and "Negative".
"theme_on_the_drug_ussage": The three themes were "Pleasure", "Craving" and "Disgust".

Clarifications on these fields can be found in our publication, please refer to it for further details.

* To see which are the drugs of Interest, please refer to our publication.
** The available genres are "First-hand experience", "Other's Experience", "Activism", "Cultural reference", "Humor", "News", "Info/resource", "Marketing", "Opinion", "Sentiment".

