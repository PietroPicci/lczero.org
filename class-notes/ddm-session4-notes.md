# Data-Driven Marketing – Session 4: Text & Data Mining + Visual Mining
ESCP Business School – Master in Management

Legend: **[SLIDE]** = from the deck · **[PROF]** = something the professor said in class

---

## 1. Introduction (slides 3–8)
**[SLIDE]**
- Predictive analytics market: $5.29B (2020) → $41.52B (2028*) (Statista).
- AI market: ~$208B (2023) → ~$1,847B (2030).
- Video case: Coca-Cola using Text & Data Mining (TDM).
- Framing questions for every TDM technique: what is the algorithm, how does it work, who executes it, when is it used, what are its limits?
- Definitions:
  - **Text Mining** – analytics on unstructured text; automatic grouping of similar texts.
  - **Data Mining** – exploring data to uncover meaningful patterns/rules.
  - **Predictive Analytics** – predicting future outcomes from historical data + statistics, data mining, ML.
  - **Social Listening** – identifying/assessing what is said about a company, person, product or brand online.
  - **Sentiment Analysis** – detecting the emotional tone of online text (positive / negative / neutral).
  - **Visual Mining** – extracting trends/patterns from visual data via data mining, computer vision, visualization.

**[PROF]**
- _(waiting for your notes)_

---

## 2. Text Mining (slides 9–14)
**[SLIDE]** Typical pipeline:
1. **Tokenization** – split text into tokens.
2. **Stop-word removal** – drop meaningless words ("and", "the").
3. **Stemming / Lemmatization** – reduce words to root form.
4. **TF-IDF** – weight words by frequency in a document vs. rarity across documents.
5. **Named Entity Recognition (NER)** – find names, places, etc.
6. **Opinion mining / Sentiment analysis** – classify positive/negative/neutral.
7. **Topic modeling & text classification** – discover hidden themes / assign predefined labels.

Success factors: data quality ("garbage in, garbage out"), cleansing, algorithm choice, scalability, model evaluation, ethical boundaries.

Applications by sector: manufacturers (root causes of issues, competitor products), government (fraud, public sentiment), finance (call-center transcripts, money laundering), retail (profitable customers, brand on social), legal, healthcare, telecom (churn, up/cross-sell), life sciences, insurance.
**Most relevant for marketing managers:** Telecom (churn, up/cross-sell), Retail (loyal/profitable customers, brand management), Manufacturers (market trends, competitors).

**[PROF]** (walking through the pipeline on a sample sentence)
- **Tokenization:** literally break the sentence down into chunks (tokens).
- **Stop-word elimination:** remove words that are not very meaningful.
- **Stemming:** take the verbs and reduce them to their basic form (e.g. "finished" → "finish").
- **NER:** tag entities by type, e.g. "L'Oréal" → organization, "Italy" → location.
- **Sentiment:** the sample sentence came out as neutral.
- **Topic modelling:** assigned the text to themes such as travel, education, career.
- **Areas of application:** many sectors, but the ones of particular relevance are those tied to marketing, since that is the goal of the course (slide 14: telecom, retail, manufacturers).
- **Coca-Cola video** (shown at the start of class, slide 6): Coca-Cola's social listening "Hub".
  - *Summary:* The Hub is a team that connects Coca-Cola's social marketers worldwide to understand how consumers perceive the company. Consumers are always talking about the brand (about **33 mentions of Coke per minute in English**), so "people are telling us what they think; it's up to us to listen". The Hub's job is to track the global impact of those conversations so the company can keep improving how it engages consumers. The workspace has about 33 screens and 12 people. A 130-year-old brand is working at the cutting edge of technology. Because new social networks and new ways of engaging keep appearing, the team must keep adapting and make sure marketers know how to adapt too.
  - *Takeaways for the course:* social listening = turning huge volumes of unstructured text (mentions) into insight; it is a continuous process, not a one-off; it needs both tools and people in house (links to the social listening process on slide 27); the landscape changes fast, so capability must evolve.
  - *Transcript (as pasted by the student):* "The hub is a team that connects our social marketers around the world trying to understand how our consumers perceive our company. They're always talking about us. There are 33 mentions of Coke per minute in English. So, people are telling us what they think about us. It's up to us to actually listen. So, our job at the hub is really to look at the global impact of conversations so that we can get better and constantly improve how we're engaging with our consumers. One of the cool parts about my job is I get to work in this great workspace here. 30, 31, 32, 33. So, we've got about 33 screens and 12 people. It's been really exciting to be a part of the hub and as we built this capability for Coca-Cola, this great 130-year-old brand, and here we are on the cutting edge of technology. So, just as soon as we think we've got something nailed down, it's going to evolve. There's going to be a new social network. There's going to be a new place that people are engaging and a new way they're engaging. And we're going to have to adapt to that and make sure our marketers know how to adapt to that."
- **General rules for text mining:** success depends on quality of data, data cleansing, selection of algorithms, scalability, evaluation and ethical boundaries (matches slide 12).

---

## 3. Data Mining (slides 15–20)
**[SLIDE]**
- Process (6 steps): data cleaning → integration → selection → transformation → data mining → knowledge representation.
- Algorithms:
  - **Association rule mining** – relationships between items (e.g. basket analysis).
  - **Classification** – predict categorical labels for new cases.
  - **Neural networks** – brain-inspired models.
  - **Clustering** – group similar data points (highlighted on slide).
  - **Sequential pattern mining** – patterns in time series / transactions.
  - **Regression** – predict continuous values (linear, logistic).
  - **Anomaly detection** – unusual patterns, e.g. fraudulent transactions (matched to Financial Institutions).
- Tools: SSDT, Sisense, RapidMiner, IBM Cognos, SPSS Modeler, KNIME, Weka, Orange, Mahout, Spark, Python, H2O, SAS, Oracle, etc.
- Slide's message: marketers will most likely **not mine data themselves** – they use tools / analysts.

**[PROF]** (examples for each data mining algorithm)
- **Association rule mining:** products on Amazon that are correlated or linked (e.g. "customers also bought").
- **Classification:** e.g. spam emails (spam / not spam).
- **Neural networks:** (no example noted yet).
- **Clustering:** groups of homogeneous data, e.g. customer segmentation.
- **Sequential patterns:** e.g. the order in which movies are watched.
- **Regression:** predicts continuous numerical values.
- **Anomaly detection:** weird patterns, e.g. fraud, banks.

---

## 4. Predictive Analytics (slides 21–24)
**[SLIDE]**
- Role of AI/ML: demand forecasting, healthcare diagnostics, predicting customer behaviour, financial analysis (fraud), supply-chain optimization, stock-market predictions.
- Highlighted for marketing: **Demand forecasting**, **Predict customer behaviour**, **Supply chain optimization**.

**[PROF]**
- _(waiting for your notes)_

---

## 5. Social Listening & Sentiment Analysis (slides 25–31)
**[SLIDE]**
- Social listening process: (1) set marketing objectives – in house; (2) data collection – tools; (3) data analysis – tools; (4) insights generation – tools; (5) engagement & response – in house; (6) monitoring – tools.
- Sentiment analysis applications: brand reputation, customer research/feedback, **market research for decision making** (emphasized), crisis prevention, social/financial/political analysis, customer service.
- Example: Nike tweets labelled positive / negative / neutral by a tool.
- Case – **Boeing**: reputation score of −80 (top 5% worst brands) after the China Eastern 737-800 crash; mention spikes visible on timeline → sentiment tracking monitors reputational damage.
- Case – **Crypto**: social-media sentiment used to predict short-term crypto prices (linear regression, boosting, neural nets); sentiment sampled 3×/day; price driven by perception more than regulation; final model profitable. (Full article on Blackboard.)

**[PROF]**
- **Social listening:** (she introduced the topic; no further detail noted yet).
- **Sentiment analysis:** classifies mentions as positive, negative or neutral about you, i.e. what the consumer perceives of the brand.
- **Boeing** (case, slide 30): example of sentiment/reputation tracking after the China Eastern 737-800 crash.

---

## 6. Visual Mining (slides 32–39)
**[SLIDE]**
- **Dash Hudson** (Vision AI, learning since 2016): goes beyond keywords/hashtags to surface *visual* trends; clients like Condé Nast, P&G, KraftHeinz, Apple, Harrods.
- **YouScan**: social listening with visual insights ("what they say / who they are / what they do"); clients Nestlé, Unicef, Samsung, Danone, Coca-Cola, L'Oréal, Vodafone.
- Takeaways: >80% of visual imagery is untapped; links multimedia, computer vision, pattern recognition; good for spotting emerging trends and watching competitors; improves marketer decisions.
- **TDVM summary:** extract insights from text, data and visuals at scale → understand sentiment/preferences/behaviour → personalise, optimise campaigns, improve engagement & conversion.

**[PROF]**
- _(waiting for your notes)_

---

## 7. Team Activity – Microsoft vs Apple on Brand24 (slides 40–49)
**Task:** teams of 5–6 compare Microsoft vs Apple over 20 Jun–20 Jul 2024. Extract volume of mentions, social reach, non-social reach, positive/negative mentions; compute **Sentiment Ratio = Positive / Negative**; discuss which events explain the results; write a report.

**[SLIDE] Data extracted**

| Metric | Microsoft | Apple |
|---|---|---|
| Mentions | 53,908 (≈54K) | 53,918 (≈54K) |
| Social media mentions | 14,230 | 8,372 |
| Non-social mentions | 39,678 | 45,546 |
| Social media reach | 64M (62M in summary view) | 106M |
| Non-social media reach | 335M | 510M |
| Interactions | 5.3M | 2.7M |
| Likes | 4.4M | 2.6M |
| User-generated content | 18,189 | 15,064 |
| Positive mentions | 844 (64%) | 6,824 (78%) |
| Negative mentions | 469 (36%) | 1,908 (22%) |
| **Sentiment ratio (pos/neg)** | **844 / 469 ≈ 1.80** | **6,824 / 1,908 ≈ 3.58** |
| AVE (ad value equivalent) | $42M | $80M |
| Mentions from X | 98 | 82 |
| Top site | youtube.com 8,102 | youtube.com 5,295 |
| Top category | News 30,267 | News 33,102 |

Top hashtags – Microsoft: #microsoft, #shorts, **#crowdstrike (687)**, #gaming, #viral, #xbox, #ai, #windows… Apple: #apple, #iphone, #shorts, #viral, #trending, #beautiful, #cute, #bollywood, #samsung…
Word cloud – Microsoft: crowdstrike, windows, azure, copilot, openai, nvidia, xbox, excel, seguridad (security), "fallo" (failure). Apple: iphone, music, instagram, spotify, amazon, podcast, streaming, android.

**Preliminary reading (to confirm with prof's guidance)**
- Same volume of mentions, but Apple has ~65% more social reach, ~52% more non-social reach and a ~2× sentiment ratio.
- Microsoft's mention curve rises sharply toward 20 Jul → matches the **CrowdStrike outage (19 Jul 2024)** that crashed Windows machines worldwide; this explains the spike in negative mentions (+4,550%) and the #crowdstrike / "fallo" / security vocabulary.
- Apple's conversation is product/lifestyle/entertainment (iPhone, music, streaming) and more diffuse; positive share is higher.
- Caveat: only a small share of mentions carry a sentiment label (e.g. 1,313 of ~54K for Microsoft), so ratios are based on a subset; "previous period" comparison is empty, making the +% changes meaningless.

**[PROF]**
- _(waiting for your notes)_

---

## Running log of professor's remarks (chronological)
_(Everything you send me gets added here and then merged into the sections above.)_

1. Text mining pipeline demo on one sentence: tokenization → stop-word removal → stemming ("finished" → "finish") → NER (L'Oréal = organization, Italy = location) → sentiment (neutral) → topic modelling (travel, education, career). → merged into section 2.
2. General rules for text mining success: data quality, data cleansing, algorithm selection, scalability, evaluation, ethical boundaries. → merged into section 2.
3. Areas of application: focus on those particularly relevant to marketing (the course goal). Coca-Cola opening video: transcript + summary added (Coca-Cola social listening Hub, 33 mentions/min). → merged into section 2.
4. Data mining algorithm examples: association (Amazon related products), classification (spam), neural networks, clustering (segmentation), sequential patterns (movie viewing order), regression (continuous values), anomalies (fraud, banks). → merged into section 3.
5. Social listening introduced; sentiment analysis = positive/negative/neutral view of what consumers perceive about you; Boeing case. → merged into section 5.
