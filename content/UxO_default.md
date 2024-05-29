1. List of wallets

0x77FDf95dC7B04CC0c94b9449747fF6fE98d14885

0x8AD6bB30586Aa256f30C2B7060869967E732b97e

0xf361b12C004b2f1ee98139aB7d4494d4C968016D

0x9bA8AbBb748d667da608C3AedB7251725461aC41

0x81BE83cfd1C0f83a811bF972E8d67D11be965828

0x686e922dd2394384c1bBe91C4E734f66e65c824d

0x677f7B6ABD4F731b1FfB2f8d3273368312bc7681

0xdE6317739e36468FE0a4f24816d0053657B8B7bC

0xF9Cb8874B516b0aE463e2a0793433B61dA33745f

0xD2ef72e7D444eB4a7339E20c7b71A3AF1683F5E0

0x010549a9D5AB1D1f04f471F997bB27992aBb2316

0xc03b2cE6e064C1231c1bC2832E57908aC109B0A8

0x1462B27DdbD9a16d8c4B963cc4aB66AdbD607591

0x6031Bf4370CB59c3a08146dA90f702bB68480a1B

0xdc295D5E4583e59dE1F4e234eB231c93Db9b7970

0x746fD0e1D4d58C58916Dcd3D92EFF6E889580bf5

0xBA561B70911E5d05953094145467c3e3E24Ddd52

0x5AfDB3033524A699D57e8443F47CC2B07dCC5043

0x1a0b1307e260b0Df20E7838d1f6cC8970d49C7A8

0xBFfA02AbfaD7Ece80A2c36Ee44A73a8a779E7e1F

0x2f9f45a78b9CE7F030fA19Eb3381C58A3D70559D

0xcc13887A2dd8a9e6d7ab16d48c6f67d9033F74C5

0x1223909A770A2f591Dc959DE9Ae64dB78F9Db828

0x956C692c5A29500C78851eb6649b8C036C4Dd937

0x44fA2D14fA28a72f3b1261918372A1d5f2773078

0xCdf9159A9479BF564eBD20fb0E28f27546c30DdF

0x17f256D32B66392A5c6b7Da8E2B67Ef00F689Ea6

0x6bAAFc4DCD46349bdAFC9F5068F42893d7b11919

0x99E85F1DBc47FaCEC31C0313735e245FB10e8CE9

0x729b5C6aB30C60C429698baB41079108d9965f8a

0xE3809CF379ea4A3F1aE76299C1802208dBc618d8

0x9aD443521A5E0fcbDca8C326F9B42dfF827AC78d

0xbE3F53F20c019602737ae7df0cF1614E27066a07

0x6Aa5fc08aC27257ed9EA49fd32aa38b169341951

0xC873cC219FC00fC75B9781aFC33dd4a1b444EaE5

2. Description of report

Found 35 sybill address above based on ETH Mainnet activity that:

* funded by same entity (HTX)

* funded with same ETH value 0.7816 ETH

* funded at same date Apr 2, 2023

* transacted on the same date on multiple LayerZero products

3. Detailed methodology & walkthrough, supported by screenshots of Arkham, LayerZeroScan, DeBank, block explorers, etc to support arguments

I manually checking address on Dune based on ETH mainnet days activity, then found 2 address with same funding amount (0.7816 ETH) at same date (Apr 2, 2023). Then, those address interact with Arbitrum Nova Bridge with 0.76 ETH to 0.77 ETH value.

Address 1 [https://debank.com/profile/0xf361b12c004b2f1ee98139ab7d4494d4c968016d/history?chain=eth&token=](https://debank.com/profile/0xf361b12c004b2f1ee98139ab7d4494d4c968016d/history?chain=eth&token=) 

![](/images/wAy_Image_1.png)

![](/images/EFo_Image_2.png)

So, I decided to filter address that interact with Arbitrum nova bridge on Arkham Intel with:

* Value 0.76 to 0.77 ETH

* Date Apr 2, 2023 to Apr 3, 2023

and found 35 address

![](/images/5ky_Image_3.png)

Then check all address using DeBank and the result all address have same activity at same date: [https://docs.google.com/spreadsheets/d/1diz_rsljfJ9NUcp8CqiJ0wHmOwCLjJtqPCyvoM4Sgaw/edit?usp=sharing](https://docs.google.com/spreadsheets/d/1diz_rsljfJ9NUcp8CqiJ0wHmOwCLjJtqPCyvoM4Sgaw/edit?usp=sharing) 

![](/images/7mh_Image_4.png)

This proves these wallets are controlled by the same person who is Sybil attacking LayerZero.

4. Reward address

If eligible, please distribute 50% of the payout to each of these two wallets:

0x4C5403F9D47bd544c40B3eE605e6575a5c0795E7 (sponsor)

0x73697bc0259E0EdB7302FF96358Dd9E1A2C13c28 (bounty hunter)

This is a sponsored report. The sponsor and bounty hunter have mutually agreed on a 50/50 split of any rewards that this report is eligible for. The sponsor?s wallet submitting this report and paying the bond is 0x4C5403F9D47bd544c40B3eE605e6575a5c0795E7. The bounty hunter?s wallet for 50% payout if eligible is 0x73697bc0259E0EdB7302FF96358Dd9E1A2C13c28 . The bounty hunter has signed a verified Etherscan signature confirming the above to be true: [https://etherscan.io/verifySig/182277](https://etherscan.io/verifySig/182277).
