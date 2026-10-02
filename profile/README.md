# WakeUp Labs

We make it safe to automate what moves value.

We design, build, and operate production infrastructure for programmable value: payments, treasury, settlement, and protocol operations. The frame is the same every time: a mandate, a policy, an action, and evidence. We stay after go-live.

[wakeuplabs.io](https://www.wakeuplabs.io) · [Blog](https://wup.ar/blog) · [hello@wakeuplabs.io](mailto:hello@wakeuplabs.io) · [@wakeuplabs](https://x.com/wakeuplabs)

## Open source

Public code from systems we have built and operated. The headings are the industries on the site. Each title is the idea a team in that industry can reuse. The link is the repo.

Newer work is under [wakeuplabs-io](https://github.com/wakeuplabs-io). Earlier public repos are on [wakeuplabs](https://github.com/wakeuplabs).

### Financial services

Credit, treasury and settlement flows.

- **Hold the money until the condition is met, then release it.** [cdp-escrow](https://github.com/wakeuplabs-io/cdp-escrow). Escrow on Coinbase: funds sit until the rule says they move.
- **Collect from many customers and pay the right parties.** [cdp-collector](https://github.com/wakeuplabs-io/cdp-collector). Take funds in and distribute them, on Coinbase.
- **Put one deposit to work across several sources of yield.** [Vaulty](https://github.com/wakeuplabs/ArbitrumMiniApp-3-Vaulty). A single USDC deposit splits across four lending protocols. Live on Arbitrum One.
- **Move value without showing the amount or who was on the other side.** [starkware-private-erc20](https://github.com/wakeuplabs-io/starkware-private-erc20). A proof of concept for private transfers on Starknet.

### Consumer & retail

Loyalty, incentives and loops.

- **Let a customer exchange one balance for another, at the better price, inside the app they already use.** [BananitaSwap](https://github.com/wakeuplabs-io/Arbitrum-Miniapp1-BananitaSwap). A swap inside the Lemon wallet, sent to the better of two venues. Live on Arbitrum One.
- **Check a rewards payout against the list you published, before the money moves.** [velora-distribution-verifier](https://github.com/wakeuplabs-io/velora-distribution-verifier). For Velora (ParaSwap) reward and gas-refund distributions.
- **Let someone use an asset until a date, without giving them ownership.** [delegable-token](https://github.com/wakeuplabs/delegable-token). An NFT with a delegated user. Published as `@wakeuplabs/delegable-token`.

### Enterprise operations

Regulated flows with an audit trail.

- **A certificate that stays with the good, so a buyer or an auditor can check it.** [SiCFoBA](https://github.com/wakeuplabs/chaco-forestal). Built for forest certification. App: [chaco-forestal-client](https://github.com/wakeuplabs/chaco-forestal-client).
- **Prove a fact about a person without handing over the document.** [opid](https://github.com/wakeuplabs-io/opid). Identity credentials on Optimism (`did:opid`).
- **Nothing moves until the required people have signed.** [alpen-multisig](https://github.com/wakeuplabs-io/alpen-multisig). Desktop app for Alpen and Strata governance on Bitcoin: a proposal, the signatures, then the broadcast.

### Network infrastructure

Operate the network after go-live, including the fallback when a sequencer stops.

- **If the main rail stops, a customer can still force a transaction through and withdraw.** [arbitrum-connect](https://github.com/wakeuplabs-io/arbitrum-connect). Withdrawal from a child chain to its parent, with a fallback when the sequencer is down.
- **Check that something is true, where the transaction settles, without seeing the private data.** [noir-stylus-verifier](https://github.com/wakeuplabs-io/noir-stylus-verifier). An UltraHonk verifier for Arbitrum Stylus.
- **Let the team you already have write the fast programs, in TypeScript.** [assembly-script-stylus-sdk](https://github.com/wakeuplabs-io/assembly-script-stylus-sdk). Stylus contracts in AssemblyScript. Alpha: not a production bet yet.
- **A draw nobody can rig, and the money comes back if the result never arrives.** [Verifiable randomness](https://github.com/wakeuplabs/ArbitrumMiniApp-2-verifiable-randomness). A reference pattern. The demo is a game. Live on Arbitrum Sepolia.
- **What it took to put three of these into production: what held, what broke, what we would repeat.** [Final report](https://github.com/wakeuplabs/ArbitrumMiniApp-4-FinalMilestone). Closing write-up of the three Stylus mini-apps.
- **Show which contributions created impact, so funding can follow the evidence.** [optimism-making-impact](https://github.com/wakeuplabs-io/optimism-making-impact). Optimism governance and RetroPGF. Live at [retroimpactguidelines.xyz](https://retroimpactguidelines.xyz).
- **One account for the customer across every network you run.** [superchain-accounts](https://github.com/wakeuplabs-io/superchain-accounts). Creation, recovery, and gas across Optimism chains. Live at [superchainaccounts.xyz](https://superchainaccounts.xyz).
- **A dedicated network for one product, operated as a service.** [op-ruaas](https://github.com/wakeuplabs-io/op-ruaas). Rollup as a service on the OP Stack: CLI, marketplace, and console.
- **Ask what a balance or a rule was on a specific past date.** [rfg1-optimism](https://github.com/wakeuplabs/rfg1-optimism). Query any public view on Optimism as of a past moment. MIT.
- **A class a partner team can take, with a certificate at the end.** [Optimism workshop, class 2](https://github.com/wakeuplabs/Optimism-Workshop-Clase2). With OP en Español and L2 en Español. Certificate minter: [nftminterscript](https://github.com/wakeuplabs/nftminterscript).

## Company

WakeUp is a brand operated by TreeMansion LLC, a Delaware limited liability company.

The public site is in English, Spanish, and Portuguese.

- Site: [wakeuplabs.io](https://www.wakeuplabs.io)
- Work with us: [wup.ar/apply](https://wup.ar/apply)
- Email: [hello@wakeuplabs.io](mailto:hello@wakeuplabs.io)
