# Blockchain-Major-Project

Blockchain technology is revolutionary. It will make life simpler and safer, changing the way personal information is stored and how transactions for good and services are made. Blockchain technology creates a permanent and immutable record of every transaction. This impenetrable digital ledger makes fraud, hacking, data theft, and information loss impossible. The technology will affect every industry in the world, including manufacturing, retail, transportation, healthcare, and real estate Companies as Google, IBM, Microsoft, American Express, Walmart, Nestle, Chase, Intel, Hitachi, and Dole are all working to become early adopters of blockchain. Nearly $400 trillion across various industries is set to be transformed by blockchain.

Top key functionality of my project:

Mining a new Block:

      The mining of the new block is done by finding the answer to the proof of work. 

      To make mining hard the proof of work must be hard enough to get exploited.

      Mining a new Block means successfully adding a new block to the Blockchain.

      We keep iterating the nonce until you get the hash below the target.

      Once nonce gets below the target the block gets accepted.
      
![image](https://user-images.githubusercontent.com/60074533/116411627-83af7c80-a853-11eb-8d7b-5c8748226cbf.png)


Displaying a Block:

      The data will be stored and displayed in JSON format which is very easy to implement and easy to read.

      Each Block contains multiple transaction/data.

      Each and every minute multiple block are added and to differentiate one from other we will use fingerprinting.

      The fingerprinting is done by using hash and to be particular we will use the SHA256 hashing algorithm.

      Every block will contain its own hash and also the hash of the previous function so that it cannot get tampered.

      This fingerprinting will be used to chain the blocks together. 

![image](https://user-images.githubusercontent.com/60074533/116411674-8f9b3e80-a853-11eb-921e-72b68abd31d0.png)


Checking the Validity of the Block:

      After mining several blocks the validity of the chain must be checked in order to prevent any kind of tampering with the blockchain.

      If the blockchain shows invalid as a output it means that tampering of blockchain has been done.

      If the blockchain shows valid as a output it means that no tampering of blockchain has been done.

      Then the web app will be made by using Flask and deployed locally.

      Now by HTTP request we call the different GET method and display the output.
      
![image](https://user-images.githubusercontent.com/60074533/116411730-9b870080-a853-11eb-9e46-13c08dfec9b5.png)

