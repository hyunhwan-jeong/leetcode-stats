# Leetcode stats

## What is it?

The repo contains notebooks that crawl your [leetcode](https://leetcode.com/) submission page of and visualize some plots for the submissions.

## Why did you create?

The reason is simple. The stats provided by leetcode are very limited. They even don't show the number of problems solved per day (they only provides the number of submissions).  

## Dependency

* [jupyter notebook](https://jupyter.org/)
* [pandas](https://pandas.pydata.org/)
* [browsercookie](https://github.com/richardpenman/browsercookie)
* [requests](https://requests.readthedocs.io/en/master/)

## How to use

1. Load jupyter notebook.
2. Run [submission-data-crawling.ipynb](https://github.com/hyunhwaj/leetcode-stats/blob/master/submission-data-crawling.ipynb) to collect the submission status.
 * To use this notebook, you need to use Chrome browser and need to be logged in.
3. Run [leetcode-stats.ipynb](https://github.com/hyunhwaj/leetcode-stats/blob/master/leetcode-stats.ipynb) to view the summary stats.
