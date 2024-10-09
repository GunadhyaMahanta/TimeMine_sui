
[Alpha  Telegram](https://t.me/+xIQLofb3wKQ2YjM1)

About
----------------------------------------------------------------------------------------------------------------------------------
$TIME is a Proof-of-Time based cryptocurrency with a fair launch, mineable by everyone. Everyone gets a fair chance to mine and earn rewards! 

How it works
----------------------------------------------------------------------------------------------------------------------------------
In the name of time, $TIME Treasury supplies 1 $time coin per hour. Each second is considered an epoch, offering everyone a validation opportunity. This validation involves the current time, miner's address, and current difficulty. Miners who successfully validate will be fairly rewarded with TIK coins based on their share. In other words, a reward of 2.7777778*10^-4 TIK is supplied every second. 

- The validation algorithm: (blake2b256(timestamp&address) as u128) mod difficulty == 0
- Difficulty: (Number of miners who mined blocks in the previous 30 epochs / 1000) + 24
- Shares: The base share is 10, and it can be increased through "lock". Each day of lock increases the share by 1. The maximum is 60.
- Ecosystem: One $time  per hour, 99% for miner and 1% for community. Continuously, until the end of time.

Smart Contract
----------------------------------------------------------------------------------------------------------------------------------

- Shared Object Treasury: has the Treasury cap to mint $TIME.
- Shared Object Miner: record proofs for each miner.
- Shared Object Epochs: Record the total shares and number of miners for each epoch.

----------------------------------------------------------------------------------------------------------------------------------
$TIME is powered by [sui](https://sui.io/) - a new, horizontally scalable layer-one chain, promising revolutionary transaction speeds at low cost.  


Ready to start mining? Check this out: [CLI](https://github.com/GunadhyaMahanta/TimeMine_sui_cli)
