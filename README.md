# lending_club_project

With technological advances, people can now invest in other people's loans using online peer-to-peer lending platforms like, Lending Club. So far the most straightforward metric for identifying risk / reward is available to investors: higher interest rate means more risk (lower investment grade), lower interest rate means less risk (higher investment grade). Attempt to identifying other features that should be used to identify whether a loan is going to performs poorly (Default or be Charged Off) or will do just fine (Fully Paid) using Machine Leaning techniques.

Goal of the project:

Given Lending Club data on 2M+ loans can we classify them into the defaulting ones vs fully paid ones? If we are an investor seeking to allocate some of our capital into asset-based lending, can we build a model that would flag problematic loans early on?

Seconday questions include: what drives a loan to default? are there any problematic demographic clusters that are correlated with high default rates?

Background knowledge:

The term “default” lacks specificity, as many credit card companies have moved away from using it to describe overdue card payments. In the strictest terms, an account is in default if you haven’t made a payment by the due date. However, the term has come to be used to describe any debt that the card issuer no longer expects to be paid in full.

When a credit card company has decided that the outstanding debt they’re owed is unlikely to be paid at all, they will typically “charge-off” the debt. What this means to the card issuer is the entire amount of the outstanding debt, plus interest and fees, goes onto their books as an uncollectable debt.

Target:

Out target then is to predict Charged Off and Defaults together, collectively, they will represent "bad" loans.

Implementation:

Lastly, we will connect the analysis and the model we build to the business needs.
