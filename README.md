## Project Description
With the landslide victory of Democratic Party in 2022 midterm election, this project explores the causal relationship between issue salience, measured by the presence of abortion-related ballot measures, and issue-based voting behavior in 2022 Senate election. Using matching, this project will match individuals in states where abortion are on ballot to similar individuals in states where abortion are not on the ballot to examine the impact of abortion’s salience on voting outcome. The matching process will control for demographic, economic, and political factors. 

## Initial Finding

By condudcting exploratory data analysis, we see that a majority of people voted in the midterm election.
![](figs/whether_voted_dist.png)

Among people who voted in the midterm election, a majority of them voted for the Democratic senate candidate
![](figs/party_voted_dist.png)

## Finding's Relevance
This finding is relevant because it gives us confidence that some people who originally would vote for Repulican switched party to vote for Democrats

## Replicate Findings
The code is running on Python 3.9.12. To install necessary packages, run the following in terminal: `pip install -r requirements.txt`

Since the data is larger than 300mb, I zipped it. Once you clone the repository and unzip the data, change the path location in the Jupiter Notebook to replicate the findings


## How to cite
To cite this repository, use the following example BibTeX entry:
```
@misc{Huang2023,
  author = {Huang, Yuanning},
  title = {Abortion on Ballots and Senate Voting Outcome},
  year = {2023},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/macs30200-s23/replication-materials-yuanninghuang}},
  commit = {cccfa3b1f1971db9a4517132c7091d48ed357fc0}
}
```
