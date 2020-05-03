# The Financials of B2B SaaS

SaaS financials are simple compared to rewards financials. And much easier to work with than contracts for software built to spec. 

But SaaS financials introduce some new terms, acronyms, and formulae that you'll need to understand. Here's a quick overview of how companies make money with SaaS:

### Key Terms and Concepts

* MRR/ARR: Monthly Recurring Revenue/Annual Recurring Revenue
* LTV: Lifetime Value
* CAC: Cost of Acquiring a Customer
* MAU: Monthly Active Users
* Bookings: Customers begin paying MRR
* CAC Payback Period: Months of MRR required to cover CAC
* Churn: Accounts that stop paying MRR
* SLA: Service-Level Agreement 
* Net New Accounts: Bookings minus churn 
* R&D: Research and Development

That's it. 

Now, what they mean. (I apologize if this is elementary to you. It's important, though, that everyone understand these pillars of profit in the SaaS world.)

As Barry Kirk noticed during his time with a Silicon Valley startup, the startup world thrives on one number: bookings. The only things Bunch Ball's sales force was measured on were bookings and deal size. 

Barry tried to convince Bunch Ball (and their venture capital backers) that they'd eventually run out of companies to sell. To survive, Bunch Ball needed to retain some customers. But the culture of Silicon Valley was all about bookings and deal size. Apparently, growth (new customers) was then (and might still be) the thing that made for spectacular IPOs. And everyone in the VC business was in it for the epic IPO.

Bunch Ball recently sold to our competitor BI for about $6 million. Investors had dumped almost $100 million into the company since its founding in 2006. Despite having attracted many accounts with very big names, few of its accounts renewed for a second year. 

This brings us to our first principle of SaaS sales success: **Lifetime Value of a customer is the only way SaaS makes money**. 

### LTV: Lifetime Value

Lifetime value is a simple formula. It's revenue based. Lifetime value is the sum of monthly recurring revenue from a customer, from booking to churn. 

There are two ways (excluding price increases) to grow the LTV of a given customer:

* Longevity
* Upsell

The key to long-term success selling SaaS is to book customers with high potential to stick around, to increase their member base, and to add new features.

### CAC: Cost of Acquiring a Customer

Cost of acquiring is also a simple formula: CAC = (marketing costs(t) + sales costs(t)) / bookings(t), where (t) is a given timeframe. 

Using the CAC from the financial statement above, assuming we acquired 10 new customers in the timeframe given in the figure, our CAC is (12,000 + 15,000) = 27,000 / 10 = $2,700. 

This becomes important when evaluating a potential sale because of CAC Payback Period.

### CAC Payback Period

Another simple formula. We'll introduce MRR here, but we'll explain it a bit later. While MRR is easy enough, how it's arrived at can be rather complicated. 

CAC Payback Period is number of months required for MRR to cover the cost of acquiring this customer. 

CACPBP = CAC / MRR

Again, using the numbers from our sample financial statement, let's say the MRR from a new customer is $800. 

CACPBP = $2,700/$800 = 3.375 or 4 months

Assuming our sample company typically auto-renews each month with the option to cancel at any time, this new booking would have to renew at least 3 times to cover the cost of the sale. 

In our world, of course, the CAC is significantly higher, so the payback periods are much longer. We balance this with longer-term periods, of course, but most contracts allow the customer to churn with some notice and penalties before the contract expires. 

**CAUTION**: As more of our competitors shift to SaaS contracting, our ability to lock customers into long-term contracts with punitive termination terms will decrease. Sales Performance clients, for example, are likely responsible for their Salesforce.com contract, too. And, possibly, other big contracts from SaaS sellers. How long will it be before these clients start demanding auto-renewed annual subscriptions? Or, are we already seeing this demand?

**OPPORTUNITY**: How could we gain a competitive advantage by offering an auto-renewed, annual subscription that customers cancel at the end of any term? 



### MRR: Monthly Recurring Revenue

Monthly Recurring Revenue is the most important number in SaaS. MRR is composed of the total recurring revenue for the SaaS license. But that doesn't mean it's static. 

Typical components of MRR include:

* Basic usage of the software
* MAU fees
* Monthly active member fees
* SLA fees
* Add-on fees
* Data storage fees
* Data transmission fees


(**Monthly Active Members**: In most loyalty and incentive systems, users are individuals with a license to operate and administer the system to some degree, which "members" are participants. Member can often control how they experience and use the system, but Users control how everyone experiences and uses the system. BIE and CultureNext cloud this distinction a bit, but most in most systems like ours someone who is both a User and a Member would have two separate sets of credentials.)

MRR will vary from month to month as clients add or remove admin users, as members join or leave the program, as the client enables or disables add-ons (feature sets), or as any of the inputs to MRR change. 

In our previous example of $800 MRR, let's break that down. For simplicity's sake, let's also say that we did the smart thing and wrapped some of the technology variables into the basic license fee. The MRR breakdown might look like this

| Component | Contribution |
| --- | ---:|
| Basic License | $400 |
| MAU | $200 |
| MAM | $100 |
| Add-Ons | -|
| SLA | $100 |
| Total | $800 |

We used this $800 MRR at the time of the booking to calculate a 4-month (rounded) payback period. 

But, in month 3, the client enables the Recognition tool at $200 a month. This add-on triggers a bump in the SLA cost, so, beginning in month 4, the MRR goes to $1,020 a month. Our new MRR calculator looks like this:

| Component | Contribution |
| --- | ---:|
| Basic License | $400 |
| MAU | $200 |
| MAM | $100 |
| Add-Ons | $200|
| SLA | $120 |
| Total | $1,020 |

(We're using MRR instead of ARR because ARR is much more difficult to project without knowing how MAU and MAM will change over time and when clients will enable or disable various add-ons.)

The nice thing about MRR is that it provides an easy metric for targeting cross-sell and up-sell opportunities. It gives you clear levers for increasing the LTV of a given account without doing a bunch of math. 

### SLA: Service Level Agreements

SLAs in the SaaS world are totally different than SLAs in custom software, and while SaaS-style SLAs can be used in a non-SaaS system, you cannot apply custom SLAs to SaaS. 

One reason is environment. In a custom world, we could simply buy or lease more and better hardware to meet most of the demands of certain customers. A customer that requires 99.999, for instance, would built in an environment designed for that ridiculous level of availability. The other more reasonable customers could be deployed in an environment we can actually afford. 

But in SaaS, everybody is in the same environment. Additionally, SaaS products are composed of various other SaaS components that have their own availability and response SLA standards. BIE cannot have higher availability limits than the lowest availability limits of its constituent parts. We cannot, for instance, promise availability levels higher than Contentful's. 

Typical SLAs cover channel (email, phone, chat), response times, and availability by major component (admin portal, member portal, etc.) And SLAs are priced as a percentage of the base plus add-ons. This is because the base and add-ons, not the number of participants, is what drives support costs. Here's an example SLA option sheet:

/Screen Shot 2020-04-30 at 11.32.24 AM.png

We probably don't need to explain how a model like this reduces stress about SLAs. As an organization, though, we do need to realize that the SLA fees we collect might be given back in the case of SLA misses, which will happen. Therefore, **SLA fees should go fund R&D related to improving availability of the system (not features) and as a rainy day fund to pay SLA exceptions (which will happen to the best of systems).

### Churn

Churn is the number of customers who stop paying MRR in a given period. It means getting fired by the customer. 

Churn cannot be prevented, but it must be managed. And churn management begins with prospecting, cold calling, and pursuing clients. Pursue the wrong clients, and your churn will be high even if your product is great, your prices are wonderful, and customer success standards are top shelf. (Of course, good selling cannot prevent churn alone, but bad selling will lead to high churn.)

Different classes of accounts require different churn tolerances. For example, strategic accounts should have 100% retention, 0% churn, while down-market accounts might be able to tolerate 15% or 20% annualized churn, depending on the CAC payback period, etc. 

