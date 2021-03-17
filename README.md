# Large Scale Data Processing: Project 1 Report
## Group Member Name: Hengrui Xie, Yinzhe Ma
## Eagle ID: 57807123,52133365

## Question 1
1. K=2: xS=216859874this_is_a_bitcoin_block_of_52133365_and_57807123, hash value=00f99ad44474296b34066661a008389ed7f5cd92092cae2dc830fc5ce287556f, time=1s, 2. trials=10000
2. K=3: xS=1744195699this_is_a_bitcoin_block_of_52133365_and_57807123, hash value=0007fef841a3de454a0a1f40020f5413a40f851a416f7f5af7723a51f37eb86d, time=2s, 3. trials=10000
3. K=4: xS=1212091877this_is_a_bitcoin_block_of_52133365_and_57807123, hash value=00000cef060321adadefe8459158519fe2c9a4d5f854001482f69dbffd62c6d3, time=2s,trials=100000
4. K=5: xS=1066350209this_is_a_bitcoin_block_of_52133365_and_57807123, hash value=00000e263b15b3b2d947d80cf079c54eadc850a77a1c7f38ca820042ed54bae8, time=6s,trails=5000000
5. K=6: xS=1304221970this_is_a_bitcoin_block_of_52133365_and_57807123, hash value=000000885ea896b5372baec4120fc4c6b1176b2664e4d0cdbd51510f6d9f61a6, time=40s,trails=50000000

## Question 2
K=7: xS=1691073514this_is_a_bitcoin_block_of_52133365_and_57807123, hash value=000000044c2ffc496f289f6f5aaca8ed97a7f8c2a3872a3861899739cbe646a9, time=1812s,trails=500000000, machine type=n1-standard-4, CPU=20%

## Question 3
This would not because ideally, we want hash function to randomly hash any value into a bucket with equal chances; so two different and independent values would have the same probability of being hashed to a hash value with k leading 0s.
