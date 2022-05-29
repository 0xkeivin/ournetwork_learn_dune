# token standards
- create tokens
- handle transactions
- track balances
## ERC20
- keeps track of fungible tokens (each unit is identical to rest)
- has 6 mandatory functions
1. totalSupply()
2. balanceOf(account)
3. transfer(recipient, amount)
4. allowance(owner, spender)
5. approve(spender, amount)
6. transferFrom(sender, recipient, amount)
- optional
1. Name
2. symbol
3. deci
## ERC721
- keeps track of non-fungible tokens (every token is unique)
- 9 mandatory functions
1. balanceOf(owner)
2. ownerOf(tokenId)
3. transferFrom(from, to, tokenId)
4. approve(to,tokenId)
5. getApproved(tokenId)
6. safeTransferFrom(from, to, tokenId)
7. setApprovalForAll(operator, _approved)
8. isApprovedForAll(owner, operator)
9. safeTransferFrom(from, to, tokenId, data)

## Dune decoding
- converts bytecode to easy to read tables
- 

## Common Table Expressions (CTE)