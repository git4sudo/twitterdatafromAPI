# Twitter Dataset Overview

## Dataset Description

This dataset comprises a collection of annotations and classifications from Twitter, containing detailed evaluations of tweet content in terms of credibility and user perceptions. It includes 9,427 entries, each rich in metadata related to Twitter interactions and content assessment.

## Key Features

- **Entries**: 9,427
- **Columns**: 77

### Data Fields

- `noteId`, `tweetId`: Unique identifiers for each tweet and annotation.
- `noteAuthorParticipantId`: Identifier for the user who created the annotation.
- `createdAtMillis`, `created_at`: Timestamps detailing when the tweet and the annotation were created.
- `classification`, `believable`, `harmful`: Fields categorizing the perceived credibility and potential harm of the tweet.
- `misleadingFactualError`, `notMisleadingFactuallyCorrect`: Indicators of the tweet’s factual accuracy or errors.
- `trustworthySources`: Evaluations of the source credibility cited in the tweets.
- `text`: The actual text content of the tweet.

### Content Evaluation

This dataset provides extensive evaluations regarding the content's nature:
- **Misleading Information**: Various flags such as `misleadingFactualError`, `misleadingManipulatedMedia`, and more.
- **Credibility Assessment**: Flags like `notMisleadingFactuallyCorrect` and `trustworthySources` evaluate the accuracy and reliability of information.
- **User Interactions**: Metrics like `notHelpfulSpamHarassmentOrAbuse` reflect user feedback on the content.

## Potential Uses

This dataset is ideal for research and development in fields such as:
- Misinformation detection and analysis.
- Social media content credibility analysis.
- Machine learning models focusing on text analysis and user behavior.
