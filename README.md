# Reddit Outbound Links Dataset

The dataset in this repository is a sample of a (much) larger dataset of links posted within comments on Reddit. I derived the larger dataset   from a full data dump of Reddit (from pushshift.io). The derived links dataset is about 80 GB. The data used here is a random sample of 1,000,000 rows from the larger database. The dataset includes the outbound link and metadata for its associated comment, such as subreddit, permalink, score, and timestamp.

`test.db` contains 1,000,000 randomly sampled rows from the larger dataset, while `small_test.db` contains 10,000 randomly sampled rows.
