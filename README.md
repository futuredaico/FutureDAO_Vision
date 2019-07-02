# FutureDAO whitepaper

Bruce Liu v1.0

Table of Contents


1.Background:

1.1.     Trends of network community and cultural diversity 

1.2.     Start-up financing costs hinder creativity and cultural prosperity 

1.3.     Traditional Internet-based equity crowdfunding 

1.4.     ICO 's success and failure 

1.5.     IEO problems

2.Looking for a better ICO-DAICO

2.1.     Token bonding curve

2.2.     Two bonding curves financing model

2.3.     CO: continuous organizations

2.4.     CO two bonding curves financing model

3.FutureDAO

3.1.     Design philosophy

3.2.     Single bonding curve VS two bonding curves

3.3.     On-chain governance

3.4.     Off-chain governance

4.Compliance

5.Use cases

6.Value and significance

7.Summary









## 1.      Background:
### 1.1.     Trends of network community and cultural diversity:
The mobile Internet has built a huge online social network. In the first quarter of 2019, Facebook’s monthly active users reached 2.3 billion, while WeChat has 1.1 billion. Most of the world’s population has been linked through a few social networks, and people’s communication becomes convenient and close. Based on a widely connected social platform, different groups of people form niche communities with a certain culture as the core, and the ACG (Animation, Comic, Game) cultural community is the main form. These communities have a strong sense of cultural belonging and a strong willingness and ability to consume. Take gaming as an example. According to Newzoo analysis, global gaming revenue reached $137.9 billion in 2018, with more than 2.3 billion active players and over $1.1 billion paid players. As artificial intelligence technology matures, more and more manual labor and jobs will be replaced by artificial intelligence and robots. Human beings will spend more time on cultural products. Therefore, cultural and creative consumption will rise, and the creation of cultural and creative products will prosper.

### 1.2.     Startups’ financing costs hinder creativity and cultural prosperity
Cultural and creative products have the characteristics of niche and popularization. For traditional investment institutions and individuals, Whether the product is popular or not is uncertain, and the risks are high. At the same time, due to legal and regulatory reasons, the financing costs of startups are very high, which hinders the prosperity of cultural and creative products.

### 1.3.     Traditional Internet-based equity crowdfunding
The emergence of Kickstarter in 2009 provided a new Internet-based crowdfunding financing model for creative products, but the crowdfunding at Kickstarter is charitable donation, and there is no dividend right, so the funds that can be raised are limited. In 2018, the most funded Kickstarter project raised $5.2 million, and the 20th funded project raised $ 1.3 million. The equity crowdfunding developed based on Kickstarter is faced with strict government regulations. At the same time, it is difficult to become a financing method for creative products, as there is no liquidity due to the lack of exit channel for equity, and the small number of investment participants.
### 1.4.      ICO 's success and failure
After the emergence of blockchain platforms such as Bitcoin and Ethereum, ICO has become a new financing method based on blockchain smart contract technology. The cost of asset issuance is very low, and with the support of various blockchain token trading platforms, the tokens can be listed and traded for liquidity after being issued. Early investors’ exit time is greatly shortened. In 2017, ICO financing reached a climax. Arguably, the key factor for the success of ICO is its high liquidity. However, because ICO is not regulated, it comes with many ICO scams, causing losses to investors, and eventually, ICO is banned by mainstream countries. In a few countries, ICO is allowed only after its registration is approved by regulators, and the regulated ICO still does not reduce financing costs.

### 1.5.     IEO problems
After the ICO was banned, IEO became a new token financing mechanism in 2019. Through IEO, tokens can be directly listed and traded after financing. In order to attract investors, Project team usually pump prices after their tokens are traded, which costs them more money than financing itself. So IEO is not a financing tool. It is just a way to attract traffic, and at the same time, it has to pay a high cost. In order to recover the cost, the project team has to manipulate prices at the secondary market to earn profits. And early investors do not care about the actual value and significance of the project; they expect the project team to manipulate prices at the secondary market so they can sell for profits. Therefore, when the project team applies the IEO method to finance, the exchange, the project founders and the investors actually form a vicious community.  

The development of the blockchain to this day still hasn’t solved the problem of financing cost.

## 2.      Looking for a better ICO-DAICO
In order to avoid the shortcomings of ICO financing, many people have explored better ICO mechanisms. In 2017, Vitalik discussed DAICO, a combination form of DAO and ICO. In 2017, Simon de la Rouviere first proposed the token bonded curve as a concept of token issuance mechanism, while the Bancor project proposes a Bancor protocol as a token issuance mechanism, with the BNT token as a reserve. In 2018, Wilson Lau discussed the double bonding curve model as the project financing model.

### 2.1.      Token Bonding Curve
A bonding curve contract is a specific type of smart-contract that issues its own tokens through Buy and Sell functions. To buy tokens, the buyer sends ETH to the Buy function, which calculates the average price of the token in ETH and issues you the correct amount. The Sell function works in reverse: The contract calculates the current average selling price and sends you the correct amount of ETH (excerpt taken from Token Bonding Curves Explained).

The token bonding curve has the following characteristics:


* **Limitless supply**.There is no limit to the number of tokens that can be minted.

* **Deterministic price calculation**.The buying and selling price of the token increases or decreases with the number of tokens.

* **Guaranteed and immediate liquidity**.The bonding curve contract is the counterparty of the transaction and always holds enough funds in reserve to buy tokens back. So tokens can be bought or sold instantaneously at any time, the bonding curve acts as an automated market maker.
* **Continuous prices**.The price of token n is lower than the token n+1 and higher than the token n-1. Calculating the number of tokens minted for a given amount of usd/DAI (or the number of usd/DAI sent back for a given amount of tokens) requires some calculus.

**Algorithm model**：

The bonding curve can have a variety of calculation models, such as linear, exponential, and reciprocal. Let us take the simplest linear bonding curve as an example. The x-axis represents the quantity Q of the token issued, the y-axis represents the price, and the price can be used y =x to indicate. To buy the amount of Q(1)-Q(0) tokens at the Q(0) point, the total amount of money to be spent is the area of ​​the A.

![图片](https://github.com/futuredaico/vision/blob/master/fdpicture/%E5%9B%BE%E7%89%87%201.png)
 
 

### 2.2.     ‘Two bonding curves model’ for fundraising：
The basic model of the bonding curve is just a token issuance mechanism, but it does not consider how the project team obtains and uses the funds. Some of the early ideas were to establish a difference between buying prices and selling prices, and the difference was the capital of the project team, which can be used at the discretion of the project team. In 2018, Wilson Lau explored the use of ‘two- curve model’ as a financing mechanism.


### 2.3.      CO: Continuous Organizations
In 2018, thibauld established continuous Organizations .A Continuous Organization is an organization that issues fully digital securities called FAIR Securities by funneling part or all of its cash-flows into a Decentralized Autonomous Trust (DAT). A DAT is a smart-contract that automatically mints, burns, and distributes FAIR Securities (FAIRs) following a token bonding curve contract.

CO mainly achieves continuous fundraising for the organization through the ‘double curve model’ mechanism. The investor does not own the organization, and the organization decides the use of the fund.

### 2.4.     CO two bonding curves financing model
CO uses the double bonding curves model, one for the buy curve and the other for the sell curve: **B**（for**buy**）and**S**（for**sell）with**![图片](https://github.com/futuredaico/vision/blob/master/fdpicture/2.png)。![图片](https://github.com/futuredaico/vision/blob/master/fdpicture/3.png)

**Investment- buy（）**

The first (in "time", not in "proportion") source of cash-flows for a Continuous Organization are investors who want to invest in the Continuous Organization. They do that by calling the buy() function of the DAT. Whenever an "external" investor (as opposed to the organization itself) sends funds to the DAT, a fraction of the funds sent are being held in the "buyback" reserve by the DAT, and the rest of the funds are being transferred to the organization's wallet. We'll call I (for invest) the percentage of the funds being held in the buyback reserve. I is a constant.

![图片](https://github.com/futuredaico/vision/blob/master/fdpicture/4.png)

*Value flow when an investment occurs*

![图片](https://github.com/futuredaico/vision/blob/master/fdpicture/5.png)

*Impact on the Bonding Curve Contract of the DAT when an investment occurs*

The investors buying tokens are doing so to invest money in the underlying organization. Investors don't want their money to be held in reserve by the DAT; they want their money to be put to good use by the organization. Consequently, the value of *s* must be an order of magnitude lower than *b*.

*Example*：Let's say that an investor sends 10 ETH to the DAT if I=10% then the DAT will transfer 9 ETH to the organization's wallet and will keep 1 ETH in its "buyback" reserve.

When an investor buys *FAIRs* for a cost c, he receives x *FAIRs*, with x being equal to:

![图片](https://github.com/futuredaico/vision/blob/master/fdpicture/6.png)

with *c* the amount used to buy FAIRs, *b* the sell slope and *a* the number of *FAIRs* already in circulation before the transaction.


**Investment-sell():**

Investors can, at any time, decide to sell their *FAIRs* to get ETH back. They do that by calling the sell() function of the *DAT*. When the *DAT* receives *FAIRs*, it burns the received *FAIRs* and sends ETH back to the selling investor according to a function **S** (for *sell*). **S** has a slope *s* that increases discretely over time, every time the *DAT* receives a payment. The ETH sent back to the investor is taken from the *DAT* "buyback" reserve and does not affect the organization's cash reserve.

![图片](https://github.com/futuredaico/vision/blob/master/fdpicture/7.png)

*Value flow when a FAIR sale occurs*

![图片](https://github.com/futuredaico/vision/blob/master/fdpicture/8.png)

*Impact on the Bonding Curve Contract of the DAT when an investor sells its tokens*

**Calculus :**

When an investor sells *x* *FAIRs*, assuming no *FAIRs* were previously burnt, he receives an amount *c*, with *c* being equal to:
![图片](https://github.com/futuredaico/vision/blob/master/fdpicture/9.png)

with *s* the sell slope and *a* the number of *FAIRs* in circulation before the transaction.

For complete algorithm and proof, please refer[here](https://github.com/C-ORG/whitepaper)。

## 3.      FutureDAO
### 3.1.     Design philosophy
The core purpose of FutureDAO is to reduce the financing costs of startups or organizations, so protecting the rights of investors is the core idea of FutureDAO design. We hope to solve the problem of the lack of liquidity of small-enterprise equity through the bonding curve. At the same time, we believe that all investors jointly own the organization, have the decision-making power to use the funds of the organization, and vote to decide whether to pass a proposal for the use of funds or not.

### 3.2.     Single bonding curve VS two bonding curves
Under the single bonding curve financing mechanism, all funds are reserve funds, and the organization has the right to decide how to use all funds. The advantage of the single bonding curve financing mechanism is that when 51%  attacks occur, others can protect themselves by immediately exiting, but 100% reserve is conducive to speculation. In extreme cases, this model will be simplified to a FOMO model, and at the same time, a panic run may occur when whales exit, thus the organization's liquidity is exhausted, and there are not enough funds to support the project development. At the same time, under the 100% reserve system, when there are major conflicts in the community, it is impossible to clear the fund according to the shareholding ratio, because when the exit is about to happen, it is most beneficial to exiting from the bonding curve contract as soon as possible, so everyone will rush to exit, triggering a run.

Under the two bonding curves financing mechanism, part of the funds are used as reserves to support investors to exit at any time, and the other part is used as a project governance fund pool for project development. Exiting from the reserve pool does not affect the project funds, and there will be no panic run. The project is guaranteed to be safe. However, since the funds in the governance pool can only be used by voting, double bonding curves will face 51% attacks.

FutureDAO uses CO's two bonding curve model as a financing mechanism, and at the same time, manages organizational funds through a simple majority vote. Under the fractional reserve system, 51% of attacks cannot be eliminated, but we can increase the difficulty of 51% attack. 

### 3.3.     On-chain governance
#### 3.3.1.   Voting
FutureDAO achieves governance through a simple majority vote, and the investor's shareholding is the voting weight. In order to avoid the 51% attack problem, when the NO votes reach 30% of the total votes, the proposal is rejected. Since most people do not actually participate in governance, it is usually difficult to reach 30% of the votes. At this point, a simple majority vote is effective. But when there was an attack, and attack spread in the community, each investor would protect themselves by voting. The 30% votes required to veto a proposal does not completely avoid 51% attacks but increases the difficulty of 51% attacks to 71%.

#### 3.3.2.   Refunding
When there is an irreconcilable conflict in the community, such as core member quit, continued 30% NO votes to veto a proposal, or a project cycle has been completed, investors can withdraw funds from all funds，reserve pool and governance fund pool， according to their shareholding ratio. We can have a refunding proposal. When it reaches 30% (or other) of total votes, those who vote for the proposal can be refunded, they can take away funds from both pools according to their shareholding ratio, and their shares get burned, and the rest continue to manage the organization. Unlike 51% attacks which should be avoided, this type of refunding is benign, because at least the investor's funds are guaranteed, and the refunded money can be reinvested into other organizations, which is a process of resource redistribution.

#### 3.3.3.    Pre-minting
When a project is financing, it may not have an idea only but already has a team and the team have already done some work. In this case, the founding team can reserve a portion of the shares by pre-minting. However, pre-minting will lower the slope of the selling curve, which increases the difficulty of making profits for later investors. Pre-minted shares need to be locked for a certain period to avoid founding team fraud and provide incentives.

#### 3.3.4.   Seed funding
When a project starts to raise funds, the bonding curve should not be applied from the beginning. Instead, the threshold for starting funds should be set. When the financing threshold is not met within the specified period, the funds raised should be refunded completely to investors. We call it the seed round financing. Project owners can set the initial issue price and the amount issued, and start the application of the bonding curve after the threshold funds are reached. Because the seed round investors have an advantage in price, the shares of seed round investors should also be locked for a certain period.

### 3.4.     Off-chain governance
The core purpose of FutureDAO is to reduce the financing costs for startup organizations. It is not important whether the organization itself is a decentralized organization or a company. In fact, for the sake of efficiency, It is encouraged that the executive team is a company. The core of on-chain governance is how to use money and to avoid 51% attacks, without having to go into all the details of organizational governance. In theory, all members of the organization can initiate a proposal, but this should not be. The organization should have off-chain governance rules. For example, there should be a Council composed of executives and major shareholders. The Council is responsible for determining the organization's development strategies, setting budgets, and initiating proposals. At the same time, all shareholders can vote for supervisors to form a Board of Supervisors. The Board of Supervisors is responsible for supervising the Council and the executive team. It can be responsible for calling shareholders to vote against the proposal and initiate a major refunding. The Council may set a budget on a quarterly or annual basis, or a milestone basis. After the proposal is approved, the budgetary funds are left to the discretion of the executive team. In order to further increase the transparency of the use of funds, the Council and the Board of Supervisors can form a private DAO. The budget funds flow into the private DAO. A minority of people, including the Council and the Board of Supervisors vote to decide the use of funds, but all funds are available for public scrutiny.

## 4.      Compliance
We don't think FutureDAO's design need to necessarily fully complies with current financial regulations. We understand that the core purpose of regulation is to control risk, such as controlling money crowdfunded by start-ups. If we fully comply with SEC's crowdfunding regulations for startups, then the bonding curve does not work effectively. However, smart contracts are themselves a means of regulation. If we believe that rules can control risks, we can write them directly into smart contracts. DAO can have multiple means of controlling risks. For example, everyone can participate in the decision for the use of funds. For example, investors can exit from the reserve pool or get their money refunded, and we can also limit the maximum amount of money that can be used each year in the contract instead of controlling the amount of money financed. Therefore, within the DAO mechanism, the overall risk is controllable. The current regulatory rules are based on past technical conditions. When we have new technologies and mechanisms to control risks, we should not be bound by past regulatory laws. Otherwise, the potential of new technologies cannot be realized.

## 5.      Use cases
In theory, FutureDAO can be used as an equity financing management platform for any organization, but we believe that what fits FutureDAO is the cultural and creative startup with clear profit models and profitable expectations, such as gaming, animation, and so forth. We can organize the production of products through a DAO, and the product itself does not necessarily have to apply the blockchain technology. In the case of gaming, one game itself is not necessarily to be a blockchain game but maybe just a game catering to traditional game players, thereby increasing profit expectations. In the future, when the payment itself also occurs on the blockchain, we can form a complete trustless process of financing, payment, and dividends distribution on the chain. The interests and rights of investors are guaranteed to the most extent, thereby reducing investment costs and promoting the prosperity of investment markets.

## 6.      Value and significance
We believe that the DAICO platform has significant value and significance. Through the liquid reserve system and the on-chain governance mechanism, it reduces the financing costs for start-ups, especially for cultural and creative company’s financing, At the same time, when a startup starts financing through the DAICO platform, it already acts like a public company: fully open, co-governing, and shares can be traded at any time. The application of smart contracts and token economics reduces the management costs of distributed organizations, trade frictions, balances the rights and obligations between shareholders and executive teams, and promotes social innovation and prosperity.

## 7.      Summary
Mrs zuckerberg，Priscilla Chen said in an interview: "Luck should not be an important factor in success." The reason why luck is a factor is that the financing costs of small businesses in the past were too high, and many talented people have difficulty obtaining funds to show their talents. A reasonable DAICO model is, arguably, able to reduce the management costs of distributed organizations, financing costs, and make it easier for talents and funds to match so that talents can more easily reflect their value. It is the vision of FutureDAO to make talented people more successful and to make the culture of society more prosperous and rich.


 
 



