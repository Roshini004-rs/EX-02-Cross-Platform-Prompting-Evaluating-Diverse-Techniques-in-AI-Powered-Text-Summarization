# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

## Algorithm


## ChatGPT:

**Zero-Shot Output**: 

Blockchain is a distributed ledger system that securely records transactions across multiple nodes. It relies on cryptographic hashing and consensus protocols to ensure data accuracy and security. Its applications span cryptocurrencies, supply chain management, and healthcare systems.

**Few-Shot Output**: 

Blockchain operates as a decentralized network where data is stored in interconnected blocks secured by hashes. It guarantees transparency, immutability, and trust. Validation is achieved through mechanisms like Proof of Work and Proof of Stake, with use cases in finance, identity verification, and smart contracts.

**Chain-of-Thought Output**: 

Step 1: Blockchain functions as a decentralized ledger.

Step 2: Information is organized into blocks connected through hashes.

Step 3: Transactions are verified using consensus algorithms.

Step 4: It is applied in areas such as cryptocurrency and logistics.

**Role-Based Output**: 

From an academic viewpoint, blockchain is a distributed ledger that maintains secure and unchangeable transaction records. By combining cryptography and consensus methods, it removes the need for intermediaries and powers technologies like cryptocurrencies and smart contracts.

## Copilot:

**Zero-Shot Output**: 

Blockchain is a decentralized digital ledger that securely stores transaction data in connected blocks using cryptographic methods.

**Few-Shot Output**: 

Blockchain organizes data into linked blocks secured by hashes, providing transparency and reliability. Consensus mechanisms are used to validate transactions, with applications in cryptocurrencies and beyond.

**Chain-of-Thought Output**: 

Step 1: Blockchain is a distributed system.

Step 2: Transactions are stored within blocks.

Step 3: Hashing ensures data integrity.

Step 4: Consensus mechanisms confirm transactions.

**Role-Based Output**

From an instructional standpoint, blockchain is a distributed framework that uses cryptography and consensus algorithms to maintain secure, transparent, and reliable records.

## Gemini:

**Zero-Shot Output**:

Blockchain is a decentralized, peer-to-peer ledger that records transactions in a sequence of connected blocks. Security and integrity are ensured through cryptographic hashing and consensus processes.

**Few-Shot Output**:

Blockchain is composed of blocks that store transaction data along with hashes linking them to previous blocks. This structure ensures decentralization, transparency, and strong security, with applications extending beyond digital currencies.

**Chain-of-Thought Output**

Step 1: Describe blockchain as a distributed ledger system.

Step 2: Explain the structure of blocks and hashing.

Step 3: Outline how consensus mechanisms function.

Step 4: Highlight key real-world applications.

**Role-Based Output**:

From a technical systems perspective, blockchain represents a decentralized model that replaces centralized trust with cryptographic verification and consensus-driven validation.


##  Claude:

**Zero-Shot Output**:

Blockchain is a decentralized ledger that logs transactions in blocks connected by cryptographic hashes, ensuring both transparency and security.

**Few-Shot Output**:

Blockchain records transactions in linked blocks secured through hashing techniques. Consensus protocols verify the data, enabling applications such as cryptocurrencies and smart contracts.

**Chain-of-Thought Output**

Step 1: Define blockchain as a distributed ledger.

Step 2: Describe how blocks are structured and linked.

Step 3: Introduce the concept of consensus mechanisms.

Step 4: Provide examples of practical uses.


**Role-Based Output**:

In an academic context, blockchain is a decentralized ledger system that guarantees trust and immutability through cryptographic methods and distributed consensus.




### Performance Evaluation Table:

| Platform    | Accuracy | Coherence | Simplicity | Speed   | User Experience | Key Observation                                         |
| ----------- | -------- | --------- | ---------- | ------- | --------------- | ------------------------------------------------------- |
| **ChatGPT** | 9.0      | 9.0       | **9.5**    | **9.5** | 9.0             | Best balance of clarity, simplicity, and fast responses |
| **Gemini**  | 9.0      | 8.5       | 8.0        | 8.5     | 8.0             | Strong structured output but slightly less accessible   |
| **Claude**  | **9.5**  | **9.5**   | 8.5        | 8.0     | 9.0             | Most accurate and coherent, more academic in tone       |
| **Copilot** | 8.5      | 8.5       | 9.0        | 8.5     | 8.0             | Very simple and beginner-friendly but less detailed     |


### Summary Insight:

* **Best Accuracy & Coherence:** Claude
* **Best Simplicity & Speed:** ChatGPT
* **Best Beginner-Friendly Output:** Copilot
* **Best Structured Reasoning Style:** Gemini
* **Best Overall Balanced Performance:** ChatGPT & Claude

## Conclusion:

Across all platforms, prompting technique significantly influences clarity and structure, but the model choice determines depth and refinement. Claude performs best in accuracy and coherence, while ChatGPT provides the most balanced combination of simplicity, speed, and usability for students. Gemini is strong in structured reasoning, and Copilot excels in simplicity but lacks depth.

## Result:

The experiment clearly shows that prompting technique and model choice together significantly affect summary quality, and role-based prompting consistently delivers the most effective results across platforms for educational content generation.
