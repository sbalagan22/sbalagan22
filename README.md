<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:2563eb&height=200&section=header&text=Sukhman&fontSize=64&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Data%20Engineer%20%7C%20AI%20%2F%20ML%20Builder%20%7C%203x%20Hackathon%20Winner&descAlignY=58&descSize=18" alt="header" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=60A5FA&center=true&vCenter=true&width=650&lines=Data+Engineer+%40+Motorola+Solutions;Building+AI+%2F+ML+products+end+to+end;Models%2C+pipelines%2C+and+deployed+apps;CS+%40+York+University" alt="typing"/>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](YOUR_LINKEDIN_URL)
[![Portfolio](https://img.shields.io/badge/Portfolio-0f172a?style=for-the-badge&logo=vercel&logoColor=white)](YOUR_WEBSITE_URL)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:YOUR_EMAIL)
[![Resume](https://img.shields.io/badge/Resume-16a34a?style=for-the-badge&logo=readthedocs&logoColor=white)](YOUR_RESUME_URL)

</div>

---

## About

I build AI and ML products end to end: train the model, build the data pipeline, ship the app. Data Engineer at **Motorola Solutions**, previously AI Software Engineer at **PTAG**, and a Computer Science (Co-op) student at **York University**. I win a lot of hackathons because I ship working demos, not slide decks.

| | |
|---|---|
| **Now** | Data Engineer @ Motorola Solutions (Sept 2026 to present) |
| **Before** | AI Software Engineer @ PTAG (May to Aug 2026) |
| **Also** | Workshop Developer @ GDG York, freelance full-stack work |
| **School** | BSc Computer Science, Co-op, York University |
| **Based in** | Toronto, Ontario |
| **Ask me about** | Transformers from scratch, RAG systems, prediction models, AWS event-driven architecture, hackathon strategy |

---

## Featured work

### ML systems and research

**DiamondAI** | MLB pitch-sequence Transformer, live ML web app
A ~7.5M-parameter decoder-only Transformer written in JAX/Flax, trained from scratch on ~7M Statcast pitches (2015 to 2024) on a Kaggle TPU v5e-8. Served through an event-driven AWS architecture (Lambda, Kinesis, SageMaker real-time endpoint, DynamoDB, API Gateway WebSocket, EventBridge, CDK). Hand-wrote a FlashAttention-style fused attention kernel in Pallas that runs **1.5x to 3.3x faster than XLA**.
<!-- add repo/demo link -->

**Learning Polymarket Taker Trade Direction from the On-Chain Tape** | Sole-authored research preprint
Classical trade-direction classifiers (tick rule, BVC) collapse to near coin-flip on Polymarket. Using true on-chain ground-truth labels, LightGBM beats the price-bin-corrected tick rule by about 16 points (**0.8175 vs 0.6536** test accuracy), consistently across every price decile. An ablation shows maker identity alone scores at chance, so the signal comes from price trajectory, not leakage. Feeding predicted directions into microstructure metrics lifts OFI correlation with ground truth from 0.270 to **0.684**.
Python, polars, LightGBM, PyTorch (1D CNN) | [Paper (DOI)](https://doi.org/10.5281/zenodo.21039812) | [Code](https://github.com/sbalagan22/polymarket-trade-direction) | [Dataset](https://huggingface.co/datasets/TimeSeventeen/Polymarket-v1)

**OctagonAI** | UFC fight prediction platform
CatBoost classifier with Glicko-2 ratings over 20+ years of fight data, evaluated with walk-forward validation. **~60.1% blind-test accuracy** (2019 to 2024) and +14.2% historical ROI in backtests.
[Live site](https://octagonai.app)

### Hackathon builds

| Project | Result | What it does |
|---|---|---|
| **Bloomr** | 1st place, GDG x UofT AI Case Competition | AI study app with a 3D garden interface, gacha rewards, and quiz-based progression. Next.js, React Three Fiber, Supabase |
| **VibeCheck** | Best Cybersecurity & Trust, IBM Z x UNSA Hackathon | Security scanner for vibe-coded apps. Two-tier pipeline (Qwen2.5-Coder-32B triage, IBM watsonx.ai Granite deep scan, Watson NLU severity scoring) streaming findings over SSE. Built in 36 hours |
| **SideCode** | Runner-up, GDG York AI Case Competition | Renders a GitHub repo as a live interactive graph with multi-agent (security, bug, coordinator) Gemini review, Firebase live listeners, and webhook rescans. [Demo](https://bugtrap-puce.vercel.app) |
| **HomeCrowd** | Finalist, NVIDIA Spark Hackathon | Fully local AI system forecasting how neighborhood events affect Toronto small businesses. Nemotron, cuOpt, cuML, FastAPI, Deck.gl. Built on DGX Spark in one weekend |
| **Mouthpiece** | Finalist, Cursor Toronto Tech Week | Chrome extension that reads pages aloud with ElevenLabs voices and live Hindi/Spanish translation |
| **Parliament Watch** | Finalist, Toronto Anthropic AI Hackathon | Canadian civics platform: real-time bill tracking, all 338 MP profiles, bias-aware news comparison across 5 outlets, Gemini-powered assistant |

### Production and freelance

**The Groundwater Project** | AI semantic search over an educational library (contract)
RAG pipeline with Supabase/pgvector embeddings, MeiliSearch hybrid retrieval, and Meta NLLB for multilingual answers including African languages. Custom search UI, plus documented evaluation and user-testing results.
[Live](https://groundwater-search.pages.dev)

---

## Open source

| Repo | Contribution |
|---|---|
| [facebook/react-native](https://github.com/facebook/react-native/pull/57465) | Merged PR adding a TypeScript type-test that pins the `View` imperative ref contract |
| [firecrawl/firecrawl](https://github.com/firecrawl/firecrawl/pull/3962) | Merged PR fixing `ignoreRobotsTxt` being silently dropped from the JS SDK crawl payload, written failing-test-first |

---

## Recognition

| Event | Result |
|---|---|
| GDG x UofT AI Case Competition | 1st place |
| IBM Z x UNSA Hackathon | Best Cybersecurity & Trust |
| GDG York AI Case Competition | Runner-up |
| GDG UTSC x UofT Build With AI | 2nd place |
| NVIDIA Spark, Cursor Toronto Tech Week, Toronto Anthropic AI Hackathon | Finalist |

---

## Tech stack

<div align="center">

<img src="https://skillicons.dev/icons?i=py,ts,js,react,nextjs,tailwind,fastapi,pytorch,aws,gcp,firebase,supabase,postgres,rails,vercel,git&perline=8" alt="tech stack"/>

</div>

**ML:** JAX/Flax, PyTorch, LightGBM, CatBoost, XGBoost, ONNX, polars, cuML
**Cloud and data:** AWS (Lambda, Kinesis, SageMaker, DynamoDB, CDK), GCP (Vertex AI), Firebase, Supabase/pgvector, MeiliSearch
**LLM work:** RAG, multi-agent pipelines, Gemini, watsonx.ai, Nemotron, OpenAI APIs

---

## Community

- **Workshop Developer, Google Developer Group York:** build and maintain hands-on coding workshops and demo apps (Firebase, Gemini API, GCP) and support live debugging at events
- **Dev Team, The Launch Room:** built technical workshops for entrepreneurship events and conferences
- **Vice President, DECA:** led a 7-person board and trained 50+ competitors to 11 Top-10 regional placements

---

<div align="center">

<a href="https://github.com/sbalagan22"><img height="170" src="https://github-readme-stats.vercel.app/api?username=sbalagan22&show_icons=true&theme=tokyonight&hide_border=true" alt="stats"/></a>
<a href="https://github.com/sbalagan22"><img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sbalagan22&layout=compact&theme=tokyonight&hide_border=true" alt="top languages"/></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2563eb,100:0f172a&height=100&section=footer" alt="footer" width="100%"/>

</div>
