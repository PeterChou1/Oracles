# Research topics



## Create an Oracle:

> Build based on a problem: 
>
> ​	Create services based on issues in existing Oracle services/structure.
>
> Build something new: 
>
> ​	By combining multiple topics, E.g., Orcale+{ZK, Bridge, Stablecoin, Automation, Detect Vulnerabilities}

1. Build generalized oracle nodes hosted on existing chains (Smart Contract). 

   - Not like Chainlink running its LINK chain/coin.
   - I haven't thought about what's the benefit.
   
2. Oracle + DNS or ENS?
   - Is there anything that could go wrong or pass chainlink's tamper-proof to return a fake IP address for "Apple.com"?
   
     | Web2 Browser + extension | Web3 Smart Contract + Oracle                                 |
     | ------------------------ | ------------------------------------------------------------ |
     | -> ENS Contract          | -> ***actual DNS record loaded by a centralized node or Chainlink node?*** |
     | -> address               | -> IP address                                                |
     | -> IPFS object           | -> server object                                             |




## Using existing Oracle:

1. Create Oracle that uses/combines all other oracles: DIA+Chainlink+Band Protocol

2. Use Chainlink:

   - Use Chainlink

   - Use Chainlink/Market Data

   - Use Chainlink/Weather Data
     - Classic example: Insurance Smart Contract that execution depends on Oracle data.

   - Use Chainlink/Sports Data

   - Use Chainlink/Automation

   - Use Chainlink/Randomness

   - Use Chainlink/AnyAPI




## Peter's idea

Make a Chainlink!



## Soso's idea

Peter mentioned the nodes only trust a limited amount of source that is hard coded in each oracle script. For example, the weather oracle script will have weather.google.com and weather.yahoo.com hard coded in it, which looks pretty centralized and makes web3 highly dependent on some servers in web2.



This issue is bonded with current big Oracle companies, like Chainlink and Band Protocol; there is no simple way to use or change their blockchain to fix this issue. We have to create a new chain.



I propose a hardware oracle that runs on a PoS blockchain we built using Cosmos SDK (similar to how Bandchain was created, similar to Polkadot).



https://explorer.helium.com/

The hardware is similar to Helium miners. Helium miners/nodes are the physic devices that look like a wifi router. They validate each other's location and range.

They build new networks by connecting with each other, and getting paid depends on the amount of data they transfer.

You can see that rewarding people with coins motivates people to buy hundred-dollar devices worldwide.



We are copying the Helium chain; for our purpose of Oracles, we don't need the nodes to have a routher with a powerful antenna.

The only thing for each node to run is an old phone connected to a network. Our Oracle now supports queries with the geographic coordinate system and different data depending on what modern-day cell phone sensors have.

iPhone 10 (2017)

- Barometer
- lidar, Face ID
- camera
- Three‑axis gyro, Accelerometer, Proximity sensor, Ambient light sensor
- Note: there is professional measuring equipment that can also have connection functions. Therefore it's possible to attach them to a node as well.

You can see by good use of old phone's sensors and their unique location on the earth. We made an Oracle that is a near-optimal decentralized way to get the world brightness and barometer data, which a web2 technology can never do because of privacy issues(people not getting paid or no way to validate each other).



Another possible example: people/smart contracts can pay Oracle a very high price to encourage people to upload/verify the 3d model inside some building by integrating iPhone lidar (3dScanner, Polycam). The reward will be released when enough validators upload the 3d model of the area.



