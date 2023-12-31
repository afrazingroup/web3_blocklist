# web3_blocklist

## NOTE: The automation to update the master blocklist has been disabled for now. The polygon specific blocklist is still regularly updated. Please refer to these blocks lists directly in addition to the Polygon Labs specific one:

Metamask
(https://raw.githubusercontent.com/MetaMask/eth-phishing-detect/master/src/config.json)

Scam Sniffer
(https://raw.githubusercontent.com/scamsniffer/scam-database/main/blacklist/domains.json)

Phantom Wallet
(https://raw.githubusercontent.com/phantom-labs/blocklist/master/blocklist.yaml)

========================

This repository contains two lists. The first list, polygon_blocklist.json, contains domains that are impersonating Polygon as part of a malicious campaign.

The second list, blocklist.json, is a merge of all the web3 blocklists that I can find that are open source. Credit goes to the fine security researchers who are flagging domains everyday to the benefit of the web3 community, I literally just dedup them into one list.

Lists are pulled from their sources every two hours. The sources themselves might add or remove items from their respective lists at different frequencies.

When I add domains for actors impersonating Polygon I verify each one is malicious to a reasonable degree, but false positives are possible and will be corrected upon request.

I do not verify domains pulled from trusted sources are malicious myself, I rely on the sources to verify.

# Current Sources

Metamask
(https://raw.githubusercontent.com/MetaMask/eth-phishing-detect/master/src/config.json)

Scam Sniffer
(https://raw.githubusercontent.com/scamsniffer/scam-database/main/blacklist/domains.json)

Phantom Wallet
(https://raw.githubusercontent.com/phantom-labs/blocklist/master/blocklist.yaml)

