# Zachary P. Malosh, MS, MBA

+ [LinkedIn](https://www.linkedin.com/in/malosh/)
+ [Github](https://github.com/zmalosh)
+ [Atlantis Intelligence](http://atlantis.soccer) - Soccer Prediction Dashboard
+ [NCAA FB - 2018 FBS Clustering (Excel)](https://malosh.z14.web.core.windows.net/Fbs2018.xlsx) - Team Clustering by Division
+ [NCAA FB - 2018 FCS Clustering (Excel)](https://malosh.z14.web.core.windows.net/Fcs2018.xlsx) - Team Clustering by Division

## Next Project Idea - League Strength by Transfer Network
Determine the strength of a league based on the leagues that its teams perform transfers with. In general, leagues would be expected to perform transfers with similar-level leagues. 

+ Assume league A has many transactions with league B, so leagues A and B have a strong relationship.
+ Assume league B has many transactions with league C, so leagues B and C have a strong relationship.
+ If leagues A and C have a weak relationship, B is similar to A and C but A is not similar to C. This would be interpreted as the league strengths being ordered as A > B > C or C > B > A. Relationships with other leagues would be required to determine which order is appropriate.

By assuming that the "Big 5" leagues (Premier League, La Liga, Bundesliga, Serie A, Ligue 1) will be at or near the top of the rankings, the rest of the leagues should fall into place based on the relationship strength between leagues.

The goal would be to create a single numeric value to allow for comparison between leagues and, ultimately, create a league power ranking.

The following are considerations for this analysis:
+ Transfers vs Loans vs Free Transfers - How do each contribute to the strength of the relationship between leagues?
+ Designated competition for teams transitioning between leagues 
  + Would 2019 Fulham be EPL, Championship, or some fraction of both?
  + Are promotion and relegation treated the same? If going down, a team may be more likely to sell off players when compared to the buying practices of teams being promoted.
+ Geographic considerations - teams tend to transact with leagues near them
  + How do same-country transfers count?
  + How do same-league transfers count?
  + Are there distance considerations? It is easier to scout other teams near you, especially on a limited budget.
  + Do culturally similar countries count less?
    + Will former USSR countries transact more with Russia due to cultural similarities?
    + Will countries speaking the same language transact more?
+ Impact of academies - large teams with academies will have more players with skill levels not consistent with the top-flight team. How do those lower-level transactions count toward the parent club?
