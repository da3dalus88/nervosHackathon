Screenshot of the console output immediately after I have successfully issued a smart contract call:

<img width="661" alt="console output contract call" src="https://user-images.githubusercontent.com/6180310/128673872-6b9d42c1-ee91-41bd-83ea-0e8708e4810d.png">

The transaction hash from the console output (in text format): 0xb50ef5e5c1bb0eeb65610190d5cb81d5cd13408e0aaa01c48a1328e99668f610

The contract address that you called (in text format): 0x538943E1FF319341C210EEb5bFb3d69EDB2a771b

The ABI for contract you made a call on (in text format): 

[
    {
      "inputs": [],
      "stateMutability": "payable",
      "type": "constructor"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "x",
          "type": "uint256"
        }
      ],
      "name": "set",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "get",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    }
]
