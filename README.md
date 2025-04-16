# AUDIT SUMMARY
<a href="https://x.com/0xdemonnn"><img src="https://img.shields.io/badge/-X-1DA1F2?&style=for-the-badge&logo=x&logoColor=white" /></a>


Hi,
On this Github repo, I will make a summary of all the vulnerabilities I have encountered in every project I have helped to secure.

*note : only include vulnerabilities with the MEDIUM / HIGH severity in this summary*

## Findings

|  Protocol  |  Protocol Description  |  Website  |  Severity  |  Finding  |
|------------|------------------------|-----------|------------|-----------|
|Open Dollar|A floating $1.00 pegged stablecoin backed by Liquid Staking Tokens with NFT controlled vaults|<a href="https://www.opendollar.com">Open Dollar</a>|Medium|<a href="https://github.com/Emanueldlvg/Findings/blob/main/Open%20Dollar%20-%20The%20delegatecall%20function%20does%20not%20change%20the%20storage%20in%20the%20target%20contract%20so%20the%20user%20cannot%20set%20the%20address%20of%20a%20user%20who%20can%20manage%20SAFE%20with%20the%20allowSafe%20function.md">*detail*</a>|
|Ethereum Credit Guild|A trust minimized pooled lending protocol|<a href="https://creditguild.org/">Ethereum Credit Guild</a>|Medium|<a href="https://github.com/Emanueldlvg/Findings/blob/main/ECG%20-%20Borrower%20loan%20can%E2%80%99t%20be%20called%20to%20AuctionHouse%20for%20a%20period%20of%20time%2C%20even%20if%20the%20borrower%20does%20not%20pay%20any%20repayment.md">*detail*</a>|
|Curves|The first interoperable SocialFi protocol. Buy, sell and trade SocialFi tokens across a universe of dapps|-|High|<a href="https://github.com/Emanueldlvg/Findings/blob/main/Curves%20-%20curvesTokenSubject%20may%20set%20referralFeeDestination%20to%20malicious%20address%20that%20cause%20gas%20griefing%20in%20_transferFees%20function%20and%20DoS%20the%20protocol.md">*detail*</a>|
|Spectra|A permissionless interest rate derivatives protocol on Ethereum|<a href="https://www.spectra.finance/">Spectra</a>|Medium|<a href="https://github.com/Emanueldlvg/Findings/blob/main/Spectra%20-%20The%20ERC-5095%20standard%20is%20not%20followed%20correctly.md">*detail*</a>|
|Revert Lend|A lending protocol specifically designed for liquidity providers on Uniswap v3|<a href="https://revert.finance/">Revert Lend</a>|Medium|<a href="https://github.com/Emanueldlvg/Findings/blob/main/Revert%20Lend%20-%20The%20ERC-4626%20standard%20is%20not%20followed%20correctly.md">*detail*</a>|
|Ondo Finance|Institutional-Grade Finance, Now Onchain|<a href="https://ondo.finance/">Ondo Finance</a>|Medium|<a href="https://github.com/Emanueldlvg/Findings/blob/main/Ondo%20Finance%20-%20%60rOUSG%3A%3Aburn()%60%20always%20revert%20if%20the%20account%20is%20not%20on%20the%20KYC%20list.md">*detail*</a>|
|DYAD|The first capital efficient overcollateralized stablecoin|<a href="https://www.dyadstable.xyz/">DYAD</a>|High|<a href="https://github.com/Emanueldlvg/Findings/blob/main/DYAD%20-%20Malicious%20actors%20can%20make%20deposits%20to%20other%20user%20DNFT%20ID%20to%20continue%20to%20block%20that%20user%20from%20making%20withdrawal.md">*detail*</a>|
|NOYA|NOYA enables AI Agents to direct omnichain liquidity trustlessly using ZKML|<a href="https://noya.ai/">NOYA</a>|Medium|*not yet published*|
|Renzo|A protocol that abstracts all staking complexity from the end-user and enables easy collaboration with EigenLayer node operators and a Validated Services (AVSs)|<a href="https://www.renzoprotocol.com/">Renzo</a>|Medium|<a href="https://github.com/Emanueldlvg/Findings/blob/main/Renzo%20-%20There%20is%20no%20slippage%20when%20users%20make%20deposits%20and%20withdraws,%20which%20may%20cause%20users%20to%20get%20less%20ezETH%20than%20desired.md">*detail*</a>|
|TempleGold|Temple Gold is a claim on future airdrops|<a href="https://templedao.link/">TempleGold</a>|High|<a href="https://github.com/Emanueldlvg/Findings/blob/main/TempleGold%20-%20Temple%20Gold%20token%20will%20lost%20if%20user%20using%20account%20abstraction%20wallet%20.md">*detail*</a>|
|TraitForge|The ultimate NFT game where your digital entities evolve, breed, and nuke for big ETH rewards. Mint, forge, and compete in this unique game|<a href="https://traitforge.info/">TraitForge</a>|Medium|<a href="https://github.com/Emanueldlvg/Findings/blob/main/TraitForge%20-%20pause%20and%20unpause%20functionality%20is%20not%20implemented%20in%20DevFund%2C%20EntityTrading%2C%20EntropyGenerator%2C%20NukeFund%2C%20EntityForging%2C%20and%20TraitForgeNft%20contracts.md">*detail*</a>|
||||Medium|<a href="https://github.com/Emanueldlvg/Findings/blob/main/TraitForge%20-%20There%20is%20no%20mechanism%20to%20withdraw%20remaining%20funds%20from%20NukeFund%20contract%2C%20this%20causes%20the%20remaining%20funds%20on%20NukeFund%20to%20be%20locked.md">*detail*</a>|
|Tadle|Tadle offers decentralized pre-market infrastructure facilitating the bridging of liquidity between primary and secondary financial markets|<a href="https://tadle.com/">Tadle</a>|Medium|<a href="https://github.com/Emanueldlvg/Findings/blob/main/Tadle%20-%20TokenManager%3A%3A_transfer()%20not%20compatible%20with%20fee%20on%20transfer%20and%20rebasing%20token.md">*detail*</a>|
|Sentiment V2|Sentiment is a decentralized onchain lending protocol, that enables users to programmatically lend and borrow digital assets|<a href="https://www.sentiment.xyz/">Sentiment V2</a>|Medium|<a href="https://github.com/Emanueldlvg/Findings/blob/main/Sentiment%20V2%20-%20The%20superPool%20contract%20cannot%20be%20paused%20and%20unpaused%20completely%20when%20needed%20(i.e.%20superPool%20is%20hacked)%20because%20none%20of%20the%20functions%20in%20it%20use%20the%20whenNotPaused%20and%20whenPaused%20modifiers.md">*detail*</a>|
||||Medium|<a href="https://github.com/sherlock-audit/2024-08-sentiment-v2-judging/issues/570">*detail*</a>|
|Boost Core Incentive Protocol|The Boost Protocol is a permissionless, trustless, and decentralized growth engine for protocol and application developers|<a href="https://boost.xyz/">Boost Core Incentive Protocol</a>|High|<a href="https://github.com/Emanueldlvg/Findings/blob/main/Boost%20-%20drawRaffle()%20cannot%20be%20call%2C%20this%20results%20in%20boost%20participants%20not%20getting%20their%20incentives.md">*detail*</a>|
||||Medium|<a href="https://github.com/Emanueldlvg/Findings/blob/main/Boost%20-%20Fee%20on%20Transfer%20Token%20can't%20be%20used%20for%20budget%20asset%20.md">*detail*</a>|




## Public Audit Profile
-  <a href="https://code4rena.com/@0xDemon">Code4rena</a>
-  <a href="https://audits.sherlock.xyz/watson/0xDemon">Sherlock</a>






##### DM for audit :)
