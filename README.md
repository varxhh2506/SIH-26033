# Smart India Hackathon Workshop
# Date:25/11/2026
## Reference Number:26019047
## Name: VARSHIKA T

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description
Expected Solution: Create a digital marketplace that:
• Connects farmers/FPOs directly with consumers and bulk buyers.
• Provides logistics support.
• Uses AI for demand forecasting and route optimization.

Benefits:
• Better prices for farmers.
• Lower prices for consumers.
• Reduced supply chain inefficiencies.

## Proposed Solution
KrishiSetu (proposed platform name) is an integrated B2B and B2C digital marketplace that connects smallholder farmers and Farmer Producer Organizations (FPOs) directly with household consumers, local retailers, and institutional bulk buyers (hotels, supermarkets, and food processors). 

The platform operates through three interconnected modules:
• Farmer & FPO Mobile App: A vernacular, voice-assisted app where farmers list available harvests, expected yield dates, quality grades, and reserve prices.
• Buyer Web & Mobile Portal: A transparent storefront allowing consumers to buy fresh produce and bulk buyers to place scheduled wholesale orders directly from farm clusters.
• AI & Logistics Orchestration Engine: An automated backend that forecasts regional demand, suggests fair market prices, pools nearby farm harvests into shared transport vehicles, and optimizes multi-stop delivery routes.

How It Addresses the Problem
• Eliminates Multi-Tier Intermediaries: Replaces traditional commission agents and layered wholesale middlemen with direct digital price discovery and peer-to-peer transactions, ensuring farmers retain maximum value while consumers pay lower retail rates.
• Solves First-Mile Logistics Bottlenecks: Small farmers often rely on middlemen because they lack transport. Our platform aggregates small yields across neighboring farms into full truckloads via partnered third-party logistics (3PL) vehicles.
• Prevents Wastage & Price Crashes via AI: AI demand forecasting alerts farmers to upcoming regional shortages or surpluses before harvest, while route optimization minimizes transit time for perishable crops.

Innovation and Uniqueness of the Solution
• Micro-Harvest Pooling at the FPO Level: Enables multiple small-acreage farmers in the same village cluster to digitally combine their produce to fulfill large institutional orders they could not meet individually.
• Dynamic Fair-Price Recommendation Engine: Benchmarks real-time government mandi prices (e-NAM / Agmarknet) against live platform demand and logistics costs to recommend a transparent, win-win price band.
• Low-Bandwidth & Voice-First Rural UX: Incorporates regional speech-to-text input and SMS/IVR order alerts so farmers with limited digital literacy or intermittent internet connectivity can participate effortlessly.
• Smart Escrow with Instant UPI Payouts: Protects both parties by holding buyer funds in escrow during transit and triggering instant direct-to-bank UPI settlement upon QR-code quality verification at delivery.

## Technical Approach
1. Technologies to be used: Flutter (Cross-platform Farmer and Driver mobile apps), React.js and Tailwind CSS (Buyer web portal and Admin dashboard), Node.js with Express and Python FastAPI (Backend APIs), PostgreSQL and Redis (Database and live price caching), Python with Prophet and LSTM (AI demand forecasting), Google OR-Tools (Vehicle routing optimization), and UPI, Google Maps, e-NAM, and Bhashini APIs (Payments, geolocation, mandi prices, and regional voice support).
2. Methodology and process for implementation:
Step 1: Farmers and FPOs complete KYC registration and list available harvest quantities, grades, and dates.
Step 2: The AI engine forecasts regional demand and recommends fair market prices based on live e-NAM benchmarks.
Step 3: Consumers and bulk buyers place orders, and the system pools nearby farm pickups to maximize vehicle capacity.
Step 4: Google OR-Tools generates the shortest multi-stop pickup and delivery route for logistics partners.
Step 5: Delivery is verified via QR/OTP scan at the buyer hub, triggering instant UPI escrow settlement to the farmer.

Flowchart:
<img width="551" height="757" alt="image" src="https://github.com/user-attachments/assets/7f9bd724-9322-4993-9d2d-fdb95c60a0d2" />


## Feasibility and Viability
1. Analysis of the Feasibility of the Idea: Built on scalable cloud-native microservices, open-source routing solvers (Google OR-Tools), and lightweight cross-platform frameworks running on entry-level Android devices. It leverages existing registered Farmer Producer Organizations (FPOs) and local transport providers, avoiding the need for heavy upfront physical infrastructure. The sustainable 2% to 4% facilitation fee charged to bulk buyers and logistics partners keeps farmer onboarding completely free.
2. Potential Challenges and Risks: Rural digital literacy barriers, potential disputes over produce quality, freshness, or weight upon delivery, and cold-chain/internet connectivity gaps in remote villages.
3. Strategies for Overcoming These Challenges: Deploying vernacular voice-assisted interfaces and appointing FPO youth coordinators (Krishi Mitras) to assist farmers; requiring geo-tagged harvest photos with standardized grade checklists before pickup, backed by escrow protection; and setting up village-level collection micro-hubs along main roadways.
## Impact and Benefits
1. Potential Impact on the Target Audience
• Farmers & FPOs: Gain direct market access, transparent pricing, and faster payment cycles (same-day vs. weeks of mandi delays).
• Consumers & Bulk Buyers: Access fresher, farm-traceable produce at predictable, lower-than-retail prices.
• Logistics Operators: Higher fleet utilization and reduced empty return trips through AI-pooled shipments.

2. Benefits of the Solution
• Economic: Increases farmer net income by 20%–35% by capturing middleman margins, while reducing end-consumer retail prices by 10%–20%.
• Social: Empowers smallholder farmers with financial independence, reduces rural distress, and strengthens cooperative FPO ecosystems.
• Environmental: Cuts food wastage by 25%–30% through demand-aligned harvesting and lowers carbon emissions via optimized delivery routes.

## Research and References
1. e-NAM (National Agriculture Market): Government of India pan-India electronic trading portal benchmarks — https://www.enam.gov.in
2. NABARD FPO Guidelines: Operational framework for Farmer Producer Organizations in India — https://www.nabard.org
3. Agmarknet (Directorate of Marketing & Inspection): Daily agricultural commodity pricing and arrival data — https://agmarknet.gov.in
4. Google OR-Tools (Vehicle Routing): Open-source optimization library for multi-stop logistics routing — https://developers.google.com/optimization/routing
5. Bhashini (National Language Translation Mission): AI-led vernacular speech and text APIs for rural inclusion — https://bhashini.gov.in
