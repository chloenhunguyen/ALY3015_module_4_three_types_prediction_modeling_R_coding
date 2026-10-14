# Instagram Analytics Dataset
## Data Background
This dataset contains data on 4,509 Instagram posts (shared by users during Nov 2024 – Nov
2025) with key performance metrics commonly used for content analytics and growth
modeling. It includes engagement counts (likes, comments, shares, saves), exposure
metrics (reach, impressions), content metadata (media type, category, caption length,
hashtags), account features (account type, follower count), traffic source, posting time
features, and a performance bucket label (multicategory variable of post popularity).
This dataset is useful for performing binary/multiclass classification and count data
modeling.

## Notes
Some engagement fields may contain missing values (NaNs). This reflects realistic analytics
exports where certain post types or tracking conditions may omit metrics. For this
assignment purpose, you should drop such rows with missing values. Do not apply any
imputation technique to replace missing values.

## Response Variables:

• [Part-A] Binary classification problem: predict which Instagram posts will become
viral. For this derive a binary response variable from performance_bucket_label
column.
• [Part-B] Multi-category classification problem: predict different popularity levels
for Instagram posts. For this use performance_bucket_label column as response
variable.
• [Part-C] Count modeling problem: predict number of new followers gained by users
after sharing a new post on Instagram. For this use follower_count as response
variable.
Dataset Source: This dataset was created from an original raw dataset from Kaggle.com for
the purpose of ALY3015 course assignment.
