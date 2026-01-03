# baseergr
Tracking ETH Sent Per Block
total = sum(tx["value"] for tx in block.transactions)
print("ETH moved:", w3.from_wei(total, "ether"))
