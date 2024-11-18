
Documentation of Enaleia Hub


# Introduction

[Enaleia](https://enaleia.com/) is a well-established social enterprise that collaborates with thousands of fishermen to reduce marine pollution by training them to collect plastic waste while fishing and adopt sustainable practices. To date, they have collected over 1,200 tons of marine plastic, helping clean the Mediterranean and support a circular economy by turning waste into resources.  The **Enaleia Hub** aims to showcase Enaleia’s environmental impact using blockchain and the open-source approach. By integrating key features such as reporting, attestation, role management, traceability, and product passports, the Hub will offer a streamlined internal system and a public-facing interface.

After a thorough analysis of Enaleia’s current operations (Q3, 2024), we have identified several challenges that limits its potential impact:

1. **Limited data on private blockchain:** The existing blockchain implementation operated by a third party can only handle minimal data submissions, preventing Enaleia from fully showcasing its supply chain and environmental achievements.
2. **Manual reporting & lack of traceability:** Enaleia currently relies on manual data entry and basic visualization tools for reporting. This results in high-level summaries lacking full data points necessary for traceability, reducing the abilities and effectiveness of its reporting. In its current form the process cannot achieve a much-anticipated demonstration of sustainability and accountability.

Based on our deep understanding of Ethereum blockchain, open-source platforms, and design principles, we see clear opportunities to address these challenges and create significant value.

Here are a few:

1. **Enhanced data visualization & public engagement:** We will use Ethereum blockchain to make Enaleia’s environmental efforts transparent and easily understandable, empowering public engagement in marine conservation.
2. **Help in establishing new norms regarding environmental regulations:** By empowering Enaleia, we can pave the way by showcasing alternative immutable data collection methods for its submissions to the **United Nations**, contributing to informed decision-making with transparent data.
3. **Robust traceability using blockchain:** We will develop a system where every step of Enaleia’s supply chain and processing is fully traceable with the use of Ethereum techonology.
4. **Streamlined operations for efficiency:** With an intuitive mobile interface to track key supply chain stages—ocean waste collection, sorting, pelletization and manufacturing—Enaleia will showcase blockchain-based real-time traceability while optimizing operations and streamlining logistics management.
5. **Partner motivation & ecosystem engagement:** In the future phase, we can implement features designed to incentivize partners, ensuring they remain active contributors to the growing ecosystem.
6. **Enriched consumer experience:** By introducing the concept of blockchain immutability into consumer purchase decisions, we will demonstrate a strong example of modern innovation from the traditional untraceable product supply chain by enriching community participation and experience.

# Design principles

Given that Enaleia is focused on marine science rather than software development, the tech stack has been selected with long-term sustainability and ease of use in mind. The Enaleia Hub adheres to core decentralized principles, ensuring authenticity and transparency. Key design principles include:

- **No centralized control of user private keys**: All ecosystem participants will manage their own keys, ensuring true decentralization and security.
- **Decentralized data submission**: Every ecosystem actor will submit data with their own digital signature, ensuring immutability and transparency without central intervention.
- **System flexibility**: Operating across multiple Mediterranean countries come with diverse operational workflows, the Enaleia Hub is built to accommodate these variations, ensuring flexibility and scalability.


# Tech stacks

- **Directus**: Backend-as-a-Service (BaaS) for flexible and scalable backend management.
- **Ethereum Attestation Service**: For cryptographic proof of data validity and integrity.
- **Generic Account Abstraction Wallet (Custom library)**: Simplifying blockchain interactions for end users while maintaining security.
- **Expo**: A React Native framework for cross-platform mobile app development.
- **Nativewind**: A Tailwind CSS framework for native app UI design.

# High level architecture

The high-level architecture showcases the interaction between blockchain components, user interfaces, and backend services, ensuring a decentralized, transparent, and scalable solution.

<img width="3242" alt="Enaleia-Hub-techmap" src="https://github.com/user-attachments/assets/a8cbfcfa-d03f-4991-a6c5-9b69198d5156">


# Path for the next billion

With a goal of contributing to the broader effort of onboarding the next billion users to Ethereum, Enaleia Hub is designed to support the inclusion of users like fishermen, who play a crucial role in ocean plastic collection. We’ve developed a simple identification system that lays the groundwork for future phases, where these users can be rewarded with reputation scores on-chain.

Unlike traditional product passports, the **Ethereum Attestation Service (EAS)** allows us to verify data authenticity and traceability across the supply chain. This creates the possibility for consumers to claim these recycled products on-chain as proof of purchase. By leveraging blockchain technology, we aim to enhance transparency and accountability in the process, while also providing an accessible and straightforward system for all users.
