# ETL2.0

nfl_stats

Project Proposal - We will pull the top 100 all time nfl quarterback rankings from a recent usa today article (https://ftw.usatoday.com/2019/09/nfl-100-best-quarterbacks).

Then we will pull all-time passing statistics from Pro Football Reference on the top 100 players from the usa today article (https://www.pro-football-reference.com/leaders/pass_yds_career.htm).

Statistics include passing yards, touchdowns, interceptions, quarterback rating, passing attempts, passing completions and completion percentage.

Our goal is to analyze the rankings from the article (and possible bias) with relevant data from all-time passing statistics from the subject quarterbacks.

Extract - CSV (Pro Football Reference - stats) | HTML (usa today rankings)

Transform - Joined python dictionary of all data from both sources

Load - Mongo DB to store the data
