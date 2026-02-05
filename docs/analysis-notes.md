# Analysis Notes

## Key Findings (from notebook)
- **Response speed**: Bot accounts reply significantly faster than human accounts, suggesting automation.
- **Linguistic signals**: Bots show lower sentiment variability and shorter average word lengths, consistent with templated responses.
- **Subreddit concentration**: A subset of subreddits ranks highest in bot ratio, indicating uneven infiltration.
- **Account age**: Newer accounts exhibit higher modeled bot probabilities.

## Open Questions
- How sensitive are the findings to different outlier-removal thresholds?
- Do results hold across larger or more recent datasets?
- Can additional features (e.g., posting cadence or lexical diversity) sharpen bot detection accuracy?

## Recommended Next Steps
- Normalize or standardize numeric features before modeling.
- Add a simple baseline classifier (e.g., logistic regression) and evaluate precision/recall.
- Expand dataset to include more subreddits and time windows.
