## EX-02: Cross-Platform Prompting - Evaluating Diverse Techniques in AI-Powered Text Summarization
## AIM

To evaluate and compare the effectiveness of different prompting techniques (Zero-shot, Few-shot, Chain-of-Thought, and Role-based) across multiple AI platforms (ChatGPT, Gemini, Grok, and Claude) for text summarization.

## Scenario

You are part of a content curation team for an educational platform that provides concise summaries of research papers to undergraduate students. Your task is to summarize a 500-word article on "The Basics of Blockchain Technology" using different AI platforms and prompting techniques.

The summaries are evaluated based on:

Accuracy
Coherence
Simplicity
Speed
User Experience
## Algorithm
## 1. Input Preparation

Select a 500-word article on "The Basics of Blockchain Technology" containing its definition, working, components, advantages, disadvantages, and applications.

## 2. Define Prompting Techniques
Zero-shot Prompting: Summarize the article in simple language.
Few-shot Prompting: Provide one example summary before requesting the blockchain summary.
Chain-of-Thought Prompting: Identify key points step by step before generating the summary.
Role-based Prompting: Ask the AI to act as a professor teaching first-year students.
## 3. Run Experiments

Use the same article and prompts on:

ChatGPT
Gemini
Grok
Claude

Save the generated summaries.

## 4. Evaluate

Evaluate every output using:

Accuracy
Coherence
Simplicity
Speed
User Experience
## 5. Compare Results

Assign ratings and compare the outputs to determine the best prompting technique and platform.

## OUTPUT
### Platform 1: ChatGPT
#### Zero-shot Output

Blockchain is a decentralized digital ledger where transactions are stored in linked blocks secured by cryptographic hashes. It ensures transparency, security, and immutability without relying on a central authority. Blockchain is widely used in cryptocurrencies, healthcare, supply chains, and finance, though it faces challenges such as scalability and energy consumption.

#### Few-shot Output

Blockchain is a distributed ledger that stores transactions in linked blocks secured with hashes. It eliminates intermediaries, improves transparency, and supports applications such as Bitcoin, Ethereum, digital identity, and supply chain management. While highly secure, it still faces issues like scalability and regulation.

#### Chain-of-Thought Output

Blockchain is a decentralized ledger that stores information in linked blocks verified through consensus mechanisms. It improves security, transparency, and trust while supporting applications in cryptocurrency, healthcare, and logistics. However, challenges such as energy usage and scalability remain.

#### Role-based Output

Blockchain works like a shared notebook maintained by thousands of computers. Every page (block) is linked securely to the previous one, making changes easy to detect. It enables secure transactions without banks and powers technologies such as Bitcoin and smart contracts while facing challenges in energy use and scalability.

### Platform 2: Gemini
#### Zero-shot Output

Blockchain is a decentralized digital ledger that stores transactions securely in connected blocks using cryptographic hashing. It improves transparency, trust, and security while supporting applications in cryptocurrencies, healthcare, and supply chains.

#### Few-shot Output

Blockchain links transaction records into secure blocks maintained by a distributed network. It provides transparency, decentralization, and security, making it useful in digital currencies, smart contracts, and business applications.

#### Chain-of-Thought Output

## Step 1: Define blockchain as a decentralized ledger.

## Step 2: Explain linked blocks and cryptographic hashes.

## Step 3: Describe consensus mechanisms.

## Step 4: Mention applications and challenges.

## Summary: Blockchain is a secure decentralized ledger that stores transactions in linked blocks. It provides transparency, trust, and security but faces challenges like scalability and energy consumption.

#### Role-based Output

Blockchain is a secure digital record book shared across many computers instead of one central server. It uses cryptography to protect information and is widely used in finance, healthcare, and supply chain management.

### Platform 3: Grok
#### Zero-shot Output

Blockchain is a shared digital ledger that records transactions in connected blocks secured by cryptography. Since many computers maintain the ledger, it is difficult to alter data, making blockchain reliable for digital payments and record management.

#### Few-shot Output

Blockchain stores transaction records in linked blocks verified by network participants instead of a central authority. It offers transparency, security, and trust while supporting cryptocurrencies, digital identity, and supply chain tracking.

#### Chain-of-Thought Output

Step 1: Blockchain is a decentralized ledger.

Step 2: Data is stored in linked blocks.

Step 3: Consensus verifies transactions.

Step 4: Applications include finance and healthcare.

## Summary: Blockchain securely stores data across many computers, reducing fraud and improving transparency, though scalability remains a challenge.

Role-based Output

Imagine a notebook shared by thousands of people where nobody can secretly erase or change a page. That is how blockchain works. It securely stores records, removes middlemen, and is widely used in banking, logistics, and digital currencies.

### Platform 4: Claude
#### Zero-shot Output

Blockchain is a digital ledger made up of linked blocks connected through cryptographic hashes. It is decentralized, making stored data highly secure and difficult to modify. Applications include Bitcoin, Ethereum, banking, healthcare, and supply chain management, though scalability and energy use remain challenges.

#### Few-shot Output

Blockchain is a shared digital ledger where transactions are grouped into linked blocks secured by hashes. It provides transparency, immutability, and decentralization while enabling applications such as Bitcoin, Ethereum, smart contracts, banking, and healthcare.

#### Chain-of-Thought Output

Main Topic: Blockchain Technology

Key Concepts: Digital ledger, blocks, cryptographic hashing, decentralization, consensus, applications, benefits, and challenges.

## Summary: Blockchain securely stores information in linked blocks verified by distributed computers. It supports cryptocurrencies and smart contracts while improving transparency and trust. However, scalability, regulation, and energy consumption remain important challenges.

## Role-based Output

Think of blockchain as a notebook shared by thousands of computers. Every page is permanently linked to the previous one using cryptography, making it extremely difficult to alter. It removes the need for a central authority and supports Bitcoin, Ethereum, banking, and supply chain management while still facing challenges in energy consumption and scalability.

## Performance Evaluation Table
<img width="1691" height="930" alt="ChatGPT Image Jul 25, 2026, 02_23_51 PM" src="https://github.com/user-attachments/assets/b0e695c3-6665-457c-8c5a-7277f6a33650" />


## Summary Insight
Best Accuracy: Claude
Best Coherence: Gemini
Best Simplicity: ChatGPT & Grok
Fastest Response: ChatGPT & Grok
Best Overall Performance: ChatGPT & Claude

## Conclusion

The experiment demonstrates that both the AI platform and the prompting technique significantly influence summary quality. Role-based prompting consistently produced the clearest summaries for undergraduate students. Claude delivered the highest accuracy, Gemini excelled in structured reasoning, Grok provided the simplest explanations, and ChatGPT offered the best overall balance of clarity, speed, and usability.

## Result

Thus, the Cross-Platform Prompting Evaluation for AI-powered text summarization was successfully carried out. The results show that role-based prompting produced the most effective summaries, while ChatGPT and Claude provided the best overall performance.
