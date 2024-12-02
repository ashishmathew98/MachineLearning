## Description
In the rapidly evolving landscape of digital marketing, businesses strive to drive traffic to their websites to maximize consumer engagement with website content and for online retailers also promote sales. Display advertising is one method used to drive traffic. Success of a display ad is judged by the percentage of visitors who click on the ad, commonly known as Click-Through Rate (CTR). The goal of this competition is to predict CTR based on a set of variables describing the quality, relevance, type, target audience, and content of the display advertisement.

## Data Description

1. Ad number (id): Number that uniquely identifies the ad

2. Targeting Score (targeting_score): A score from 1 to 10 representing how well the ad is targeted to the audience. Higher scores indicate better targeting.

3. Visual Appeal (visual_appeal): A score from 1 to 10 representing the visual attractiveness of the ad. Higher scores indicate a more visually appealing ad.

4. Contextual Relevance (contextual_relevance): Indicates whether the ad content is relevant to the context in which it is displayed. A value of 1 means relevant; 0 means not relevant.

5. CTA Strength (cta_strength): A score from 1 to 10 representing the effectiveness of the Call-to-Action (CTA) in the ad. Higher scores indicate a stronger CTA.

6. Position on Page (position_on_page): The position of the ad on the web page. It has three possible values: Top Banner, Side Banner, and In-Content.

7. Ad Format (ad_format): The format of the ad, with three possible values: Image, Video, and Text.

8. Age Group (age_group): The age group of the target audience, with possible values: 18-24, 25-34, 35-44, 45-54, 55-64, 65-74, 75-84, and 85+.

9. Gender (gender): The gender of the target audience, with possible values: Male, Female, and Other.

10. Location (location): The geographic region where the ad is displayed, with four possible values: Northeast, Midwest, South, and West.

11. Time of Day (time_of_day): The time of day when the ad is displayed, with four possible values: Morning, Afternoon, Evening, and Night.

12. Day of Week (day_of_week): The day of the week when the ad is displayed, with seven possible values: Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, and Sunday.

13. Brand Familiarity (brand_familiarity): A score from 1 to 10 representing the audience's familiarity with the brand being advertised. Higher scores indicate greater familiarity.

14. Device Type (device_type): The type of device on which the ad is displayed, with three possible values: Mobile, Desktop, and Tablet.

15. Ad Frequency (ad_frequency): The number of times the ad has been shown to the same audience.

16. Market Saturation (market_saturation): A score from 1 to 10 indicating how saturated the market is with similar ads. Higher scores indicate higher saturation.

17. Seasonality (seasonality): Indicates whether the ad is displayed during a peak season (1) or not (0).

18. Headline Length (headline_length): The number of characters in the ad's headline. Headline Sentiment (headline_sentiment): A score indicating the sentiment of the headline text, where positive values indicate positive sentiment and negative values indicate negative sentiment.

19. Headline Word Count (headline_word_count): The number of words in the ad's headline.

20. Headline Power Words (headline_power_words): Indicates whether the headline contains powerful, persuasive words (1) or not (0).

21. Body Text Length (body_text_length): The number of characters in the ad's body text.

23. Body Word Count (body_word_count): The number of words in the ad's body text.

24. Body Sentiment (body_sentiment): A score indicating the sentiment of the body text, where positive values indicate positive sentiment and negative values indicate negative sentiment.

25. Headline Question (headline_question): Indicates whether the headline is framed as a question (1) or not (0).

26. Headline Numbers (headline_numbers): Indicates whether the headline contains numbers (1) or not (0).

27. Body Keyword Density (body_keyword_density): The density of keywords in the body text, represented as a proportion.

28. Body Readability Score (body_readability_score): A score indicating the readability of the body text, where higher scores indicate easier readability.

**Target Variable:** Click-Through Rate (CTR): Represents the percentage of users who clicked on the ad after viewing it.