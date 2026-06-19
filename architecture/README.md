# Architecture Documentation

This directory contains the core system architecture diagrams and major workflow diagrams of PantryTales.

The materials provided here are intended for project demonstration purposes only and do not include deployable configurations or complete system implementations.

---

## 1. System Architecture Diagram

![System Architecture](./system-architecture-diagram.png)

This diagram illustrates the overall technical architecture of PantryTales, including:

* React Native mobile application
* ASP.NET Core backend services
* PostgreSQL and pgvector
* AI service integration
* Object storage
* Recommendation and recognition workflows

---

## 2. Core Database ER Diagram

![Database ER Diagram](./core-database-er-diagram.png)

This diagram presents the core data model relationships within the system, covering:

* Users
* Families and family members
* Inventory ingredients
* Recipes
* Likes, saves, and comments
* Recipe-ingredient relationships

The public version only includes the major entities. Complete database schemas and migration files are omitted.

---

## 3. Ingredient Scan Workflow

![Ingredient Scan Workflow](./ingredient-scan-flow.png)

This workflow demonstrates how the system processes ingredient recognition and inventory updates after users upload images or receipts.

The process includes:

* Uploading images
* AI-based ingredient or receipt item recognition
* Structured information extraction
* User confirmation
* Ingredient name normalization
* Inventory update

---

## 4. AI Recommendation Workflow

![AI Recommendation Workflow](./ai-recommendation-workflow.png)

This workflow illustrates the main steps involved in the Smart Recipe recommendation process.

The workflow includes:

* Analyzing user inventory, dietary preferences, and serving requirements
* Generating or retrieving vector representations
* Semantic retrieval of candidate recipes
* Ranking recipes based on user preferences and business rules
* Returning personalized recommendations

---

## 5. Vector Retrieval Workflow

![Vector Search Workflow](./vector-search-workflow.png)

This diagram explains how vector representations and similarity search are used to support recipe recommendations.

The workflow includes:

* Generating recipe embeddings
* Storing vector representations
* Performing similarity search
* Retrieving candidate recipes
* Ranking results using business rules

---

## 6. Deployment Architecture Diagram

![Deployment Architecture](./deployment-architecture.png)

This diagram is provided solely to demonstrate the cloud deployment strategy used in the original project.

The public repository does not include deployment scripts, credentials, environment variables, or database connection configurations.
