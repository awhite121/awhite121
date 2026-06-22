# Andrew White 👋👾💻

**MS Business Analytics, UT Austin McCombs | Data & Analytics Consultant | Machine Learning / AI / BI**

I build data science, machine learning, and analytics projects that turn messy real-world data into usable products, models, dashboards, and decision-support tools. My work spans machine learning, computer vision, NLP, generative AI, recommender systems, analytics engineering, and business intelligence.

* 🔭 Currently working in data and BI consulting, building client-facing analytics solutions across SQL, Snowflake, Power BI, Domo, MicroStrategy, ETL pipelines, and dashboard automation.
* 🧠 Building applied AI/ML projects across medical imaging, event recommendation, sports analytics, NLP, and decision-support systems.
* 📊 Focused on machine learning, analytics engineering, data modeling, predictive analytics, NLP, computer vision, and product-oriented analytics.
* 🌐 Portfolio: [andrewwhitedata.com](https://www.andrewwhitedata.com)
* 🎓 MS Business Analytics graduate from UT Austin McCombs, with coursework in advanced machine learning, optimization, unstructured data, marketing analytics, unsupervised learning, information management, and statistical modeling.

---

## Tech Stack

**Languages:** Python, SQL, R

**Libraries & Frameworks:** pandas, NumPy, scikit-learn, XGBoost, CatBoost, TensorFlow, Keras, PyTorch, MONAI, LangChain, SHAP, NLTK, spaCy, BeautifulSoup, Selenium, Playwright

**ML / AI:** Machine Learning, Statistical Modeling, Deep Learning, Computer Vision, NLP, Generative AI, Prompt Engineering, Transformer Models, CNNs, Transfer Learning, Feature Engineering, Model Validation, Hyperparameter Tuning, Threshold Optimization, Dimensionality Reduction

**Data / Cloud:** Snowflake, dbt, Spark, GCP, Vertex AI, REST APIs, ETL Pipelines, Medallion Architecture, Incremental Data Loads, Docker, AWS Lightsail

**BI / Visualization:** Tableau, Power BI, Domo, MicroStrategy, Excel, Streamlit, Plotly

**Tools:** Git, GitHub, Jupyter, Google Colab, Anvil

---

## Featured Projects

### 🩻 [AI-Assisted Spine MRI Screening](https://github.com/awhite121/AI-Radiology-Screening-Lumbar-Spine-MRI-Severity-Classification)

Deep learning pipeline for study-level lumbar spine MRI severity classification. Built an end-to-end medical imaging workflow using DICOM preprocessing, leakage-safe study-level splits, ResNet18 transfer learning, multi-slice transformer aggregation, MedSAM ROI localization, and threshold tuning for severe spinal canal stenosis screening. Framed as clinical decision support to prioritize studies for human review, not replace radiologists.

`Python` · `PyTorch` · `MONAI` · `Computer Vision` · `ResNet18` · `Transformers` · `MedSAM` · `DICOM` · `Medical AI`

### 🎟️ [Concert Copilot](https://github.com/awhite121/concert-copilot-streamlit)

AI-powered concert recommendation and planning app built with Streamlit. Blends Spotify taste profiles, genre clustering, live event retrieval, price metadata, feedback learning, and LLM-powered planning to recommend concerts based on user taste. Includes ranking modes for familiar favorites, fresh discoveries, up-and-coming artists, group-listener blending, shortlist feedback, and a Copilot tab that can compare shows or build a night plan around a selected event.

`Python` · `Streamlit` · `Spotify API` · `OpenAI` · `XGBoost` · `Recommender Systems` · `Plotly` · `APIs`

### 🏈 [CFB Power Index](https://github.com/awhite121/cfb-power-index)

Composite efficiency ranking system for all 136 FBS college football teams. Engineered six per-play metrics including offensive efficiency, defensive efficiency, explosive score, and havoc rate, standardized them into z-scores, and validated the index against the 2025–26 College Football Playoff. Includes a logistic win probability model that retroactively predicted CFP bracket outcomes.

`Python` · `Pandas` · `scikit-learn` · `Logistic Regression` · `Feature Engineering`

[![Live Dashboard](https://img.shields.io/badge/Streamlit-Live_Dashboard-FF4B4B?logo=streamlit\&logoColor=white)](https://cfb-power-index.streamlit.app/)

### 🎮 [Connect 4 AI: CNN vs Transformer](https://github.com/awhite121/connect4-ai)

Trained two deep learning architectures, CNN and Transformer, on 4,000 MCTS-generated games to build competitive Connect 4 agents. Both models were deployed as live, playable opponents via Docker on AWS Lightsail with an interactive Anvil web frontend. Full ML lifecycle: synthetic data generation, model architecture design, containerized deployment, and production serving.

`Python` · `TensorFlow` · `Keras` · `CNNs` · `Transformers` · `Docker` · `AWS`

[![Play the AI](https://img.shields.io/badge/Anvil-Play_the_AI-6C63FF?logo=data\:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJ3aGl0ZSI+PHBhdGggZD0iTTggNXYxNGwxMS03eiIvPjwvc3ZnPg==\&logoColor=white)](https://msba25optim2-18.anvil.app/)

### 🎵 [RateYourMusic Recommender System](https://github.com/awhite121/RateYourMusic-Recommender-System)

Content-based album recommender built on crowdsourced music reviews. Converts unstructured text into numerical representations using TF-IDF and embedding-based similarity, with sentiment analysis for interpretability. Users input genre, instrument, and vibe preferences and receive ranked recommendations with evidence snippets.

`Python` · `NLP` · `TF-IDF` · `Embeddings` · `Sentiment Analysis` · `Cosine Similarity`

### 🏀 [UT Women's Basketball Instagram Engagement](https://github.com/awhite121/ut-wbb-instagram-engagement)

End-to-end analytics pipeline that scraped 500+ Instagram posts with Selenium, labeled images via Google Vision API, vectorized captions, and trained classifiers to predict engagement. Topic modeling with LDA uncovered that behind-the-scenes and in-game content consistently outperformed branded graphics.

`Python` · `Selenium` · `Google Vision API` · `LDA` · `Logistic Regression` · `Web Scraping`

### 🚕 [NYC Taxi Trip Duration & Late Risk Prediction](https://github.com/awhite121/NYC-Taxi-Trip-Duration-Late-Risk-Prediction)

End-to-end ML pipeline predicting Manhattan-to-airport trip times and classifying late-arrival risk. Compared regression and classification models including Random Forest, XGBoost, and CatBoost, then translated predictions into practical buffer-time departure guidance with threshold-tuned decision frameworks.

`Python` · `XGBoost` · `CatBoost` · `Classification` · `Regression` · `Threshold Tuning`

### 🔗 [Jmail Network Explorer](https://github.com/awhite121/jmail-network-explorer)

End-to-end network analysis of the Jeffrey Epstein email archive. Scraped ~1,533 nodes and ~2,132 edges with a two-phase Selenium pipeline, built a directed weighted graph with NetworkX, and computed centrality metrics across all participants. Applied Louvain community detection to identify 102 clusters, with the giant component covering 94% of the network. Deployed as a 6-tab Streamlit dashboard with PyVis force-directed graphs, Sankey flow diagrams, and ego network exploration.

`Python` · `NetworkX` · `Streamlit` · `PyVis` · `Plotly` · `Selenium` · `Louvain Community Detection`

[![Live Dashboard](https://img.shields.io/badge/Streamlit-Live_Dashboard-FF4B4B?logo=streamlit\&logoColor=white)](https://jmail-network-msba.streamlit.app/)

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=awhite121&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="165" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=awhite121&theme=tokyonight&hide_border=true" height="165" />
</p>

---

## Connect

[![Portfolio](https://img.shields.io/badge/Portfolio-andrewwhitedata.com-c45d3e?style=for-the-badge&logo=google-chrome&logoColor=white)](https://www.andrewwhitedata.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/andrew-white12/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:andrewwhiteack@gmail.com)
