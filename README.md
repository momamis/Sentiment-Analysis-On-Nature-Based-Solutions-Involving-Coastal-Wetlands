# Project Title
Sentiment Analysis on Nature-Based Solutions Involving Coastal Wetlands

## Project Description and Overview

Nature-based solutions (NbS) refer to actions that work with and enhance nature to address societal challenges, such as climate change, disaster risk, water security, food security, human health, and biodiversity loss. Examples include restoring wetlands to reduce flooding, planting mangroves to buffer storm surges, or creating green urban spaces to mitigate heat islands and improve air quality. This project explores how nature-based solutions (NBS) — particularly those involving coastal wetlands — are portrayed in media and institutional discourse. It uses sentiment analysis on a curated set of web articles to understand public and institutional attitudes towards these ecological interventions. The project aims to identify whether these narratives lean positive, negative, or neutral, and how they may influence policy, conservation action, and public perception.

![sentiment_media](https://github.com/momamis/Sentiment-Analysis-On-Nature-Based-Solutions-Involving-Coastal-Wetlands/blob/main/sentiment_wetlands_media.png)

![sentiment_reserach](https://github.com/momamis/Sentiment-Analysis-On-Nature-Based-Solutions-Involving-Coastal-Wetlands/blob/main/sentiment_wetlands_research.png)

## Work Flow and Steps

- Scraped 40+ articles from reputable media and institutional sources (Nature Conservancy, The Guardian, EPA, Mongabay, etc.).
- Retrieved 100 research abstracts using Semantics Scholar API.
- Cleaned and preprocessed data for NLP model.
- Used Vader for sentiment analysis.
- Scores articles as positive, negative, or neutral based on textual tone.
- Identified the frequency of different nature-based solutions in each sentiment category.

## Key Insights

![heatmap_media](https://github.com/momamis/Sentiment-Analysis-On-Nature-Based-Solutions-Involving-Coastal-Wetlands/blob/main/Sentiment%20(%25)%20of%20Media%20Articles%20per%20NbS%20Type.png)

![heatmap_research](https://github.com/momamis/Sentiment-Analysis-On-Nature-Based-Solutions-Involving-Coastal-Wetlands/blob/main/Sentiment%20(%25)%20of%20Research%20Papers%20per%20NbS%20Type.png)

- Mangroves and seagrasses receive overwhelmingly positive attention from both scholars and journalists, underscoring their strong evidence base and public appeal.
- Salt marshes are viewed even more positively in media (100%) than in research, which still contains minor critiques—possibly reflecting ecosystem-specific limitations or implementation concerns.
- The "Other NbS" category shows the greatest apparent disconnect between research and media sentiment. While media coverage frames these solutions positively (91.7%), academic abstracts were more cautious (~50% positive)—but it's important to note that this group in research includes null or unclassified entries, potentially skewing sentiment downward.
- The contrast here may partly stem from categorization limitations rather than genuine disagreement. Still, this pattern suggests that less-defined or hybrid NbS may suffer from underrepresentation or ambiguity in academic discourse—highlighting a need for clearer taxonomy and more robust framing in both science and media.



