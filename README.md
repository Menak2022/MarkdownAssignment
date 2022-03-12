# Markdown Assignment
# Williamena Kwapo
## Questions
#### 1. Which industries contributed the most to the Republican and Democratic parties? How much was contributed to each party?
##### *The Republican/Conservative industry contributed the most to the Republican party with a total contribution of $4,939,000.*
`!['Q1-Republican','This shows the top industries that contributed the most to the Republican party with Republican/Conservative industry being the top'](/Q1-Republican.png)`

**Image from a .jpg file in the repo*
!['Q1-Republican'](/Q1-Republican.png)
##### To answer this question...
    1. After cleaning the raw dataset in OpenRefine, I input the data into Google Sheets
    2. I create a pivot table in Google Sheets
    3. I set "Row" to Industry putting the "order" to descending and "sorting by" sum of amount.
    4. I set "Value" to Amount and "summarize by" SUM leaving "show as" in default
    5. I set "Filter" to Party and under "status" only checked R for which represents the Republicans party in the data
##### *The Entertainment industry contributed the most to the Democratic party with a total contribution of $1,880,000.*
`!['Q1-Democratic','This shows the top industries that contributed the most to the Democratic party with Entertainment industry being the top'](/Q1-Democratic.png)`

**Image from a .jpg file in the repo*
!['Q1-Democratic'](/Q1-Democratic.png)
##### To answer this questions...
    1. After cleaning the raw dataset in OpenRefine, I input the data into Google Sheets
    2. I create a pivot table in Google Sheets
    3. I set "Row" to Industry putting the "order" to descending and "sorting by" sum of amount.
    4. I set "Value" to Amount and "summarize by" SUM leaving "show as" in default
    5. I set "Filter" to Party and under "status" only checked D for which represents the Democratic party in the data
#### 2. How much did donors from the Misc. Business sector contribute to the Democratic party? Which donors were based in Miami Lakes, FL?
##### *Donors from the Misc. Business sector donated a total of $3,520,000 to the Democratic party. The donor that was based in Miami Lakes, FL was Windmere Corp.*
`!['Q2-MiscBusiness','This shows the total amount that Misc. Business sector donated to the Democratic party as well as the cities each donors within the Misc Business sector that donoated to the Democratic party is based or headquartered'](/Q2-MiscBusiness.png)`

**Image from a .jpg file in the repo*
!['Q2-MiscBusiness'](/Q2-MiscBusiness.png)
##### To answer this questions...
    1. After cleaning the raw dataset in OpenRefine, I input the data into Google Sheets
    2. I create a pivot table in Google Sheets
    3. I set "Row" to Sector, Donor, and City leaving the "order" in ascending. I kept each "sort by" as their respective names
    4. I set "Value" to Amount and "summarize by" SUM leaving "show as" in default
    5. I set "Filter" to Party, and Sector
    6. Under "Filter", I cleared all the original filters. 
    7. I then filtered Party for "D" only, and Sector as "Misc Business" only so that only one item was checked in the "status"
#### 3. What percentage of the tobacco industry’s donations does Philip Morris account for? How much is it?
##### *Philip Morris account for 70.82% of the tobacco industry's donations which was a total of $1,820,000*
`!['Q3-Tobacco','This shows the percentage of the tobacco industry's donation that Philip Morris accounts for as well as the total donated by Philip Morris'](/Q2-MiscBusiness.png)`

**Image from a .jpg file in the repo*
!['Q3-Tobacco'](/Q3-Tobacco.png)
##### To answer this questions...
    1. After cleaning the raw dataset in OpenRefine, I input the data into Google Sheets
    2. I create a pivot table in Google Sheets
    3. I set "Row" to Sector, Donor, "order" in ascending. I kept each "sort by" as their respective names and unchecked "total shows" under industry
    4. I set "Values" to Amount twice. For the first Amount, I put "summarize by" as SUM and "show as" in % of column. For the second amount, I left "summarizey by" as SUM and "show as" in default
    5. I set "Filter" to Industry
    6. Under "Filter", I cleared all the original filters. 
    7. I then filtered Party for "Tobacco" only to show donors in the Tobacco industry
    8. I looked for the role "Philip Morris" appeared in and found my answer
#### 4. Describe (in two to three sentences — no need for a detailed story pitch) one potential story from this dataset that you’d find promising if this were a project you were working on. Give it a headline. Include up to three types of sources you would call to report out the story and a few of the questions you might ask.
#### 5. 5.	What data might be suitable to join with this data to provide context or additional stories? Give me two examples.
