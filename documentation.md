
# Fry Foundation Documentation

**What are the differences between the 3 UNreleased nodes ?**

**Storage Validator Node** - Used for Validating our decentralized data storage system.[ https://www.fryfoundation.com/product-page/fry-storage-validator-node](https://www.fryfoundation.com/product-page/fry-storage-validator-node) 

**Reward Decentralization Node** - Used for decentralizing our reward mechanism. Each node will receive a base payout each day, but if the node is selected to distribute $FRY rewards it will receive double what it would normally earn.[ https://www.fryfoundation.com/product-page/fry-reward-decentralization-node](https://www.fryfoundation.com/product-page/fry-reward-decentralization-node) 

**Storage Decentralization Node** - Used for decentralizing our data storage system[ https://www.fryfoundation.com/product-page/fry-storage-decentralization-node](https://www.fryfoundation.com/product-page/fry-storage-decentralization-node) More info will come out as we approach, stay tuned! 

Please note : There will not be any BYOD options for these, The software will be pre-loaded with the nodes. No download option available. (edited)

#### How long does it take for the miners to ship out?

The ribbon/picture on each miner type on our website shows the ETA for when the miner will be shipped.

Please make a note of what the ribbon on the miner purchase page said for the miner you purchased. This ribbon displays when the miner will be shipped.

-Bandwidth/Satellite/Decibel miners all ship in batches.

The ribbon/picture on the miner purchase page displays when the miner will be shipped.

-Cameras/Weather miners usually ship out within 3-6 weeks from the time of the order, depending on your location.

-Unreleased MINERS (Radiation/Energy/Air or Water Quality miners) Will start shipping out at the end of Q1! 

-Unreleased NODES will start shipping around Q3/Q4 of 2024! You can pre-order them now as the price will gradually increase until they're released!

#### How do I find which weather miner frequency I need for my country?

[https://www.thethingsnetwork.org/docs/lorawan/frequencies-by-country/ https://docs.helium.com/iot/lorawan-region-plans/](https://www.thethingsnetwork.org/docs/lorawan/frequencies-by-country/) 

#### I just received my miner (Bandwidth/Satellite/Decibel). How do I set it up?



* Connect the mini PC miner to a power source and to a monitor or TV, the display cable will be based on the mini PC’s graphic card’s port (HDMI/VGA/DVI/Display port which you need to procure).
* Connect a network cable or use wifi if the miner came with a wifi dongle or has wifi built in.
* Power on the mini PC miner. Setup your Windows account and sign in.
* Create a new Algorand wallet address that’s for mining purposes and to be able to opt-in to Fry token and receive rewards
* Head to the https://www.fryfoundation.com website (on the miner directly!)
* Find ‘hardware miner resources’, click on your miner type under Downloads and download the software then Install it.

**Setup videos :**

[https://www.youtube.com/watch?v=rnvwQ7TftGE&t=307s https://www.youtube.com/watch?v=DaZ_QUMk1Kc https://www.youtube.com/watch?v=9S_uulffr-8&t=4s&ab_channel=CryptoJar](https://www.youtube.com/watch?v=rnvwQ7TftGE&t=307s)

**How do i onboard my own device (BYOD) into FRY's ecosystem?**

BYOD licenses costs $105USD total (50% in Algo and 50% in Fry)



1. Set up an Algo account (Pera wallet or Defly) if you don't have one.
2. Transfer 105$USD worth of Algo tokens into the wallet(from an exchange or other wallet)

(To avoid any purchase errors/issues, make sure to transfer an extra dollar or two)



1. OPT-in to FRY Token in your wallet.
2. Swap half of the algo (52.5$USD worth) for Fry tokens (you can perform a swap within Pera wallet directly)

Make sure to leave around 10 Algo to cover your miner’s proof of connectivity transaction fees. You can buy a BYOD License here :[ https://byod.fryfoundation.com/](https://byod.fryfoundation.com/) Once the purchase is complete, you will get a license number by email. 

**Bandwidth, Decibel, Satellite** (you can use your own pc/laptop, requirements are : win10/11 home/pro , 4GB RAM , 1GB Free disk space) 

NOTE : You will need to leave this computer powered on 24/7 and connected to the internet. Steps :



1. Download the desired mining software from our website and install it.
2. Once the installation is complete, go to Fry's website for registration, under the BYOD registrations tab (Very important) and make sure to submit the correct form type to avoid rejections and delays.
3. Input your BYOD license key, your name, email address used to purchase the license and a picture of your miner (your computer running the software will do).

Make sure your computer's power settings are set to never sleep mode and don't power it off! Wait for your registration to be processed (takes 3-4 days usually) and start earning $FRY.  

BYOD Video Instructions:[ https://www.fryfoundation.com/byod-video-instructions](https://www.fryfoundation.com/byod-video-instructions) 

Cameras (any wifi cam but must have RTSP capability)[ https://www.youtube.com/watch?v=blCJVPDJc88 https://www.youtube.com/watch?v=r1CaT1Hs7-I&t=73s](https://www.youtube.com/watch?v=blCJVPDJc88)

#### I just finished installing the bandwidth / satellite / decibel software. How do I know if my miner is working? Is there an application that I can see running and how does that work?

There’s no program that you will see running, the miner operates in the background as a Windows task that executes once an hour to send proof of connectivity from the miner. You will notice a black DOS window that pops up on your computer once an hour, the window is going to be showing information about your bandwidth connectivity and speedtest results. 

To find out if it’s working, you can check your wallet activity and make sure you are seeing 0.0 fry transactions every hour. If you don’t see any transactions after a full hour, try uninstalling the fry software and re-install and checking again. Make sure your wallet is not a rekeyed wallet as it won’t be able to send proof of connectivity. If you have a rekeyed wallet, you will need to create a new wallet and re-install the software using the new wallet’s 25 words seed phrase. If an account has been rekeyed then they must sign the transaction with auth-addr account. If they do not have that account, then they are unable to do anything.

#### Why did I stop getting rewards for my (bandwidth/decibel/satellite) miners? OR Why are my rewards lower than usual on my (bandwidth/decibel/satellite) miners?



* If you stopped getting rewarded, check your wallet activity to see if your miner is still sending the proof of connectivity checks. These will show up as 0.0 fry transactions in your wallet activity every hour and count towards your rewards. Your miner needs to send 24 checks every day to get fully rewarded. If you get reduced rewards, it’s because it didn’t send the 24 checks during that day and missed some. In this case check your internet connectivity and power settings, try re-installing the software, avoid connecting your miner to wi-fi as a wired ethernet connection is more stable and recommended. 
* If it stopped sending the connectivity checks completely, then check your Algo balance.
* You must have a minimum balance of 5 to 10 algos in your wallet at all times to cover the POC (proof of connectivity) transactions gas fees. The proof of connectivity checks charge a small gas fee of 0.001 algo every time they send out the check from your miner. The software requires a minimum of 10 algos to be able to keep working properly and keep sending the connectivity checks. 
* Make sure you are running the latest version for your type of miner. Go to our website, download the latest version under the downloads Tab :[ https://www.fryfoundation.com/](https://www.fryfoundation.com/)
* 
* When updating the software, Always run the fryuninstaller file first to remove the previous version (fryuninstaller is located in the download zip file, if no uninstaller file available, use the installer as it will prompt to uninstall the existing version or uninstall it from Windows settings - Apps )
* And then run the fryinstaller of the newest version
* If you run into any error messages, please run the fryuninstaller again and re-install
* If you run into errors again, then Download and install the latest version of nodejs:[ https://nodejs.org/en/download/current](https://nodejs.org/en/download/current) 
* Re-install using the fryinstaller again
* Once installation is complete, you can check if it worked by going to this folder: 
* For Bandwidth : Documents/Fry Bandwidth Data/JavaScript/Connectivity Validation/ 
* For Satellite : Documents/Fry Satellite Data/JavaScript/Connectivity Validation/
* For Decibel : Documents/Fry Decibel/Connectivity Validation/
* run the POC.BAT file (double click) then check wallet activity for 0.0 FRY transactions. If you see 0.0 fry then all is good.
* If nothing showed up in the wallet activity and you have 5-10 Algos and OPTED-in frys token then go to the Connectivity Validation folder and right click on config.json file and open it with notepad and double check the wallet seed phrase. Make sure there’s no typos, only ONE space between the words and no commas or periods or anything else.

#### Where can I stake FRY?

You can here: [ https://app.cometa.farm](https://app.cometa.farm/)  
You can connect your Algo wallet. Then, you can decide between staking or farming, both of which reward you and support the sustainability of the Fry project. When farming during a specific period, you'll need to provide liquidity in Fry token and Algo to earn rewards. Staking involves locking up Fry tokens for a certain period to earn Fry tokens with a high interest rate, although the rate decreases if more people participate in staking or farming. 

#### Why is the light on the pebble tracker red?
The light on your Pebble tracker is red, it likely means your Pebble SIM card is running low on data. You'll receive an email notification reminding you to refill your data so that Pebble can continue streaming data, which could impact your rewards if the data runs out.

#### Do we need Algo tokens in the wallet for transaction fees related to indoor/outdoor air quality?
No, you don't need Algo tokens for transaction fees on IAQ or OAQ, but you do need them when trading your Fry tokens.

#### Where can I trade fry token?     
You can trade Fry tokens on the following platforms and on different blockchains: coininn.com, humble.sh, nonkyc.io, xeggex.com, pancakeswap.finance, quickswap.exchange, jug.ag, orca.so, traderjoexyz.com, tinyman.org, and app.pact.fi

#### What apps do I need to start after a power outage ?
None, everything starts automatically even after a restart

#### I can't interact or withdraw my money or rewards from Cometa(cometa.farm), is there any solutions?
Try to disconnect your wallet connect sessions in your mobile wallet settings and reconnect.

#### Where do i find the api and app key of my Ecowitt weather station?
To obtain the API and App Key for your Ecowitt weather station, follow these steps:
Sign in to your Ecowitt.net Account: Go to the Ecowitt website and sign in to your account. If you haven't created an account yet, you'll need to register.

Navigate to Device Management: Once logged in, look for an option like "Device Management" or "My Devices" in your account settings.

Select your Weather Station: Within the Device Management section, locate your weather station from the list of devices associated with your account. Click on it to access its settings.

Find API and App Key: Look for an option related to API access or developer tools within your weather station's settings. Ecowitt provides an option to generate an API key and App Key for accessing your weather station data.

Generate Keys: Click on the option to generate the API and App Keys. Ecowitt should provide you with both keys once generated.

Record your Keys: Make sure to copy and securely store both your API key and App Key. These keys are necessary for accessing your weather station data through third-party applications or services.

Use responsibly: Remember that API keys are sensitive information. Do not share them publicly or with unauthorized individuals to ensure the security of your data.

If you encounter any difficulties or can't find the API and App Key in your Ecowitt account settings, refer to the Ecowitt documentation or contact their support for assistance.
#### Where do i find the api and app key of my Ambient weather station?
To find the API and App Key for your Ambient Weather Station, you'll need to follow these steps:

Sign in to your Ambient Weather Account: Go to the Ambient Weather website and sign in to your account. If you don't have an account, you'll need to create one.

Navigate to the API section: Once logged in, navigate to your account settings or dashboard. Look for a section related to API access or developer tools. This is where you'll find the information you need.

Generate API Key: In the API section, you should see an option to generate an API key. Click on it, and the website will provide you with both the API key and App Key.

Make a note of your keys: Once generated, make sure to copy and securely store both your API key and App Key. These keys are essential for accessing your Ambient Weather Station data through third-party applications or services.

Use responsibly: Keep in mind that API keys are sensitive information. Do not share them publicly or with unauthorized individuals to ensure the security of your data.

If you encounter any issues or have trouble finding the API and App Key, you may need to refer to the Ambient Weather documentation or contact their support for assistance.

#### I purchased a byod license and it took my algo payment and my fry payment but I never received my license in my email. What do I do? 
Please open a ticket in our discord's help desk channel to let the team know, include your e-mail address, your wallet address and both transaction IDs of the payment. A member of our team will assist you.

#### I purchased a byod license and it took my algo payment but it's not taking my fry payment and giving me an error. What do I do now? 
Make sure you opted-in to fry token and have enough fry tokens to make the 52$usd payment as the price can be volatile and change the amount of fry tokens needed to make the payment. 
Refresh the site and try again. 
Make sure you are using a PC web browser and connect to your Pera or Defly mobile app on your phone by scanning the QR code on the PC web site. https://byod.fryfoundation.com/ 
You can swap algo to fry directly from your mobile wallet.
#### I submitted my weather/air quality/pebble registration over 4 days ago and I still don't see rewards
Did you link them to Fry's ecosystem? 
If it's a weather miner, make sure you linked your weather station here : https://weather.fryfoundation.com/
If it's an air quality or Pebble miner, make sure you linked them here : https://air.fryfoundation.com/
Once done, re-submit a new registration form.

#### I forgot my windows password to unlock my miner and get into the Operating system. 
If you forgot the miner's password that you initially set when setting up your windows/microsoft account, try these steps to unlock the device and get into the operating system: 
https://www.top-password.com/blog/how-to-reset-windows-10-without-logging-in/

#### Can i get a refund on my BYOD license?
You cannot get a refund on your BYOD license. All crypto transactions are final and non-refundable.

#### How do I cancel my order?

To cancel an order please join our Discord here[ https://discord.gg/THCVfwXYQY](https://discord.gg/THCVfwXYQY) and make a help desk ticket

#### How do I get in contact with the $FRY team?

To get in contact please join our discord at this link and make a ticket:[ https://discord.gg/THCVfwXYQY](https://discord.gg/THCVfwXYQY)

#### How Often Are Rewards Distributed?

Rewards are distributed once a day at 4:20am CST / 10:30am UTC
However, the exact time may change.

#### How do I transfer algo into my Pera/Defly wallet?

You can buy some algo from your favorite exchange like Coinbase, Binance, Mexc, etc. and withdraw from your exchange to your Pera wallet address.

####  How do i sell/swap my fry directly from my wallet? 

To sell you fry tokens (or buy) you can do it directly from your Pera wallet or Defly wallet. Simply click the swap button, select Fry token in the “From” field and “Algo” in the “To” field and click Swap! 

####  Where can i see the live price? 

You can view the token price : [https://vestige.fi/asset/924268058](https://vestige.fi/asset/924268058) 

#### How do I OPT-in to Fry token in my wallet?

Open your wallet app, click on your wallet account first then click the + button and search for “FrysCrypto”, make sure the ASA (Algorand Standard Asset) ID is : 924268058 

#### What is the Algorand Standard Asset ID for Frys token? 

ASSET ID : 924268058

#### Where do I find my 25 words seed phrase for my fry/algo wallet? 

Open your wallet app, click on your wallet account first then click the “More” button with the three little dots and click “View passphrase”

#### Which exchange can I use to buy/sell fry? 

Vestige : [https://vestige.fi/asset/924268058](https://vestige.fi/asset/924268058) 

Coininn : [https://www.coininn.com/coin/FRY](https://www.coininn.com/coin/FRY) 

Nonkyc : [https://nonkyc.io/market/FRY_USDT](https://nonkyc.io/market/FRY_USDT) 

Xeggex : [https://xeggex.com/market/FRY_USDT](https://xeggex.com/market/FRY_USDT) 

HumbleSwap : [https://app.humble.sh/swap](https://app.humble.sh/swap) 

PancakeSwap: [https://pancakeswap.finance/swap?outputCurrency=0x08D54146050ED575775d5D8f9fCDB4c646f5B717&chain=bsc](https://pancakeswap.finance/swap?outputCurrency=0x08D54146050ED575775d5D8f9fCDB4c646f5B717&chain=bsc) 

QuickSwap : [https://quickswap.exchange/#/swap?currency0=ETH&currency1=0x22E61C07F898Cc0a17826dE622793A6Cc2935c37&swapIndex=0](https://quickswap.exchange/#/swap?currency0=ETH&currency1=0x22E61C07F898Cc0a17826dE622793A6Cc2935c37&swapIndex=0) 

Jupiter : [https://jup.ag/swap/SOL-FRY_HWcrH99mVocuP5hBV9X5fNGH3WBKCcjw3DxfY4AGaeXg](https://jup.ag/swap/SOL-FRY_HWcrH99mVocuP5hBV9X5fNGH3WBKCcjw3DxfY4AGaeXg) 

Orca : https://www.orca.so/

Trader Joe : [https://traderjoexyz.com/avalanche/trade](https://traderjoexyz.com/avalanche/trade) 

Tinyman : [https://app.tinyman.org/#/swap?asset_in=0&asset_out=924268058](https://app.tinyman.org/#/swap?asset_in=0&asset_out=924268058) 

Pact Fi : [https://app.pact.fi/swap?pair=ALGO:0/FRYSCRYPTO:924268058](https://app.pact.fi/swap?pair=ALGO:0/FRYSCRYPTO:924268058) 

#### A VK-172 or VK-162 GPS dongle cannot be used for Outdoor Satellite GPS Mining. You need a land survey antenna and a Ublox breakout board.

#### I have a WXM, can I dual mine Fry token with it? 

If you already own a WeatherXM, you need to onboard it and engage in dual mining with the Frys project. To do this, you'll need to obtain a BYOD license, which costs $104 (50% in Algo, 50% in Fry's). 

Here are some fun facts on our WeatherXM $WXM Weather Station Support :



1. Linking your WeatherXM station to our ecosystem doesn't remove it from their ecosystem. This means you can dual mine $WXM and $FRY
1. We don't store your WXM login credentials, they're simply used to fetch your account API key
1. We are in no way affiliated with WeatherXM
1. Our ecosystem supports all WeatherXM weather stations (WiFi, LoRaWAN, and the upcoming LTE stations)

#### Do I need to use the same wallet to send poc as the wallet I registered? 

Yes, the wallet that is sending the POC (proof of connectivity) checks has to be the same as the wallet you submitted during your registration.

#### How do I see the output of the black window that pops up every hour? 

Right click on your start button in the bottom left and click Run

Write `cmd` and press enter , a command prompt window will open up. Inside, write : 



* For Bandwidth : cd Documents\Fry Bandwidth Data\JavaScript\Connectivity Validation\ 
* For Satellite : cd Documents\Fry Satellite Data\JavaScript\Connectivity Validation\
* For Decibel : cd Documents\Fry Decibel\Connectivity Validation\

Press Enter

Write `poc.bat` and press enter

You will also notice a 0.0 fry transaction pop up in your wallet activity (that’s the proof of connectivity)

You can now have 1 WXM + 1 Fry hardware high end weather + 1 Fry hardware low end weather in the same location! You can also have a Geodnet Dual Miner + 1 Fry hardware outdoor satellite miner in the same location! 

#### What are the Multipliers on the rewards/earnings? 

The Fry Foundation ecosystem fosters active and sustained participation, rewarding consistent contributors with extra rewards. Our distinct multiplier system boosts the $FRY tokens you can earn based on factors like uptime, bandwidth provided, data accuracy, and more. Additionally, our multiplier system adapts to the market price of $FRY. When the price of $FRY drops below 1 cent, the base reward is multiplied by 2. Subsequently, each zero added to the right of the decimal point in the price leads to an additional 1.5x multiplier, ensuring fair remuneration irrespective of market fluctuations. When the price is above 1¢, the x2 multiplier to your rewards gets removed!

The 1.5x early bird multiplier will be removed at the two year mark of our tokens birth (October 28th, 2024)

**How much does each miner earn as base reward and what are the device limits for each without the multipliers? The following rewards are for Fry Hardware Unverified rewards. The Fry BYOD rewards are half of these amounts but the same device limit.**



* Bandwidth Miner: 107.86 $FRY; Limit of 1 per Public IP 
* Indoor Satellite Miner: 82.86 $FRY; Limit of 5 per Location
* Outdoor Satellite Miner: 107.86 $FRY ; Limit of 1 per Location
* Indoor Decibel Miner: 107.86 $FRY ; Limit of 1 per Location
* Outdoor Decibel Miner: 107.86 $FRY ; Limit of 1 per Location
* High-End Weather Miner: 215.72 $FRY; Limit of 1 High-End & 1 Low-End per Location
* Low-End Weather Miner: 107.86 $FRY ; Limit of 1 High-End & 1 Low-End per Location
* Sky Camera Miner: 107.86 $FRY ; Limit of 1 Facing the Sky per Location
* Traffic Camera Miner: 107.86 $FRY ; Limit of 1 Facing Each Street per Location
* Wildlife Camera Miner: 107.86 $FRY ; Limit of 1 Facing Each Outdoor Area per Location
* Weather Station Camera Miner: 107.86 $FRY ; Limit of 1 Weather Station Camera Miner Facing Towards your Weather Miner (Includes Indoor and Outdoor)
* Indoor Radiation Miner: 107.86 $FRY ; Limit of 1 per Location
* Energy Miner: 107.86 $FRY ; No Limit
* Indoor Air Quality Miner: 107.86 $FRY ; Limit of 1 per Household
* Outdoor Air Quality Miner: 107.86 $FRY ; Limit of 1 per Location
* Outdoor Water Quality Miner: 107.86 $FRY ; Limit of 1 per Body of Water
* Reward Decentralization Node: 431.44 $FRY ; No limit
* Storage Decentralization Node: 431.44 $FRY ; No limit
* Storage Validator Node: 431.44 $FRY ; No limit

#### Once the verification system is on mainnet (as it’s on testnet at the moment) the rewards will become verified rewards with these amounts (with the BYOD verified rewards being half of these reward amounts but the same device limits) : 



* Bandwidth Miner: 323.58 $FRY; Limit of 1 per Public IP 
* Indoor Satellite Miner: 248.58 $FRY; Limit of 5 per Location
* Outdoor Satellite Miner: 323.58 $FRY ; Limit of 1 per Location
* Indoor Decibel Miner: 323.58 $FRY ; Limit of 1 per Location
* Outdoor Decibel Miner: 323.58 $FRY ; Limit of 1 per Location
* High-End Weather Miner: 647.16 $FRY; Limit of 1 High-End & 1 Low-End per Location
* Low-End Weather Miner: 323.58 $FRY ; Limit of 1 High-End & 1 Low-End per Location
* Sky Camera Miner: 323.58 $FRY ; Limit of 1 Facing the Sky per Location
* Traffic Camera Miner: 323.58 $FRY ; Limit of 1 Facing Each Street per Location
* Wildlife Camera Miner: 323.58 $FRY ; Limit of 1 Facing Each Outdoor Area per Location
* Weather Station Camera Miner: 323.58 $FRY ; Limit of 1 Weather Station Camera Miner Facing Towards your Weather Miner (Includes Indoor and Outdoor)
* Indoor Radiation Miner: 323.58 $FRY ; Limit of1 per Location
* Energy Miner: 323.58 $FRY ; No Limit
* Indoor Air Quality Miner: 323.58 $FRY ; Limit of 1 per Household
* Outdoor Air Quality Miner: 323.58 $FRY ; Limit of 1 per Location
* Outdoor Water Quality Miner: 323.58 $FRY ; Limit of 1 per Body of Water
* Reward Decentralization Node: 1294.32 $FRY ; No limit
* Storage Decentralization Node: 1294.32 $FRY ; No limit
* Storage Validator Node: 1294.32 $FRY ; No limit

#### Why do you need my 25 words seed phrase from my wallet? 

While installing the bandwidth/decibel/satellite softwares, it is required to input the 25 words seed phrase from the Algorand wallet (That is stored on your miner ONLY and not sent to FRY in any way, it is used strictly to be able to send proof of connectivity out from your miner, it is possible that this will change in the future but is required at the moment)

We always recommend creating a fresh new wallet for any mining purposes.

#### How to get an affiliate code ? 
To get an affiliate code, you can use this [link](https://affiliate.fryfoundation.com/) and sign up for the affiliate program.

#### How to get in touch for a partnership ?
If you want to get in touch for a partnership, you can join our discord and open a help-desk ticket in the appropriate section and tell us about you and your partnership proposal.
Please include some details about your company (if you have one) and what you are looking for in the partnership.

#### Why isn't my miner showing up on the dashboard ? 
The verification and dashboard are still in testnet right now, not everyone is able to see all their miners properly yet, we are well aware of the issue and our devs are working hard on it! 
Please do not open a ticket for this. 
Simply keep your eyes on ⁠⎾📢⏌announcements to stay up to date on when it will be resolved. Also please note we are all still earning UNverified rewards at the moment.


#### Clarity about vm / vpns
You are allowed to use Virtual Machines or VPNs to run the software. However, you are not allowed to use these for the recycle miner program.

#### Which miners need to send proof of connectivity checks and which ones don't need to send?
Bandwidth, decibel and satellite miners need to send proof of connectivity every hour to be able to get rewarded. If there's less than 24 poc checks in a 24 hour period, the rewards will be reduced. 

Weather stations, cameras, air quality, energy miners, do not need to send poc checks at the moment. They may need to sometime in the future and we will update everyone if that is needed. 


#### What kind of data is recorded with the decibel miners via the microphone? 

Decibel miners strictly record the dB measurements only, nothing else. A decibel is a unit of measurement for the intensity and amplitude of sound, so only the sound level is recorded, not the actual sound itself.

#### How can I change the wallet address where I receive my rewards?

If you want to change the wallet address where you receive the rewards in, then you will need to do this : 

For Bandwidth, Decibel, Satellite miners, you need to uninstall the software and reinstall using the new wallet 25 words seed phrase. Once that’s done, run the poc.bat located in the Connectivity Validation folder and check the new wallet activity for 0.0 fry transaction to make sure it’s working. 

Once that’s completed, go on the Fry foundation website and submit a new registration form with the new wallet address. Finally, go to our discord, open a help-desk ticket and explain that you want to change/switch wallets. 


If you want to change the wallet address for cameras, weather miners or anything else, you just need to submit a new registration form and go to our discord and open a help-desk ticket and explain that you want to change/switch wallets. 

**What is the source of the liquidity supporting $FRY?**

The initial funding for our liquidity pools was generously provided by our founder using personal funds. This foundational liquidity is permanently established in our exchange pools. Following this initial contribution, we've developed additional liquidity through two main avenues, enhancing the stability and efficiency of our trading pairs:

**Staking Pools**: Encouraging long-term investment and engagement within our community.

Contributions amounting to 10% from revenues generated by hardware sales, data services, and subscription fees.

#### Why are the shipping costs so high? 

This would be due to the scarcity of products outside of the US, UK, and AU. This scarcity causes us to have to import devices for people who order outside of those 3 countries and that means we have to pay a decent amount for shipping

**Is there an algorand explorer where I can see my wallet activity?**

Yes you can try Pera explorer : [https://explorer.perawallet.app](https://explorer.perawallet.app) 

And Allo.info : [https://allo.info](https://allo.info) 

#### Why is it failing to sign me in to my WXM account when I try to link my WXM on Fry’s weather portal, it gives incorrect password error but I can login fine on the WXM site. 

Incorrect password WXM API : make sure you are you creating your accounts here: [https://app.weatherxm.com/login](https://app.weatherxm.com/login)

#### I have multiple satellite, bandwidth and decibel miners, how can I know which one is working and which one isn’t? 
If you have Multiple miners and want to check which one is working or not working :

Navigate to the Connectivity Validation folder on each type of miner you have and Open the config.json file on each: 



* For Bandwidth : Documents\Fry Bandwidth Data\JavaScript\Connectivity Validation\ 
* For Satellite : Documents\Fry Satellite Data\JavaScript\Connectivity Validation\
* For Decibel : Documents\Fry Decibel\Connectivity Validation\

Right click and open it with notepad to edit it in the note field.

The line that shows "note_to_send": "Connectivity Check for 12:34:56:AB:CD:EF",

After "Connectivity check" write for example: satminer1, satminer2 satminer3, bandminer1, decminer1 

Make sure sure to leave the quotation marks intact and not to edit anything else. 

It will need to look like this : "Connectivity check satminer1" (You can name them whatever you want as long as it follows the formatting)

Once that's done, launch the poc.bat file, located in the same folder (Connectivity Validation) on each miner :

Run the POC file (double click) then check wallet activity for 0.0 FRY transactions. 

Now you can identify and see which one is sending POC checks and which one isn't by looking in your wallet activity transaction details in the note at the bottom or on the algorand explorer.


#### Can I run multiple miner types like bandwidth + satellite + decibel on the same PC? 

Yes you can but you need to purchase a BYOD license for each type.

#### What and how can i dual mine with FRY? 

WXM dual mining instructions :[ https://www.youtube.com/watch?v=EsypWdKuIB8&t=2s](https://www.youtube.com/watch?v=EsypWdKuIB8&t=2s) 

IOTX pebble dual mining :[ https://www.youtube.com/watch?v=QMzkFTyK9F8](https://www.youtube.com/watch?v=QMzkFTyK9F8) 

Geodnet:[ https://www.youtube.com/watch?v=HsA-ecPclbU](https://www.youtube.com/watch?v=HsA-ecPclbU) 


### How do I Bridge $FRY from Algorand to Other chains?

Watch this video : [https://www.youtube.com/watch?v=lrOK_Y46tg0&embeds_referring_euri=https%3A%2F%2Fwww.fryfoundation.com%2F&embeds_referring_origin=https%3A%2F%2Fwww.fryfoundation.com&feature=emb_imp_woyt](https://www.youtube.com/watch?v=lrOK_Y46tg0&embeds_referring_euri=https%3A%2F%2Fwww.fryfoundation.com%2F&embeds_referring_origin=https%3A%2F%2Fwww.fryfoundation.com&feature=emb_imp_woyt) 

###  What are the different contract addresses for the different chains that Fry is on? 

Algorand (ASA): 924268058 

Binance Smart Chain (BEP-20): 0x08D54146050ED575775d5D8f9fCDB4c646f5B717 

Polygon (ERC-20): 0x22E61C07F898Cc0a17826dE622793A6Cc2935c37 

Solana: HWcrH99mVocuP5hBV9X5fNGH3WBKCcjw3DxfY4AGaeXg 

Avalanche (C-Chain): 0xFEb6c209e609E6ca1da0991dcaAFDBf515d692dd

#### When was FRY token created? 
Oct. 30, 2022, 9:25 a.m. UTC

#### What is the total supply of FRY? 
8.0 Billion FRY

#### I registered 7 days ago and still didn’t get rewarded. What's going on?

If you still haven’t seen any rewards after 7 days of submitting your registration form, try to submit a new form and make sure all the fields have the correct information and that you are submitting the correct form type to avoid any rejections and delays. If you still don’t see rewards after that, you should open a ticket in the help-desk channel to look into it. BYOD can only be used once and will get rejected if registered again. If you want to switch your license to a different miner type, you will need to submit a registration form for the new byod type of miner and open a ticket in discord so the team is aware it’s a switch. 

#### Which weather stations can I onboard with a byod license?

You can onboard WXM, Ambient or Ecowitt weather stations. 

#### Which cameras can I onboard with a byod license? 

Any camera that has RTSP (Real Time Streaming Protocol) capability. 

#### U center shows no devices ?



# FrysCrypto ($FRY) White Paper

Published by Samuel Fry, Founder

Our Mission

### Introduction

At the Fry Foundation, our vision is twofold: to democratize access to cryptocurrency for individuals from all walks of life, regardless of their technical expertise, and to champion environmental sustainability by actively reducing electronic waste (e-waste). We are committed to redefining the landscape of cryptocurrency mining through innovative practices that align with these core principles.

### Our Dual Objectives

1.	Combating Electronic Waste

Recognizing the detrimental impact of e-waste on our environment, the Fry Foundation is dedicated to mitigating this challenge. We have adopted a pioneering approach where all our cryptocurrency miners are constructed using repurposed electronics and components. This initiative not only breathes new life into existing technology but also significantly diminishes the demand for new electronic production, thereby curbing
e-waste generation.

2.    Lowering the Barrier to Entry in Cryptocurrency Mining

The Fry Foundation is passionate about making cryptocurrency mining accessible and approachable for everyone, irrespective of their technical background. We have
meticulously designed our $FRY cryptocurrency miners to be the most user-friendly and simple-to-set-up miners available today. Our goal is to remove the intimidation factor often associated with crypto mining. With our straightforward, intuitive setup process, even novices to the cryptocurrency world can commence mining expeditiously.

By broadening the accessibility of mining, we aim to cultivate a more inclusive cryptocurrency community. We are firm believers in the transformative power of cryptocurrency and are dedicated to enabling more individuals to partake in this digital revolution.

### Conclusion

Our mission at the Fry Foundation extends beyond mere participation in the cryptocurrency market. We are driven by a commitment to foster sustainability, inclusivity, and innovation within the cryptocurrency ecosystem. Through our endeavors, we aspire to contribute to a more equitable and environmentally conscious future for all.



### Samuel Fry CEO, CTO, CMO, & Founder



### What is FrysCrypto?



### Overview

FrysCrypto ($FRY) is more than just a cryptocurrency token; it is a testament to our commitment to sustainability, security, and
decentralization. Developed within the robust Algorand ecosystem, $FRY is not only a symbol of technological innovation but
also an embodiment of our environmental responsibility. Our choice of the Algorand platform ensures that $FRY is inherently green and carbon-neutral, aligning with our ethos of promoting eco-friendly digital currencies.




### Key Features of $FRY








### Green and Carbon Neutral

By building $FRY on the Algorand ecosystem, we have ensured that our token adheres to the highest standards of environmental sustainability. Algorand’s carbon-neutral network minimizes the ecological footprint of $FRY, making it an ideal choice for environmentally conscious users and investors.

### Secure and Decentralized

Security and decentralization are at the heart of $FRY. The Algorand platform provides a secure and decentralized infrastructure, offering peace of mind to our users. This security ensures the integrity and safety of transactions, while decentralization guarantees that $FRY remains free from central control and manipulation.


### Utility of $FRY

Rewards for Mining: $FRY is designed to be an integral part of our mining ecosystem. Users who engage in mining
with our diverse range of $FRY miners will be rewarded in $FRY tokens. This not only incentivizes participation but also fosters a vibrant and active mining community.

Compensation for Delayed Purchases: We value customer satisfaction and timely service. In instances of delayed
purchases, $FRY serves as a compensatory currency, providing users with a tangible acknowledgment of the inconvenience and reinforcing our commitment to exceptional customer service.

Currency for Purchasing $FRY BYOD Licenses: $FRY extends its utility to the realm of software licensing. Users can utilize \$FRY tokens to purchase licenses for our “Bring Your Own Device” ($FRY BYOD) mining solutions. This feature enhances



the versatility of $FRY and enriches its ecosystem within our platform.

Versatile Uses: The utility of $FRY goes beyond the aforementioned uses. It is a dynamic digital asset with a multitude of applications within our ecosystem and beyond. Whether it’s for transactions within our network, external trades, or
as a store of value, $FRY is designed to be a multifaceted and functional cryptocurrency.

In conclusion, FrysCrypto ($FRY) represents a new era in the digital currency space, where sustainability, security, and decentralization are not just features but fundamental principles. Through $FRY,
we are not only offering a cryptocurrency token but also inviting users to be a part of a greener, safer, and more equitable digital future.


### Benefits







### STABILITY

Since $FRY is built on the Algorand ecosystem, it is extremely stable. This is because Algorand has never experienced downtime as of the writing of this whitepaper







### Passively Earn

Since one can earn $FRY by participating in our decentralized networks,
there are many ways one can passively earn $FRY

### Security

We have disabled clawback and freeze as we believe you own the crypto you buy or earn. We and no one else have the right to seize your crypto








### Green

We always aim to produce green $FRY miners. Supply chain issues may sometimes limit this, but our goal is to use recycled e-waste and pursue other eco-friendly initiatives in our production process




### Usage



### Introduction

FrysCrypto ($FRY) offers a diverse array of applications and earning opportunities within our decentralized network. This guide details the multifaceted ways in which users can engage with and benefit from $FRY, demonstrating its versatility and integral role in our ecosystem.

### Earning and Using $FRY: A Six-Step Overview


1.	Earning through Mining

Users can earn $FRY by participating in our decentralized network through two primary mining methods:

of devices. The reward allocation for each device is determined based on its uptime, thus incentivizing consistent participation and reliability in the network.



•	Hardware Miners: Available for purchase on our website, these miners offer a straightforward path to earning $FRY.

•	BYOD (Bring Your Own Device) Miners: For those who prefer a more hands-
on approach, building your own BYOD miner is an innovative way to earn $FRY, offering flexibility and customization.

2.    BYOD Licensing

To facilitate BYOD mining, users can acquire licenses using a combination of $FRY and $ALGO (Algorand’s native token). This dual-token payment approach not only integrates $FRY into the purchasing process but also strengthens the synergy between FrysCrypto and the Algorand ecosystem.

3.    Proof-of-Connectivity (PoC)

$FRY plays a crucial role in our unique Proof-of-Connectivity (PoC) model within the Algorand Blockchain. PoC utilizes $FRY to verify the online status

4.    Staking Opportunities

Users have the opportunity to stake $FRY and $FRY Liquidity Provider (LP) tokens. Staking is a powerful way to participate in the network while earning rewards, adding an additional layer of utility to $FRY within our ecosystem.

5.    Data Sales Transactions

All transactions related to data sales within our network are conducted exclusively in $FRY. This policy not only streamlines transactions but also enhances the demand and utility of
$FRY as the central currency in our data marketplace.

6.    Accessing Decentralized Wireless (DeWI) Networks

$FRY is the designated currency for accessing our Decentralized Wireless (DeWI) networks. This application of $FRY reinforces its role as a versatile and essential token within our innovative wireless solutions.


FrysCrypto ($FRY) is not just a digital asset; it is a cornerstone of our decentralized ecosystem, offering multiple avenues for earning and utilization. From mining and staking to purchasing licenses and accessing wireless networks, $FRY is intricately woven into the fabric of our network’s operations. We invite users to explore the full potential of
$FRY, engaging with our diverse offerings to maximize their experience in the world of cryptocurrency.



### Our Decentralized Networks



### Our Mission

At FrysCrypto, we are dedicated to pioneering a groundbreaking concept: a decentralized network comprised of multiple interconnected decentralized networks. Each network within this
ecosystem serves a distinct purpose, yet is designed to integrate seamlessly with others, creating a robust and versatile framework.











### The Network Ecosystem

Diverse Data Collection Networks: Our ecosystem encompasses a variety of data collection networks, each tailored to specific needs. These include networks for monitoring air quality, gathering weather data, and more. These networks are not only crucial for collecting valuable environmental information but also play a vital role in enhancing our understanding of the world around us.

Decentralized Wireless (DeWI) Networks: We are also developing advanced Decentralized Wireless (DeWI) networks, which encompass a range of technologies like decentralized VPNs (dVPNs), WiFi networks, and LoRaWAN. These networks are central to our vision, offering secure, decentralized connectivity options.

Vision of Integration and Cohesion

Synergistic Network Operations: Our vision extends beyond the mere coexistence
of these networks. We envisage a system where networks not only operate independently but also collaborate synergistically. For instance:

•	Weather and Air Quality Integration: Our weather stations will leverage data from our air quality networks
to enhance the accuracy and comprehensiveness of environmental data.

•	Data Security Enhancement: Our data collection networks will utilize our dVPN network, bolstering data security and ensuring privacy.


### The Ultimate Goal: Being the Backbone of DePIN

Establishing a Decentralized Physical Infrastructure Network (DePIN)

Our ultimate aim is to be the foundational backbone of everything related to Decentralized Physical Infrastructure Networks (DePIN). By weaving together
a tapestry of decentralized networks, we aspire to revolutionize how industries and communities interact with technology.

In creating this decentralized network of networks, our goal is to deliver a more resilient, reliable, and adaptable infrastructure. Our commitment to interoperability and collaborative functionality is pivotal in achieving a network that is not only sustainable but
also scalable to meet the future demands of various industries and communities.


In summary, FrysCrypto is not just building a network; we are crafting an interconnected ecosystem of networks, each serving distinct yet complementary roles. This visionary approach positions us at the forefront of decentralized technology, paving the way for a more
connected, secure, and sustainable future.


### Our dGNSS Network




### Introduction

FrysCrypto introduces its innovative Decentralized Global Navigation Satellite System (dGNSS), a groundbreaking advancement over traditional centralized GNSS networks. Our dGNSS is engineered to offer superior reliability, enhanced location accuracy, and crucial
contributions to space safety, particularly in preventing Kessler Syndrome.

Key Advantages of dGNSS

Enhanced Reliability Through Distributed Architecture

•	No Single Points of Failure: By distributing its functionality across numerous nodes, our dGNSS network mitigates the risk of system-wide outages. Each node plays a vital role in the network’s overall performance, ensuring uninterrupted service and enhanced system reliability.

Improved Location Accuracy

•	Data Aggregation from Multiple Sources: The decentralized nature of dGNSS allows for the integration of data from a broader array of sources, leading to more precise and accurate location information.


This level of accuracy is particularly critical in applications requiring high precision, such as autonomous vehicle navigation.

Leveraging Decentralization for Superior GNSS Services

A More Secure and Reliable Platform

•	Security and Dependability: The decentralized structure of our dGNSS network not only enhances precision but also elevates the security and reliability of location data services. This approach is instrumental in providing
a dependable platform for various applications, ranging from personal navigation to complex logistical operations.

FrysCrypto’s decentralized GNSS network represents a significant leap forward in the realm of location services. By embracing decentralization, we deliver a GNSS network that is not only more reliable and accurate but also plays a pivotal role in ensuring the safety and sustainability of space operations. Our commitment to leveraging decentralized technologies
in our dGNSS network underscores our dedication to providing cutting-edge, secure, and efficient location data solutions for a wide array of applications.

### Our ddB Network



### Introduction	Promoting Environmental Conservation


FrysCrypto proudly introduces the Decentralized Decibel Network (ddB), a state-of-the-art network designed to
transcend the capabilities of traditional centralized sound measurement systems. Our ddB network is crafted to offer unparalleled accuracy in sound measurement and make a significant contribution to environmental health.

•	Reducing Environmental Footprint: The ddB network’s decentralized approach minimizes the need for large, centralized sound measurement equipment. This not only lessens
the environmental impact but also ensures minimal disturbance to sensitive ecosystems, aligning with our commitment to environmental stewardship.



Advantages of ddb

Enhanced Reliability Through Decentralization

•	Elimination of Single Failure Points: The ddB’s decentralized architecture, spread across a multitude of nodes, ensures that the risk of complete system shutdowns is significantly minimized. Each node independently contributes to the network’s functionality, providing a more reliable and resilient system.

Superior Sound Measurement Accuracy

•      Integrating Diverse Data Sources: By aggregating data from a broad
spectrum of sources, the ddB network achieves a higher level of precision in sound measurement. This is particularly vital in applications like urban planning and noise pollution management, where accurate decibel level readings are crucial.


ddB’s Superiority over Centralized Networks

Key Areas of Outperformance

•	Reliability and Accuracy: The ddB network surpasses centralized networks in reliability and sound measurement precision. This advancement is critical for various sectors that rely on accurate sound data.

•	Environmental Impact: By reducing the reliance on large-scale infrastructure, the ddB network demonstrates a more environmentally friendly approach to sound measurement, aligning with global sustainability goals.

### Conclusion

The Decentralized Decibel Network (ddB) by FrysCrypto represents a paradigm shift in the field of sound measurement and environmental health. By leveraging the power of decentralization, we not only enhance the accuracy and reliability of sound data collection but also significantly contribute to environmental conservation. Our ddB network is a testament to our commitment to delivering innovative, sustainable, and highly efficient solutions for a diverse range of applications.


### Our dWN Network




### Introduction

FrysCrypto is proud to introduce its Decentralized Weather Network (dWN), a pioneering solution that significantly advances the capabilities of traditional
weather networks. Our dWN is meticulously designed to enhance the accuracy
of weather predictions and bolster environmental monitoring efforts.


This approach not only diminishes the environmental footprint but also minimizes disturbance to natural
habitats, reflecting our commitment to ecological preservation.

Superiority of a dWN over Traditional Networks

Key Areas of Improvement



Advantages of dWN

Robust Reliability through Decentralized Architecture

•	Elimination of Single Points of Failure: The decentralized structure of dWN, composed of numerous nodes,
each contributing to the network’s functionality, drastically reduces the risk of total network failures. This design ensures a higher level of reliability and continuous operation, which is crucial for accurate weather forecasting and monitoring.


•	Reliability and Precision: The dWN network significantly outperforms traditional centralized weather networks in both reliability and the accuracy of weather data collection. This improvement is essential for various sectors that depend on detailed and reliable meteorological information.

•	Environmental Impact: The decentralized nature of dWN embodies a more environmentally friendly approach to weather data collection and monitoring, aligning with global efforts for sustainability.



Enhanced Accuracy in Weather Data Collection

•	Broad Spectrum Data Integration: The dWN’s capacity to aggregate and analyze data from a wide range of sources translates to more precise
weather measurements. This accuracy is paramount in fields such as climate research, agricultural planning, and disaster management, where precise meteorological data can have far-reaching impacts.

Contribution to Environmental Conservation


### Conclusion

FrysCrypto’s Decentralized Weather Network (dWN) marks a significant leap forward in meteorological data collection and environmental monitoring. By harnessing the power of decentralization, we offer not only a more reliable and precise platform for weather data but also demonstrate our dedication to reducing environmental impact. The dWN stands as a testament to our commitment to delivering innovative and sustainable solutions for a wide array of applications in weather forecasting and environmental stewardship.


•	Minimizing Environmental Impact: By decentralizing the network across multiple nodes, dWN reduces the
reliance on large-scale infrastructure.



### Our dAQ Network



### Introduction	Contribution to Environmental Sustainability

FrysCrypto is at the forefront of environmental innovation with its Decentralized Air Quality Network (dAQ). This network represents a significant improvement over traditional centralized air quality networks, offering enhanced capabilities in monitoring air pollution and analyzing environmental health.

Advantages of dAQ


•	Reducing Environmental Impact: By distributing the network across
various nodes, dAQ minimizes the need for large, centralized infrastructure. This approach not only lowers the environmental impact but also lessens the disruption to local ecosystems, aligning with our commitment to ecological preservation.



Enhanced Dependability through a Distributed Structure

•	Elimination of Central Failure Points: The dAQ’s distributed architecture, encompassing a broad network
of nodes, each contributing to the network’s collective function,
significantly reduces the risk of total network failures. This design ensures higher system dependability, which is vital for continuous and accurate air quality monitoring.

Superior Accuracy in Air Quality Measurements

•	Diverse Data Source Integration: Leveraging its decentralized nature, the dAQ is capable of collecting and combining data from a wider range of sources, leading to more precise air quality measurements. This level of accuracy is crucial in applications
such as public health initiatives, urban planning, and environmental policy-making, where exact air quality data is indispensable.

Superiority of dAQ Over Traditional Networks

Key Areas of Improvement

•	Reliability and Precision: dAQ outshines centralized air quality networks in terms of reliability and the accuracy
of air quality data collection. This enhancement is crucial for sectors that rely on detailed and consistent environmental data.

•	Reduced Environmental Footprint: The decentralized approach of dAQ represents a more environmentally friendly method of air quality monitoring, contributing to global sustainability efforts.

FrysCrypto’s Decentralized Air Quality Network (dAQ) is a groundbreaking solution in the realm of environmental monitoring and health analysis.
By harnessing the strengths of decentralization, we provide a more reliable, accurate, and eco-friendly platform for air quality monitoring. The dAQ is a testament to our dedication to delivering innovative, sustainable, and effective solutions for a diverse range of applications, from public health to environmental policy development.



### Our dVDC Network




### Introduction

FrysCrypto introduces the Decentralized Visual Data Collection Network (dVDC), a cutting-edge solution that significantly surpasses traditional centralized camera networks. Our dVDC network is
designed to enhance the scope, precision, and accuracy of visual data analysis, leveraging the power of decentralization and advanced AI technologies.

Advantages of dVDC

Enhanced Reliability Through Distributed Structure

•	Reduction of Central Failure Points: The dVDC’s expansive network, comprised of a wide array of nodes, each contributing to the overall functionality, greatly diminishes the risk of complete network outages. This structure ensures higher reliability and consistency in data collection and analysis.

Superior Accuracy in Visual Data Collection

•	Diverse Location Data Aggregation: The decentralized nature of the dVDC enables the collection of visual data from a more varied and extensive
set of locations. Coupled with advanced AI algorithms, the network provides detailed insights into various phenomena such as traffic patterns, wildlife movements, and weather conditions with enhanced accuracy.

Deep Insights through AI Analysis

•	Intricate Data Extraction for Informed Decisions: The AI component of the dVDC excels at distilling complex details from visual data. This capability is crucial for comprehending
environmental trends, urban dynamics, and ecological changes, directly benefiting sectors like urban planning, environmental research, and wildlife conservation.

Reduced Environmental Impact

•	Minimizing Ecological Footprint: By decentralizing the network, the dVDC significantly reduces the reliance
on large, centralized infrastructure. This approach not only lowers the environmental impact but also minimizes disturbance to natural habitats.

Superiority Over Traditional Networks

Key Areas of Outperformance

•	Reliability and Detail: The dVDC network offers improved reliability and a heightened level of detail and accuracy in visual data collection, surpassing conventional centralized camera networks.

•	Environmental Consideration: The decentralized approach of the dVDC is more eco-friendly, aligning with our commitment to environmental stewardship and sustainable technological development.

### Conclusion

FrysCrypto’s Decentralized Visual Data Collection Network (dVDC) represents a paradigm shift in visual data analysis. By combining the strengths of a decentralized network with advanced AI capabilities,
we provide a more robust, efficient, and insightful visual data collection platform. The dVDC network is a testament to
our dedication to delivering innovative, sustainable, and effective solutions for a diverse range of applications, from urban development to environmental conservation.

### Our dBW Network



### Introduction	Promoting Technological Sustainability


FrysCrypto proudly unveils its Decentralized Bandwidth Network (dBW), a groundbreaking advancement beyond traditional centralized bandwidth monitoring systems. Our dBW network is intricately designed to augment internet traffic analysis and enhance network management capabilities.

•	Reducing Environmental and Infrastructural Impact: The dBW’s decentralized approach minimizes the reliance on large, centralized systems. This not only lessens the environmental footprint but also reduces the disturbance to local infrastructures, reflecting our commitment to sustainable technology practices.



Advantages of dBW

Enhanced Dependability through a Distributed Architecture

•	Elimination of Central Points of Failure: The dBW’s distributed structure, encompassing a broad network of nodes, each playing a role in the network’s collective strength, significantly reduces the risk of total network failures. This ensures greater system dependability, crucial for continuous and effective bandwidth monitoring.

Superior Accuracy in Bandwidth Measurements

•	Varied Data Source Integration: Leveraging its decentralized nature, the dBW efficiently collects and integrates data from a diverse range of sources. This leads to more accurate and precise bandwidth measurements, essential for optimizing network management, internet traffic, and enhancing the user experience in sectors dependent on reliable internet connectivity.


Superiority Over Traditional Systems

Key Areas of Improvement

•	Reliability and Precision: The dBW network surpasses traditional centralized bandwidth monitoring systems in both reliability and the accuracy of bandwidth data collection. This advancement is vital for various industries that rely on detailed and reliable internet traffic data.

•	Environmental and Infrastructural Consideration: The decentralized approach of the dBW is more eco-friendly and less disruptive to local infrastructures, aligning with our goals for sustainable and community-friendly technological development.

FrysCrypto’s Decentralized Bandwidth Network (dBW) marks a significant milestone in the field of internet traffic analysis and network management. By harnessing the power of decentralization, we provide a more robust, efficient, and accurate bandwidth data monitoring platform. The dBW network is a testament to our dedication to delivering innovative, sustainable, and impactful solutions for a wide range of applications, from optimizing network performance to enhancing end-user connectivity experiences.



### Our dH2O Network



### Introduction	Contribution to Environmental Sustainability

FrysCrypto introduces the Decentralized Water Quality Network (dH2O), a pioneering advancement over traditional centralized water quality systems. Our dH2O network is designed to significantly enhance the monitoring and analysis of water health, employing a distributed architecture for greater effectiveness.

Advantages of dH2O


•	Minimizing Ecological Impact: By decentralizing the network across multiple nodes, dH2O reduces reliance on large, centralized infrastructure. This not only lowers the environmental impact but also minimizes interference with natural water ecosystems, aligning with our commitment to ecological preservation.



Increased Reliability Through Distributed Structure

•	Elimination of Central Failure Points: The dH2O’s expansive network, composed of numerous nodes, each contributing to the network’s overall effectiveness, significantly diminishes the risk of complete system failures. This structure ensures higher reliability and consistent monitoring of water quality.

Enhanced Precision in Water Quality Measurements

•	Diverse Source Data Integration: The decentralized approach of dH2O enables the collection and amalgamation of data from a wide variety of water sources. This leads to more accurate and precise water quality measurements, which are vital for environmental protection, public health, and efficient resource management.


Superiority Over Traditional Systems

Key Areas of Improvement

•	Reliability and Accuracy: The dH2O network outperforms traditional centralized water quality systems in terms of reliability and the accuracy of water quality data collection. This
improvement is crucial for sectors that depend on detailed and consistent water health information.

•	Environmental Consideration: The decentralized approach of dH2O represents a more eco-friendly method of water quality monitoring, contributing to global sustainability efforts.

FrysCrypto’s Decentralized Water Quality Network (dH2O) marks a significant leap forward in the field of water health monitoring and analysis. By harnessing the strengths of a decentralized network, we provide a more robust, efficient, and precise water quality monitoring platform. The dH2O network is a testament to our dedication to delivering innovative, sustainable, and effective solutions for a diverse range of applications, from environmental protection to public health and resource management.



### Our dRAD Network




### Introduction

FrysCrypto is proud to present the Decentralized Radiation Network (dRAD), a groundbreaking development in radiation detection technology. This network represents a significant leap forward from traditional centralized systems, offering enhanced capabilities in radiation data collection and critical safety analysis.

Advantages of dRAD

Increased System Reliability Through Decentralization

•	Elimination of Central Failure Points: dRAD’s distributed structure, featuring a wide network of nodes, each contributing to the network’s efficiency, substantially reduces the risk of total system failures. This ensures greater reliability and uninterrupted radiation monitoring, which is vital for safety and environmental protection.

Enhanced Accuracy in Radiation Measurements

•	Diverse Data Source Integration: The decentralized nature of dRAD allows for the collection and integration of data from a broader range of sources. This results in more accurate and precise radiation measurements, crucial in areas such as nuclear safety, environmental protection, and public health.

Promoting Environmental and Public Safety


on large, centralized infrastructures. This approach not only lessens the environmental and logistical footprint but also improves the coverage and responsiveness of the radiation monitoring system.

Superiority Over Traditional Detection Systems

Key Areas of Improvement

•	Reliability and Precision: dRAD surpasses traditional centralized radiation detection systems in both reliability and the accuracy of radiation data collection. This is especially important for applications requiring detailed and reliable radiation information.

•	Environmental and Community Impact: The decentralized format of dRAD is more environmentally friendly and less disruptive to communities, aligning with our commitment to sustainable and responsible technological practices.

FrysCrypto’s Decentralized Radiation Network (dRAD) marks a significant advancement in the field of radiation monitoring and safety analysis. By leveraging the power of decentralization, we provide a more robust, efficient,
and precise platform for radiation data collection. The dRAD network is a
testament to our dedication to delivering innovative, sustainable, and impactful solutions for various critical applications, from nuclear safety to environmental protection and public health.

•	Reducing Infrastructure Footprint and Increasing Coverage: By dispersing the network across numerous nodes, dRAD minimizes the dependence

### Our dEN Network



### Introduction	Promoting Energy Efficiency and Environmental Conservation

FrysCrypto introduces the Decentralized Energy Network (dEN), a transformative solution in energy monitoring systems. This network signifies a major evolution from traditional centralized systems, focusing on enhancing the tracking and analysis of energy consumption.

Advantages of dEN


•	Smart Technology Integration: Utilizing smart plugs and decentralized
data collection, dEN minimizes the dependence on large, centralized monitoring systems. This not only lessens the environmental impact but also enables more localized and effective energy-saving strategies.



Enhanced Reliability Through a Distributed Framework

Superiority Over Traditional Monitoring Systems



•	Elimination of Central Points of Failure: dEN’s distributed framework, integrating an extensive array of smart plugs across various locations, each contributing to the network’s performance, drastically reduces the risk of complete network malfunctions. This ensures higher reliability and consistent energy usage monitoring.

Key Areas of Improvement

•	Reliability and Precision: dEN surpasses traditional centralized energy monitoring systems in terms of reliability and the accuracy of energy usage data collection. This
improvement is critical for sectors that depend on detailed and reliable energy consumption information.



Superior Accuracy in Energy Usage Measurements

•	Wide-Range Data Synthesis: The decentralized approach of dEN allows for the collection and synthesis of data from a diverse array of
energy sources. This leads to more accurate and precise energy usage measurements, essential for efficient energy management and promoting sustainable practices in residential and commercial environments.


•	Environmental Impact and Efficiency: The use of smart technology in dEN represents a more environmentally friendly approach to energy monitoring, aiding in the reduction of carbon footprints and the promotion of sustainable energy practices.

FrysCrypto’s Decentralized Energy Network (dEN) marks a significant step forward in the field of energy consumption monitoring and analysis. By leveraging the capabilities of decentralized smart technology, we provide a more secure, efficient, and insightful platform for monitoring energy usage. The dEN network is a testament to our commitment to delivering innovative, sustainable, and effective solutions for various applications, from optimizing energy management in homes and businesses to advancing environmental conservation efforts.


### Our dSEIS Network



### Introduction	Advancing Geological Research and Public Safety

FrysCrypto proudly unveils the Decentralized Earthquake Detection Network (dSEIS), a pioneering system significantly advancing beyond traditional centralized seismic monitoring systems. Our dSEIS network is expertly designed
to enhance the detection and analysis of seismic activities.

Advantages of dSEIS


•	Reducing Infrastructure Footprint and Improving Responsiveness: By
distributing the network across multiple nodes, dSEIS reduces reliance on large, centralized seismic stations. This not only lowers the environmental and logistical footprint but also increases the granularity and responsiveness of earthquake detection.



Increased Reliability Through a Distributed Framework

Superiority Over Traditional Seismic Systems



•	Elimination of Central Points of Failure: The distributed structure of dSEIS, consisting of numerous nodes across various locations, significantly lowers the risk of total system failures. This ensures greater reliability and continuous seismic monitoring, essential for prompt disaster response and public safety.

Key Areas of Improvement

•	Reliability and Accuracy: dSEIS surpasses traditional centralized earthquake monitoring systems in terms of reliability and the accuracy of seismic data collection. This is critical for areas requiring detailed and reliable seismic information for safety and planning.



Enhanced Precision in Earthquake Measurements

•	Diverse Geographic Data Integration: dSEIS’s decentralized approach enables the collection and integration of seismic data from a broader range of geographic locations. This leads to more accurate and precise earthquake measurements, crucial for effective disaster response, urban planning, and enhancing public safety.


•	Environmental and Infrastructural Impact: The decentralized nature of dSEIS is more environmentally friendly and less disruptive to infrastructures, aligning with our commitment
to sustainable and responsible technological development.

FrysCrypto’s Decentralized Earthquake Detection Network (dSEIS) represents a significant leap forward in the field
of seismic monitoring and analysis. By harnessing the power of decentralization, we provide a more robust, efficient, and precise platform for earthquake detection and analysis. The dSEIS network is a testament to our dedication to delivering innovative, sustainable, and impactful solutions for critical applications, including disaster response, urban planning, and public safety.



### Our dPCP Network



### Introduction	Proactive Maintenance and System Longevity

FrysCrypto introduces the Decentralized Computer Performance Network (dPCP), a groundbreaking development in the realm of computer performance monitoring.
This network represents a substantial advancement over traditional centralized systems, offering enhanced capabilities in tracking and analyzing computer hardware metrics.

Advantages of dPCP


•	Granular and Comprehensive Hardware Monitoring: By leveraging decentralized monitoring points, dPCP minimizes the reliance on centralized, single-point solutions. This approach not only provides a more granular view of hardware health but also facilitates early detection and resolution of potential issues, contributing to enhanced system longevity.



Enhanced Reliability Through Distributed Architecture

Superiority Over Traditional Monitoring Systems



•	Elimination of Central Points of Failure: dPCP’s distributed structure, composed of numerous nodes,
each contributing to the network’s functionality, significantly reduces the risk of total system malfunctions. This ensures higher reliability and consistent monitoring of computer performance across various environments.

Key Areas of Improvement

•	Reliability and Detail: dPCP surpasses traditional centralized computer performance monitoring systems
in both reliability and the detail of hardware data collection. This is particularly important in settings where computing efficiency and uptime are critical.



Superior Accuracy in Hardware Metrics Collection

•	Broad Spectrum Data Aggregation: The decentralized nature of dPCP enables the collection and aggregation of detailed hardware data from a diverse range of computers. This results in more accurate and precise measurements of key metrics like
CPU temperatures, clock speeds, RAM usage, and GPU performance, essential for optimizing computer efficiency, preventive maintenance, and system diagnostics.


•	Holistic Computer Health Monitoring: The decentralized approach of dPCP allows for a more comprehensive
and proactive stance on computer maintenance, offering benefits like early issue detection and system optimization.

FrysCrypto’s Decentralized Computer Performance Network (dPCP) marks a significant step forward in computer hardware monitoring and analysis.
By harnessing the strengths of a decentralized network, we provide a more secure, efficient, and detailed platform for monitoring computer performance. The dPCP network is a testament to our commitment to delivering innovative, comprehensive, and effective solutions for a wide range of applications, from individual computing to large-scale enterprise systems.

### Our dOCG Network



### Introduction	Advancing Marine Science and Conservation

FrysCrypto is excited to introduce the Decentralized Oceanographic Network (dOCG), a transformative approach to oceanographic monitoring that marks a significant advancement over traditional centralized systems. Our dOCG network is designed to enhance the collection and analysis of critical marine data.

Advantages of dOCG


•	Minimizing Environmental Impact and Enhancing Data Quality: By spreading the network across multiple nodes, dOCG reduces reliance on large, centralized oceanographic stations. This approach not only lessens the environmental impact on marine ecosystems but also broadens the scope and resolution of oceanographic data collection.



Enhanced Reliability Through a Distributed Framework

•	Elimination of Central Points of Failure**: dOCG’s distributed
framework, featuring numerous nodes strategically located across
different oceanic regions, considerably reduces the risk of complete system failures. This ensures greater reliability and continuous monitoring of oceanographic parameters.

Superior Accuracy in Marine Data Collection

•	Comprehensive Oceanographic Data Synthesis: The decentralized structure of dOCG enables the gathering and analysis of data from a wider range
of marine environments. This leads to more accurate measurements of oceanic parameters such as temperature, salinity, currents, and marine biodiversity, essential for
marine research, climate studies, and ecosystem management.


Superiority Over Traditional Oceanographic Systems

Key Areas of Improvement

•	Reliability and Comprehensive Data Collection: dOCG outperforms
traditional centralized oceanographic monitoring systems in terms of reliability and the comprehensiveness of marine data collection. This is crucial for applications requiring detailed and accurate oceanographic information.

•	Environmental Impact and Scientific Contribution: The decentralized nature of dOCG is more environmentally friendly and offers enhanced scientific insights, aligning with our commitment to sustainable marine research and conservation.

FrysCrypto’s Decentralized Oceanographic Network (dOCG) represents a significant leap forward in the field of marine data collection and analysis. By leveraging the power of decentralization, we provide a more secure, efficient, and comprehensive platform for oceanographic data collection. The dOCG network is a testament to our dedication to delivering innovative, sustainable, and impactful solutions for a wide range of maritime applications, from advancing marine science to supporting ecosystem management and climate research.

### Our dSQ Network



### Introduction	Promoting Sustainable Land Use and Agriculture

FrysCrypto proudly announces the Decentralized Soil Quality Network (dSQ), a groundbreaking innovation that marks a significant advancement over traditional centralized soil monitoring systems. Our dSQ network is designed to enhance the assessment and analysis of soil health, employing a distributed configuration for optimal effectiveness.

Advantages of dSQ


•	Localized and Specific Soil Health Assessments: By distributing the network across numerous nodes, dSQ reduces dependence on large, centralized soil testing facilities. This approach not only minimizes the
environmental impact but also enables more targeted and localized soil health assessments, supporting sustainable land use and agricultural practices.



Increased Reliability Through Distributed Configuration

Superiority Over Traditional Soil Monitoring Systems



•	Elimination of Central Points of Failure: dSQ’s extensive network, with nodes spread across diverse geographical areas, significantly lowers the risk of complete system shutdowns. This ensures higher
reliability and continuous monitoring of soil quality, essential for effective land management.

Key Areas of Improvement

•	Reliability and Detailed Data Collection: dSQ surpasses traditional centralized soil quality systems in terms of reliability and the detail of soil data collection. This is particularly important for applications requiring precise and comprehensive soil health information.



Superior Accuracy in Soil Data Collection

•	Comprehensive Soil Data Integration: The decentralized nature of dSQ allows for the collection and combination
of soil data from a broader range of environments. This leads to more
accurate measurements of crucial soil properties like nutrient content, pH levels, moisture, and organic matter composition, vital for sectors such as agriculture, environmental research, and land management.

•	Environmental Impact and Agricultural Support: The decentralized approach of dSQ is more environmentally friendly and supports more sustainable agricultural practices, aligning with
our commitment to responsible and sustainable land management.

FrysCrypto’s Decentralized Soil Quality Network (dSQ) represents a significant step forward in the field of soil health assessment and analysis. By leveraging the strengths of a decentralized network, we provide a more secure, efficient,
and precise platform for monitoring soil quality. The dSQ network is a testament to our dedication to delivering innovative, sustainable, and effective solutions for various applications, from agriculture
to environmental research and land management.


### Our dVPN Network




### Introduction

In the ever-evolving landscape of digital security, FrysCrypto’s Decentralized VPN Network (dVPN) stands out as a necessary tool for modern online interactions.
Our dVPN network offers significant advantages over traditional centralized VPN services, prioritizing user privacy and security in today’s digital world.

Advantages of dVPN

Decentralization for Enhanced Security

•	No Central Authority or Control Point: The completely decentralized nature of our dVPN network means there is no single point of control or failure. This significantly reduces the risk of
network compromise, thereby ensuring enhanced user privacy and security.

Scalability and Performance

•	Accommodating Large User Numbers**: Thanks to the distributed architecture of our dVPN network, which spans a large number of nodes, we can support a high volume of users without sacrificing performance or security. Each node plays a role in maintaining the network’s overall functionality, allowing for efficient scalability.

Transparent and Trustworthy Network

•	Public Ledger for Transactions: Our dVPN network maintains complete transparency with all actions and


transactions recorded on a public ledger. This visibility ensures that users can easily verify the authenticity of transactions, fostering trust and accountability within the network.

The Necessity of dVPN in Today’s Digital Age

Ensuring Online Privacy and Security

•	Meeting the Demand for Digital Security: In an era where online privacy and security are increasingly paramount, our dVPN network is
not just an option but a necessity. It addresses the growing concerns over data privacy and security in online environments.

•	Providing a Safe and Reliable Online Platform: By delivering a decentralized, scalable, and transparent VPN service, we aim to equip users with a robust platform for their online activities, ensuring their digital interactions are secure and private.

FrysCrypto’s Decentralized VPN Network (dVPN) is a critical innovation in the realm of digital privacy and security. By embracing decentralization, scalability, and transparency, we offer a superior
alternative to traditional VPN services. Our dVPN network is dedicated to providing users with a safe, reliable, and private online experience, meeting the essential needs of privacy and security in today’s digital age.


### Indoor GNSS base stations = Bad Data?




### Introduction

Traditionally, indoor Global Navigation Satellite System (GNSS) base stations have faced challenges in achieving the accuracy level of their outdoor counterparts, mainly due to interference from building structures. Recognizing this limitation, FrysCrypto has developed an innovative system to enhance the precision of indoor location-based services.

Advancements in Indoor GNSS Technology

Mitigating Interference for Greater Accuracy

•	Reducing Data Inaccuracies: Building structures can interfere with the GNSS signal, leading to the generation of bad data and consequent inaccuracies in location-based services. Our system addresses this issue by deploying multiple Indoor Satellite Miners in a single area.

Multiple Indoor Base Stations Approach

Impact on Location-Dependent Industries

Transformative Potential for Various Sectors

•	Boosting Efficiency and Safety: The enhanced accuracy provided by our Indoor Satellite Miners is a game-changer for sectors that depend on reliable location data. This technology is poised to revolutionize practices
in logistics, navigation, autonomous vehicle operation, and more, by providing reliable and precise indoor positioning.

FrysCrypto’s innovative approach to indoor GNSS base stations marks a significant leap in the realm of location-based services. By implementing a system of multiple Indoor Satellite Miners, we provide a solution that overcomes traditional limitations, offering more accurate and reliable indoor location services. This advancement is set to transform industries that depend on precise location data, enhancing efficiency, safety, and overall user experience.


•	Eliminating Outlier Data: The presence of multiple Indoor Satellite Miners allows for the cross-verification of data, effectively mitigating the risk of bad data. By filtering out outlier data, our system significantly enhances the accuracy of location-based services indoors.

Independent of Outdoor Stations

•	Reliable Indoor Location Services: Our system of multiple indoor GNSS base stations ensures that users can experience accurate location-based services independently of
outdoor stations. This breakthrough is particularly beneficial for industries that rely on precise location data, such as logistics, navigation, and autonomous vehicles.



### The Formula




To demonstrate how multiple indoor GNSS (Global Navigation Satellite System)
base stations can mitigate the issues of poor data quality traditionally associated with indoor GNSS reception, we can formulate an approach based on the principles of trilateration and signal quality enhancement. Here’s a simplified version of the concept:

1.	Signal Trilateration Formula:

Let $(P_1, P_2, ..., P_n)$ be the positions of $n$ GNSS base stations inside a building.

Let $S(x,y,z)$ be the position of the GNSS receiver where $(x, y, z)$ are its coordinates.

The improved signal data from each base station is then used to calculate a more accurate position of the receiver.

3.    Combining Data from Multiple Stations:

The position of the receiver $S(x,y,z)$ is determined by solving the system of equations formed by the distances $d$ to each base station. 

With multiple base stations, the system of equations becomes overdetermined, allowing for error minimization techniques like least squares to be applied for more accurate positioning.

4.    Error Reduction:



The distance $d_i$ from the receiver to each base station is given by the
formula: $d_i = \sqrt{(x-x_i)^2+(y-y_i)^2+(z-z_i)^2}$ are the coordinates of base station $P_i$

2.    Signal Quality Improvement:

Each base station receives satellite signals, which are then processed to improve signal quality. This can
involve filtering out noise, correcting for multipath errors (where signals bounce off surfaces), and integrating data from multiple satellites.

The use of multiple base stations allows for cross-referencing and error checking. Inconsistencies between the data from different stations can be identified and corrected.

This redundancy reduces the impact of any one station’s poor data quality or temporary signal loss.

5.    Algorithmic Enhancement:

Advanced algorithms can be used to further refine the position estimates by considering factors like signal-to-noise ratio, historical data patterns, and environmental factors affecting signal propagation.

### A Decentralized Network of Decentralized Networks?





### Introduction

FrysCrypto envisions the creation of an expansive decentralized network of
decentralized networks, spanning various industries and applications. This intricate web of interconnected networks aims
to serve as a foundational backbone for a wide array of digital and physical applications.


•	Device Integration Across Networks: Our approach includes supporting devices from various projects, enhancing the range and quality
of data contributed to our network and improving the effectiveness of our Decentralized Wireless (DeWI) networks.

Enhancing Data Quality and Network Sustainability



Core Components of Our Vision

Commitment to Interoperability and Collaboration

•	Fostering Stronger Networks: By embracing interoperability and collaborative efforts with other decentralized networks, we aim to forge a more resilient and adaptable system, tailored to meet the evolving needs of our users.


•	Diverse Device Ecosystem: By enabling a wide range of devices to integrate and provide data, we enhance not only the quality but also the diversity of the data collected. This contributes significantly to the sustainability and growth of the network.


Support for Multi-Token Mining and Device Compatibility

•	Dual/Triple Mining Capabilities: In line with our commitment to network diversity and strength, we will support dual, triple, or multiple token mining, including $FRY and tokens from other projects.





### Our Ultimate Goal



### Creating a Versatile and Secure Decentralized Network

•	Supporting Various Applications and Industries: Our objective is to establish a decentralized network capable
of accommodating a multitude of applications and industries, offering users the privacy, security, and reliability essential in the digital era.

Open Collaboration and API Integration

•	Inclusive Support for External Devices: Beyond official collaborations, we also plan to support devices from other projects via public APIs. This inclusive approach ensures that our network’s capability extends to a broader range of devices, even those not part of official collaborations.



•	Empowering Through Decentralization: Leveraging the strengths of decentralized networks and collaborating with other entities, we aim to forge a future that is more connected, secure, and beneficial for all participants.

FrysCrypto’s vision of a decentralized network of networks is poised to revolutionize how digital and physical systems interact and operate. By fostering interoperability, supporting diverse mining capabilities, and ensuring wide-ranging device compatibility, we are committed
to building a network that is not only expansive but also resilient, adaptable, and inclusive. Our ultimate goal is to create a decentralized infrastructure that empowers users and industries, paving the way for a more interconnected and efficient future.


### Potential $FRY Use Cases



### Introduction	


FrysCrypto’s $FRY token is designed as a multifaceted utility token, central to the FRY ecosystem. Our goal is to establish $FRY as a versatile tool within our network, fostering a robust and sustainable ecosystem through its various applications.


### Key Use Cases of $FRY	

1.	Payment for BYOD Licenses
•	Facilitating Access to Technology: $FRY serves as a currency for purchasing licenses in our “Bring Your Own Device” (BYOD) program, simplifying the process for users
to join and contribute to the FRY ecosystem.


2.    Payment for Data Purchases
•	Streamlining Data Transactions: Users can utilize $FRY to
acquire valuable data within the ecosystem, making transactions seamless and efficient.

3.    Payment for Advertising Space
•	Empowering Marketing Efforts: $FRY is used as a medium of exchange for advertising space within the FRY network, offering businesses and individuals a unique opportunity to promote their services or products.

4.	Payment for DeWI Network Utilization
•	Accessing Decentralized Wireless Services: Users can pay with $FRY to access the Decentralized Wireless (DeWI) networks, enhancing
the accessibility and use of decentralized connectivity solutions.

5.    Compensation Backpay
•	Rewarding Contributions: $FRY acts as a form of compensation, rewarding users for their participation and contributions to the FRY ecosystem.

6.    Trading Pairs
•	Facilitating Cryptocurrency Exchange: $FRY is used in trading pairs, allowing users to exchange it for other cryptocurrencies, enhancing its liquidity and utility within the broader crypto market.

7.	Charity Donations
•	Supporting Social Causes: Users have the opportunity to use $FRY for charitable donations, enabling the FRY community to contribute to social and humanitarian causes.

### The Vision for a Sustainable Ecosystem

### Building a Robust Network

•	Encouraging Diverse Applications: By promoting the use of $FRY in various capacities, we aim to build an ecosystem that is not only robust but also adaptable and sustainable,
catering to a wide range of needs and preferences within our community.

The $FRY utility token is a cornerstone of FrysCrypto’s vision for a versatile and thriving ecosystem. By enabling a wide array of use cases – from technology access and data transactions to advertising and charity – $FRY is poised to become an integral part of our users’
digital experience, driving the growth and sustainability of the FRY ecosystem.


### Mining Rewards



### Introduction

The Fry Foundation recognizes the importance of incentivizing user participation in our decentralized network ecosystem. To encourage active engagement, we have implemented a tiered device system, designed to regulate the earning potential of $FRY based on the type and contribution of each device.

### Device Tiers and Their Rewards

#### Tier X

$FRY/day: 4442.47

Restrictions: Exclusive to $FRY staff.

Example: Contributor Nodes – specialized nodes operated by Fry Foundation staff for network development.


#### Tier 2

$FRY/day: 107.86

Restrictions: Only one device allowed per public IP.

Example: Bandwidth Miner – focused on bandwidth usage and optimization.

#### Tier S

$FRY/day: 431.44

Restrictions: No Bring Your Own Device (BYOD) option.

Example: Infrastructure Nodes – critical for the foundational structure of the network.



#### Tier 3

$FRY/day: 107.86

Restrictions: Limited to one device per
location, irrespective of public IP.

Example: Indoor Air Quality Miner, Pebble – devices for monitoring indoor air quality.

#### Tier 1

$FRY/day: 215.72

Restrictions: Limited to one device per location, regardless of public IP.

Example: High-End Weather Miner – specialized in advanced weather data collection.



#### Tier 4

$FRY/day: 82.86

Restrictions: Up to 5 devices permitted per location, regardless of public IP.

Example: Indoor Satellite Miner – contributing to indoor GNSS data accuracy.



#### Tier Z

$FRY/day: 1

Restrictions: Maximum of 25 devices in total; separate Algorand Address required for each device; no Virtual
Private Servers (VPS) or Virtual Machines (VMs) allowed.

Example: Recycle Miner – incentivizes the use of
repurposed devices for mining.

The Purpose of the Tier System

•	Fair Distribution of Earnings: The tier system is strategically designed to balance the $FRY earnings in relation to the significance and utility of each device within the network.

Enhancing Network Diversity and Efficiency

•	Diversity in Device Deployment: By varying the reward structure and imposing specific restrictions, we encourage the deployment of a diverse array of devices, enhancing the
network’s data collection capacity and overall efficiency.



The Fry Foundation’s tiered device system is integral to fostering a dynamic, sustainable, and thriving decentralized network. By offering structured incentives aligned with the type and contribution of each device, we aim to motivate users to play an active role in the
network’s growth, ensuring its longevity and effectiveness across various applications and industries.



### BYOD Program



FrysCrypto’s Bring-Your-Own-Device (BYOD) program presents an accessible and cost-effective opportunity for individuals to engage with our decentralized networks. This initiative allows users to convert their own devices into $FRY miners, earning rewards while contributing to the network’s expansion.



BYOD Program Details




•	One-Time Fee: To join the BYOD program, users incur a one-time fee of $105 USD per device.

•	Payment Structure: Each license must be acquired with $52.5 USD worth of $FRY and $52.5 USD worth of $ALGO. There are no alternate payment methods available.

•	Open to Individual Involvement: The BYOD program is designed to make participation in our decentralized networks accessible to a broader audience, offering individuals a chance to contribute using devices they already own.


### Reward System

•	Earning Potential: Participants in the BYOD program will receive rewards for their mining efforts. However, it’s important to note that these rewards are half of what our proprietary “hardware” miners earn.

•	Incentivized Participation: By offering rewards for participation, we aim to encourage active engagement in our network. Although the rewards for BYOD miners are structured differently, they represent a valuable opportunity for users to earn while contributing to the network’s growth.



Encouraging Hardware Miner Use

•	Advocating for Eco-Friendly Solutions: Our preference for users to utilize
our hardware miners stems from our commitment to environmental sustainability. These miners are
verified for using recycled equipment, contributing to e-waste reduction.

License Requirement for Participation

FrysCrypto’s BYOD program is a strategic initiative aimed at expanding participation in our decentralized networks. By offering a straightforward and incentivized path for individuals to use their own devices as $FRY miners, we create a more inclusive, sustainable, and thriving network
ecosystem. This program not only opens up avenues for wider community involvement but also aligns with our commitment to environmental stewardship.


•	Mandatory Licensing for Each Device: Users must obtain a license for every device they wish to onboard into
the network. This licensing process ensures orderly participation and helps maintain network integrity.


### Reward Multipliers




### Introduction

The Fry Foundation is committed to encouraging active and consistent participation in our ecosystem. To achieve this, we have implemented a unique multiplier system that amplifies the rewards for our contributors, based on the Proof
of Connectivity (PoC) and responsive adjustments to market price fluctuations of $FRY.

Multiplier System Based on Device Connectivity

Proof of Connectivity (PoC) Model

•	Hourly Connectivity Checks: Devices within our network are required to send a connectivity check every hour through the Algorand blockchain, using a 0 FRY transaction. This ensures consistent online presence of the devices.

Reward Calculation

•	Daily Rewards Formula: Daily rewards for each device are calculated using the formula x/24 * device tier reward, where x represents the number of connectivity checks sent by the device in a 24-hour period.

Market-Responsive Reward Structure

Adapting to Market Price of $FRY

•	Multiplier Effect on Base Reward: When the market price of $FRY falls below 1 cent USD, the base reward earned by participants is doubled (multiplied by 2).

•	Additional Multipliers for Price Declines: For every additional zero added to the right of the decimal point in $FRY’s price, an extra 1.5x multiplier is applied to the base reward.

Encouraging Participation in Varying Market Conditions

•	Rewarding Consistent Online Presence: This adaptive reward system is designed to motivate users to keep their devices online, even in less favorable market conditions. It ensures that participants receive fair compensation regardless of $FRY’s market value fluctuations.

The Fry Foundation’s ecosystem is innovatively designed to reward and motivate consistent participation. Our multiplier system, coupled with the Proof of Connectivity model, ensures that active contributors are fairly remunerated, especially during market downturns. This approach not only stabilizes the reward system but also encourages ongoing
participation, contributing to the resilience and growth of our decentralized network.



### Compensation




### Introduction

At the Fry Foundation, we prioritize timely delivery of our products and understand its importance to our users. To address any inconveniences caused by order delays, we have established a compensation
program that offers $FRY tokens to users as recompense for any delays in their orders.

Compensation Program Details

Process for Compensation

•	User-Initiated Claims: Compensation for delayed orders is not automatic. Users must proactively contact
our support team to initiate the compensation process.

•	Compensation Amount: In the event of a delay, users are compensated with an amount of $FRY equivalent to the daily earnings potential of each device in the delayed order.

Benefits of the Compensation Program

Maintaining Market Reputation

•	Enhancing Customer Satisfaction: By offering compensation for delays, we aim to maintain a positive reputation in the market, which is crucial for attracting and retaining customers.

Incentive for Timely Delivery

•	Motivation to Avoid Delays: The compensation program serves as an incentive for us to ensure timely delivery


of orders, as delays result in additional costs to the business.

Building Trust and Loyalty

•	Strengthening User Relationships: Offering compensation for delays fosters trust and loyalty between the Fry Foundation and its users, a key factor in the long-term sustainability of our business.

Claiming Compensation

Steps to Follow

•	Joining Discord for Support: Users can claim compensation for delayed orders by joining our Discord server and creating a ticket in the help desk channel.

•	Verification and Credit: Users should provide their order number and details of the delay. Our team will verify the delay and, once confirmed, credit the user’s account with the appropriate amount of $FRY after the order arrives.

The Fry Foundation’s compensation program for order delays is a testament to our commitment to user satisfaction and business integrity. By offering this program, we not only address the immediate concerns of our users but also reinforce the values of trust, reliability, and customer-centric service. This approach plays a vital role in strengthening our market position and building enduring relationships with our users.



### Our Green Initiative



### Introduction

At $FRY, we are deeply committed to environmental consciousness, recognizing our responsibility in reducing e-waste. Our approach to being a green utility coin project involves unique steps to ensure that our $FRY miners are not only efficient but also eco-friendly.

Green Initiatives in $FRY Mining

Utilization of Recycled Technological Parts

•	Recycling and Reusing Components: A key aspect of our green approach is the use of recycled RAM, CPUs, SSDs, and entire computer systems in constructing our $FRY bandwidth and satellite miners. This strategy significantly reduces our environmental footprint and addresses the pressing issue of e-waste.

Quality Assurance

•	High Standards for Recycled Miners: While prioritizing recycled materials, we ensure that the quality of our miners is not compromised. Each miner undergoes rigorous quality checks to ensure efficient and problem-free mining of $FRY.

Ongoing Commitment to Environmental Impact Reduction

Balancing Quality with Sustainability

•	Continued Efforts in Eco-Conscious Practices: Our dedication to minimizing environmental impact goes hand in hand with our commitment to delivering high-quality mining equipment to our users. We continuously seek innovative ways to enhance our eco-friendly practices.

Adaptability in Supply Chain Challenges

•	Striving for Recycled Sourcing: We acknowledge that supply-chain limitations may occasionally hinder our ability to source recycled parts. Nonetheless, our commitment to seeking eco-friendly solutions remains steadfast, and we endeavor to make recycling a priority in our procurement process.

The green initiative of our $FRY project is a cornerstone of our vision and operational philosophy. By embracing the recycling of e-waste and maintaining high-quality standards in our equipment, we strive to reduce our environmental impact while providing a reliable and efficient mining experience. Our commitment to environmental sustainability is integral to our ethos, driving us to innovate and contribute positively to the ecosystem in which we operate.



### Liquidity




### Introduction

Understanding the critical importance of liquidity in the cryptocurrency market, FrysCrypto has implemented a liquidity provision mechanism. This strategy is designed to maintain a healthy and sustainable ecosystem for our crypto project, particularly for our token swap pairs such as ALGO/FRY, among others.

Liquidity Provision Mechanism

Allocation of Revenue for Liquidity

•	Revenue Contribution: We have allocated 10% of all revenue from hardware sales and earnings from our decentralized networks towards enhancing the project’s liquidity.

•	Purposeful Allocation: The portion of revenue set aside from hardware sales, network activities, and data sales is dedicated specifically to maintaining liquidity in our swap pairs.

Controlled Liquidity Management

•	Non-Automatic Process: The process of adding liquidity is not automated. Our team retains control over when and how liquidity is provided. This approach ensures we have the flexibility to adapt to market conditions and sustain the project’s long-term viability.

Benefits of Liquidity Provision

Enhancing User Experience in Token Transactions


•	Preventing Trading Difficulties: By proactively managing liquidity, we aim to prevent scenarios where users
face challenges in buying or selling our tokens due to insufficient liquidity.

Favorable Conditions for Token Holders

•	Ease of Trading: Our commitment to liquidity provision means that token holders will find it easier to trade
our tokens, likely at more favorable prices, enhancing the overall trading experience.

Commitment to Long-Term Success

Ensuring Ecosystem Health and Sustainability

•	Strategic Approach for Growth: Our focus on liquidity provision demonstrates our dedication to the long-term success and stability of our project. By ensuring a robust ecosystem, we are confident in the
continued growth and development of FrysCrypto.

FrysCrypto’s liquidity provision strategy is a vital component of our commitment to creating a stable and thriving ecosystem for our crypto project. By allocating a portion of our revenue to ensure sufficient liquidity and carefully managing the process, we are not only enhancing the trading experience for our users but also laying a strong foundation for the project’s future success.


### Bandwidth Miner Risks




### Introduction

Participating in bandwidth mining within a decentralized network like FrysCrypto comes with certain risks. It is crucial for
potential contributors to understand these risks and adopt measures to mitigate them effectively.

Primary Risks in Bandwidth Mining

Potential Misuse by Bad Actors

•	Risk of Illegal Activities: There is a possibility that your miner could be exploited by bad actors for illegal activities, ranging from distributing prohibited content to launching DDoS attacks.

•	Mitigation Strategies: While completely eliminating this risk is challenging, certain steps can be implemented to reduce the likelihood of such misuse.


Alternative Option: Satellite Miners

•	For Enhanced Security and Peace of Mind: For contributors concerned about the risks associated with bandwidth mining, we recommend using our satellite miners.

•	Independent Operation: Satellite miners operate independently of the contributor’s primary network, only using it to forward GNSS data. This minimizes the risk of the miner being
used for unauthorized access or content distribution.

•	Security vs. Earning Potential: While satellite miners may yield lower $FRY earnings compared to bandwidth miners, they offer a higher level of security and peace of mind.


Utilization of OpenDNS

•	Content Filtering Tool: OpenDNS serves as an effective tool to filter network content. It restricts access to websites and content that might be illegal or harmful, thereby reducing the risk of your miner being used for nefarious purposes.

### Conclusion
•	Informed Decision-Making: Contributors should weigh the risks and benefits of different mining options. By using tools like OpenDNS and considering satellite miners, contributors can participate in our dVPN network more securely.

•	Commitment to Contributor Safety: FrysCrypto is dedicated to ensuring the safety and integrity of our decentralized network. We encourage our contributors to take proactive steps to secure their participation, thereby enhancing
the overall health and security of the network.


### Risks Associated with Cryptocurrency



In our commitment to transparency and informed decision-making, this section of the [Project Name] whitepaper is dedicated to outlining the specific risks associated with the use of cryptocurrency. It is crucial for stakeholders to understand these risks to make well-informed decisions regarding their involvement with our project.

Market Volatility

Cryptocurrency markets are notably volatile, with prices subject to rapid and significant fluctuations. This volatility can impact the value of assets held by the Fry Foundation, affecting our financial planning and stability. Stakeholders should be prepared for the possibility of sudden and substantial changes in the value of their crypto investments.

Regulatory Risks

The legal landscape for cryptocurrencies is in a constant state of flux. Changes
in laws and regulations can significantly affect the legality, taxation, and operation of cryptocurrency projects. There is a risk that future regulatory developments could adversely impact the Fry Foundation,
including potential restrictions on the use of or access to cryptocurrencies.

Security Risks

Cryptocurrencies are vulnerable to a variety of digital threats, including hacking, phishing, and other cyber-attacks. Despite
our robust security measures, there is always a risk of loss due to such breaches. We continually update our security protocols, but stakeholders should be aware of these risks.

Technological Risks

Our project relies on the underlying blockchain technology, which, like any technology, is subject to risks such as system failures,
bugs, and vulnerabilities. These risks could lead to the loss or theft of cryptocurrency assets, impacting the project’s success and stakeholder value.

Liquidity Risks

Cryptocurrencies may experience issues with liquidity, making it challenging to execute large transactions without affecting market price significantly. This can pose a problem for the Fry Foundation when converting crypto assets to fiat currency or vice versa.

Legal and Compliance Risks

Non-compliance with applicable laws and regulations can lead to legal challenges, fines,

or sanctions. [Project Name] is committed to compliance, but the evolving nature
of cryptocurrency regulation presents an ongoing risk.

Reputation Risks

The association with cryptocurrency can lead to reputational challenges. Public perceptions of its use in illegal activities, its environmental impact, or its speculative nature could affect the project’s public image and stakeholder trust.

Operational Risks

Managing a cryptocurrency project requires specific skills and expertise. Operational risks arise from potential mismanagement or a lack of experienced personnel, which can lead to project inefficiencies or failures.

Dependence on Third Parties

The Fry Foundation relies on third-party services, including wallets, exchanges, and other platforms. Failures or issues with these services can have a direct negative impact on our operations and project success.

Counterparty Risks

There is an inherent risk that counterparties in cryptocurrency transactions may fail to meet their obligations, potentially leading to financial losses for the Fry Foundation and its stakeholders.

Adoption Risks

The success of the Fry Foundation is partly dependent on the broader adoption of cryptocurrency. Failure to achieve widespread acceptance can lead to the project’s underperformance or failure.

Environmental Risks

Some cryptocurrencies, particularly those using proof-of-work mechanisms, have significant environmental impacts due to their energy consumption. This raises concerns
and potential for regulatory action that could affect the Fry Foundation

While the Fry Foundation is committed to mitigating these risks, it is important for stakeholders to be aware of and understand these challenges. We believe in the potential of cryptocurrency to drive innovative solutions but also recognize the importance of caution and due diligence in this rapidly evolving space.

### Final Notes



### Introduction

The Fry Foundation upholds transparency and responsibility as core values. We want to clearly communicate the nature of $FRY to our community, emphasizing the importance of understanding its value, purpose, and the inherent risks associated with cryptocurrency involvement.

Understanding the Value of $FRY

Market-Driven Valuation

•	Community and Market Influence: The value of $FRY is determined solely by community engagement and market dynamics. We do not set or guarantee any specific value for $FRY.

Value Perception


ownership in the Fry Foundation. Its primary role is as a currency on the Algorand blockchain, facilitating transactions such as payment for work or goods.

Unique Functionalities

•	Proof-of-Connectivity (PoC): $FRY miners use Proof-of-Connectivity to verify their active contribution to
the network, showcasing the unique programming functions of $FRY.

Participation Agreement

Acknowledgment of Risks

•	Acceptance of Whitepaper Terms: By participating in the project, including visiting our website, users agree to the terms outlined in this whitepaper.



•	$FRY Valuation: The value of $FRY should be perceived based on its own merit, without comparisons to fiat currencies or other cryptocurrencies. One $FRY is equal to one $FRY and nothing more.


•	Risk Awareness: Potential participants are reminded of the high risks in crypto investment and are encouraged to consider their financial situation and risk tolerance carefully.

No Guarantee of Financial Gains

Investment Risks

•	No Promised Returns: We do not promise or guarantee any financial gains from activities associated with $FRY, including trading, mining, or providing liquidity.

•	Individual Responsibility in Risk Management: The risks associated with cryptocurrency investment are solely the responsibility of the participant.

Nature and Purpose of $FRY

Not a Security or Stock

•	$FRY as a Currency: $FRY is not a security or stock and does not represent

### Disclaimer of Liability

•	No Liability for Losses: The Fry Foundation, its founder Samuel Fry, and staff are not liable for any losses or
damages incurred through participation in the project, including mining, buying, or trading $FRY.

The Fry Foundation emphasizes the importance of understanding and accepting the inherent risks in
cryptocurrency investment, especially with $FRY. Our commitment to transparency and responsible communication is aimed at ensuring that participants are fully aware of the nature of $FRY and the risks involved. We strongly advise our community members to engage with our project cautiously, with a clear understanding of the only guarantee in crypto: risk.


### Conclusion



Embracing a Future of Decentralization and Sustainability

Crafting a Network of Networks

•	Our Core Mission: FrysCrypto ($FRY), flourishing within the Algorand ecosystem, is ambitiously set to create a comprehensive decentralized network of decentralized networks.
This innovative structure is designed to offer resilience and adaptability across diverse industries and applications.

Commitment to Mainstream Crypto Adoption and Environmental Consciousness

•	Dual Objectives: We are dedicated not only to fostering the mainstream adoption of cryptocurrencies but also to minimizing e-waste. This dual focus underscores our commitment to both digital advancement and environmental sustainability.

Simplifying Cryptocurrency Usage

User-Friendly $FRY Miners

•	Ease of Access: Simplifying the setup of our $FRY miners has been a key focus, ensuring accessibility for users regardless of their technical background in crypto mining.

Green Initiative and Sustainable Practices

•	Eco-Friendly Approach: Aligning with our green initiative, our miners are constructed using recycled components, highlighting our
dedication to reducing environmental impact and promoting sustainable technological practices.

Independent Yet Interconnected Networks

A Balanced Ecosystem

•	Autonomous yet Connected: Our network design ensures that each individual network can function independently while also being capable of interconnection. This approach guarantees both the independence and collective strength of our decentralized network.

The Practical Utility of $FRY

A Versatile Cryptocurrency

•	Wide-Ranging Use Cases: $FRY is positioned as a versatile tool within our ecosystem. It is not just a digital currency but also a means for facilitating various activities, such as payments for goods and services, within the Fry Foundation’s network.

Forward-Looking Statement

As we advance, FrysCrypto stands as a beacon of integrating decentralized technology with sustainability. Our commitment to building an intricate network, promoting the adoption
of cryptocurrency, and prioritizing environmental responsibility distinguishes us in the digital landscape. Moving forward, our focus is to continually provide a secure, efficient, and user-centric platform. With $FRY, we are not just envisioning a future where technology harmonizes with sustainability; we are actively forging this reality.

