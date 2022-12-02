<p align="center">
  <img src="Lockbox.png" />
</p>

<h1 align="center">  
  <b>
  Lockbox: streamlined crypto treasury management
  </b>
</h1>

<h3 align="center">
  1st place on the Telos track at <a href="https://www.hackboston.xyz/" target="_blank">Hack Boston 2022</a><br/>
  1st place on the academy track at <a href="https://trondao.org/hackathon/" target="_blank">Tron Grand Hackathon Season 3</a>
</h3>

<p align="center">
  Check us out at <a href="https://getlockbox.xyz" target="_blank">getlockbox.xyz</a>
</p>

## What is Lockbox?
Lockbox streamlines managing shared funds. DAO treasuries, investing syndicates, VC firms with token portfolios, etc. all involve multiple individuals managing a shared pool of funds. Too often, these groups resort to disorganized spreadsheets (obviously insecure) or multi sigs (that can get locked out) to keep track of spending requests, approvals, and wallet permissions. We wanted to build software that was intuitive, secure, and flexible enough as organizations change (their membership, hierarchy, etc.). 

Setting up a Lockbox is simple: the address creating the contract (first to interact with Lockbox) is automatically made admin. From that point forward, those with admin roles can add/remove regular members from the organization. Any member or admin can deposit funds for a category or submit proposals that either 1) modify admin privileges (promote a member or demote an admin) or 2) propose spending decisions. Proposals require a simple majority from admins to be passed, with each admin provided 1 vote per proposal (can be withdrawn before approval). Regardless of how decentralized your organization is, we believe that this structure of admins and proposals is the most fundamental way of making decisions. 

To reiterate the novelty and uniqueness of Lockbox, we believe it is a major improvement on multi sigs (the current dominant way of treasury management for groups) because having specific category budgets and proposal listings makes it clear and easy to know the purpose of funds/spending. We all learned so much in the past 24 hours; from dealing with annoying properties of Solidity (so many mapping errors) to React debugging, we definitely stretched ourselves to make a usable and awesome final product. Lockbox works with any EVM-compatible blockchain, and we hope that its ability to streamline and automate a lot of the fund management process will lead to greater and safer crypto adoption!

## FAQ

- __Who should use Lockbox?__
  Any group with shared funds! DAOs, investment clubs of friends, or even institutions holding tokens could all benefit from a more secure a streamlined fund management system.
  
- __What do I need to do to use Lockbox?__
  Deploy a lockbox solidity contract or go through the website. All that you need is a wallet and addresses of other members, admins, or places to send funds!
