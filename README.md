# Supply Chain
This is a simple supply chain management project that I edited from the ['Ethereum Blockchain Developer With Solidity'](https://www.udemy.com/course/blockchain-developer) on Udemy.com.

This is my third project and helped me expand on my React app development skills. I learnt a lot about mapping through arrays to render them in a table in JSX. Most importantly I learnt a lot of react skills that I would like to master. React hooks as well as file separation and organization will certainly help me take my skills to the next level. I experimented with separating components into separate files but ultimately opted to publish the project as is, to allow me to learn these techniques in a broader sense. I will be back soon to update this project with new skills!

In solidity I was able to further understand the usefulness of nesting mapping and structs. Creating child and parent contracts and the implications of gas costs on this strategy.

# Skills Used:
* Blockchain:
  Smart contract development -Solidity
  -Event triggers
  -low-level functions like address.call()
  -Workflow with Truffle
  Smart contract deployment to Ropsten test network through Infura.io
  Smart contract testing with Truffle
* Front-end:
  Array mapping
  Alerts
  Asynchronous functions
  Smart contract interaction
  Functions written to handle a variety of user-inputs


# Technologies Used:
* Solidity
* Ropsten Test Network
* OpenZeppelin
* MetaMask
* Truffle
* Web3
* React
* CSS3
* HTML5
* Infura
* Git
* GitHub
* JavaScript
* Bulma

# Approach:
I started with the Supply Chain project which I did as part of the ['Ethereum Blockchain Developer With Solidity'](https://www.udemy.com/course/blockchain-developer). The project was designed to track products through the supply chain from listing, to sale and finally delivery. It was designed so that the ItemManager contract would create a child contract for each individual item. Thinking about the possible real-world uses for such a contract, online retail came to mind. In this case there are often many individual items for any given product and it would be very impractical to create a new contract for each item. Therefore, I changed the 'Item' contract to a 'ProductSale' which could track each type of item. I displayed all the products create on the main web app and added buttons for users to buy the items through MetaMask. I hid the section where products are created as this does not concern the user (Although anyone can still access it for this example). 
# Successes and short-comings:
* Success:
  * Mapping through arrays to render them in JSX.
  * The time to produce this project was much faster than my previous two projects.

* Short-comings:
  * Component organization
  * This quantity does not update after sale is made (This works when calling UpdateQuantity in ItemManager.sol directly but not when calling it through the UpdateQuantity function in ProductSale.sol). 

# Code Highlights:

# What I still want to add:
* Feature to warn users when duplicate names are added.
* Hide products with supply of 0 from the page.
* The ability to edit product name, cost, and index.
