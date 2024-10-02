# EcoVeritas

**ConsumeWise** is a Gen AI-powered tool designed to enhance transparency and trust in consumer goods, particularly in the domains of food and personal care products. The platform aims to provide verifiable and personalized information about the impact of these goods on health, the environment, and society, promoting conscious consumption and sustainable product adoption.

## Motivation

- Encourage consumers to make better choices by providing clear, trustworthy, and personalized data about product health and sustainability.
- Promote the production and mainstream adoption of healthier, environmentally friendly products by highlighting their benefits.
- Overcome barriers such as price sensitivity, convenience, and lack of awareness by nudging consumers with actionable insights at the right time in their shopping journey.

## Key Features

1. **Accurate Data Collection**: 
   - Sources information from publicly available databases, producers, and verifiable third-party sources.
   - Ensures data accuracy through robust validation and verification mechanisms.

2. **Credibility and Decentralization**:
   - Establishes a credible, bias-free system for defining what is healthy and sustainable.
   - Utilizes decentralized frameworks to avoid the influence of vested interests.

3. **User-Friendly and Personalized Interface**:
   - Delivers actionable insights to users without overwhelming them.
   - Integrates seamlessly into shopping experiences (e.g., e-commerce) to provide product information at critical decision points.
   - Personalization tailored to India’s diverse population, ensuring accessibility to a wide audience.

## Outcome

- **Informed Decision Making**: Consumers will have easy access to personalized product information that highlights which items are healthy and environmentally sustainable.
- **Behavioural Change**: By raising awareness, ConsumeWise nudges consumers toward making better choices, influencing the demand for healthier and more sustainable products.
- **Market Transformation**: Over time, the demand for conscious products will prompt producers to adapt to sustainable practices.

---

## Tech Stack

- **Frontend**: React.js, Next.js, TailwindCSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB, PostgreSQL
- **AI Model**: GPT-based models for personalized recommendations and content generation
- **API Integration**: OpenAI API, Public databases (e.g., food safety, environmental standards)
- **Authentication**: Supabase for user management and authentication
- **Data Scraping**: Python for web scraping (to gather product data from public sources and e-commerce platforms)
- **Verification Mechanism**: Blockchain-based verification system (e.g., Ethereum, Hyperledger) to ensure data authenticity and decentralization

---

## Project Architecture

### 1. **Data Ingestion Layer**:
   - **Public Data Sources**: Aggregates data from publicly available sources such as government databases, research institutions, and NGOs.
   - **Producer Data**: Allows producers to submit verified data about their products (e.g., ingredients, environmental impact).

### 2. **AI-Powered Analysis Engine**:
   - **Natural Language Processing (NLP)**: Parses product information to classify and label items based on health and sustainability criteria.
   - **Personalization Algorithms**: Uses user preferences, past shopping behavior, and demographic information to tailor recommendations.
   - **Impact Scoring**: Generates scores for products based on their health, environmental, and social impact.

### 3. **Blockchain Verification Layer**:
   - Ensures that the data provided by producers and public databases is tamper-proof and decentralized.
   - Allows for transparent auditing of product data by third-party verifiers.

### 4. **Frontend**:
   - **User Dashboard**: Displays personalized insights about products.
   - **E-Commerce Integration**: Provides product scores and suggestions directly within the shopping journey, using browser extensions or API integrations with e-commerce platforms.
   - **Accessibility**: Designed for diverse user bases, including multi-language support and simplified UIs for regions with lower digital literacy.

### 5. **Backend & Database**:
   - **API Gateway**: Handles communication between the frontend and AI/Blockchain engines.
   - **MongoDB/PostgreSQL**: Stores user preferences, product information, and impact scores.
   - **Node.js Backend**: Serves API requests and handles business logic for data aggregation and user insights.

---

## Installation & Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/ConsumeWise.git
