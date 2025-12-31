⚡ **Azure AZ-900 Core Concepts Flashcards**

A complete, interactive study deck built from handwritten notes covering the essential domains for the Microsoft Azure Fundamentals (AZ-900) certification exam.

🚀 **Live Demo & Study Link**

The flashcard application is hosted directly on GitHub Pages for easy access on any device.

👉 [Launch the AZ-900 Flashcard App Here](https://ahmed-moourad.github.io/az-900-flash-cards/) 👈


✨ **Key Features**

Complete Deck: Contains over 30 cards covering all topics from the notes: Identity, Networking, Databases, and Resource Hierarchy.

Interactive Design: Click the card to flip between Question (Front) and Answer (Back).

Shuffle Function: Test your recall by shuffling the deck order with the dedicated 🔀 Shuffle button.

Mobile Friendly: Fully responsive design for studying on the go.

📚 **Study Summary: Core AZ-900 Concepts**

This table summarizes the core services and concepts covered in the flashcard deck.

Domain

Concept

Definition / Key Rule

IDENTITY

Microsoft Entra ID

Cloud Identity. Features: MFA, SSPR, SSO.

IDENTITY

RBAC Assignment

Authorization. Must specify: Who (Principal), What (Role), and Where (Scope).

NETWORKING

Azure Firewall

Managed, Stateful service filtering all traffic; positioned outside the VNet.

NETWORKING

NSG (Network Security Group)

Filters traffic inside the VNet at the NIC/Subnet level.

NETWORKING

ExpressRoute

Private connection to Azure (no public internet); NOT encrypted by default.

NETWORKING

Private Link

Access PaaS services (e.g., Storage, SQL) using Private Endpoints inside your VNet.

DATABASE

Azure Cosmos DB

Global, schemaless NoSQL database offering $99.999\%$ availability.

DATABASE

Synapse Analytics

Distributed data warehouse for OLAP (petabyte-scale data analysis).

HIERARCHY

Management Group

Used for centralized policy and compliance across multiple subscriptions.

HIERARCHY

Resource Group Rule

Can hold resources from multiple regions, but is linked to ONLY one subscription.

🛠️ **Setup Instructions (For Contributors)**

This project is a single-file application, making it easy to run and contribute to.

Prerequisites

A GitHub Account (for hosting via GitHub Pages).

Local Setup

Clone the repository:
```sh
git clone https://github.com/Ahmed-Moourad/az-900-flash-cards.git
cd azure-900-flashcards
```

Open the file: Simply double-click the index.html file in your file explorer. It will open in your default web browser.

Deploying with GitHub Pages

Ensure you have pushed the index.html file to your main branch.

Go to Settings $\rightarrow$ Pages in your repository.

Set the source to the main branch and save.

Your live study link will be available shortly!

_Created from handwritten notes to fully functional study app._
