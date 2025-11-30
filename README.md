Football Transfers – Age vs Transfer Fee Project
DSA210 Term Project – Umut Tekinalp

Project Proposal:
The goal of this project is to investigate whether younger football players are transferred for higher fees.
The football transfer market strongly emphasizes player potential, future performance, and resale value.

This study aims to:

Examine how player age relates to transfer fee.
Compare high-fee vs low-fee transfers.
Test whether age significantly affects transfer value.
Provide statistical evidence for or against the hypothesis that younger players are more expensive.
The project uses exploratory data analysis, visualization, and statistical hypothesis testing to support conclusions.

Data Description:

The dataset contains Premier League football transfer records, with each row representing a single player transfer.

Key variables include:

player_name – Name of the transferred player
age – Player age at the time of transfer
fee_cleaned – Transfer fee (in millions EUR)
club_name – Buying club
club_involved_name – Selling club
position – Playing position
transfer_movement – Inbound or outbound transfer
transfer_period – Winter or Summer
league_name, season, year, country

After cleaning, approximately 9,000 records contain valid age and fee information.

Data Collection Plan:

The dataset was obtained from a structured CSV file published as part of football transfer records.

The data was imported using pandas and cleaned by:

Removing missing values in age and fee fields.
Converting transfer fee strings to numeric format.
Creating a new binary feature:

high_fee = 1 if transfer fee ≥ dataset median, else 0.

All analysis operations (EDA, plots, t-test, correlation) were performed using:

pandas
numpy
matplotlib / seaborn
scipy.stats
No additional data sources were required; all work was done on the provided dataset.

Planned Outcome:

By the end of the project, the following outcomes are expected:

1. Understand age distribution of transferred players
Identify which age ranges are most common.
Visualize the distribution of ages.

2. Compare high-fee vs low-fee transfers
Use descriptive statistics and plots.
Determine whether younger or older players tend to receive higher fees.

3. Statistical Tests
t-test to compare mean ages of high-fee vs low-fee transfers.
Pearson correlation to assess the strength and direction of the relationship between age and transfer fee.

4. Final conclusion
Provide a clear, statistically supported answer to the main question:
“Are younger players transferred for higher fees?”


This project will deliver a full analytical report including data preparation, visualization, and statistical testing. The final findings will show whether age meaningfully influences transfer fees and how strongly this factor shapes the football transfer market.
