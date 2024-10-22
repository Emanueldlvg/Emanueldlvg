# AUDIT SUMMARY
<a href="https://www.linkedin.com/in/emanuel-febriano-29021996"><img src="https://img.shields.io/badge/-LinkedIn-0072b1?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://x.com/0xdemonnn"><img src="https://img.shields.io/badge/-X-1DA1F2?&style=for-the-badge&logo=x&logoColor=white" /></a>


Hi everyone,
my name is Emanuel Febriano or known as 0xDemon in WEB3 Security. 
On this Github repo, I will make a summary of all the vulnerabilities I have encountered in every project I have helped to secure.

*I only include vulnerabilities with the MEDIUM / HIGH severity in this summary*

## Findings

|  Protocol  |  Protocol Description  |  Website  |  Severity  |  Finding  |
|------------|------------------------|-----------|------------|-----------|
|Open Dollar|A floating $1.00 pegged stablecoin backed by Liquid Staking Tokens with NFT controlled vaults|<a href="https://www.opendollar.com">Open Dollar</a>|Medium|<a href="https://github.com/Emanueldlvg/Findings/blob/main/Open%20Dollar%20-%20The%20delegatecall%20function%20does%20not%20change%20the%20storage%20in%20the%20target%20contract%20so%20the%20user%20cannot%20set%20the%20address%20of%20a%20user%20who%20can%20manage%20SAFE%20with%20the%20allowSafe%20function.md">*detail*</a>|
|Ethereum Credit Guild|A trust minimized pooled lending protocol|<a href="https://creditguild.org/">Ethereum Credit Guild</a>|Medium|<a href="https://github.com/Emanueldlvg/Findings/blob/main/ECG%20-%20Borrower%20loan%20can%E2%80%99t%20be%20called%20to%20AuctionHouse%20for%20a%20period%20of%20time%2C%20even%20if%20the%20borrower%20does%20not%20pay%20any%20repayment.md">*detail*</a>|
|Curves|The first interoperable SocialFi protocol. Buy, sell and trade SocialFi tokens across a universe of dapps|-|High|<a href="https://github.com/Emanueldlvg/Findings/blob/main/Curves%20-%20curvesTokenSubject%20may%20set%20referralFeeDestination%20to%20malicious%20address%20that%20cause%20gas%20griefing%20in%20_transferFees%20function%20and%20DoS%20the%20protocol.md">*detail*</a>|
|Spectra|A permissionless interest rate derivatives protocol on Ethereum|<a href="https://www.spectra.finance/">Spectra</a>|Medium|<a href="https://github.com/Emanueldlvg/Findings/blob/main/Spectra%20-%20The%20ERC-5095%20standard%20is%20not%20followed%20correctly.md">*detail*</a>|


## Public Audit Profile
-  <a href="https://code4rena.com/@0xDemon">Code4rena</a>
-  <a href="https://audits.sherlock.xyz/watson/0xDemon">Sherlock</a>
