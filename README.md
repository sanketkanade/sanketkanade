### Hi, I'm Sanket

Software engineer finishing a Master of Artificial Intelligence at Monash University, Melbourne (Nov 2026). I build backend systems and applied ML: payment batch jobs in production at Mindgate Solutions, and most recently the language-model pipeline behind **BetweenWords**, which won the **Monash Final Year Industry Project Expo, first among 125 teams**.

[Portfolio](https://sanketkande.vercel.app) · [LinkedIn](https://linkedin.com/in/sanket-kanade-599sk) · [Email](mailto:sanketkanade2105@gmail.com)

---

#### Featured work

**[BetweenWords](https://github.com/TA-35/TheSignalBridge)** · [live app](https://thesignalbridge.com)<br>
Accessible full-stack web app with a fine-tuned small language model and a verified message-reading pipeline. Expo winner, Semester 2 2026. Top contributor, with 47 merged pull requests.
- Fine-tuned Qwen3.5-4B with LoRA and served it as a 4-bit GGUF model with llama.cpp: entity recall 91% to 98%, meaning preserved 86% to 96% on a locked 180-message test set.
- Rebuilt the reading pipeline on GPT-OSS-120B with quote and entity checks and a self-repair loop: verified answers 68% to 100%, median latency 15 s to 2 s, under $0.001 per message.

`Python` `PyTorch` `LoRA` `llama.cpp` `Flask` `Vue 3` `TypeScript` `AWS`

**[MovieLens recommender](https://github.com/sanketkanade/movielens-recsys)**<br>
Top-10 recommenders on MovieLens-1M: popularity, item-kNN, NumPy ALS and a scikit-learn GBM re-ranker on a temporal split. Reproducible with Docker.

`Python` `NumPy` `scikit-learn` `Docker`

**[BirdTag](https://github.com/sanketkanade/BirdTag)**<br>
Serverless AWS media storage with ML species detection, automated tagging, multi-tag search and real-time notifications, behind fine-grained IAM access control.

`AWS Lambda` `S3` `API Gateway` `DynamoDB` `Cognito` `SNS`

**[Kinship](https://github.com/sanketkanade/UniHack_project)** · built at UniHack<br>
Full-stack community platform: tag extraction, matchmaking and a map of nearby connections.

`Next.js` `FastAPI` `Supabase` `Leaflet`

---

#### Experience

- **Software Engineer, Mindgate Solutions** (Aug 2023 – Nov 2024). Payment batch jobs handling millions of transactions daily: processing time down 25% at 99.99% uptime. Spring Security role-based access control and SAML SSO, cutting login tickets 30%.
- **Winter Vacation Researcher, Monash University** (Jun – Jul 2025). Python ETL pipeline linking historical Tasmanian street directory records, with matching that cut false matches by 30%.

#### Toolbox

**Languages** Java, Python, C++, TypeScript, SQL<br>
**ML** PyTorch, Hugging Face Transformers, LoRA, llama.cpp, spaCy, RAG<br>
**Back end** Spring Boot, Spring Security, Flask, FastAPI, Node.js<br>
**Cloud and DevOps** AWS (Lambda, S3, DynamoDB, EC2, RDS, CloudFront), Azure, Docker, GitHub Actions
