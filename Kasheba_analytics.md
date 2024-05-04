## Kasheba Analytics
> Kasheba is a decentralized marketplace for people to speculate on real estate market price movement globally, through trading city indexes. To make this a reality we need to build an analytics engine, backed by real world data regarding real estate through out the globe.

## Information
> The information or data which we need to create a city index trading platform, Kasheba. Please note, for the scope of this hackathon, we will limit our cities to 2 at most. Examples of metropolitan cities are New York, Paris etc
-	Property prices in these cities such as
-	Median Growth
-	Median Value
-	Rental information such as
-	Median Rent
-	Rental Yields
-	Demographics indicators
-	Age of the occupants
-	Householders such as Couple with kids, Childless couples, Single and others
-	Occupancy type such as Owned, purchased, renters
-	Amenities such as Schools, Hospitals, Shopping centres

### All the above factors will affect the index price of these cities and will feed into a speculative future growth of the city. This price action will be tracked over a specific period of time.

## Some of the possible source we can refer to access this information could be
-	Australia: https://onthehouse.com.au
-	France:⦁	 https://www.mordorintelligence.com/industry-reports/residential-real-estate-market-in-france

## Requirements
-	We need to expose this information on the blockchain
-	We need this information to be accessed on-demand
-	We need the response to have price action reflected over a period of time
Scope

## Following is the scope of the analytics functionality for the sake of Chain-link hackathon
-	We will restrict the data points for atmost 2 cities
-	We will hardcode the data with random price swings.
-	We have to use chainlink oracle data feed architecture to expose this index price feeds

Implementation
<p align="center" width="100%">
  <img src="https://github.com/kasheba/kasheba-platform/assets/58889001/33cdf227-6fab-44dc-aff0-1fa3a90592f7" alt="site"/>
</p>
 


## The above sequence diagram represent a possible sequence of interaction between following different components
-	Analytics API
-	Off Chain Component, created by us
-	A microservice which will be responsible for collating the city real estate metrics as we discussed above
-	We can hardcode a random payload generator instead of integrating with real world API
-	Analytics Contract
-	On Chain Contract, created by us
-	This contract is an on-chain Chainlink Function contract, responsible for fetching the information from Analytics API off-chain.

-	Reference⦁	 ⦁	Connect the World’s APIs to Web3 With Chainlink Functions
-	City Index Contract
-	On Chain contract managed by us
-	This contract will be an on-chain contract, which is responsible for making a call to Analytics Contract to fetch city index price feeds.

-	Using the price feed the city index token price will be changed on the platform
Analytics API response payload

## Analytics API response payload will be in JSON and should represent the price for the city index based. Following are the possible fields
-	priceUp
-	priceDown
-	city
-	period

## Future Considerations
-	Exposing City Index Price Feed which can be used by anyone using Chainlink
-	Kasheba platform can be extended to integrate with virtual reality real estate markets as well using blockchains such as Decentraland, SAND etc, thereby enabling people to trade city indexes for virtual worlds.
-	With the help of the Government and Real estate mafia, the platform can also be extended to trade real world assets related to the real estate market globally.
-	The analytics data feed can also be exposed for country or world as indexes.
