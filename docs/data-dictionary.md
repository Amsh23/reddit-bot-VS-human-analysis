# Data Dictionary

This dataset contains 500 Reddit comment records. Each row represents a comment with associated account, timing, and linguistic features.

| Column | Type | Description |
| --- | --- | --- |
| `comment_id` | string | Reddit comment identifier (e.g., `t1_...`). |
| `subreddit` | string | Subreddit where the comment was posted. |
| `account_age_days` | integer | Account age in days at the time of the comment. |
| `user_karma` | integer | User karma at the time of the comment. |
| `reply_delay_seconds` | integer | Delay between original post and reply, in seconds. |
| `sentiment_score` | float | Sentiment polarity score for the comment text. |
| `avg_word_length` | float | Average word length in the comment. |
| `contains_links` | boolean | Whether the comment contains a URL. |
| `is_bot_flag` | boolean | Ground-truth or heuristic label indicating bot status. |
| `bot_type_label` | string | Bot label (e.g., `None (Human)`). |
| `bot_probability` | float | Modeled probability of automation. |

## Dataset Notes
- The dataset ships without missing values.
- Values are stored in CSV string form; cast to appropriate types when loading.
- Use `is_bot_flag` for binary comparison, and `bot_probability` for graded risk analysis.
