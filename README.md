# DataSets use
pd_dis_demo.head()
Columns: State, District, Population, Area (sq km), Density
pd_dis_txn .head()
Columns: State, District, Transaction Count, Amount (INR)
pd_sate_dev.head()
Columns : State	,Year,	Quarter,	Brand	,Registered Users,	Percentage
pd_ad.head()
Columns : Code,	State,	Correct Name,	Year	,Unnamed: 4,	Quarter
pd_txn.head()
Columns : State,	Year,	Quarter	,Transaction Type,	Transactions,Amount (INR),	ATV (INR)
pd_state_t_u.head()
Columns : State	,Year,	Quarter,	Transactions	,Amount (INR)	,ATV (INR)	,Registered Users,	App Opens


Analysis Performed:
1. Target Low-Density Areas with Digital Literacy Campaigns . i  Since population density has only a weak correlation with digital transaction volume, rural or less dense areas may be underutilizing digital platforms.
 ii  Action: Launch awareness and onboarding campaigns in these regions to promote digital transactions (e.g., UPI, wallets).'
2. Don not Assume High Population = High Adoption. i.Some high-population districts are not showing proportionally high transaction volume.
 ii .Action: Identify such districts and investigate barriers — possibly lack of banking infrastructure, awareness, or trust.'
3. Focus on Transaction Quality (Per Capita Metrics) i Correlation with total transaction value is misleading in large districts. Per capita transaction value gives a better measure of adoption and intensity.
 ii.Action: Calculate and monitor Amount (INR) / Population for more accurate insights on adoption levels.'
4. Use Transaction Count as a Key Performance Indicator.i  Since transaction count is highly correlated (0.98) with total value, it is  a reliable proxy for digital engagement.
 ii  Action: Focus on increasing transaction frequency per user rather than just expanding user base.

📌 Final Thought:Digital transaction growth isnot just about population — it is about access, awareness, and trust.Focus your strategies beyond demographics to truly drive financial inclusion.
