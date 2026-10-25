# Hi, I'm Bilal 👋

I build AI products and backend systems in Türkiye. I'm the founder of [ILYNT Labs](https://ilyntlabs.com) and a Software Engineering student at Fırat University.

[Website](https://bilalabic.com) · [LinkedIn](https://www.linkedin.com/in/bilalabic) · [X](https://x.com/bilalabic) · [Hugging Face](https://huggingface.co/bilalabic)

- 🧪 **ILYNT Labs:** an independent AI studio. We ship our own products, like [Sinyra](https://ilyntlabs.com/products/sinyra), a daily AI briefing in Turkish, and build RAG and custom AI systems for organizations.
- 🗂️ **Turkish AI data:** most of my open-source work is tool-calling datasets, a verified catalogue of Turkish datasets and the quality checks behind them.
- 🥇 **Hackathons:** 1st place at the Kayseri Monad Blitz, 2nd place at Gelecek Üreten Gece.
- ⚙️ **Day to day:** Python and FastAPI, C# and .NET, TypeScript and Next.js.
- 🤝 **Open to:** collaboration on Turkish NLP, datasets and developer tools.

## 🏆 Hackathon projects

Team projects built at hackathons, mostly on Monad, Stellar and Sui.

- **[MONOSFER](https://github.com/bilalabic/monosfer)** 🥇 <br>
  A courier marketplace on Monad. Couriers bid openly and Solidity escrow contracts hold the payment. 1st place at the BuilderMare Kayseri Monad Blitz. <br>
  `Vue 3` `Express` `MongoDB` `Solidity` `Foundry`
- **[WEIAP](https://github.com/bilalabic/ruzgar)** 🥈 <br>
  Wind energy investment analysis, from map-based site selection to financial feasibility, with AI reporting. 2nd place at Gelecek Üreten Gece. <br>
  `JavaScript` `Vite` `Leaflet` `Sui` `Walrus` · [original team repo](https://github.com/kevseraslan/ruzgar)
- **[ChargeMesh](https://github.com/bilalabic/ChargeMesh)** · [demo](https://chargemesh.vercel.app) <br>
  Turns idle EV chargers into reservable capacity, with settlement on Monad testnet and charging metered over OCPP. Built at Monad Blitz İstanbul. <br>
  `Vue 3` `Fastify` `MongoDB` `Solidity` `Foundry`
- **[showup](https://github.com/bilalabic/showup)** · [demo](https://showup-steel.vercel.app) <br>
  Attendance commitment bonds on Stellar: lock a refundable bond and get it back on check-in. Built for the Rise In × Stellar Pro Hackathon Türkiye 2026. <br>
  `Next.js` `Soroban` `Stellar`
## 📚 Turkish AI data

The area I'm focusing on. These projects are still early and growing.

**Catalogue**

- **[awesome-turkish-datasets](https://github.com/bilalabic/awesome-turkish-datasets)** is a community-driven catalogue of Turkish datasets, 298 so far, with licence, size and access checked per entry. Corrections and additions are welcome. [Browse it](https://bilalabic.github.io/awesome-turkish-datasets/).

**Tool-calling data (in development)**

The goal is high-quality Turkish training data for models that call tools, with verification at every step.

- **[toolcall-tr](https://github.com/bilalabic/toolcall-tr)**: every tool call is run by a real implementation and checked, and no tool output is written by an LLM. v0.1 is a small proof of the method with 200 verified examples, 35 tools and 15 providers. The next target is 10,000 to 15,000 examples.
- **[toolcall-tr-pipeline](https://github.com/bilalabic/toolcall-tr-pipeline)**: turns English tool-calling and chat data into Turkish training data. In a 1,000-candidate run, 733 records passed the quality gates and are waiting for human review.
- **[magibu-toolcall](https://github.com/bilalabic/magibu-toolcall)**: data-generation infrastructure built with the Magibu AI community, with 27 pull requests from 9 contributors. Currently paused after the first round of contributions.

<details>
<summary>Research, experiments and datasets on Hugging Face</summary>
<br>

- [math-toolcall-tr](https://github.com/bilalabic/math-toolcall-tr): 1,207 Turkish math tool-calling examples and a Gemma LoRA fine-tune
- [huggingface-dataset-analizi](https://github.com/bilalabic/huggingface-dataset-analizi): quality and capability analysis of 45 Turkish datasets (87,831 rows)
- [foods_bpe_tokenizer](https://github.com/bilalabic/foods_bpe_tokenizer): a BPE tokenizer from scratch and a tiny transformer that invents Turkish dish names
- Datasets: [turkish-tool-calling](https://huggingface.co/datasets/bilalabic/turkish-tool-calling) · [quality-gated preview](https://huggingface.co/datasets/bilalabic/turkish-tool-calling-quality-gated-preview) · [toolcall-tr-pilot](https://huggingface.co/datasets/bilalabic/toolcall-tr-pilot) · [math-toolcall-tr](https://huggingface.co/datasets/bilalabic/math-toolcall-tr) · [benchmark](https://huggingface.co/datasets/bilalabic/math-toolcall-tr-benchmark)

</details>

## 🚀 Other things I've built

- **[RESQ](https://github.com/bilalabic/afet-koordinasyon-agi)** · [demo](https://afet-koordinasyon-agi.vercel.app): a team project for disaster coordination with request scoring, geographic clustering and vehicle recommendations. I built the backend and mobile parts
- **[firat-hackathon-community](https://github.com/bilalabic/firat-hackathon-community)** · [demo](https://firat-hackathon-community.vercel.app): a directory to discover, verify and publish hackathons
- **[listur](https://github.com/bilalabic/listur)** · [demo](https://listur.bilalabic.com): Türkiye's tech event platform for hackathons, meetups and conferences
- **[udf-dilekce](https://github.com/bilalabic/udf-dilekce)** · [demo](https://udf-dilekce.vercel.app): bulk petition generation from Word and UYAP templates, entirely in the browser
- **[kalkan](https://github.com/bilalabic/kalkan)**: scam detection for second-hand marketplace chats
- **[ProjectTracker](https://github.com/bilalabic/ProjectTracker)**: project planning and tracking with AI-assisted risk analysis

## 🛠 Tools I reach for

- **Languages:** `Python` `C#` `TypeScript` `JavaScript` `Java`
- **Backend:** `FastAPI` `ASP.NET Core` `Node.js`
- **Frontend:** `Next.js` `React` `Vue 3` `Tailwind CSS`
- **Data:** `PostgreSQL` `PostGIS` `MongoDB` `Supabase`
- **AI:** `RAG` `tool calling` `LoRA fine-tuning` `Hugging Face`
- **Web3:** `Solidity` `Foundry` `Move` `Soroban`
- **Shipping:** `Docker` `GitHub Actions` `Vercel`

<details>
<summary>Archive: coursework and learning projects</summary>
<br>

Kept public as a record of how I learned. Archived and not maintained.

- [university-coursework](https://github.com/bilalabic/university-coursework): C# and Windows Forms assignments and a Java assignment, with their original history
- [web3-learning](https://github.com/bilalabic/web3-learning): a 21-day Sui Move challenge and a Stellar bill-splitting dApp

</details>

---

Want to build something together? Reach me at [bilalabic.com](https://bilalabic.com) or on [LinkedIn](https://www.linkedin.com/in/bilalabic).
