This is a list of candidates for U.S. midterm election 2018 with their twitter handles, compiled by [Yiqing Hua](yiqing-hua.com) from Cornell Tech.

*This is an ongoing project. Star this project for updates!*

# List of Candidates
We first retrieve the full list of candidates running for House and Senate, as well as gubernatorial candidates from [Ballotpedia](https://ballotpedia.org/List_of_candidates_running_in_U.S._Congress_elections,_2018).
Those who haven’t passed the primary election are filtered out (except for candidates in Louisiana, where the primary election is held with the general election).
This includes a list of 967 candidates, 505 democrats, 459 republicans and 4 independent candidates from 50 states.

# Twitter Handles
We obtain the candidate twitter accounts by manually verifying the campaign accounts listed on their ballotpedia pages, campaign websites and including their personal or office account (as an incumbent) if there’s any.
924 candidates have at least one twitter account.

# Candidate Gender
We obtain the gender information of each candidate by predicating their gender using first name using a [Python gender guesser package](https://pypi.org/project/gender-guesser/).
We manually examine the gender of candidates when the library indicates uncertainty of its gender guessing result.
Our dataset includes 268 female candidates and 656 male candidates.

# Data Format
Each line of the csv file represents a candidate Twitter account. This data was collected in September, 2018. As information on Twitter can be updated, some of the account profile here might be outdated. The data entries of each account include:
- `candidate_name`: Name of the candidate as on Ballotpedia.
- `gender`: Gender of the candidate.
- `party`: Party of the candidate.
- `position`: The position that the candidate is running (house, senate or governor)
- `state`: The state where the candidate is running.
- `district`: The district number where the candidate is running (if running for House).
- `twitter id`: ID of the account.
- `twitter handle`: Handle of the account.
- `twitter name`: Name of the account.
- `url`: URL contained in the Twitter account.
- `created_at`: Creation time of the Twitter account.
- `description`: Description of the Twitter account.
- `followers_count`: Number of followers of the account.
- `friends_count`: Number of friends of the account.
- `location`: Location of the account.

# Contact
Yiqing Hua
yiqing[at]cs[dot]cornell[dot]edu
