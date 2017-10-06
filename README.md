# Safe Harbour Investment Pledge

#### The Safe Harbour Investment Pledge (SHIP) is a safe, sane way for cryptocurrency investors to engage in early-stage projects.

**SHIP** is a smart contract that pledges funds for a _future_ presale and donates a small percentage up-front to serve as no-strings-attached seed funding.

The rest is held in escrow for a minimum "incubation" period which gives developers time to prove themselves, and pledged funds serve as a publicly visible measure of community support. 

Investors are incentivised to pledge early, but can back out and recover all funds (less donation) should the project not produce a desirable outcome.

## In Human Terms

If this were a written agreement, it would look something like this:

> I _[investor]_ pledge _[amount]_ to _[project]_, _[percentage]_ of which will be donated up-front to the project and the remainder of which will be reserved for participation in a future presale.
>
> I agree to have my pledged funds (less donation) held in a publicly visible escrow until either:
>   1. The presale occurs
>   2. The incubation period of _[period]_ from the project start elapses
>
> I reserve the right to:
>   1. Participate in any presale that is offered to holders of this agreement
>   2. Abstain from the presale should I not agree with the terms
>   3. Choose how many presale rounds I participate in should there be more than one
>   4. Withdraw any pledged funds after the incubation period ends, or leave them pledged at my discretion
>   5. Withdraw any pledged funds that are left over after the presale due to abstinence and/or presale cap conditions
>
> I release all rights and expectations pertaining to the donated amount, and give _[project]_ sole discretion over how the donated amount is spent.

## Benefits

There are plenty of good reasons to adopt the Safe Harbour Investment Pledge:

### More time

For <b>developers</b> to:
- Find product to market fit and pivot if need be
- Demonstrate progress and establish a reputation
- Build, engage with and learn from a community of investors
- Develop solid economic models and obtain peer review
- Build and ship a real product that can be sold in the presale

For <b>investors</b> to:
- Make considered investment decisions insulated from a FOMO-driven market
- Interact with developers and understand the <i>people</i> better before committing

### More transparency

For <b>developers</b> into:
- Market opportunity via investor validation
- Customer and investor feedback/sentiment
- The potential size of the presale

For <b>investors</b> into:
- The ability of the developers to deliver tangible results
- The level of real community backing a project has
- The downside of early-stage investments

### More freedom

For <b>developers</b> to:
- Focus on engineering and shipping a working product without getting distracted by marketing and legal concerns (until the right time)
- Fund and build a business that uses a token to solve a real problem OR doesn't use a token at all - and let the right decision emerge organically
- Fund any kind of business with cryptocurrency - even a physical product

For <b>investors</b> to:
- Commit their funds incrementally in accordance with real progress
- Commit to a presale at a price that makes sense for them
- Get guaranteed participation even in a capped presale

### More safety

For <b>developers</b> to:
- Build an open-source product or platform without worrying about losing market share to copycats
- Iterate on and develop their idea without having to worry about the legalities and practicalities of managing investor money

For <b>investors</b> to:
- Support early-stage projects without exposing themselves to unlimited downside and without entrusting a fledgling company with 100% of the balance up-front

## How it Works

### Pledge
- Investors pledge an amount of ether to the SHIP Contract to register their interest in a project
- A donation percentage (e.g. 5%) is awarded immediately to the developers, and the rest is held in escrow by the SHIP Contract until one of the following happens:
  1. The developers deploy a presale contract and the investor commits their funds to the presale
  2. The presale finishes and the investor instigates a refund for either uncommitted or leftover funds
  3. The incubation period ends and the investor instigates a refund (if they are not satisfied with progress/opportunity)

### Incubation
- Developers have a fixed period of time (e.g. 6 months) in which investor funds are locked - this provides a safe period in which developers can focus without worrying about losing support, but also prevents funds being held indefinitely
- The incubation period starts the moment pledges are opened
- Over the course of the incubation period the donation increases from an "initial" to a "final" percentage to encourage early investment and improve cash flow
- After the incubation period ends, developers are fully responsible for retaining investor's interest
- Investors can continue pledging after the incubation period ends

### Commit
- When developers have completed the presale contract (and all prerequesite tasks), they "deploy" the presale to the SHIP Contract and indicate the presale structure (number of rounds, round caps)
- Following deployment, investors have a fixed window (e.g. 7 days) in which to evaulate all available materials and signal full committment of their funds to the specified number of rounds (investors do not have to participate in all rounds)
- During the committment phase, existing investors may commit additional funding and new investors may join by committing
- If the developers identify an issue and wish to change the presale contract, duration or rounds/caps, all prior committments are invalidated and the process starts again

### Presale
- After the committment period ends, the developer can begin the semi-automated presale process
- If the cap for a given round is less than the total amount of funds committed, each investor is awarded a proportionate amount of the cap (e.g. if the cap is 50% of the total committed funds, each investor will have half of their funds committed)
- An investor will not receive a larger share of earlier rounds by abstaining from later rounds

### Completion
- After the presale ends, investors who still hold pledged funds may issue a refund

## Supported Presale Models

All of the following options are provided:
- One round or multiple rounds (where earlier rounds deliver higher value / lower prices to investors)
- Capped, uncapped or a combination (e.g. one capped round and another uncapped)

SHIP is not an ERC20 token and does not require the use of an ERC20 token in the presale.

## Questions

### How much should the donation be?
- The initial donation should be high enough such that moderate interest (e.g. $2-3m in pledged funds) should generate enough funding (e.g. $100-$150k @ 5%) to make a significant iteration and attract more pledges
- The initial donation should be high enough such that pledges signal real committment to a project, not just "parking"
- The final donation should be low enough to represent an acceptable immediate loss for the investor

## Project Status
This project is currently in concept phase. The contract compiles, but has not been tested or audited.

Following community feedback, a suite of unit tests will be developed and a security audit will be sought.

Contributions welcome.
