# ethereum landscape
1. ethereum."transactions" - calldata / signed tx
2. ethereum."traces" - sub-transactions that happen "internally"
3. ethereum."logs" - event logged at end of function call


## event logs
- "topics" are the identifier for the transaction
- topic 1 is the event signature

## traces


# SQL
- SELECT is for columns
- FROM refers to the table
- LIMIT is to limit first X rows
- WHERE is the conditional clause
- IN is shorthand for OR 

## hash address in sql
- uses '\x00000' instead of '0x00000'
- sometimes need to cast with '\x00000000...'::bytea


## quotes
- use double quotes for column or table ""
- single quotes for string

## numbers shifted
- 0 is shifted to 1 
- e.g. topic0 becomes topic1 in dune

## columns
- when functions are applied to columns, it will show as ?column?
- use ".. AS new_name" instead

## queries 
- timeout in 30 mins

## convert bytecode to address
CONCAT('\x', RIGHT(encode("topic2", 'hex'),40))::bytea

## 