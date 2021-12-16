## Lending Club Data Analysis:

### Lending Club - its Business Model, Advantages ....

Lending Club is a online money lending platform that follow a peer-to-peer lending (P2P) business model. P2P lending (also known as crowdlending or marketplace lending) lending is a crowdfunding type that allows individuals and institutional investors to provide debt financing to a consumer (natural person) or business borrower (legal entity) in the form of a loan agreement that includes the obligation to repay the loan amount including interest (if any).
 
The primary stakeholders in P2P lending are borrowers and lenders who are generally referred to as investors. The P2P platform role is of an intermediary which supports the whole process and all stakeholders. 

For borrowers, they need to maintain their profile by meeting the terms of loans continuously, then approval to the future requirement of loans becomes much easier and they don't have to go through the documentation process. They can get loans approved at a competitive interest rate, flexible repayment terms and a fast online application process. Like advantages, there are certain disadvantages such as, there is no surety that a borrower’s profile will be accepted for loan approval. And, if the loan amount is higher, the borrower has to pitch to a larger lender base to meet all your requirements.

For investors, P2P lending offers a great deal to their money as an alternative source of investing. Investors can browse the loans on the platform and build a portfolio of loans. The minimum investment an investor can make is just $25 per loan. Each portion of a loan is called a note and smart investors build a portfolio of notes to spread their risk among many borrowers. 

The investor or the lender can earn higher interest rates on their investment in a range of 15-30%. The investments have predictable and stable returns and act as a great asset class for portfolio diversification. An investor can also have greater control over their money, like whom to lend. The risks are even higher compared to borrowers. All the loans issued on P2P platforms are unsecured in nature and the platform also doesn’t guarantee its performance. If the borrower defaults on his loan payment, it will directly affect the investor.

Advantages of Lending Club over other P2P Lenders are:
- **Lower Interest Rates for Borrowers:** Lending Club provides loans at a competitive interest rate and its rates tend to be lower for borrowers with similar risk profiles.
- **Minimum Personal Loan Is $1,000:** As an individual borrower, Lending Club allows loans as small as $1,000 without any high monthly repayments that a larger loan would bring.
- **Business Loans Available Up to $300,000:** Lending Club offers loans of up to $300,000 to entrepreneurs and established business owners which is higher than some smaller competitors.
- **Lower Origination Fees:** Lending Club’s origination fees (upfront fee charged by a lender to process a new loan application) offer a better deal than other online lenders. For instance, Lending Club borrowers with an A rating pay origination fees between 1% and 3% on 36-month loans, depending on their sub-rating.
- **Lower Default Rates:** Among competing P2P platforms, Lending Club historically offers the lowest rates of borrower default. Since 2010, its default rate has been anywhere from 0.5% to 4%. This means that you may see fewer losses as an investor. 
- **Niche Solutions for Patients and Car Owners:** Lending Club’s Patient Solutions and auto refinancing loans are great for one who is preoccupied with hefty medical bills or legacy car loans issued when rates were much higher (or their credit was much poorer).

Lending Club, makes money by collecting fees from both borrowers and investors. The borrower fees depend on various factors such as credit history and rating, the borrowing amount and total debt-to-income ratio. Incase of investors a service fee of one percent (1%) of the amount of any borrower payments received by the payment due date or during applicable grace periods and a collection fee of up to 40% on all amounts collected on a delinquent loan (net of legal fees and expenses) to the extent any litigation has been initiated against the borrower or Up to 30% on all amounts collected on a delinquent loan in all cases not involving litigation.


References:
- www.lendingclub.com
- www.thepennyhoarder.com/bank-accounts/lending-club-vs-prosper/
- www.lendacademy.com/lending-club-review/
- www.goodfinancialcents.com/lending-club-review-for-investors-and-borrowers/
- www.moneycrashers.com/lending-club-review-peer-to-peer-lending/


---
### About Project

In this project, I analyzed data from an online lending platform, Lending Club with 100K observations. The goal is to develop different models to predict which loans are at risk of default. Different models - Decision Trees, Random Forest, Boosting models, linear models were built to predict default rate of loans and devise an investment strategy.

First data exploration is done on the entire 100k observations to develop an understanding of loan grades and subgrades and how they may relate to default and returns performance, loan purpose and any relation to performance, analyses of returns from loans, etc. Then I also had to look into missing data, and how to address this. While the data carries information on over 100 variables, we need to determine which data will be available when looking to invest in a loan i.e, removing data leakage variables — since our goal is to develop a model to predict loan default and then decide which loans to invest in; such a model will thus be only able to consider variables available before a loan is issued.

Later, the subsequent task is to develop models to identify loan status ‘fully paid’ or ‘charged off’, and evaluate these. We will also consider investment performance corresponding to these models and identify the best model.

---
