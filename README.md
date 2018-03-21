
## Blockchain
Reference at: https://hackernoon.com/learn-blockchains-by-building-one-117428612f46
|               |                    |
|----------------|-|
|**Fields**			 |chain = []					             |
|      |current_transactions = []			         					 |
|**Methods**           | new_block()|
|      |new_transaction()	 |
|      |hash(block) 	 |
|     |last_block()	 |

**Block**
|                |Block 0                        |Block 1                      |
|----------------|-------------------------------|-----------------------------|
|ID				 |0					             |1					           |
|Timestamp       |1521661194 			         					 |1521662567            |
|Data            |[amount:1000, from: user_id,where: anotherUser_id ]|[amount:50, from: user_id,where: anotherUser_id ]|
|Hash       |6c14da109e294d1e8155be8aa4b1ce8e	 |8542516f8870173d7d1daba1daaaf0a1     |
|PrevHash       |0 	 |6c14da109e294d1e8155be8aa4b1ce8e          |
|Proof       |324984774000 	 |3446546545650          |
## Wallet

Functionality for work with the block. A user account, transactions and other interface will be designed during the development process