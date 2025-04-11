# Banking Preformance Analysis

## Background and Overview
GlobalTrust Bank maintains detailed client records but lacks strategies to leverage data for cross-selling, risk management, and client retention. This analysis uses loyalty tier, loan, and deposit data to identify revenue opportunities.  

This project uses SQL, Python, and Power BI to analyze loans, deposits, and loyalty tiers. The goal is to gather actionable insights that drive decision making for ....


## Executive Summary 

#Loyalty Program Inefficiencies
Gold Client Issues:
 -585 clients maintain $664K avg deposits (5% below Jade)
 -Yet carry highest credit balances ($3,281) - 16% above Jade
 -Potential to convert high-spenders into full-service clients

Platinum Tier Failure:
 -Low metrics across deposits ($611K), clients (317), and engagement
 -Performs below Silver tier ($658K deposits) despite "premium label"

#Deposit Findings: 
 - European clients hold 46% of deposits ($874M) and 2.6x more deposits than American clients ($874M vs $335M)
 - Over-reliance on one demographic increases vulnerability

#Loans Findings:
 - Middle-income borrowers dominate loans (53%) while high-income borrowers lag behind with 21%.
 - Economic downturns could disproportionately impact mid-tier borrowers
   
#Strategic Imperatives
 - Offer deposit incentives to convert Gold to Jade clients. This is to monetize their spending while growing deposits, other-wise Gold clients will be stuck in mid-tier profitability.
 - Rebuild or merge Platinum tier with Gold tier because it underperforms silver despite its premium label. Maintaining the underperforming Platnium label may drain company resources.
 - Target high income earners (engineers & doctors) because they only represent 21% of loans despite capacity for more. Relying on middle-income borrows (53% of loans) increases risk during recessions. 
