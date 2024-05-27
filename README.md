# Kasheba
   <img src="TODO" alt="TODO"/>

### Inspiration

The global real estate market is a dynamic and ever-changing landscape, offering immense opportunities for speculation and investment. However, accessing accurate and timely data for informed decision-making is often challenging. We envisioned Kasheba Analytics as a decentralized platform that democratizes access to real estate market data, enabling users to speculate on city index price movements globally. Inspired by the potential of blockchain technology to provide transparency and security, we set out to create a solution that bridges the gap between real-world data and decentralized finance (DeFi).

### What it does

Kasheba Analytics is a decentralized marketplace where users can speculate on real estate market price movements by trading city indexes. The platform aggregates various real estate metrics such as median property growth, rental yields, and demographic indicators, and uses this data to create an index price for each city. Users can trade these indexes, predicting future price movements and potentially profiting from their trades. The data is made accessible on the blockchain, ensuring transparency, security, and on-demand availability.

<p align="center" width="100%">
  <img src="https://imgur.com/iINMzWH.png" alt="site"/>
</p>


<p align="center" width="100%">
  <img src="https://imgur.com/wxoIhL4.png" alt="site"/>
</p>

### How we built it

We built Kasheba Analytics using a combination of blockchain technology, Chainlink oracles, and a robust backend system. Here's a high-level overview of the process:

1. **Data Collection**: We identified key real estate metrics necessary for creating city indexes, including property prices, rental information, and demographic indicators. For the hackathon, we hardcoded random data to simulate real-world inputs.
2. **Analytics API**: Developed an API to collate and process the collected data, providing a standardized format for the analytics engine.
3. **Chainlink Oracles**: Integrated Chainlink oracles to fetch data from our off-chain analytics API and bring it onto the blockchain securely.
4. **Smart Contracts**: Created smart contracts to handle data requests and store city index prices on the blockchain.
5. **Frontend**: Designed a user-friendly interface for users to view and trade city indexes.

#### Sequence Diagram

<p align="center" width="100%">
  <img src="https://imgur.com/OERlswm.png" alt="site"/>
</p>

### Challenges we ran into

- **Data Integration**: Aggregating real estate data from multiple sources and ensuring its accuracy was a complex task.
- **Blockchain Integration**: Integrating Chainlink oracles with our smart contracts required careful planning and execution to ensure seamless data flow.
- **Security**: Ensuring the security and integrity of the data on the blockchain was paramount, requiring thorough testing and validation.

### Accomplishments that we're proud of

- Successfully creating a working prototype that demonstrates the concept of a decentralized real estate market speculation platform.
- Integrating Chainlink oracles to securely fetch and display real estate data on the blockchain.
- Developing a user-friendly interface that allows users to easily interact with the platform and trade city indexes.
- Building a robust analytics engine capable of processing and analyzing real estate data in real-time.

### What we learned

- The importance of accurate and timely data in creating reliable financial products.
- How to leverage blockchain technology and Chainlink oracles to bring off-chain data onto the blockchain securely.
- The complexities involved in integrating various data sources and ensuring their accuracy and reliability.
- The potential of decentralized finance to create new and innovative financial products and markets.

### What's next for Kasheba

- **Real Data Integration**: Integrate real-world data sources to replace the hardcoded random data with actual real estate metrics.
- **Expand City Coverage**: Increase the number of cities covered by the platform, offering users a wider range of investment opportunities.
- **Advanced Analytics**: Enhance the analytics engine with more sophisticated algorithms to provide deeper insights and more accurate predictions.
- **User Engagement**: Develop features to improve user engagement, such as educational content, community forums, and investment tools.
- **Partnerships**: Establish partnerships with real estate data providers, financial institutions, and blockchain projects to expand the platform's capabilities and reach.
- **Virtual Real Estate**: Explore integration with virtual reality real estate markets, enabling users to trade indexes for virtual worlds like Decentraland and SAND.
- **Global Expansion**: Work towards extending Kasheba to include country and world indexes, providing a comprehensive platform for global real estate speculation.