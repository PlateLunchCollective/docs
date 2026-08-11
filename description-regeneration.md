# Glossary description regeneration

Applies the approved rule (cap **200**; source = opening `## Definition` sentence; Candidate A = paired-em-dash removal; Candidate B = longest valid structural cut ≤200; choose by reading) to all **340** truncated descriptions from `description-audit.md`. The set is now closed.

**Working-tree changes only.** Markdown links stripped to plain text; every value stored as a YAML double-quoted scalar.

## Counts

| Outcome | Count |
|---|---|
| Verbatim (opening sentence ≤200) | 91 |
| Candidate A (paired-interruption removal) | 38 |
| Candidate B (structural trim) | 188 |
| Hand-write (reviewed & applied) | 22 |
| Special — `preferred-source` (body sentence + description) | 1 |
| **Total applied** | **340** |

---

## `preferred-source.mdx` — applied (content change)

The only page in the set whose opening sentence did not define its term. **Body `## Definition` sentence rewritten and reordered** (all facts preserved), and the description derived from it.

- **Old opening sentence:** Google evaluates websites for topic authority through signals such as E-E-A-T … There is no formal "Preferred Source" designation…
- **New body `## Definition` (shipped):** A preferred source is a website or publisher that a search engine or AI system consistently favors and cites for a given topic, based on demonstrated authority rather than a formal designation. There is no official "Preferred Source" program; Google evaluates websites for topic authority through signals such as E-E-A-T — Experience, Expertise, Authoritativeness, and Trustworthiness — to determine relevance and citation priority in Search and AI Overviews.
- **Shipped description (159):** A preferred source is a website or publisher that a search engine or AI system consistently favors and cites for a given topic, based on demonstrated authority
- **Note:** the description is the positive clause only; "rather than a formal designation" (definition by negation) stays in the body sentence, where it reads well but would make a weak snippet.

---

## Hand-write set (22) — applied

### `ai-search-optimization.mdx`
- **Old (158):** AI search optimization is the practice of optimizing a brand's visibility, accuracy, and citation frequency across AI-powered search and discovery surfaces...
- **Opening sentence (251):** AI search optimization is the practice of optimizing a brand's visibility, accuracy, and citation frequency across AI-powered search and discovery surfaces including large language models, answer engines, voice assistants, and social search platforms.
- **Shipped (155):** AI search optimization is the practice of optimizing a brand's visibility, accuracy, and citation frequency across AI-powered search and discovery surfaces

### `aloha-economy.mdx`
- **Old (160):** The aloha economy refers to Hawaii's distinctive economic character — shaped by tourism, military presence, agriculture, small business density, and a cultur...
- **Opening sentence (276):** The aloha economy refers to Hawaii's distinctive economic character — shaped by tourism, military presence, agriculture, small business density, and a cultural ethos of hospitality and community that influences how commerce is conducted and how businesses position themselves.
- **Shipped (172):** The aloha economy is Hawaii's distinctive economic character, shaped by tourism, military presence, agriculture, small-business density, and a cultural ethos of hospitality

### `citation-consistency.mdx`
- **Old (160):** Citation consistency is the degree to which a brand's AI citations accurately and uniformly represent the same core facts, attributes, and positioning across...
- **Opening sentence (263):** Citation consistency is the degree to which a brand's AI citations accurately and uniformly represent the same core facts, attributes, and positioning across different queries, platforms, and time periods — without contradictions, gaps, or significant variations.
- **Shipped (189):** Citation consistency is the degree to which a brand's AI citations uniformly represent the same core facts, attributes, and positioning across different queries, platforms, and time periods

### `citation-injection-risk.mdx`
- **Old (160):** Citation injection risk is the vulnerability of AI retrieval systems to the introduction of low-quality, manipulative, or synthetic content that earns AI cit...
- **Opening sentence (230):** Citation injection risk is the vulnerability of AI retrieval systems to the introduction of low-quality, manipulative, or synthetic content that earns AI citations by gaming retrieval signals rather than through genuine authority.
- **Shipped (195):** Citation injection risk is the vulnerability of AI retrieval systems to manipulative or synthetic content that earns AI citations by gaming retrieval signals rather than through genuine authority

### `competitive-citation-gap.mdx`
- **Old (160):** A competitive citation gap is a query or topic area in which a competitor is being cited by AI systems but the brand is not — indicating that the competitor ...
- **Opening sentence (253):** A competitive citation gap is a query or topic area in which a competitor is being cited by AI systems but the brand is not — indicating that the competitor has stronger AI authority in that specific area and the brand has a defined position to capture.
- **Shipped (128):** A competitive citation gap is a query or topic area where a competitor is cited by AI systems but the brand is not yet appearing

### `competitive-displacement-ai.mdx`
- **Old (160):** Competitive displacement in AI search occurs when a competitor's content, entity signals, or retrieval presence causes an AI system to cite the competitor in...
- **Opening sentence (305):** Competitive displacement in AI search occurs when a competitor's content, entity signals, or retrieval presence causes an AI system to cite the competitor in response to queries where the brand should plausibly appear — actively displacing the brand from citation opportunities it would otherwise capture.
- **Shipped (184):** Competitive displacement in AI search occurs when a competitor's content or entity signals cause an AI system to cite the competitor for queries where the brand should plausibly appear

### `content-extractability.mdx`
- **Old (160):** Content extractability is the degree to which specific facts, answers, and claims within a piece of content can be identified, isolated, and reused by AI sys...
- **Opening sentence (206):** Content extractability is the degree to which specific facts, answers, and claims within a piece of content can be identified, isolated, and reused by AI systems without requiring the full document context.
- **Shipped (195):** Content extractability is the degree to which specific facts, answers, and claims within a piece of content can be identified, isolated, and reused by AI systems without the full document context

### `content-gap-analysis.mdx`
- **Old (160):** Content gap analysis is the process of identifying topics, subtopics, or query types that competitors cover but a given brand does not — used to expand topic...
- **Opening sentence (276):** Content gap analysis is the process of identifying topics, subtopics, or query types that competitors cover but a given brand does not — used to expand topical coverage and authority by systematically filling the gaps between current content and comprehensive domain coverage.
- **Shipped (142):** Content gap analysis is the process of identifying topics, subtopics, or query types that competitors cover but the brand does not yet address

### `definition-first-writing.mdx`
- **Old (160):** Definition-first writing is a content approach in which a term, concept, or topic is defined clearly and completely at the start of the piece or section, bef...
- **Opening sentence (202):** Definition-first writing is a content approach in which a term, concept, or topic is defined clearly and completely at the start of the piece or section, before any elaboration, context, or application.
- **Shipped (187):** Definition-first writing is a content approach in which a term, concept, or topic is defined clearly and completely at the start of the piece or section, before any elaboration or context

### `domain-authority.mdx`
- **Old (160):** Domain Authority (DA) is a proprietary Moz metric scored from 1 to 100 that predicts how likely a domain is to rank in search results, based primarily on the...
- **Opening sentence (219):** Domain Authority (DA) is a proprietary Moz metric scored from 1 to 100 that predicts how likely a domain is to rank in search results, based primarily on the quality and quantity of inbound links pointing to the domain.
- **Shipped (133):** Domain Authority (DA) is a proprietary Moz metric scored from 1 to 100 that predicts how likely a domain is to rank in search results

### `entity-seo.mdx`
- **Old (159):** Entity SEO is the practice of optimizing a brand's entity presence across knowledge graphs, structured data, training data sources, and AI retrieval systems...
- **Opening sentence (263):** Entity SEO is the practice of optimizing a brand's entity presence across knowledge graphs, structured data, training data sources, and AI retrieval systems so that both search engines and AI platforms can accurately identify, categorize, and represent the brand.
- **Shipped (156):** Entity SEO is the practice of optimizing a brand's entity presence across knowledge graphs, structured data, training data sources, and AI retrieval systems

### `geo.mdx`
- **Old (160):** GEO — Generative Engine Optimization — is the practice of optimizing content and brand signals to improve visibility and citation in AI-generated responses f...
- **Opening sentence (252):** GEO — Generative Engine Optimization — is the practice of optimizing content and brand signals to improve visibility and citation in AI-generated responses from systems like ChatGPT, Perplexity, Google AI Overviews, and other generative search engines.
- **Shipped (155):** GEO — Generative Engine Optimization — is the practice of optimizing content and brand signals to improve visibility and citation in AI-generated responses

### `html-first-development.mdx`
- **Old (160):** HTML-first development is a web development approach that prioritizes delivering page content as static, server-rendered HTML rather than relying on client-s...
- **Opening sentence (218):** HTML-first development is a web development approach that prioritizes delivering page content as static, server-rendered HTML rather than relying on client-side JavaScript to generate or render content after page load.
- **Shipped (171):** HTML-first development is a web development approach that prioritizes delivering page content as static, server-rendered HTML rather than relying on client-side JavaScript

### `hub-and-spoke-model.mdx`
- **Old (160):** The hub and spoke model is a content architecture in which a central hub page covers a topic at the highest level, linking outward to a set of spoke pages th...
- **Opening sentence (202):** The hub and spoke model is a content architecture in which a central hub page covers a topic at the highest level, linking outward to a set of spoke pages that each address a specific subtopic in depth.
- **Shipped (179):** The hub and spoke model is a content architecture in which a central hub page covers a topic broadly, linking outward to spoke pages that each address a specific subtopic in depth

### `passage-ranking.mdx`
- **Old (160):** Passage ranking is Google's capability to identify and rank individual passages within a long document, enabling specific sections to appear in search result...
- **Opening sentence (223):** Passage ranking is Google's capability to identify and rank individual passages within a long document, enabling specific sections to appear in search results even if the overall page is not the strongest match for a query.
- **Shipped (158):** Passage ranking is Google's capability to identify and rank individual passages within a long document, enabling specific sections to appear in search results

### `people-also-ask.mdx`
- **Old (160):** People Also Ask (PAA) is a Google SERP feature displaying a set of related questions with expandable answers, dynamically generated based on the user's query...
- **Opening sentence (233):** People Also Ask (PAA) is a Google SERP feature displaying a set of related questions with expandable answers, dynamically generated based on the user's query and the questions Google's systems identify as commonly associated with it.
- **Shipped (153):** People Also Ask (PAA) is a Google SERP feature displaying a set of related questions with expandable answers, dynamically generated from the user's query

### `perplexity-pages.mdx`
- **Old (160):** Perplexity Pages is a feature within Perplexity AI that allows users to create structured, long-form research documents generated by the AI, with citations, ...
- **Opening sentence (201):** Perplexity Pages is a feature within Perplexity AI that allows users to create structured, long-form research documents generated by the AI, with citations, section headings, and exportable formatting.
- **Shipped (176):** Perplexity Pages is a feature within Perplexity AI that allows users to create structured, long-form research documents generated by the AI, with citations and section headings

### `reddit-citation.mdx`
- **Old (160):** A Reddit citation is a reference to a brand, product, or piece of content within a Reddit post, comment, or thread that can be indexed, retrieved, and used a...
- **Opening sentence (201):** A Reddit citation is a reference to a brand, product, or piece of content within a Reddit post, comment, or thread that can be indexed, retrieved, and used as evidence by AI systems generating answers.
- **Shipped (181):** A Reddit citation is a reference to a brand, product, or piece of content within a Reddit post, comment, or thread that can be indexed, retrieved, and used as evidence by AI systems

### `social-content-infrastructure.mdx`
- **Old (160):** Social content infrastructure is the systematic architecture of a brand's social media presence — designed to function as a durable retrieval surface rather ...
- **Opening sentence (216):** Social content infrastructure is the systematic architecture of a brand's social media presence — designed to function as a durable retrieval surface rather than a series of individual posts optimized for engagement.
- **Shipped (189):** Social content infrastructure is the systematic architecture of a brand's social media presence, designed to function as a durable retrieval surface rather than a series of individual posts

### `social-discoverability.mdx`
- **Old (160):** Social discoverability is the degree to which a brand's social media content surfaces in response to relevant queries through platform-native search, AI-gene...
- **Opening sentence (217):** Social discoverability is the degree to which a brand's social media content surfaces in response to relevant queries through platform-native search, AI-generated recommendations, and cross-platform retrieval systems.
- **Shipped (181):** Social discoverability is the degree to which a brand's social media content surfaces in response to relevant queries through platform-native search and AI-generated recommendations

### `topic-cluster.mdx`
- **Old (160):** A topic cluster is a content architecture in which a central pillar page covers a broad topic comprehensively, supported by a set of cluster pages covering r...
- **Opening sentence (238):** A topic cluster is a content architecture in which a central pillar page covers a broad topic comprehensively, supported by a set of cluster pages covering related subtopics in depth, all internally linked to each other and to the pillar.
- **Shipped (173):** A topic cluster is a content architecture in which a central pillar page covers a broad topic comprehensively, supported by cluster pages covering related subtopics in depth

### `zero-shot-learning.mdx`
- **Old (160):** Zero-shot learning is a machine learning paradigm in which a model performs tasks it was not explicitly trained on — relying on generalized knowledge from pr...
- **Opening sentence (204):** Zero-shot learning is a machine learning paradigm in which a model performs tasks it was not explicitly trained on — relying on generalized knowledge from pre-training to handle novel categories or tasks.
- **Shipped (171):** Zero-shot learning is a machine learning paradigm in which a model performs tasks it was never explicitly trained to do, relying on generalized knowledge from pre-training

---

## Full ledger (340)

### `above-the-fold-answer.mdx`  ·  A
- **Old (160):** An above-the-fold answer is a direct response to a query that appears within the first visible portion of a page — before the user scrolls — typically in the...
- **Candidate A (186):** An above-the-fold answer is a direct response to a query that appears within the first visible portion of a page typically in the opening paragraph or immediately below the main heading.
- **Candidate B (138):** An above-the-fold answer is a direct response to a query that appears within the first visible portion of a page — before the user scrolls
- **Shipped (186):** An above-the-fold answer is a direct response to a query that appears within the first visible portion of a page typically in the opening paragraph or immediately below the main heading.
- **Why:** Candidate A (paired-interruption removal) states the complete definition; B would drop the predicate or sever the clause.

### `aeo.mdx`  ·  verbatim
- **Old (160):** AEO — Answer Engine Optimization — is the practice of structuring content to earn featured placement in AI-generated answer surfaces, voice assistants, and d...
- **Shipped (186):** AEO — Answer Engine Optimization — is the practice of structuring content to earn featured placement in AI-generated answer surfaces, voice assistants, and direct-answer search features.
- **Why:** Opening sentence ≤200; used verbatim.

### `agentic-search.mdx`  ·  A
- **Old (160):** Agentic search is a mode of AI-powered information retrieval in which an AI agent autonomously conducts multi-step research — breaking a complex query into s...
- **Candidate A (180):** Agentic search is a mode of AI-powered information retrieval in which an AI agent autonomously conducts multi-step research rather than returning a single answer to a single query.
- **Candidate B (123):** Agentic search is a mode of AI-powered information retrieval in which an AI agent autonomously conducts multi-step research
- **Shipped (180):** Agentic search is a mode of AI-powered information retrieval in which an AI agent autonomously conducts multi-step research rather than returning a single answer to a single query.
- **Why:** Candidate A (paired-interruption removal) states the complete definition; B would drop the predicate or sever the clause.

### `agentic-seo.mdx`  ·  B
- **Old (160):** Agentic SEO is the practice of optimizing content, entity signals, and digital infrastructure to be discoverable and citable by AI agents conducting autonomo...
- **Candidate B (179):** Agentic SEO is the practice of optimizing content, entity signals, and digital infrastructure to be discoverable and citable by AI agents conducting autonomous multi-step research
- **Shipped (179):** Agentic SEO is the practice of optimizing content, entity signals, and digital infrastructure to be discoverable and citable by AI agents conducting autonomous multi-step research
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `ai-agent-discoverability.mdx`  ·  B
- **Old (160):** AI agent discoverability is the degree to which a brand's content, entity signals, and digital infrastructure are accessible and legible to AI agents — auton...
- **Candidate A (237):** AI agent discoverability is the degree to which a brand's content, entity signals, and digital infrastructure are accessible and legible to AI agents as distinct from human-facing discoverability or single-turn AI search discoverability.
- **Candidate B (149):** AI agent discoverability is the degree to which a brand's content, entity signals, and digital infrastructure are accessible and legible to AI agents
- **Shipped (149):** AI agent discoverability is the degree to which a brand's content, entity signals, and digital infrastructure are accessible and legible to AI agents
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `ai-brand-ambassador.mdx`  ·  B
- **Old (160):** An AI brand ambassador is a brand's deliberate strategy of ensuring that AI systems consistently represent, recommend, and characterize the brand positively ...
- **Candidate B (180):** An AI brand ambassador is a brand's deliberate strategy of ensuring that AI systems consistently represent, recommend, and characterize the brand positively across relevant queries
- **Shipped (180):** An AI brand ambassador is a brand's deliberate strategy of ensuring that AI systems consistently represent, recommend, and characterize the brand positively across relevant queries
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `ai-brand-score.mdx`  ·  B
- **Old (160):** AI brand score is a composite metric that measures a brand's overall AI search presence — aggregating citation rate, citation accuracy, citation sentiment, c...
- **Candidate B (87):** AI brand score is a composite metric that measures a brand's overall AI search presence
- **Shipped (87):** AI brand score is a composite metric that measures a brand's overall AI search presence
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `ai-citation-audit.mdx`  ·  B
- **Old (160):** An AI citation audit is a systematic evaluation of how a brand is currently represented across AI search platforms — what is being said about it, which sourc...
- **Candidate B (114):** An AI citation audit is a systematic evaluation of how a brand is currently represented across AI search platforms
- **Shipped (114):** An AI citation audit is a systematic evaluation of how a brand is currently represented across AI search platforms
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `ai-citation-monitoring.mdx`  ·  B
- **Old (160):** AI citation monitoring is the ongoing practice of tracking a brand's presence and characterization in AI-generated responses over time — measuring changes in...
- **Candidate B (134):** AI citation monitoring is the ongoing practice of tracking a brand's presence and characterization in AI-generated responses over time
- **Shipped (134):** AI citation monitoring is the ongoing practice of tracking a brand's presence and characterization in AI-generated responses over time
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `ai-citation-strategy.mdx`  ·  B
- **Old (160):** An AI citation strategy is a deliberate approach to earning references within AI-generated responses — combining content structure, authority signal building...
- **Candidate B (100):** An AI citation strategy is a deliberate approach to earning references within AI-generated responses
- **Shipped (100):** An AI citation strategy is a deliberate approach to earning references within AI-generated responses
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `ai-content-detection.mdx`  ·  verbatim
- **Old (160):** AI content detection refers to systems and techniques used to identify whether a piece of content was generated by an AI system rather than written by a huma...
- **Shipped (166):** AI content detection refers to systems and techniques used to identify whether a piece of content was generated by an AI system rather than written by a human author.
- **Why:** Opening sentence ≤200; used verbatim.

### `ai-crawler-accessibility.mdx`  ·  B
- **Old (160):** AI crawler accessibility is the degree to which a website's content is technically accessible to AI crawlers — determined by factors such as server-side rend...
- **Candidate B (108):** AI crawler accessibility is the degree to which a website's content is technically accessible to AI crawlers
- **Shipped (108):** AI crawler accessibility is the degree to which a website's content is technically accessible to AI crawlers
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `ai-discoverability.mdx`  ·  B
- **Old (160):** AI discoverability is the degree to which a brand's content, entity signals, and structured data are accessible and legible to AI crawlers and retrieval syst...
- **Candidate B (160):** AI discoverability is the degree to which a brand's content, entity signals, and structured data are accessible and legible to AI crawlers and retrieval systems
- **Shipped (160):** AI discoverability is the degree to which a brand's content, entity signals, and structured data are accessible and legible to AI crawlers and retrieval systems
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `ai-first-indexing.mdx`  ·  B
- **Old (160):** AI-first indexing is the practice of designing and structuring web content with AI crawler accessibility and retrieval optimization as the primary technical ...
- **Candidate B (168):** AI-first indexing is the practice of designing and structuring web content with AI crawler accessibility and retrieval optimization as the primary technical requirement
- **Shipped (168):** AI-first indexing is the practice of designing and structuring web content with AI crawler accessibility and retrieval optimization as the primary technical requirement
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `ai-generated-answer.mdx`  ·  B
- **Old (160):** An AI-generated answer is a synthesized response produced by a generative AI system in reply to a user query — drawing from multiple indexed sources, trainin...
- **Candidate B (108):** An AI-generated answer is a synthesized response produced by a generative AI system in reply to a user query
- **Shipped (108):** An AI-generated answer is a synthesized response produced by a generative AI system in reply to a user query
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `ai-mention-tracking.mdx`  ·  B
- **Old (160):** AI mention tracking is the practice of monitoring when and how a brand is referenced across AI-generated content, AI search responses, and AI-assisted platfo...
- **Candidate B (160):** AI mention tracking is the practice of monitoring when and how a brand is referenced across AI-generated content, AI search responses, and AI-assisted platforms
- **Shipped (160):** AI mention tracking is the practice of monitoring when and how a brand is referenced across AI-generated content, AI search responses, and AI-assisted platforms
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `ai-search-ecosystem.mdx`  ·  B
- **Old (160):** The AI search ecosystem is the network of platforms, models, retrieval systems, and interfaces through which users now discover information — including ChatG...
- **Candidate B (139):** The AI search ecosystem is the network of platforms, models, retrieval systems, and interfaces through which users now discover information
- **Shipped (139):** The AI search ecosystem is the network of platforms, models, retrieval systems, and interfaces through which users now discover information
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `ai-search-optimization.mdx`  ·  hand-write
- **Old (158):** AI search optimization is the practice of optimizing a brand's visibility, accuracy, and citation frequency across AI-powered search and discovery surfaces...
- **Shipped (155):** AI search optimization is the practice of optimizing a brand's visibility, accuracy, and citation frequency across AI-powered search and discovery surfaces
- **Why:** Opening sentence >200 with only comma boundaries; hand-written to ≤200, reviewed and approved.

### `ai-search-visibility.mdx`  ·  B
- **Old (160):** AI search visibility is a quantitative measure of how frequently and prominently a brand or domain appears within AI-generated search responses across platfo...
- **Candidate B (160):** AI search visibility is a quantitative measure of how frequently and prominently a brand or domain appears within AI-generated search responses across platforms
- **Shipped (160):** AI search visibility is a quantitative measure of how frequently and prominently a brand or domain appears within AI-generated search responses across platforms
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `ai-share-of-voice.mdx`  ·  B
- **Old (160):** AI share of voice is a brand's proportional presence in AI-generated responses within a given topic area or competitive set — measured as the percentage of r...
- **Candidate B (123):** AI share of voice is a brand's proportional presence in AI-generated responses within a given topic area or competitive set
- **Shipped (123):** AI share of voice is a brand's proportional presence in AI-generated responses within a given topic area or competitive set
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `ai-traffic.mdx`  ·  B
- **Old (160):** AI traffic is the website visits generated by users clicking links within AI-generated responses — including citations in AI Overviews, source links in Perpl...
- **Candidate B (96):** AI traffic is the website visits generated by users clicking links within AI-generated responses
- **Shipped (96):** AI traffic is the website visits generated by users clicking links within AI-generated responses
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `ai-visibility-score.mdx`  ·  verbatim
- **Old (160):** An AI visibility score is a composite metric that benchmarks a brand's frequency of appearance and prominence across AI search platforms such as ChatGPT and ...
- **Shipped (168):** An AI visibility score is a composite metric that benchmarks a brand's frequency of appearance and prominence across AI search platforms such as ChatGPT and Perplexity.
- **Why:** Opening sentence ≤200; used verbatim.

### `algorithmic-feed-vs-search-feed.mdx`  ·  verbatim
- **Old (160):** An algorithmic feed is a social platform's default content stream — populated by the platform's recommendation system based on user behavior, engagement sign...
- **Shipped (185):** An algorithmic feed is a social platform's default content stream — populated by the platform's recommendation system based on user behavior, engagement signals, and predicted interest.
- **Why:** Opening sentence ≤200; used verbatim.

### `aloha-economy.mdx`  ·  hand-write
- **Old (160):** The aloha economy refers to Hawaii's distinctive economic character — shaped by tourism, military presence, agriculture, small business density, and a cultur...
- **Shipped (172):** The aloha economy is Hawaii's distinctive economic character, shaped by tourism, military presence, agriculture, small-business density, and a cultural ethos of hospitality
- **Why:** Opening sentence >200 with only comma boundaries; hand-written to ≤200, reviewed and approved.

### `anchor-content.mdx`  ·  B
- **Old (160):** Anchor content is a substantial, definitive piece of content on a specific topic — typically a comprehensive guide, research report, or authoritative explain...
- **Candidate A (214):** Anchor content is a substantial, definitive piece of content on a specific topic that serves as the primary reference point for that topic within a brand's content ecosystem and links to supporting cluster content.
- **Candidate B (159):** Anchor content is a substantial, definitive piece of content on a specific topic — typically a comprehensive guide, research report, or authoritative explainer
- **Shipped (159):** Anchor content is a substantial, definitive piece of content on a specific topic — typically a comprehensive guide, research report, or authoritative explainer
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `annual-marketing-plan.mdx`  ·  verbatim
- **Old (160):** An annual marketing plan is a documented strategy outlining a company's marketing objectives, budget allocation, channel mix, campaign calendar, and performa...
- **Shipped (194):** An annual marketing plan is a documented strategy outlining a company's marketing objectives, budget allocation, channel mix, campaign calendar, and performance benchmarks for a 12-month period.
- **Why:** Opening sentence ≤200; used verbatim.

### `answer-box.mdx`  ·  B
- **Old (160):** An answer box is a featured snippet format in which Google displays a direct answer to a query at the top of the SERP — often sourced from a single page or t...
- **Candidate B (117):** An answer box is a featured snippet format in which Google displays a direct answer to a query at the top of the SERP
- **Shipped (117):** An answer box is a featured snippet format in which Google displays a direct answer to a query at the top of the SERP
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `answer-engine-ranking.mdx`  ·  B
- **Old (160):** Answer engine ranking is a brand's relative position and prominence in AI-generated answer surfaces — measured by how frequently, how prominently, and in wha...
- **Candidate B (99):** Answer engine ranking is a brand's relative position and prominence in AI-generated answer surfaces
- **Shipped (99):** Answer engine ranking is a brand's relative position and prominence in AI-generated answer surfaces
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `answer-first-formatting.mdx`  ·  verbatim
- **Old (160):** Answer-first formatting is a content structure in which the direct answer to a question appears in the opening sentence or paragraph, before any context, bac...
- **Shipped (183):** Answer-first formatting is a content structure in which the direct answer to a question appears in the opening sentence or paragraph, before any context, background, or qualification.
- **Why:** Opening sentence ≤200; used verbatim.

### `answer-layer.mdx`  ·  A
- **Old (160):** The answer layer is the emerging AI-generated response surface that appears between a user's query and traditional search results — including AI Overviews, A...
- **Candidate A (199):** The answer layer is the emerging AI-generated response surface that appears between a user's query and traditional search results that answers queries directly rather than directing users to sources.
- **Candidate B (129):** The answer layer is the emerging AI-generated response surface that appears between a user's query and traditional search results
- **Shipped (199):** The answer layer is the emerging AI-generated response surface that appears between a user's query and traditional search results that answers queries directly rather than directing users to sources.
- **Why:** Candidate A (paired-interruption removal) states the complete definition; B would drop the predicate or sever the clause.

### `answer-snippet.mdx`  ·  verbatim
- **Old (160):** An answer snippet is a concise, self-contained passage within a web page that directly answers a specific question — optimized for extraction by AI systems a...
- **Shipped (187):** An answer snippet is a concise, self-contained passage within a web page that directly answers a specific question — optimized for extraction by AI systems and featured snippet selection.
- **Why:** Opening sentence ≤200; used verbatim.

### `atomic-content-unit.mdx`  ·  B
- **Old (160):** An atomic content unit is the smallest self-contained piece of content that can stand alone, answer a specific question, and be extracted or cited independen...
- **Candidate B (160):** An atomic content unit is the smallest self-contained piece of content that can stand alone, answer a specific question, and be extracted or cited independently
- **Shipped (160):** An atomic content unit is the smallest self-contained piece of content that can stand alone, answer a specific question, and be extracted or cited independently
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `attributed-citation.mdx`  ·  verbatim
- **Old (160):** An attributed citation is a direct reference to a source URL or brand name within an AI-generated response — explicitly naming the source and often providing...
- **Shipped (165):** An attributed citation is a direct reference to a source URL or brand name within an AI-generated response — explicitly naming the source and often providing a link.
- **Why:** Opening sentence ≤200; used verbatim.

### `audience-research.mdx`  ·  verbatim
- **Old (160):** Audience research is the systematic process of identifying where, how, and on what platforms a target audience searches for information, consumes content, an...
- **Shipped (174):** Audience research is the systematic process of identifying where, how, and on what platforms a target audience searches for information, consumes content, and forms opinions.
- **Why:** Opening sentence ≤200; used verbatim.

### `author-authority.mdx`  ·  verbatim
- **Old (160):** Author authority is the credibility and expertise attributed to a content creator — used by search engines and AI systems as a signal of content trustworthin...
- **Shipped (161):** Author authority is the credibility and expertise attributed to a content creator — used by search engines and AI systems as a signal of content trustworthiness.
- **Why:** Opening sentence ≤200; used verbatim.

### `authoritativeness-signal.mdx`  ·  A
- **Old (160):** An authoritativeness signal is any measurable indicator — such as backlinks, citations, reviews, structured data, or Wikipedia presence — that communicates t...
- **Candidate A (162):** An authoritativeness signal is any measurable indicator that communicates to search engines and AI systems that a source is credible and expert within its domain.
- **Candidate B (135):** An authoritativeness signal is any measurable indicator — such as backlinks, citations, reviews, structured data, or Wikipedia presence
- **Shipped (162):** An authoritativeness signal is any measurable indicator that communicates to search engines and AI systems that a source is credible and expert within its domain.
- **Why:** Candidate A (paired-interruption removal) states the complete definition; B would drop the predicate or sever the clause.

### `authority-signal.mdx`  ·  B
- **Old (160):** An authority signal is any piece of evidence that indicates a source, entity, or piece of content is credible and trustworthy within its domain — including i...
- **Candidate B (143):** An authority signal is any piece of evidence that indicates a source, entity, or piece of content is credible and trustworthy within its domain
- **Shipped (143):** An authority signal is any piece of evidence that indicates a source, entity, or piece of content is credible and trustworthy within its domain
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `brand-architecture.mdx`  ·  B
- **Old (160):** Brand architecture is the structured relationship between a company's master brand, sub-brands, product lines, and service offerings — defining how they rela...
- **Candidate B (132):** Brand architecture is the structured relationship between a company's master brand, sub-brands, product lines, and service offerings
- **Shipped (132):** Brand architecture is the structured relationship between a company's master brand, sub-brands, product lines, and service offerings
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `brand-authority.mdx`  ·  B
- **Old (160):** Brand authority is the perceived credibility and expertise of a brand in its domain — built through consistent content, citations, and third-party endorsemen...
- **Candidate B (83):** Brand authority is the perceived credibility and expertise of a brand in its domain
- **Shipped (83):** Brand authority is the perceived credibility and expertise of a brand in its domain
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `brand-citation-rate.mdx`  ·  B
- **Old (160):** Brand citation rate is the percentage of relevant AI-generated responses to a defined set of queries in which a brand is cited — calculated as citations divi...
- **Candidate B (126):** Brand citation rate is the percentage of relevant AI-generated responses to a defined set of queries in which a brand is cited
- **Shipped (126):** Brand citation rate is the percentage of relevant AI-generated responses to a defined set of queries in which a brand is cited
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `brand-coverage-gap.mdx`  ·  B
- **Old (160):** A brand coverage gap is a topic, query type, or subject area relevant to a brand's domain where the brand has no content, no entity signal, and no AI citatio...
- **Candidate B (167):** A brand coverage gap is a topic, query type, or subject area relevant to a brand's domain where the brand has no content, no entity signal, and no AI citation presence
- **Shipped (167):** A brand coverage gap is a topic, query type, or subject area relevant to a brand's domain where the brand has no content, no entity signal, and no AI citation presence
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `brand-disambiguation.mdx`  ·  B
- **Old (160):** Brand disambiguation is the practice of ensuring that AI systems and knowledge graphs correctly distinguish a specific brand from other entities with similar...
- **Candidate B (163):** Brand disambiguation is the practice of ensuring that AI systems and knowledge graphs correctly distinguish a specific brand from other entities with similar names
- **Shipped (163):** Brand disambiguation is the practice of ensuring that AI systems and knowledge graphs correctly distinguish a specific brand from other entities with similar names
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `brand-entity.mdx`  ·  B
- **Old (160):** A brand entity is the structured representation of a brand as a distinct, identifiable object within a knowledge graph — linked to attributes such as locatio...
- **Candidate B (118):** A brand entity is the structured representation of a brand as a distinct, identifiable object within a knowledge graph
- **Shipped (118):** A brand entity is the structured representation of a brand as a distinct, identifiable object within a knowledge graph
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `brand-equity.mdx`  ·  B
- **Old (160):** Brand equity is the commercial value derived from consumer perception of a brand — including the premium price it can command, the loyalty it generates, and ...
- **Candidate B (80):** Brand equity is the commercial value derived from consumer perception of a brand
- **Shipped (80):** Brand equity is the commercial value derived from consumer perception of a brand
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `brand-footprint.mdx`  ·  B
- **Old (160):** Brand footprint is the aggregate of a brand's structured and unstructured presence across the web — its website, social profiles, directory listings, third-p...
- **Candidate B (97):** Brand footprint is the aggregate of a brand's structured and unstructured presence across the web
- **Shipped (97):** Brand footprint is the aggregate of a brand's structured and unstructured presence across the web
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `brand-grounding.mdx`  ·  B
- **Old (160):** Brand grounding is the practice of providing AI systems with accurate, structured, verified information about a brand — through schema markup, Wikidata entri...
- **Candidate A (263):** Brand grounding is the practice of providing AI systems with accurate, structured, verified information about a brand so that AI-generated responses about the brand are anchored in factual data rather than generated from incomplete or inaccurate training signals.
- **Candidate B (117):** Brand grounding is the practice of providing AI systems with accurate, structured, verified information about a brand
- **Shipped (117):** Brand grounding is the practice of providing AI systems with accurate, structured, verified information about a brand
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `brand-hierarchy.mdx`  ·  B
- **Old (160):** Brand hierarchy is the structured relationship between a company's brand tiers — master brand, endorsed brands, sub-brands, and product brands — defining the...
- **Candidate A (219):** Brand hierarchy is the structured relationship between a company's brand tiers defining the visual and verbal rules for how each tier is expressed and how they relate to each other in communication and identity systems.
- **Candidate B (142):** Brand hierarchy is the structured relationship between a company's brand tiers — master brand, endorsed brands, sub-brands, and product brands
- **Shipped (142):** Brand hierarchy is the structured relationship between a company's brand tiers — master brand, endorsed brands, sub-brands, and product brands
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `brand-memory-llm.mdx`  ·  B
- **Old (160):** LLM brand memory refers to the information about a brand that is encoded in a language model's weights during pre-training — the baseline knowledge the model...
- **Candidate B (122):** LLM brand memory refers to the information about a brand that is encoded in a language model's weights during pre-training
- **Shipped (122):** LLM brand memory refers to the information about a brand that is encoded in a language model's weights during pre-training
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `brand-narrative.mdx`  ·  B
- **Old (160):** A brand narrative is the cohesive story that defines what a company is, why it exists, who it serves, and what makes it distinct — expressed consistently acr...
- **Candidate B (128):** A brand narrative is the cohesive story that defines what a company is, why it exists, who it serves, and what makes it distinct
- **Shipped (128):** A brand narrative is the cohesive story that defines what a company is, why it exists, who it serves, and what makes it distinct
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `brand-positioning.mdx`  ·  B
- **Old (160):** Brand positioning is the deliberate definition of how a brand wants to be perceived relative to its competitors — the specific market space it occupies, the ...
- **Candidate B (111):** Brand positioning is the deliberate definition of how a brand wants to be perceived relative to its competitors
- **Shipped (111):** Brand positioning is the deliberate definition of how a brand wants to be perceived relative to its competitors
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `brand-retrieval-rate.mdx`  ·  B
- **Old (160):** Brand retrieval rate is the frequency with which a brand's content or entity is retrieved by AI systems when processing queries relevant to its domain — meas...
- **Candidate B (150):** Brand retrieval rate is the frequency with which a brand's content or entity is retrieved by AI systems when processing queries relevant to its domain
- **Shipped (150):** Brand retrieval rate is the frequency with which a brand's content or entity is retrieved by AI systems when processing queries relevant to its domain
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `brand-voice.mdx`  ·  B
- **Old (160):** Brand voice is the distinctive personality, tone, and style that characterizes all of a brand's written and spoken communications — making its content recogn...
- **Candidate B (129):** Brand voice is the distinctive personality, tone, and style that characterizes all of a brand's written and spoken communications
- **Shipped (129):** Brand voice is the distinctive personality, tone, and style that characterizes all of a brand's written and spoken communications
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `buyer-journey-mapping.mdx`  ·  B
- **Old (160):** Buyer journey mapping is the process of documenting the stages a potential customer moves through from initial awareness to purchase and beyond — identifying...
- **Candidate B (143):** Buyer journey mapping is the process of documenting the stages a potential customer moves through from initial awareness to purchase and beyond
- **Shipped (143):** Buyer journey mapping is the process of documenting the stages a potential customer moves through from initial awareness to purchase and beyond
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `cac.mdx`  ·  verbatim
- **Old (160):** Customer acquisition cost (CAC) is the total cost of acquiring a new customer — calculated by dividing total sales and marketing spend by the number of new c...
- **Shipped (193):** Customer acquisition cost (CAC) is the total cost of acquiring a new customer — calculated by dividing total sales and marketing spend by the number of new customers acquired in a given period.
- **Why:** Opening sentence ≤200; used verbatim.

### `canonicalization.mdx`  ·  verbatim
- **Old (160):** Canonicalization is the process of specifying the preferred URL version of a page using a canonical tag — preventing duplicate content issues and consolidati...
- **Shipped (197):** Canonicalization is the process of specifying the preferred URL version of a page using a canonical tag — preventing duplicate content issues and consolidating authority signals to the correct URL.
- **Why:** Opening sentence ≤200; used verbatim.

### `chain-of-thought-citation.mdx`  ·  B
- **Old (160):** Chain-of-thought citation is an emerging concept describing the behavior of AI systems that reason through multi-step problems — where the model cites differ...
- **Candidate B (126):** Chain-of-thought citation is an emerging concept describing the behavior of AI systems that reason through multi-step problems
- **Shipped (126):** Chain-of-thought citation is an emerging concept describing the behavior of AI systems that reason through multi-step problems
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `channel-mix.mdx`  ·  B
- **Old (160):** Channel mix is the combination of marketing channels a brand uses to reach its audience — including paid, earned, owned, and shared channels — and the alloca...
- **Candidate A (214):** Channel mix is the combination of marketing channels a brand uses to reach its audience and the allocation of budget and effort across them based on audience behavior, competitive dynamics, and business objectives.
- **Candidate B (140):** Channel mix is the combination of marketing channels a brand uses to reach its audience — including paid, earned, owned, and shared channels
- **Shipped (140):** Channel mix is the combination of marketing channels a brand uses to reach its audience — including paid, earned, owned, and shared channels
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `citable-claim.mdx`  ·  verbatim
- **Old (160):** A citable claim is a specific, verifiable statement within a piece of content that an AI system can extract, attribute to the source, and use as evidence in ...
- **Shipped (178):** A citable claim is a specific, verifiable statement within a piece of content that an AI system can extract, attribute to the source, and use as evidence in a generated response.
- **Why:** Opening sentence ≤200; used verbatim.

### `citation-architecture.mdx`  ·  B
- **Old (160):** Citation architecture is the deliberate design of a brand's content and entity ecosystem to maximize the density and diversity of AI citation opportunities —...
- **Candidate B (155):** Citation architecture is the deliberate design of a brand's content and entity ecosystem to maximize the density and diversity of AI citation opportunities
- **Shipped (155):** Citation architecture is the deliberate design of a brand's content and entity ecosystem to maximize the density and diversity of AI citation opportunities
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `citation-consistency.mdx`  ·  hand-write
- **Old (160):** Citation consistency is the degree to which a brand's AI citations accurately and uniformly represent the same core facts, attributes, and positioning across...
- **Shipped (189):** Citation consistency is the degree to which a brand's AI citations uniformly represent the same core facts, attributes, and positioning across different queries, platforms, and time periods
- **Why:** Opening sentence >200 with only comma boundaries; hand-written to ≤200, reviewed and approved.

### `citation-decay.mdx`  ·  B
- **Old (160):** Citation decay is the gradual loss of AI citation presence over time — as training data ages, newer sources displace older ones, or a brand's content becomes...
- **Candidate B (68):** Citation decay is the gradual loss of AI citation presence over time
- **Shipped (68):** Citation decay is the gradual loss of AI citation presence over time
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `citation-gap.mdx`  ·  B
- **Old (160):** A citation gap is a relevant query or topic area in which a brand is not being cited despite having legitimate authority and relevant content — a gap between...
- **Candidate B (141):** A citation gap is a relevant query or topic area in which a brand is not being cited despite having legitimate authority and relevant content
- **Shipped (141):** A citation gap is a relevant query or topic area in which a brand is not being cited despite having legitimate authority and relevant content
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `citation-injection-risk.mdx`  ·  hand-write
- **Old (160):** Citation injection risk is the vulnerability of AI retrieval systems to the introduction of low-quality, manipulative, or synthetic content that earns AI cit...
- **Shipped (195):** Citation injection risk is the vulnerability of AI retrieval systems to manipulative or synthetic content that earns AI citations by gaming retrieval signals rather than through genuine authority
- **Why:** Opening sentence >200 with only comma boundaries; hand-written to ≤200, reviewed and approved.

### `citation-opportunity.mdx`  ·  A
- **Old (160):** A citation opportunity is a specific query, topic, or context in which a brand could plausibly be cited by AI systems — based on the brand's actual expertise...
- **Candidate A (143):** A citation opportunity is a specific query, topic, or context in which a brand could plausibly be cited by AI systems but is not yet appearing.
- **Candidate B (117):** A citation opportunity is a specific query, topic, or context in which a brand could plausibly be cited by AI systems
- **Shipped (143):** A citation opportunity is a specific query, topic, or context in which a brand could plausibly be cited by AI systems but is not yet appearing.
- **Why:** Candidate A (paired-interruption removal) states the complete definition; B would drop the predicate or sever the clause.

### `citation-ready-content.mdx`  ·  verbatim
- **Old (160):** Citation-ready content is content structured so that AI retrieval systems can extract, cite, and attribute it to a specific source within an AI-generated res...
- **Shipped (163):** Citation-ready content is content structured so that AI retrieval systems can extract, cite, and attribute it to a specific source within an AI-generated response.
- **Why:** Opening sentence ≤200; used verbatim.

### `citation-velocity.mdx`  ·  B
- **Old (160):** Citation velocity is the rate at which a brand's AI citation presence is growing or declining — measured by changes in citation rate, citation breadth, and c...
- **Candidate B (93):** Citation velocity is the rate at which a brand's AI citation presence is growing or declining
- **Shipped (93):** Citation velocity is the rate at which a brand's AI citation presence is growing or declining
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `claudebot.mdx`  ·  verbatim
- **Old (160):** ClaudeBot is Anthropic's web crawler primarily used to gather training data for its AI models, which contributes to the content available for Claude AI respo...
- **Shipped (162):** ClaudeBot is Anthropic's web crawler primarily used to gather training data for its AI models, which contributes to the content available for Claude AI responses.
- **Why:** Opening sentence ≤200; used verbatim.

### `clickstream-data.mdx`  ·  verbatim
- **Old (160):** Clickstream data is the record of a user's sequential interactions with digital content — the pages visited, links clicked, time spent, and paths taken throu...
- **Shipped (188):** Clickstream data is the record of a user's sequential interactions with digital content — the pages visited, links clicked, time spent, and paths taken through a website or across the web.
- **Why:** Opening sentence ≤200; used verbatim.

### `cmo-as-a-service.mdx`  ·  B
- **Old (160):** CMO-as-a-Service is a delivery model in which senior marketing leadership is provided on a flexible, subscription or retainer basis — giving companies access...
- **Candidate B (131):** CMO-as-a-Service is a delivery model in which senior marketing leadership is provided on a flexible, subscription or retainer basis
- **Shipped (131):** CMO-as-a-Service is a delivery model in which senior marketing leadership is provided on a flexible, subscription or retainer basis
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `comment-signal.mdx`  ·  verbatim
- **Old (160):** A comment signal is the engagement and content generated in the comments section of a social media post — including questions, answers, additional informatio...
- **Shipped (179):** A comment signal is the engagement and content generated in the comments section of a social media post — including questions, answers, additional information, and user reactions.
- **Why:** Opening sentence ≤200; used verbatim.

### `community-generated-content.mdx`  ·  A
- **Old (160):** Community-generated content is content produced by a brand's audience, customers, or community members — including reviews, forum posts, social mentions, Q&A...
- **Candidate A (177):** Community-generated content is content produced by a brand's audience, customers, or community members that references the brand or its products without direct brand authorship.
- **Candidate B (191):** Community-generated content is content produced by a brand's audience, customers, or community members — including reviews, forum posts, social mentions, Q&A responses, and user-created media
- **Shipped (177):** Community-generated content is content produced by a brand's audience, customers, or community members that references the brand or its products without direct brand authorship.
- **Why:** Candidate A (paired-interruption removal) states the complete definition; B would drop the predicate or sever the clause.

### `competitive-citation-gap.mdx`  ·  hand-write
- **Old (160):** A competitive citation gap is a query or topic area in which a competitor is being cited by AI systems but the brand is not — indicating that the competitor ...
- **Shipped (128):** A competitive citation gap is a query or topic area where a competitor is cited by AI systems but the brand is not yet appearing
- **Why:** Opening sentence >200 with only comma boundaries; hand-written to ≤200, reviewed and approved.

### `competitive-displacement-ai.mdx`  ·  hand-write
- **Old (160):** Competitive displacement in AI search occurs when a competitor's content, entity signals, or retrieval presence causes an AI system to cite the competitor in...
- **Shipped (184):** Competitive displacement in AI search occurs when a competitor's content or entity signals cause an AI system to cite the competitor for queries where the brand should plausibly appear
- **Why:** Hand-write, reviewed. Dropped one enumeration item ("or retrieval presence") to preserve the "should plausibly appear" hedge rather than the cap-driven cut that asserted entitlement. 184 chars.

### `consolidated-entity-profile.mdx`  ·  B
- **Old (160):** A consolidated entity profile is a complete, consistent, and cross-referenced set of structured data about an entity — integrating information from the brand...
- **Candidate B (116):** A consolidated entity profile is a complete, consistent, and cross-referenced set of structured data about an entity
- **Shipped (116):** A consolidated entity profile is a complete, consistent, and cross-referenced set of structured data about an entity
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `content-accessibility.mdx`  ·  B
- **Old (160):** Content accessibility, in the AI SEO context, is the degree to which a page's content is available in the initial HTML response — without requiring JavaScrip...
- **Candidate A (168):** Content accessibility, in the AI SEO context, is the degree to which a page's content is available in the initial HTML response ensuring AI crawlers can fully index it.
- **Candidate B (168):** Content accessibility, in the AI SEO context, is the degree to which a page's content is available in the initial HTML response — without requiring JavaScript execution
- **Shipped (168):** Content accessibility, in the AI SEO context, is the degree to which a page's content is available in the initial HTML response — without requiring JavaScript execution
- **Why:** Both valid. Chose B: keeps "without requiring JavaScript execution"; A drops it and reads danglingly.

### `content-calendar.mdx`  ·  B
- **Old (160):** A content calendar is a planning document that schedules content production and publication across channels — specifying topics, formats, publication dates, ...
- **Candidate B (107):** A content calendar is a planning document that schedules content production and publication across channels
- **Shipped (107):** A content calendar is a planning document that schedules content production and publication across channels
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `content-depth.mdx`  ·  B
- **Old (160):** Content depth is the degree to which a piece of content thoroughly covers a topic — addressing not just the surface-level question but the sub-questions, edg...
- **Candidate B (81):** Content depth is the degree to which a piece of content thoroughly covers a topic
- **Shipped (81):** Content depth is the degree to which a piece of content thoroughly covers a topic
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `content-extractability.mdx`  ·  hand-write
- **Old (160):** Content extractability is the degree to which specific facts, answers, and claims within a piece of content can be identified, isolated, and reused by AI sys...
- **Shipped (195):** Content extractability is the degree to which specific facts, answers, and claims within a piece of content can be identified, isolated, and reused by AI systems without the full document context
- **Why:** Opening sentence >200 with only comma boundaries; hand-written to ≤200, reviewed and approved.

### `content-gap-analysis.mdx`  ·  hand-write
- **Old (160):** Content gap analysis is the process of identifying topics, subtopics, or query types that competitors cover but a given brand does not — used to expand topic...
- **Shipped (142):** Content gap analysis is the process of identifying topics, subtopics, or query types that competitors cover but the brand does not yet address
- **Why:** Opening sentence >200 with only comma boundaries; hand-written to ≤200, reviewed and approved.

### `content-hub.mdx`  ·  A
- **Old (160):** A content hub is a centralized section of a website that organizes all content related to a specific topic — including pillar pages, cluster articles, resear...
- **Candidate A (154):** A content hub is a centralized section of a website that organizes all content related to a specific topic into a structured, interconnected architecture.
- **Candidate B (106):** A content hub is a centralized section of a website that organizes all content related to a specific topic
- **Shipped (154):** A content hub is a centralized section of a website that organizes all content related to a specific topic into a structured, interconnected architecture.
- **Why:** Candidate A (paired-interruption removal) states the complete definition; B would drop the predicate or sever the clause.

### `content-moat.mdx`  ·  B
- **Old (160):** A content moat is a body of content that is difficult for competitors to replicate — typically because it is based on proprietary data, first-hand experience...
- **Candidate B (82):** A content moat is a body of content that is difficult for competitors to replicate
- **Shipped (82):** A content moat is a body of content that is difficult for competitors to replicate
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `context-map.mdx`  ·  B
- **Old (179):** A context map is Plate Lunch Collective's proprietary diagnostic that audits how AI systems currently represent a brand — what they say about it, what sources they draw from, w...
- **Candidate B (119):** A context map is Plate Lunch Collective's proprietary diagnostic that audits how AI systems currently represent a brand
- **Shipped (119):** A context map is Plate Lunch Collective's proprietary diagnostic that audits how AI systems currently represent a brand
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `context-poisoning.mdx`  ·  B
- **Old (160):** Context poisoning is a form of adversarial attack on AI systems in which malicious content is injected into the retrieval context — through prompt injection ...
- **Candidate A (203):** Context poisoning is a form of adversarial attack on AI systems in which malicious content is injected into the retrieval context to cause the AI system to generate false, misleading, or harmful outputs.
- **Candidate B (129):** Context poisoning is a form of adversarial attack on AI systems in which malicious content is injected into the retrieval context
- **Shipped (129):** Context poisoning is a form of adversarial attack on AI systems in which malicious content is injected into the retrieval context
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `conversational-ai.mdx`  ·  B
- **Old (160):** Conversational AI refers to AI systems designed to engage in natural-language dialogue with users — including chatbots, AI search assistants, and voice inter...
- **Candidate B (97):** Conversational AI refers to AI systems designed to engage in natural-language dialogue with users
- **Shipped (97):** Conversational AI refers to AI systems designed to engage in natural-language dialogue with users
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `conversational-query.mdx`  ·  verbatim
- **Old (160):** A conversational query is a natural-language question or multi-word prompt submitted to an AI search tool — as opposed to the short keyword queries typical o...
- **Shipped (178):** A conversational query is a natural-language question or multi-word prompt submitted to an AI search tool — as opposed to the short keyword queries typical of traditional search.
- **Why:** Opening sentence ≤200; used verbatim.

### `conversion-funnel.mdx`  ·  verbatim
- **Old (160):** A conversion funnel is the modeled sequence of steps a prospect takes from first awareness of a brand to completing a desired action — typically a purchase, ...
- **Shipped (182):** A conversion funnel is the modeled sequence of steps a prospect takes from first awareness of a brand to completing a desired action — typically a purchase, inquiry, or subscription.
- **Why:** Opening sentence ≤200; used verbatim.

### `core-web-vitals.mdx`  ·  B
- **Old (160):** Core Web Vitals are Google's set of user experience metrics — Largest Contentful Paint (LCP), Interaction to Next Paint (INP), and Cumulative Layout Shift (C...
- **Candidate A (101):** Core Web Vitals are Google's set of user experience metrics used as ranking signals in Google Search.
- **Candidate B (160):** Core Web Vitals are Google's set of user experience metrics — Largest Contentful Paint (LCP), Interaction to Next Paint (INP), and Cumulative Layout Shift (CLS)
- **Shipped (160):** Core Web Vitals are Google's set of user experience metrics — Largest Contentful Paint (LCP), Interaction to Next Paint (INP), and Cumulative Layout Shift (CLS)
- **Why:** Both valid. Chose B: A discards the three named metrics (LCP/INP/CLS), the substance; B names them.

### `corpus-ready-content.mdx`  ·  B
- **Old (160):** Corpus-ready content is content structured and written to function well as training and retrieval data for AI systems — factually dense, clearly attributed, ...
- **Candidate B (117):** Corpus-ready content is content structured and written to function well as training and retrieval data for AI systems
- **Shipped (117):** Corpus-ready content is content structured and written to function well as training and retrieval data for AI systems
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `cosine-similarity.mdx`  ·  B
- **Old (160):** Cosine similarity is a mathematical measure of the angle between two vectors in a high-dimensional space — used by AI retrieval systems to determine how sema...
- **Candidate B (104):** Cosine similarity is a mathematical measure of the angle between two vectors in a high-dimensional space
- **Shipped (104):** Cosine similarity is a mathematical measure of the angle between two vectors in a high-dimensional space
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `creator-authority.mdx`  ·  B
- **Old (160):** Creator authority is the credibility and influence a content creator has established within a specific topic domain on a social platform — built from consist...
- **Candidate B (136):** Creator authority is the credibility and influence a content creator has established within a specific topic domain on a social platform
- **Shipped (136):** Creator authority is the credibility and influence a content creator has established within a specific topic domain on a social platform
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `creator-entity.mdx`  ·  verbatim
- **Old (160):** A creator entity is the structured representation of a content creator — their identity, topic domain, platform presence, and associated content — within an ...
- **Shipped (185):** A creator entity is the structured representation of a content creator — their identity, topic domain, platform presence, and associated content — within an AI system's knowledge model.
- **Why:** Opening sentence ≤200; used verbatim.

### `dark-citation.mdx`  ·  B
- **Old (160):** A dark citation is a reference to a brand or its content within an AI-generated response that does not include an explicit attribution or visible citation li...
- **Candidate B (159):** A dark citation is a reference to a brand or its content within an AI-generated response that does not include an explicit attribution or visible citation link
- **Shipped (159):** A dark citation is a reference to a brand or its content within an AI-generated response that does not include an explicit attribution or visible citation link
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `dark-social.mdx`  ·  A
- **Old (160):** Dark social refers to social sharing and content consumption that occurs in private or encrypted channels — direct messages, private groups, email forwards, ...
- **Candidate A (178):** Dark social refers to social sharing and content consumption that occurs in private or encrypted channels where traffic and attribution are invisible to standard analytics tools.
- **Candidate B (175):** Dark social refers to social sharing and content consumption that occurs in private or encrypted channels — direct messages, private groups, email forwards, and messaging apps
- **Shipped (178):** Dark social refers to social sharing and content consumption that occurs in private or encrypted channels where traffic and attribution are invisible to standard analytics tools.
- **Why:** Candidate A (paired-interruption removal) states the complete definition; B would drop the predicate or sever the clause.

### `data-sanitation.mdx`  ·  verbatim
- **Old (160):** Data sanitation is the process of auditing and correcting inconsistent, conflicting, or outdated brand information across digital sources before AI systems i...
- **Shipped (166):** Data sanitation is the process of auditing and correcting inconsistent, conflicting, or outdated brand information across digital sources before AI systems ingest it.
- **Why:** Opening sentence ≤200; used verbatim.

### `declarative-content.mdx`  ·  verbatim
- **Old (160):** Declarative content is content structured around direct, unambiguous statements of fact — asserting what is true rather than hedging, contextualizing, or qua...
- **Shipped (194):** Declarative content is content structured around direct, unambiguous statements of fact — asserting what is true rather than hedging, contextualizing, or qualifying before committing to a claim.
- **Why:** Opening sentence ≤200; used verbatim.

### `deep-research.mdx`  ·  A
- **Old (160):** Deep research is an AI-assisted research mode in which a model autonomously conducts multi-step web searches — querying, reading, synthesizing, and iterating...
- **Candidate A (165):** Deep research is an AI-assisted research mode in which a model autonomously conducts multi-step web searches to produce a comprehensive answer to a complex question.
- **Candidate B (177):** Deep research is an AI-assisted research mode in which a model autonomously conducts multi-step web searches — querying, reading, synthesizing, and iterating across many sources
- **Shipped (165):** Deep research is an AI-assisted research mode in which a model autonomously conducts multi-step web searches to produce a comprehensive answer to a complex question.
- **Why:** Candidate A (paired-interruption removal) states the complete definition; B would drop the predicate or sever the clause.

### `deepseek.mdx`  ·  A
- **Old (160):** DeepSeek is a Chinese AI company that has developed a series of large language models — most notably DeepSeek-R1 — that have achieved performance comparable ...
- **Candidate A (196):** DeepSeek is a Chinese AI company that has developed a series of large language models that have achieved performance comparable to leading US models at significantly lower reported training costs.
- **Candidate B (112):** DeepSeek is a Chinese AI company that has developed a series of large language models — most notably DeepSeek-R1
- **Shipped (196):** DeepSeek is a Chinese AI company that has developed a series of large language models that have achieved performance comparable to leading US models at significantly lower reported training costs.
- **Why:** Candidate A (paired-interruption removal) states the complete definition; B would drop the predicate or sever the clause.

### `definition-first-writing.mdx`  ·  hand-write
- **Old (160):** Definition-first writing is a content approach in which a term, concept, or topic is defined clearly and completely at the start of the piece or section, bef...
- **Shipped (187):** Definition-first writing is a content approach in which a term, concept, or topic is defined clearly and completely at the start of the piece or section, before any elaboration or context
- **Why:** Opening sentence >200 with only comma boundaries; hand-written to ≤200, reviewed and approved.

### `demand-generation.mdx`  ·  B
- **Old (160):** Demand generation is the set of marketing activities designed to create awareness and interest in a brand's products or services among potential buyers who a...
- **Candidate B (195):** Demand generation is the set of marketing activities designed to create awareness and interest in a brand's products or services among potential buyers who are not yet actively seeking a solution
- **Shipped (195):** Demand generation is the set of marketing activities designed to create awareness and interest in a brand's products or services among potential buyers who are not yet actively seeking a solution
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `dense-retrieval.mdx`  ·  B
- **Old (160):** Dense retrieval is a method of information retrieval that uses neural network-generated embeddings to find semantically relevant content — as opposed to spar...
- **Candidate B (136):** Dense retrieval is a method of information retrieval that uses neural network-generated embeddings to find semantically relevant content
- **Shipped (136):** Dense retrieval is a method of information retrieval that uses neural network-generated embeddings to find semantically relevant content
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `destination-marketing.mdx`  ·  verbatim
- **Old (160):** Destination marketing is the practice of promoting a geographic location — a city, region, island, or country — as a desirable destination for travel, busine...
- **Shipped (175):** Destination marketing is the practice of promoting a geographic location — a city, region, island, or country — as a desirable destination for travel, business, or relocation.
- **Why:** Opening sentence ≤200; used verbatim.

### `direct-answer-format.mdx`  ·  verbatim
- **Old (160):** Direct answer format is a content structure in which a question is immediately followed by a complete, standalone answer — with no preamble, qualification, o...
- **Shipped (193):** Direct answer format is a content structure in which a question is immediately followed by a complete, standalone answer — with no preamble, qualification, or scene-setting before the response.
- **Why:** Opening sentence ≤200; used verbatim.

### `disambiguation-page.mdx`  ·  A
- **Old (160):** A disambiguation page is a page — typically on Wikipedia or within a knowledge system — that distinguishes between multiple entities that share the same or s...
- **Candidate A (175):** A disambiguation page is a page that distinguishes between multiple entities that share the same or similar names, directing users and AI systems to the correct entity record.
- **Candidate B (85):** A disambiguation page is a page — typically on Wikipedia or within a knowledge system
- **Shipped (175):** A disambiguation page is a page that distinguishes between multiple entities that share the same or similar names, directing users and AI systems to the correct entity record.
- **Why:** Candidate A (paired-interruption removal) states the complete definition; B would drop the predicate or sever the clause.

### `discovery-search.mdx`  ·  B
- **Old (160):** Discovery search is a mode of search behavior in which users explore a topic without a specific destination in mind — browsing for inspiration, options, or a...
- **Candidate B (115):** Discovery search is a mode of search behavior in which users explore a topic without a specific destination in mind
- **Shipped (115):** Discovery search is a mode of search behavior in which users explore a topic without a specific destination in mind
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `discovery-surface.mdx`  ·  verbatim
- **Old (160):** A discovery surface is any platform or interface — search engine, AI assistant, social network, or marketplace — through which users can find and access a br...
- **Shipped (181):** A discovery surface is any platform or interface — search engine, AI assistant, social network, or marketplace — through which users can find and access a brand or piece of content.
- **Why:** Opening sentence ≤200; used verbatim.

### `document-embedding.mdx`  ·  A
- **Old (160):** Document embedding is the process of converting an entire document — as opposed to individual words or sentences — into a single numerical vector that repres...
- **Candidate A (157):** Document embedding is the process of converting an entire document into a single numerical vector that represents the document's overall meaning and content.
- **Candidate B (112):** Document embedding is the process of converting an entire document — as opposed to individual words or sentences
- **Shipped (157):** Document embedding is the process of converting an entire document into a single numerical vector that represents the document's overall meaning and content.
- **Why:** Both valid. Chose A: A completes the definition; B severs the main clause before saying what it converts into.

### `domain-authority.mdx`  ·  hand-write
- **Old (160):** Domain Authority (DA) is a proprietary Moz metric scored from 1 to 100 that predicts how likely a domain is to rank in search results, based primarily on the...
- **Shipped (133):** Domain Authority (DA) is a proprietary Moz metric scored from 1 to 100 that predicts how likely a domain is to rank in search results
- **Why:** Opening sentence >200 with only comma boundaries; hand-written to ≤200, reviewed and approved.

### `domain-rating.mdx`  ·  verbatim
- **Old (160):** Domain Rating is Ahrefs' proprietary metric (scored 0–100) measuring the strength of a website's backlink profile relative to all other websites in the Ahref...
- **Shipped (168):** Domain Rating is Ahrefs' proprietary metric (scored 0–100) measuring the strength of a website's backlink profile relative to all other websites in the Ahrefs database.
- **Why:** Opening sentence ≤200; used verbatim.

### `editorial-authority.mdx`  ·  B
- **Old (160):** Editorial authority is the credibility a publication or brand earns through consistent, accurate, well-sourced content over time — the accumulated trust that...
- **Candidate B (128):** Editorial authority is the credibility a publication or brand earns through consistent, accurate, well-sourced content over time
- **Shipped (128):** Editorial authority is the credibility a publication or brand earns through consistent, accurate, well-sourced content over time
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `embedding.mdx`  ·  B (custom cut)
- **Old (160):** An embedding is a numerical vector representation of a piece of text — a word, sentence, or document — that encodes its meaning in a format AI systems can co...
- **Shipped (68):** An embedding is a numerical vector representation of a piece of text
- **Why:** Opening sentence ≤200 but ends on stranded "with" (fails floor). Used the valid Candidate-B cut.

### `emerging-search-behavior.mdx`  ·  verbatim
- **Old (160):** Emerging search behavior refers to the shift in how users seek information — increasingly using AI tools, social platforms, and voice interfaces alongside or...
- **Shipped (196):** Emerging search behavior refers to the shift in how users seek information — increasingly using AI tools, social platforms, and voice interfaces alongside or instead of traditional search engines.
- **Why:** Opening sentence ≤200; used verbatim.

### `engagement-signal.mdx`  ·  A
- **Old (160):** An engagement signal is any measurable user interaction with a piece of content — including likes, shares, comments, saves, watch time, and click-throughs — ...
- **Candidate A (135):** An engagement signal is any measurable user interaction with a piece of content that indicates the content resonated with its audience.
- **Candidate B (154):** An engagement signal is any measurable user interaction with a piece of content — including likes, shares, comments, saves, watch time, and click-throughs
- **Shipped (135):** An engagement signal is any measurable user interaction with a piece of content that indicates the content resonated with its audience.
- **Why:** Candidate A (paired-interruption removal) states the complete definition; B would drop the predicate or sever the clause.

### `entity-attribute.mdx`  ·  verbatim
- **Old (160):** An entity attribute is a specific, structured property associated with an entity — such as a business's founding date, location, industry category, or founde...
- **Shipped (164):** An entity attribute is a specific, structured property associated with an entity — such as a business's founding date, location, industry category, or founder name.
- **Why:** Opening sentence ≤200; used verbatim.

### `entity-categorization.mdx`  ·  A
- **Old (160):** Entity categorization is the process by which AI systems classify an entity into one or more predefined types — such as Organization, Person, Place, Product,...
- **Candidate A (178):** Entity categorization is the process by which AI systems classify an entity into one or more predefined types based on the structured and unstructured signals available about it.
- **Candidate B (166):** Entity categorization is the process by which AI systems classify an entity into one or more predefined types — such as Organization, Person, Place, Product, or Event
- **Shipped (178):** Entity categorization is the process by which AI systems classify an entity into one or more predefined types based on the structured and unstructured signals available about it.
- **Why:** Candidate A (paired-interruption removal) states the complete definition; B would drop the predicate or sever the clause.

### `entity-clarity.mdx`  ·  B
- **Old (160):** Entity clarity is the degree to which a brand or concept is unambiguously defined and consistently represented across the web — enabling AI systems to correc...
- **Candidate B (125):** Entity clarity is the degree to which a brand or concept is unambiguously defined and consistently represented across the web
- **Shipped (125):** Entity clarity is the degree to which a brand or concept is unambiguously defined and consistently represented across the web
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `entity-consistency.mdx`  ·  B
- **Old (160):** Entity consistency is the degree to which a brand's name, description, attributes, and relationships are represented uniformly across all digital platforms w...
- **Candidate B (180):** Entity consistency is the degree to which a brand's name, description, attributes, and relationships are represented uniformly across all digital platforms where the entity appears
- **Shipped (180):** Entity consistency is the degree to which a brand's name, description, attributes, and relationships are represented uniformly across all digital platforms where the entity appears
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `entity-disambiguation.mdx`  ·  B
- **Old (160):** Entity disambiguation is the process of distinguishing between multiple entities that share the same or similar names — ensuring AI systems associate content...
- **Candidate B (117):** Entity disambiguation is the process of distinguishing between multiple entities that share the same or similar names
- **Shipped (117):** Entity disambiguation is the process of distinguishing between multiple entities that share the same or similar names
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `entity-extraction.mdx`  ·  verbatim
- **Old (160):** Entity extraction is the process by which AI systems identify and pull named entities — people, organizations, locations, products, and concepts — from unstr...
- **Shipped (170):** Entity extraction is the process by which AI systems identify and pull named entities — people, organizations, locations, products, and concepts — from unstructured text.
- **Why:** Opening sentence ≤200; used verbatim.

### `entity-first-seo.mdx`  ·  verbatim
- **Old (160):** Entity-first SEO is a strategic approach to search optimization that prioritizes building a clear, complete, and verified entity record for a brand before op...
- **Shipped (198):** Entity-first SEO is a strategic approach to search optimization that prioritizes building a clear, complete, and verified entity record for a brand before optimizing for specific keywords or topics.
- **Why:** Opening sentence ≤200; used verbatim.

### `entity-graph.mdx`  ·  verbatim
- **Old (160):** An entity graph is a network of entities and the relationships between them — representing how people, organizations, places, products, and concepts are conn...
- **Shipped (189):** An entity graph is a network of entities and the relationships between them — representing how people, organizations, places, products, and concepts are connected within a knowledge system.
- **Why:** Opening sentence ≤200; used verbatim.

### `entity-home.mdx`  ·  verbatim
- **Old (160):** An entity home is a dedicated, authoritative web page that serves as the canonical source of truth for an entity's attributes, structured data, and knowledge...
- **Shipped (172):** An entity home is a dedicated, authoritative web page that serves as the canonical source of truth for an entity's attributes, structured data, and knowledge graph signals.
- **Why:** Opening sentence ≤200; used verbatim.

### `entity-id.mdx`  ·  verbatim
- **Old (160):** An entity ID is a unique, persistent identifier assigned to an entity within a structured knowledge system — such as a Wikidata QID, a Google Knowledge Graph...
- **Shipped (189):** An entity ID is a unique, persistent identifier assigned to an entity within a structured knowledge system — such as a Wikidata QID, a Google Knowledge Graph ID, or a schema.org identifier.
- **Why:** Opening sentence ≤200; used verbatim.

### `entity-injection.mdx`  ·  B
- **Old (160):** Entity injection is the deliberate introduction of accurate, structured entity information into the sources and platforms that AI systems use to build their ...
- **Candidate A (239):** Entity injection is the deliberate introduction of accurate, structured entity information into the sources and platforms that AI systems use to build their knowledge with the goal of correcting inaccurate or incomplete AI representations.
- **Candidate B (166):** Entity injection is the deliberate introduction of accurate, structured entity information into the sources and platforms that AI systems use to build their knowledge
- **Shipped (166):** Entity injection is the deliberate introduction of accurate, structured entity information into the sources and platforms that AI systems use to build their knowledge
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `entity-linked-transcripts.mdx`  ·  B
- **Old (160):** Entity-linked transcripts are video or audio transcripts that have been edited to include explicit references to named entities — brand names, people, locati...
- **Candidate A (217):** Entity-linked transcripts are video or audio transcripts that have been edited to include explicit references to named entities making the content machine-readable and citable by AI systems that index video platforms.
- **Candidate B (182):** Entity-linked transcripts are video or audio transcripts that have been edited to include explicit references to named entities — brand names, people, locations, products, and topics
- **Shipped (182):** Entity-linked transcripts are video or audio transcripts that have been edited to include explicit references to named entities — brand names, people, locations, products, and topics
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `entity-linking.mdx`  ·  B
- **Old (160):** Entity linking is the process of connecting a mention of an entity in text to its canonical record in a knowledge base — mapping 'Apple' in a sentence to the...
- **Candidate B (118):** Entity linking is the process of connecting a mention of an entity in text to its canonical record in a knowledge base
- **Shipped (118):** Entity linking is the process of connecting a mention of an entity in text to its canonical record in a knowledge base
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `entity-mention.mdx`  ·  B
- **Old (160):** An entity mention is any occurrence of an entity's name or reference in a piece of content — including direct name mentions, pronouns, and implied references...
- **Candidate B (90):** An entity mention is any occurrence of an entity's name or reference in a piece of content
- **Shipped (90):** An entity mention is any occurrence of an entity's name or reference in a piece of content
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `entity-optimization.mdx`  ·  B
- **Old (160):** Entity optimization is the practice of building, verifying, and maintaining a brand's structured entity presence across the web — ensuring that AI systems an...
- **Candidate B (127):** Entity optimization is the practice of building, verifying, and maintaining a brand's structured entity presence across the web
- **Shipped (127):** Entity optimization is the practice of building, verifying, and maintaining a brand's structured entity presence across the web
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `entity-prominence.mdx`  ·  verbatim
- **Old (160):** Entity prominence is the relative importance of an entity within its category — how well-known, widely-referenced, and structurally significant it is compare...
- **Shipped (194):** Entity prominence is the relative importance of an entity within its category — how well-known, widely-referenced, and structurally significant it is compared to other entities of the same type.
- **Why:** Opening sentence ≤200; used verbatim.

### `entity-recognition.mdx`  ·  verbatim
- **Old (160):** Entity recognition is the automated process by which AI systems identify and classify named entities — people, organizations, places, concepts — within a bod...
- **Shipped (167):** Entity recognition is the automated process by which AI systems identify and classify named entities — people, organizations, places, concepts — within a body of text.
- **Why:** Opening sentence ≤200; used verbatim.

### `entity-rich-content.mdx`  ·  B
- **Old (160):** Entity-rich content is content that explicitly names and contextualizes multiple relevant named entities — organizations, people, places, products, concepts ...
- **Candidate A (254):** Entity-rich content is content that explicitly names and contextualizes multiple relevant named entities creating a dense network of entity references that AI systems can extract, link, and use to understand what the content is about and who it involves.
- **Candidate B (156):** Entity-rich content is content that explicitly names and contextualizes multiple relevant named entities — organizations, people, places, products, concepts
- **Shipped (156):** Entity-rich content is content that explicitly names and contextualizes multiple relevant named entities — organizations, people, places, products, concepts
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `entity-salience-score.mdx`  ·  B
- **Old (160):** An entity salience score is a computed measure of how central and prominent a specific entity is within a given document — reflecting how much the document i...
- **Candidate B (120):** An entity salience score is a computed measure of how central and prominent a specific entity is within a given document
- **Shipped (120):** An entity salience score is a computed measure of how central and prominent a specific entity is within a given document
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `entity-salience.mdx`  ·  B
- **Old (160):** Entity salience refers to how central or prominent an entity is within a specific document — how much the document is 'about' that entity, as determined by h...
- **Candidate B (90):** Entity salience refers to how central or prominent an entity is within a specific document
- **Shipped (90):** Entity salience refers to how central or prominent an entity is within a specific document
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `entity-seo.mdx`  ·  hand-write
- **Old (159):** Entity SEO is the practice of optimizing a brand's entity presence across knowledge graphs, structured data, training data sources, and AI retrieval systems...
- **Shipped (156):** Entity SEO is the practice of optimizing a brand's entity presence across knowledge graphs, structured data, training data sources, and AI retrieval systems
- **Why:** Opening sentence >200 with only comma boundaries; hand-written to ≤200, reviewed and approved.

### `entity-verification.mdx`  ·  B
- **Old (160):** Entity verification is the process by which an AI system or knowledge graph confirms that a claimed entity — a brand, person, place, or concept — corresponds...
- **Candidate A (236):** Entity verification is the process by which an AI system or knowledge graph confirms that a claimed entity corresponds to a real, uniquely identifiable thing in the world, distinct from other entities with similar names or descriptions.
- **Candidate B (143):** Entity verification is the process by which an AI system or knowledge graph confirms that a claimed entity — a brand, person, place, or concept
- **Shipped (143):** Entity verification is the process by which an AI system or knowledge graph confirms that a claimed entity — a brand, person, place, or concept
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `ephemeral-content.mdx`  ·  verbatim
- **Old (160):** Ephemeral content is social media content designed to disappear after a short period — typically 24 hours — including Instagram Stories, Snapchat Snaps, and ...
- **Shipped (186):** Ephemeral content is social media content designed to disappear after a short period — typically 24 hours — including Instagram Stories, Snapchat Snaps, and similar time-limited formats.
- **Why:** Opening sentence ≤200; used verbatim.

### `experience-signal.mdx`  ·  B
- **Old (160):** An experience signal is any element of content that demonstrates first-hand, direct experience with the subject being discussed — personal accounts, case stu...
- **Candidate B (127):** An experience signal is any element of content that demonstrates first-hand, direct experience with the subject being discussed
- **Shipped (127):** An experience signal is any element of content that demonstrates first-hand, direct experience with the subject being discussed
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `expert-quote.mdx`  ·  B
- **Old (160):** An expert quote is a direct quotation from a named, credentialed individual that makes a specific claim about a topic — providing both an attributable statem...
- **Candidate B (117):** An expert quote is a direct quotation from a named, credentialed individual that makes a specific claim about a topic
- **Shipped (117):** An expert quote is a direct quotation from a named, credentialed individual that makes a specific claim about a topic
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `expertise-signal.mdx`  ·  A
- **Old (160):** An expertise signal is any indicator — such as author credentials, publication history, structured data, or domain-specific vocabulary — that communicates a ...
- **Candidate A (136):** An expertise signal is any indicator that communicates a content creator's or brand's domain expertise to search engines and AI systems.
- **Candidate B (134):** An expertise signal is any indicator — such as author credentials, publication history, structured data, or domain-specific vocabulary
- **Shipped (136):** An expertise signal is any indicator that communicates a content creator's or brand's domain expertise to search engines and AI systems.
- **Why:** Candidate A (paired-interruption removal) states the complete definition; B would drop the predicate or sever the clause.

### `explainer-content.mdx`  ·  B
- **Old (160):** Explainer content is content designed to make a complex concept accessible to a non-expert audience — breaking it down into clear definitions, concrete examp...
- **Candidate B (99):** Explainer content is content designed to make a complex concept accessible to a non-expert audience
- **Shipped (99):** Explainer content is content designed to make a complex concept accessible to a non-expert audience
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `featured-snippet.mdx`  ·  verbatim
- **Old (160):** A featured snippet is a highlighted excerpt displayed at the top of a Google search results page that directly answers a query, pulled from a page that may o...
- **Shipped (200):** A featured snippet is a highlighted excerpt displayed at the top of a Google search results page that directly answers a query, pulled from a page that may or may not be the top-ranked organic result.
- **Why:** Opening sentence ≤200; used verbatim.

### `first-person-experience.mdx`  ·  B
- **Old (160):** First-person experience refers to content that documents direct, personal involvement with a subject — written from the perspective of someone who has done t...
- **Candidate B (100):** First-person experience refers to content that documents direct, personal involvement with a subject
- **Shipped (100):** First-person experience refers to content that documents direct, personal involvement with a subject
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `foundation-model.mdx`  ·  B
- **Old (160):** A foundation model is a large AI model trained on broad, general-purpose data that serves as the base for a wide range of downstream applications — including...
- **Candidate B (145):** A foundation model is a large AI model trained on broad, general-purpose data that serves as the base for a wide range of downstream applications
- **Shipped (145):** A foundation model is a large AI model trained on broad, general-purpose data that serves as the base for a wide range of downstream applications
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `fractional-cmo.mdx`  ·  verbatim
- **Old (160):** A fractional CMO is a senior marketing leader who works with a company on a part-time or project basis, providing CMO-level strategy without the cost or comm...
- **Shipped (194):** A fractional CMO is a senior marketing leader who works with a company on a part-time or project basis, providing CMO-level strategy without the cost or commitment of a full-time executive hire.
- **Why:** Opening sentence ≤200; used verbatim.

### `freebase.mdx`  ·  verbatim
- **Old (160):** Freebase was a large, open knowledge base of structured data about entities — people, places, organizations, and concepts — operated by Google from 2010 unti...
- **Shipped (189):** Freebase was a large, open knowledge base of structured data about entities — people, places, organizations, and concepts — operated by Google from 2010 until its official shutdown in 2016.
- **Why:** Opening sentence ≤200; used verbatim.

### `freshness-signal.mdx`  ·  B
- **Old (160):** A freshness signal is any indicator that a piece of content has been recently created or updated — including publication date, last-modified date, recent cit...
- **Candidate B (96):** A freshness signal is any indicator that a piece of content has been recently created or updated
- **Shipped (96):** A freshness signal is any indicator that a piece of content has been recently created or updated
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `generative-brand-presence.mdx`  ·  B
- **Old (160):** Generative brand presence is the totality of a brand's representation across all AI-generated surfaces — the sum of how the brand is described, characterized...
- **Candidate B (102):** Generative brand presence is the totality of a brand's representation across all AI-generated surfaces
- **Shipped (102):** Generative brand presence is the totality of a brand's representation across all AI-generated surfaces
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `generative-search-ranking.mdx`  ·  B
- **Old (160):** Generative search ranking is a brand's relative position and prominence within AI-generated responses — not a numeric rank like traditional SEO positions, bu...
- **Candidate B (101):** Generative search ranking is a brand's relative position and prominence within AI-generated responses
- **Shipped (101):** Generative search ranking is a brand's relative position and prominence within AI-generated responses
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `geo.mdx`  ·  hand-write
- **Old (160):** GEO — Generative Engine Optimization — is the practice of optimizing content and brand signals to improve visibility and citation in AI-generated responses f...
- **Shipped (155):** GEO — Generative Engine Optimization — is the practice of optimizing content and brand signals to improve visibility and citation in AI-generated responses
- **Why:** Opening sentence >200 with only comma boundaries; hand-written to ≤200, reviewed and approved.

### `go-to-market-strategy.mdx`  ·  B
- **Old (160):** A go-to-market (GTM) strategy is the plan that defines how a company will bring a product or service to market — specifying target customers, value propositi...
- **Candidate B (110):** A go-to-market (GTM) strategy is the plan that defines how a company will bring a product or service to market
- **Shipped (110):** A go-to-market (GTM) strategy is the plan that defines how a company will bring a product or service to market
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `google-ai-mode.mdx`  ·  verbatim
- **Old (160):** Google AI Mode is Google's conversational AI search interface that generates synthesized, multi-turn answers rather than a traditional ranked list of blue li...
- **Shipped (161):** Google AI Mode is Google's conversational AI search interface that generates synthesized, multi-turn answers rather than a traditional ranked list of blue links.
- **Why:** Opening sentence ≤200; used verbatim.

### `google-discover.mdx`  ·  verbatim
- **Old (160):** Google Discover is Google's content recommendation feed that surfaces personalized articles and content to users based on their interests and search history ...
- **Shipped (185):** Google Discover is Google's content recommendation feed that surfaces personalized articles and content to users based on their interests and search history — without requiring a query.
- **Why:** Opening sentence ≤200; used verbatim.

### `google-knowledge-graph.mdx`  ·  verbatim
- **Old (160):** Google's Knowledge Graph is Google's proprietary knowledge base of entities and their relationships — used to power Knowledge Panels, AI Overviews, and seman...
- **Shipped (177):** Google's Knowledge Graph is Google's proprietary knowledge base of entities and their relationships — used to power Knowledge Panels, AI Overviews, and semantic search features.
- **Why:** Opening sentence ≤200; used verbatim.

### `google-knowledge-panel.mdx`  ·  B
- **Old (160):** A Google Knowledge Panel is an information box displayed on the right side of Google SERPs showing structured facts about an entity — drawn from the Google K...
- **Candidate B (131):** A Google Knowledge Panel is an information box displayed on the right side of Google SERPs showing structured facts about an entity
- **Shipped (131):** A Google Knowledge Panel is an information box displayed on the right side of Google SERPs showing structured facts about an entity
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `google-search-console.mdx`  ·  B
- **Old (160):** Google Search Console is Google's free web service that provides data on how a site performs in Google Search — including impressions, clicks, average positi...
- **Candidate B (109):** Google Search Console is Google's free web service that provides data on how a site performs in Google Search
- **Shipped (109):** Google Search Console is Google's free web service that provides data on how a site performs in Google Search
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `google-tag-manager.mdx`  ·  verbatim
- **Old (160):** Google Tag Manager is a tag management system that allows marketers to deploy tracking scripts and structured data via JavaScript — without requiring direct ...
- **Shipped (170):** Google Tag Manager is a tag management system that allows marketers to deploy tracking scripts and structured data via JavaScript — without requiring direct code changes.
- **Why:** Opening sentence ≤200; used verbatim.

### `grounding.mdx`  ·  B
- **Old (160):** Grounding is the process of anchoring an AI model's output to specific, verifiable external sources — ensuring that generated responses are based on retrieve...
- **Candidate B (99):** Grounding is the process of anchoring an AI model's output to specific, verifiable external sources
- **Shipped (99):** Grounding is the process of anchoring an AI model's output to specific, verifiable external sources
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `hallucination-mitigation.mdx`  ·  verbatim
- **Old (160):** Hallucination mitigation is the set of techniques used to reduce the frequency of AI-generated outputs that present false, fabricated, or unverifiable inform...
- **Shipped (171):** Hallucination mitigation is the set of techniques used to reduce the frequency of AI-generated outputs that present false, fabricated, or unverifiable information as fact.
- **Why:** Opening sentence ≤200; used verbatim.

### `hashtag-as-keyword.mdx`  ·  B
- **Old (160):** Treating a hashtag as a keyword means deliberately selecting hashtags for their search and retrieval function on social platforms — choosing terms that users...
- **Candidate A (212):** Treating a hashtag as a keyword means deliberately selecting hashtags for their search and retrieval function on social platforms rather than using hashtags purely for trend participation or aesthetic convention.
- **Candidate B (129):** Treating a hashtag as a keyword means deliberately selecting hashtags for their search and retrieval function on social platforms
- **Shipped (129):** Treating a hashtag as a keyword means deliberately selecting hashtags for their search and retrieval function on social platforms
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `hreflang.mdx`  ·  B
- **Old (160):** Hreflang is an HTML attribute that specifies the language and regional targeting of a web page — used for international SEO to help search engines serve the ...
- **Candidate B (94):** Hreflang is an HTML attribute that specifies the language and regional targeting of a web page
- **Shipped (94):** Hreflang is an HTML attribute that specifies the language and regional targeting of a web page
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `html-first-development.mdx`  ·  hand-write
- **Old (160):** HTML-first development is a web development approach that prioritizes delivering page content as static, server-rendered HTML rather than relying on client-s...
- **Shipped (171):** HTML-first development is a web development approach that prioritizes delivering page content as static, server-rendered HTML rather than relying on client-side JavaScript
- **Why:** Opening sentence >200 with only comma boundaries; hand-written to ≤200, reviewed and approved.

### `hub-and-spoke-model.mdx`  ·  hand-write
- **Old (160):** The hub and spoke model is a content architecture in which a central hub page covers a topic at the highest level, linking outward to a set of spoke pages th...
- **Shipped (179):** The hub and spoke model is a content architecture in which a central hub page covers a topic broadly, linking outward to spoke pages that each address a specific subtopic in depth
- **Why:** Opening sentence >200 with only comma boundaries; hand-written to ≤200, reviewed and approved.

### `hyper-local-content.mdx`  ·  A
- **Old (160):** Hyper-local content is content specifically written for and about a highly specific geographic area — a neighborhood, street, landmark, or community — that a...
- **Candidate A (187):** Hyper-local content is content specifically written for and about a highly specific geographic area that addresses the information needs of people in or interested in that specific place.
- **Candidate B (148):** Hyper-local content is content specifically written for and about a highly specific geographic area — a neighborhood, street, landmark, or community
- **Shipped (187):** Hyper-local content is content specifically written for and about a highly specific geographic area that addresses the information needs of people in or interested in that specific place.
- **Why:** Candidate A (paired-interruption removal) states the complete definition; B would drop the predicate or sever the clause.

### `hyperlocal-seo.mdx`  ·  A
- **Old (160):** Hyperlocal SEO is the practice of optimizing a business's online presence for searches within a highly specific geographic area — a neighborhood, district, o...
- **Candidate A (157):** Hyperlocal SEO is the practice of optimizing a business's online presence for searches within a highly specific geographic area rather than a city or region.
- **Candidate B (177):** Hyperlocal SEO is the practice of optimizing a business's online presence for searches within a highly specific geographic area — a neighborhood, district, or landmark proximity
- **Shipped (157):** Hyperlocal SEO is the practice of optimizing a business's online presence for searches within a highly specific geographic area rather than a city or region.
- **Why:** Candidate A (paired-interruption removal) states the complete definition; B would drop the predicate or sever the clause.

### `icp.mdx`  ·  B
- **Old (160):** An ideal customer profile (ICP) is a detailed description of the type of company or individual most likely to derive maximum value from a product or service ...
- **Candidate B (156):** An ideal customer profile (ICP) is a detailed description of the type of company or individual most likely to derive maximum value from a product or service
- **Shipped (156):** An ideal customer profile (ICP) is a detailed description of the type of company or individual most likely to derive maximum value from a product or service
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `identity-consolidation.mdx`  ·  B
- **Old (160):** Identity consolidation is the process of merging fragmented or duplicate entity records into a single, authoritative representation — ensuring that an entity...
- **Candidate B (131):** Identity consolidation is the process of merging fragmented or duplicate entity records into a single, authoritative representation
- **Shipped (131):** Identity consolidation is the process of merging fragmented or duplicate entity records into a single, authoritative representation
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `image-alt-text.mdx`  ·  verbatim
- **Old (160):** Image alt text is descriptive text added to an HTML image element that helps search engines and AI systems understand the content of an image and improves ac...
- **Shipped (193):** Image alt text is descriptive text added to an HTML image element that helps search engines and AI systems understand the content of an image and improves accessibility for screen reader users.
- **Why:** Opening sentence ≤200; used verbatim.

### `implicit-query.mdx`  ·  B
- **Old (160):** An implicit query is a search query in which the user's intent is not fully stated but must be inferred from context — requiring AI systems to apply semantic...
- **Candidate B (116):** An implicit query is a search query in which the user's intent is not fully stated but must be inferred from context
- **Shipped (116):** An implicit query is a search query in which the user's intent is not fully stated but must be inferred from context
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `implied-entity.mdx`  ·  B
- **Old (160):** An implied entity is an entity that is not explicitly named in a piece of content but can be inferred from context — through pronouns, descriptions, or assoc...
- **Candidate B (114):** An implied entity is an entity that is not explicitly named in a piece of content but can be inferred from context
- **Shipped (114):** An implied entity is an entity that is not explicitly named in a piece of content but can be inferred from context
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `index-coverage.mdx`  ·  verbatim
- **Old (160):** Index coverage is the proportion of a website's pages that have been successfully crawled and added to a search engine's index — monitored via Google Search ...
- **Shipped (165):** Index coverage is the proportion of a website's pages that have been successfully crawled and added to a search engine's index — monitored via Google Search Console.
- **Why:** Opening sentence ≤200; used verbatim.

### `inference.mdx`  ·  B
- **Old (160):** Inference is the process by which a trained AI model generates a response to a new input — applying the patterns, associations, and knowledge encoded during ...
- **Candidate B (88):** Inference is the process by which a trained AI model generates a response to a new input
- **Shipped (88):** Inference is the process by which a trained AI model generates a response to a new input
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `information-architecture.mdx`  ·  A
- **Old (160):** Information architecture is the structural organization of content on a website — including navigation hierarchy, URL structure, content taxonomy, and intern...
- **Candidate A (140):** Information architecture is the structural organization of content on a website which affects both user experience and machine crawlability.
- **Candidate B (176):** Information architecture is the structural organization of content on a website — including navigation hierarchy, URL structure, content taxonomy, and internal linking patterns
- **Shipped (140):** Information architecture is the structural organization of content on a website which affects both user experience and machine crawlability.
- **Why:** Candidate A (paired-interruption removal) states the complete definition; B would drop the predicate or sever the clause.

### `information-gain.mdx`  ·  verbatim
- **Old (160):** Information gain is the degree to which a piece of content adds new, verifiable, or unique information beyond what is already available on competing pages co...
- **Shipped (179):** Information gain is the degree to which a piece of content adds new, verifiable, or unique information beyond what is already available on competing pages covering the same topic.
- **Why:** Opening sentence ≤200; used verbatim.

### `integrated-marketing.mdx`  ·  verbatim
- **Old (160):** Integrated marketing is an approach that aligns all marketing channels — paid, earned, owned, and shared — around a consistent message, brand voice, and stra...
- **Shipped (173):** Integrated marketing is an approach that aligns all marketing channels — paid, earned, owned, and shared — around a consistent message, brand voice, and strategic objective.
- **Why:** Opening sentence ≤200; used verbatim.

### `intent-classification.mdx`  ·  A
- **Old (160):** Intent classification is the process by which AI systems categorize a user's query into intent types — informational, navigational, transactional, or commerc...
- **Candidate A (167):** Intent classification is the process by which AI systems categorize a user's query into intent types to determine the most appropriate response format and source type.
- **Candidate B (174):** Intent classification is the process by which AI systems categorize a user's query into intent types — informational, navigational, transactional, or commercial investigation
- **Shipped (167):** Intent classification is the process by which AI systems categorize a user's query into intent types to determine the most appropriate response format and source type.
- **Why:** Candidate A (paired-interruption removal) states the complete definition; B would drop the predicate or sever the clause.

### `intent-matching.mdx`  ·  B
- **Old (160):** Intent matching is the degree to which a piece of content satisfies the actual purpose behind a user's query — not just the words of the query but the underl...
- **Candidate B (108):** Intent matching is the degree to which a piece of content satisfies the actual purpose behind a user's query
- **Shipped (108):** Intent matching is the degree to which a piece of content satisfies the actual purpose behind a user's query
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `internal-linking.mdx`  ·  B
- **Old (160):** Internal linking is the practice of linking between pages within the same website — connecting related content, distributing page authority, and signaling to...
- **Candidate B (81):** Internal linking is the practice of linking between pages within the same website
- **Shipped (81):** Internal linking is the practice of linking between pages within the same website
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `inverted-pyramid-architecture.mdx`  ·  B
- **Old (160):** Inverted pyramid architecture is a content structure borrowed from journalism in which the most important information — the who, what, when, where — leads th...
- **Candidate A (217):** Inverted pyramid architecture is a content structure borrowed from journalism in which the most important information leads the piece, with supporting detail and background following in descending order of importance.
- **Candidate B (117):** Inverted pyramid architecture is a content structure borrowed from journalism in which the most important information
- **Shipped (117):** Inverted pyramid architecture is a content structure borrowed from journalism in which the most important information
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `island-economy.mdx`  ·  B
- **Old (160):** Island economy refers to the economic characteristics and constraints unique to geographically isolated island markets — including limited land and resource ...
- **Candidate B (118):** Island economy refers to the economic characteristics and constraints unique to geographically isolated island markets
- **Shipped (118):** Island economy refers to the economic characteristics and constraints unique to geographically isolated island markets
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `keyword-optimized-bio.mdx`  ·  B
- **Old (160):** A keyword-optimized bio is a social media profile description written to include the specific terms, topics, and entity references that define the account's ...
- **Candidate B (163):** A keyword-optimized bio is a social media profile description written to include the specific terms, topics, and entity references that define the account's domain
- **Shipped (163):** A keyword-optimized bio is a social media profile description written to include the specific terms, topics, and entity references that define the account's domain
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `knowledge-article.mdx`  ·  B
- **Old (160):** A knowledge article is a structured, standalone piece of content that defines a concept, answers a specific question, or documents a process — written to fun...
- **Candidate B (140):** A knowledge article is a structured, standalone piece of content that defines a concept, answers a specific question, or documents a process
- **Shipped (140):** A knowledge article is a structured, standalone piece of content that defines a concept, answers a specific question, or documents a process
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `knowledge-base.mdx`  ·  B
- **Old (160):** A knowledge base is a structured repository of information about entities and their relationships — used by AI systems as a reference for fact-checking, enti...
- **Candidate B (97):** A knowledge base is a structured repository of information about entities and their relationships
- **Shipped (97):** A knowledge base is a structured repository of information about entities and their relationships
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `knowledge-graph-poisoning.mdx`  ·  A
- **Old (160):** Knowledge graph poisoning is the introduction of inaccurate or misleading information into a knowledge graph — through false Wikipedia edits, incorrect Wikid...
- **Candidate A (182):** Knowledge graph poisoning is the introduction of inaccurate or misleading information into a knowledge graph with the effect of corrupting an AI system's representation of an entity.
- **Candidate B (200):** Knowledge graph poisoning is the introduction of inaccurate or misleading information into a knowledge graph — through false Wikipedia edits, incorrect Wikidata entries, or manipulated structured data
- **Shipped (182):** Knowledge graph poisoning is the introduction of inaccurate or misleading information into a knowledge graph with the effect of corrupting an AI system's representation of an entity.
- **Why:** Candidate A (paired-interruption removal) states the complete definition; B would drop the predicate or sever the clause.

### `knowledge-graph.mdx`  ·  B
- **Old (160):** A knowledge graph is a structured database that represents entities, their attributes, and the relationships between them as a network of interconnected node...
- **Candidate B (158):** A knowledge graph is a structured database that represents entities, their attributes, and the relationships between them as a network of interconnected nodes
- **Shipped (158):** A knowledge graph is a structured database that represents entities, their attributes, and the relationships between them as a network of interconnected nodes
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `knowledge-panel.mdx`  ·  B
- **Old (160):** A Knowledge Panel is an information box displayed on the right side of Google search results — and increasingly integrated into AI-generated answers — showin...
- **Candidate A (217):** A Knowledge Panel is an information box displayed on the right side of Google search results showing structured facts about an entity: name, description, founding date, location, social profiles, and related entities.
- **Candidate B (148):** A Knowledge Panel is an information box displayed on the right side of Google search results — and increasingly integrated into AI-generated answers
- **Shipped (148):** A Knowledge Panel is an information box displayed on the right side of Google search results — and increasingly integrated into AI-generated answers
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `latent-semantic-indexing.mdx`  ·  verbatim
- **Old (160):** Latent Semantic Indexing (LSI) is an older information retrieval technique that identifies relationships between terms and concepts in a document corpus usin...
- **Shipped (188):** Latent Semantic Indexing (LSI) is an older information retrieval technique that identifies relationships between terms and concepts in a document corpus using singular value decomposition.
- **Why:** Opening sentence ≤200; used verbatim.

### `linked-data.mdx`  ·  verbatim
- **Old (160):** Linked data is a method of publishing structured data on the web using URIs and RDF so that entities and their relationships can be interconnected across dif...
- **Shipped (177):** Linked data is a method of publishing structured data on the web using URIs and RDF so that entities and their relationships can be interconnected across different data sources.
- **Why:** Opening sentence ≤200; used verbatim.

### `llm-brand-audit.mdx`  ·  B
- **Old (160):** An LLM brand audit is a systematic evaluation of how a specific large language model represents a brand — testing a defined set of prompts across a defined m...
- **Candidate B (103):** An LLM brand audit is a systematic evaluation of how a specific large language model represents a brand
- **Shipped (103):** An LLM brand audit is a systematic evaluation of how a specific large language model represents a brand
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `llm-brand-recall.mdx`  ·  B
- **Old (160):** LLM brand recall is the accuracy and completeness with which a specific large language model can reproduce correct information about a brand from its paramet...
- **Candidate B (170):** LLM brand recall is the accuracy and completeness with which a specific large language model can reproduce correct information about a brand from its parametric knowledge
- **Shipped (170):** LLM brand recall is the accuracy and completeness with which a specific large language model can reproduce correct information about a brand from its parametric knowledge
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `llm-probing.mdx`  ·  B
- **Old (160):** LLM probing is the practice of systematically querying a specific language model with a defined set of prompts to assess how the model represents a brand, to...
- **Candidate B (173):** LLM probing is the practice of systematically querying a specific language model with a defined set of prompts to assess how the model represents a brand, topic, or category
- **Shipped (173):** LLM probing is the practice of systematically querying a specific language model with a defined set of prompts to assess how the model represents a brand, topic, or category
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `llm-visibility.mdx`  ·  B
- **Old (160):** LLM visibility is the degree to which a brand is represented, cited, and accurately characterized across large language model outputs — measuring both the fr...
- **Candidate B (133):** LLM visibility is the degree to which a brand is represented, cited, and accurately characterized across large language model outputs
- **Shipped (133):** LLM visibility is the degree to which a brand is represented, cited, and accurately characterized across large language model outputs
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `llmo.mdx`  ·  A
- **Old (160):** LLMO — Large Language Model Optimization — is the practice of optimizing content, entity signals, and brand infrastructure specifically to improve how a bran...
- **Candidate A (175):** LLMO is the practice of optimizing content, entity signals, and brand infrastructure specifically to improve how a brand is represented and cited within LLM-generated outputs.
- **Candidate B (40):** LLMO — Large Language Model Optimization
- **Shipped (175):** LLMO is the practice of optimizing content, entity signals, and brand infrastructure specifically to improve how a brand is represented and cited within LLM-generated outputs.
- **Why:** Candidate A (paired-interruption removal) states the complete definition; B would drop the predicate or sever the clause.

### `local-authority.mdx`  ·  B
- **Old (160):** Local authority is the credibility and recognition a business or entity has established within a specific geographic community — built through community invo...
- **Candidate B (126):** Local authority is the credibility and recognition a business or entity has established within a specific geographic community
- **Shipped (126):** Local authority is the credibility and recognition a business or entity has established within a specific geographic community
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `local-citation-nap.mdx`  ·  verbatim
- **Old (160):** A local citation is any online mention of a business's Name, Address, and Phone number (NAP) — appearing in directories, review sites, news articles, social ...
- **Shipped (192):** A local citation is any online mention of a business's Name, Address, and Phone number (NAP) — appearing in directories, review sites, news articles, social profiles, and any other web source.
- **Why:** Opening sentence ≤200; used verbatim.

### `local-entity-seo.mdx`  ·  B
- **Old (160):** Local entity SEO is the practice of optimizing a local business's entity presence — structured data, citations, knowledge graph entries, and geographic assoc...
- **Candidate A (203):** Local entity SEO is the practice of optimizing a local business's entity presence to improve how AI systems and search engines understand, verify, and represent the business in response to local queries.
- **Candidate B (164):** Local entity SEO is the practice of optimizing a local business's entity presence — structured data, citations, knowledge graph entries, and geographic associations
- **Shipped (164):** Local entity SEO is the practice of optimizing a local business's entity presence — structured data, citations, knowledge graph entries, and geographic associations
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `local-knowledge-panel.mdx`  ·  B
- **Old (160):** A local knowledge panel is a Knowledge Panel specifically generated for a local business — displaying the business's name, address, hours, phone number, revi...
- **Candidate B (88):** A local knowledge panel is a Knowledge Panel specifically generated for a local business
- **Shipped (88):** A local knowledge panel is a Knowledge Panel specifically generated for a local business
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `local-pack.mdx`  ·  B
- **Old (160):** The local pack is the block of typically three local business listings displayed in Google search results for location-based queries — showing business name,...
- **Candidate B (132):** The local pack is the block of typically three local business listings displayed in Google search results for location-based queries
- **Shipped (132):** The local pack is the block of typically three local business listings displayed in Google search results for location-based queries
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `local-search-intent.mdx`  ·  verbatim
- **Old (160):** Local search intent is the underlying goal of a user query that includes a geographic component — the desire to find a business, service, product, or informa...
- **Shipped (194):** Local search intent is the underlying goal of a user query that includes a geographic component — the desire to find a business, service, product, or information relevant to a specific location.
- **Why:** Opening sentence ≤200; used verbatim.

### `local-seo.mdx`  ·  B
- **Old (160):** Local SEO is the practice of optimizing a business's online presence to appear in geographically relevant search results — including Google Maps results, loc...
- **Candidate B (120):** Local SEO is the practice of optimizing a business's online presence to appear in geographically relevant search results
- **Shipped (120):** Local SEO is the practice of optimizing a business's online presence to appear in geographically relevant search results
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `log-file-analysis.mdx`  ·  B
- **Old (160):** Log file analysis is the examination of server log files to understand how search engine and AI crawlers interact with a website — revealing which pages are ...
- **Candidate B (128):** Log file analysis is the examination of server log files to understand how search engine and AI crawlers interact with a website
- **Shipped (128):** Log file analysis is the examination of server log files to understand how search engine and AI crawlers interact with a website
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `machine-readability.mdx`  ·  A
- **Old (160):** Machine readability is the degree to which a web page's content can be parsed and understood by automated systems — crawlers, AI bots, and structured data pr...
- **Candidate A (153):** Machine readability is the degree to which a web page's content can be parsed and understood by automated systems without requiring human interpretation.
- **Candidate B (165):** Machine readability is the degree to which a web page's content can be parsed and understood by automated systems — crawlers, AI bots, and structured data processors
- **Shipped (153):** Machine readability is the degree to which a web page's content can be parsed and understood by automated systems without requiring human interpretation.
- **Why:** Candidate A (paired-interruption removal) states the complete definition; B would drop the predicate or sever the clause.

### `machine-readable-pr.mdx`  ·  B
- **Old (160):** Machine-readable PR is the practice of structuring press releases, announcements, and corporate communications to be parseable by AI crawlers and retrieval s...
- **Candidate B (163):** Machine-readable PR is the practice of structuring press releases, announcements, and corporate communications to be parseable by AI crawlers and retrieval systems
- **Shipped (163):** Machine-readable PR is the practice of structuring press releases, announcements, and corporate communications to be parseable by AI crawlers and retrieval systems
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `market-segmentation.mdx`  ·  A
- **Old (160):** Market segmentation is the process of dividing a target market into distinct groups — by industry, company size, geography, behavior, or need — to enable mor...
- **Candidate A (164):** Market segmentation is the process of dividing a target market into distinct groups to enable more targeted messaging, product development, and resource allocation.
- **Candidate B (141):** Market segmentation is the process of dividing a target market into distinct groups — by industry, company size, geography, behavior, or need
- **Shipped (164):** Market segmentation is the process of dividing a target market into distinct groups to enable more targeted messaging, product development, and resource allocation.
- **Why:** Candidate A (paired-interruption removal) states the complete definition; B would drop the predicate or sever the clause.

### `marketing-infrastructure.mdx`  ·  B
- **Old (160):** Marketing infrastructure is the set of systems, tools, processes, and data structures that enable a marketing function to operate at scale — including CRM, m...
- **Candidate B (138):** Marketing infrastructure is the set of systems, tools, processes, and data structures that enable a marketing function to operate at scale
- **Shipped (138):** Marketing infrastructure is the set of systems, tools, processes, and data structures that enable a marketing function to operate at scale
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `marketing-maturity.mdx`  ·  B
- **Old (160):** Marketing maturity is the degree to which a company's marketing function operates strategically, systematically, and measurably — from early-stage ad hoc act...
- **Candidate B (127):** Marketing maturity is the degree to which a company's marketing function operates strategically, systematically, and measurably
- **Shipped (127):** Marketing maturity is the degree to which a company's marketing function operates strategically, systematically, and measurably
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `marketing-operations.mdx`  ·  B
- **Old (160):** Marketing operations is the function responsible for the technology, data, processes, and performance measurement that enable a marketing team to operate eff...
- **Candidate B (165):** Marketing operations is the function responsible for the technology, data, processes, and performance measurement that enable a marketing team to operate efficiently
- **Shipped (165):** Marketing operations is the function responsible for the technology, data, processes, and performance measurement that enable a marketing team to operate efficiently
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `marketing-stack.mdx`  ·  B
- **Old (160):** A marketing stack is the collection of software tools and platforms a marketing team uses to plan, execute, measure, and optimize its activities — typically ...
- **Candidate B (144):** A marketing stack is the collection of software tools and platforms a marketing team uses to plan, execute, measure, and optimize its activities
- **Shipped (144):** A marketing stack is the collection of software tools and platforms a marketing team uses to plan, execute, measure, and optimize its activities
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `mention-to-citation-ratio.mdx`  ·  B
- **Old (160):** Mention-to-citation ratio is the proportion of brand mentions in AI-generated responses that include an explicit attribution or citation link — as opposed to...
- **Candidate B (141):** Mention-to-citation ratio is the proportion of brand mentions in AI-generated responses that include an explicit attribution or citation link
- **Shipped (141):** Mention-to-citation ratio is the proportion of brand mentions in AI-generated responses that include an explicit attribution or citation link
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `messaging-framework.mdx`  ·  A
- **Old (160):** A messaging framework is a documented structure that organizes a brand's core messages — value proposition, audience-specific benefits, proof points, and dif...
- **Candidate A (166):** A messaging framework is a documented structure that organizes a brand's core messages into a consistent, reusable reference that guides all marketing communications.
- **Candidate B (169):** A messaging framework is a documented structure that organizes a brand's core messages — value proposition, audience-specific benefits, proof points, and differentiators
- **Shipped (166):** A messaging framework is a documented structure that organizes a brand's core messages into a consistent, reusable reference that guides all marketing communications.
- **Why:** Candidate A (paired-interruption removal) states the complete definition; B would drop the predicate or sever the clause.

### `microdata.mdx`  ·  B
- **Old (160):** Microdata is an HTML specification for embedding structured data within page content using HTML tag attributes — one of three formats supported by Google for...
- **Candidate B (110):** Microdata is an HTML specification for embedding structured data within page content using HTML tag attributes
- **Shipped (110):** Microdata is an HTML specification for embedding structured data within page content using HTML tag attributes
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `model-evaluation-brand.mdx`  ·  B
- **Old (160):** Brand model evaluation is the systematic assessment of how a specific AI model represents a brand — testing a defined set of prompts to evaluate accuracy, co...
- **Candidate B (97):** Brand model evaluation is the systematic assessment of how a specific AI model represents a brand
- **Shipped (97):** Brand model evaluation is the systematic assessment of how a specific AI model represents a brand
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `model-grounding.mdx`  ·  B
- **Old (160):** Model grounding is the practice of connecting an AI model's outputs to specific, verifiable external data sources — either through retrieval-augmented genera...
- **Candidate A (205):** Model grounding is the practice of connecting an AI model's outputs to specific, verifiable external data sources to ensure responses are factually anchored rather than generated purely from training data.
- **Candidate B (196):** Model grounding is the practice of connecting an AI model's outputs to specific, verifiable external data sources — either through retrieval-augmented generation, tool use, or real-time web access
- **Shipped (196):** Model grounding is the practice of connecting an AI model's outputs to specific, verifiable external data sources — either through retrieval-augmented generation, tool use, or real-time web access
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `modular-content.mdx`  ·  verbatim
- **Old (160):** Modular content is content built from self-contained, independently meaningful units that can be combined, rearranged, or reused across different contexts wi...
- **Shipped (180):** Modular content is content built from self-contained, independently meaningful units that can be combined, rearranged, or reused across different contexts without losing coherence.
- **Why:** Opening sentence ≤200; used verbatim.

### `multi-modal-search.mdx`  ·  A
- **Old (160):** Multi-modal search is a search or query interface that accepts and processes multiple types of input — text, images, voice, video, and documents — and return...
- **Candidate A (161):** Multi-modal search is a search or query interface that accepts and processes multiple types of input and returns results that may also span multiple media types.
- **Candidate B (144):** Multi-modal search is a search or query interface that accepts and processes multiple types of input — text, images, voice, video, and documents
- **Shipped (161):** Multi-modal search is a search or query interface that accepts and processes multiple types of input and returns results that may also span multiple media types.
- **Why:** Candidate A (paired-interruption removal) states the complete definition; B would drop the predicate or sever the clause.

### `multi-platform-presence.mdx`  ·  B
- **Old (160):** Multi-platform presence is the deliberate distribution of a brand's entity signals, content, and structured data across multiple digital platforms — website,...
- **Candidate A (229):** Multi-platform presence is the deliberate distribution of a brand's entity signals, content, and structured data across multiple digital platforms to build the corroborated footprint AI systems use to establish entity confidence.
- **Candidate B (146):** Multi-platform presence is the deliberate distribution of a brand's entity signals, content, and structured data across multiple digital platforms
- **Shipped (146):** Multi-platform presence is the deliberate distribution of a brand's entity signals, content, and structured data across multiple digital platforms
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `multi-step-reasoning.mdx`  ·  B
- **Old (160):** Multi-step reasoning is the capability of an AI system to break down a complex query into sequential sub-tasks — searching, synthesizing, and building toward...
- **Candidate B (110):** Multi-step reasoning is the capability of an AI system to break down a complex query into sequential sub-tasks
- **Shipped (110):** Multi-step reasoning is the capability of an AI system to break down a complex query into sequential sub-tasks
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `named-entity.mdx`  ·  verbatim
- **Old (160):** A named entity is a real-world object — such as a person, organization, location, or product — that can be uniquely identified and referenced within a knowle...
- **Shipped (180):** A named entity is a real-world object — such as a person, organization, location, or product — that can be uniquely identified and referenced within a knowledge graph or AI system.
- **Why:** Opening sentence ≤200; used verbatim.

### `nap-consistency.mdx`  ·  verbatim
- **Old (160):** NAP consistency refers to the uniformity of a business's Name, Address, and Phone number across all online directories, social profiles, review sites, and li...
- **Shipped (164):** NAP consistency refers to the uniformity of a business's Name, Address, and Phone number across all online directories, social profiles, review sites, and listings.
- **Why:** Opening sentence ≤200; used verbatim.

### `native-search-behavior.mdx`  ·  A
- **Old (160):** Native search behavior refers to users conducting searches directly within a social platform — using TikTok's search bar, YouTube's search function, Instagra...
- **Candidate A (142):** Native search behavior refers to users conducting searches directly within a social platform rather than going to a traditional search engine.
- **Candidate B (92):** Native search behavior refers to users conducting searches directly within a social platform
- **Shipped (142):** Native search behavior refers to users conducting searches directly within a social platform rather than going to a traditional search engine.
- **Why:** Candidate A (paired-interruption removal) states the complete definition; B would drop the predicate or sever the clause.

### `near-me-search.mdx`  ·  B
- **Old (160):** Near-me search is a category of local search query in which a user specifies proximity as the primary criterion — 'coffee shops near me,' 'AI consultant near...
- **Candidate A (194):** Near-me search is a category of local search query in which a user specifies proximity as the primary criterion relying on their device's location data to return geographically relevant results.
- **Candidate B (161):** Near-me search is a category of local search query in which a user specifies proximity as the primary criterion — "coffee shops near me," "AI consultant near me"
- **Shipped (161):** Near-me search is a category of local search query in which a user specifies proximity as the primary criterion — "coffee shops near me," "AI consultant near me"
- **Why:** Both valid. Chose B: A reads as a dangling participle; B ends cleanly on the illustrative queries.

### `ner.mdx`  ·  A
- **Old (160):** Named entity recognition (NER) is a natural language processing technique that identifies and classifies named entities in text — people, organizations, loca...
- **Candidate A (155):** Named entity recognition (NER) is a natural language processing technique that identifies and classifies named entities in text into predefined categories.
- **Candidate B (127):** Named entity recognition (NER) is a natural language processing technique that identifies and classifies named entities in text
- **Shipped (155):** Named entity recognition (NER) is a natural language processing technique that identifies and classifies named entities in text into predefined categories.
- **Why:** Candidate A (paired-interruption removal) states the complete definition; B would drop the predicate or sever the clause.

### `neural-matching.mdx`  ·  B
- **Old (160):** Neural matching is Google's AI system for understanding the conceptual relationship between a search query and page content — moving beyond keyword matching ...
- **Candidate B (123):** Neural matching is Google's AI system for understanding the conceptual relationship between a search query and page content
- **Shipped (123):** Neural matching is Google's AI system for understanding the conceptual relationship between a search query and page content
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `neural-search.mdx`  ·  verbatim
- **Old (160):** Neural search is a search methodology that uses neural networks — specifically deep learning models — to understand the meaning of queries and documents rath...
- **Shipped (195):** Neural search is a search methodology that uses neural networks — specifically deep learning models — to understand the meaning of queries and documents rather than matching on keyword frequency.
- **Why:** Opening sentence ≤200; used verbatim.

### `no-click-search.mdx`  ·  verbatim
- **Old (160):** No-click search is a search session in which the user's information need is satisfied directly on the SERP or by an AI assistant — without the user clicking ...
- **Shipped (189):** No-click search is a search session in which the user's information need is satisfied directly on the SERP or by an AI assistant — without the user clicking through to any external website.
- **Why:** Opening sentence ≤200; used verbatim.

### `okrs.mdx`  ·  A
- **Old (160):** OKRs — Objectives and Key Results — are a goal-setting framework in which a company or team defines ambitious qualitative objectives alongside measurable key...
- **Candidate A (182):** OKRs are a goal-setting framework in which a company or team defines ambitious qualitative objectives alongside measurable key results that indicate progress toward those objectives.
- **Shipped (182):** OKRs are a goal-setting framework in which a company or team defines ambitious qualitative objectives alongside measurable key results that indicate progress toward those objectives.
- **Why:** Only Candidate A valid; complete definition.

### `ontology.mdx`  ·  verbatim
- **Old (160):** An ontology is a formal representation of knowledge within a domain — defining the entities, concepts, properties, and relationships that exist within that d...
- **Shipped (197):** An ontology is a formal representation of knowledge within a domain — defining the entities, concepts, properties, and relationships that exist within that domain and how they relate to each other.
- **Why:** Opening sentence ≤200; used verbatim.

### `opengraph.mdx`  ·  B
- **Old (160):** OpenGraph is a protocol using HTML meta tags to control how web pages are represented when shared on social platforms — providing title, description, and ima...
- **Candidate B (117):** OpenGraph is a protocol using HTML meta tags to control how web pages are represented when shared on social platforms
- **Shipped (117):** OpenGraph is a protocol using HTML meta tags to control how web pages are represented when shared on social platforms
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `organic-ai-mention.mdx`  ·  B
- **Old (160):** An organic AI mention is a reference to a brand in an AI-generated response that occurs without the brand directly prompting for it — appearing because the A...
- **Candidate B (131):** An organic AI mention is a reference to a brand in an AI-generated response that occurs without the brand directly prompting for it
- **Shipped (131):** An organic AI mention is a reference to a brand in an AI-generated response that occurs without the brand directly prompting for it
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `part-time-cmo.mdx`  ·  B
- **Old (160):** A part-time CMO is a senior marketing executive who works with a company on a reduced-hour basis — typically a set number of days per week or month — providi...
- **Candidate A (226):** A part-time CMO is a senior marketing executive who works with a company on a reduced-hour basis providing strategic marketing leadership without the full-time salary, benefits, and organizational overhead of a permanent hire.
- **Candidate B (147):** A part-time CMO is a senior marketing executive who works with a company on a reduced-hour basis — typically a set number of days per week or month
- **Shipped (147):** A part-time CMO is a senior marketing executive who works with a company on a reduced-hour basis — typically a set number of days per week or month
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `passage-ranking.mdx`  ·  hand-write
- **Old (160):** Passage ranking is Google's capability to identify and rank individual passages within a long document, enabling specific sections to appear in search result...
- **Shipped (158):** Passage ranking is Google's capability to identify and rank individual passages within a long document, enabling specific sections to appear in search results
- **Why:** Opening sentence >200 with only comma boundaries; hand-written to ≤200, reviewed and approved.

### `people-also-ask.mdx`  ·  hand-write
- **Old (160):** People Also Ask (PAA) is a Google SERP feature displaying a set of related questions with expandable answers, dynamically generated based on the user's query...
- **Shipped (153):** People Also Ask (PAA) is a Google SERP feature displaying a set of related questions with expandable answers, dynamically generated from the user's query
- **Why:** Opening sentence >200 with only comma boundaries; hand-written to ≤200, reviewed and approved.

### `performance-baseline.mdx`  ·  B
- **Old (160):** A performance baseline is the documented measurement of a brand's current marketing performance across key metrics — before any new strategy, campaign, or op...
- **Candidate A (197):** A performance baseline is the documented measurement of a brand's current marketing performance across key metrics establishing the starting point against which future performance will be measured.
- **Candidate B (181):** A performance baseline is the documented measurement of a brand's current marketing performance across key metrics — before any new strategy, campaign, or optimization effort begins
- **Shipped (181):** A performance baseline is the documented measurement of a brand's current marketing performance across key metrics — before any new strategy, campaign, or optimization effort begins
- **Why:** Both valid. Chose B: A produces the dangling participle "metrics establishing…"; B keeps the clause.

### `perplexity-pages.mdx`  ·  hand-write
- **Old (160):** Perplexity Pages is a feature within Perplexity AI that allows users to create structured, long-form research documents generated by the AI, with citations, ...
- **Shipped (176):** Perplexity Pages is a feature within Perplexity AI that allows users to create structured, long-form research documents generated by the AI, with citations and section headings
- **Why:** Opening sentence >200 with only comma boundaries; hand-written to ≤200, reviewed and approved.

### `pinterest-search.mdx`  ·  B
- **Old (160):** Pinterest search is the search and discovery system within Pinterest — a visual platform where users search for ideas, products, and inspiration using text q...
- **Candidate B (68):** Pinterest search is the search and discovery system within Pinterest
- **Shipped (68):** Pinterest search is the search and discovery system within Pinterest
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `platform-knowledge-graph.mdx`  ·  B
- **Old (160):** A platform knowledge graph is the internal structured data model a social platform uses to understand entities, relationships, and topics within its ecosyste...
- **Candidate B (158):** A platform knowledge graph is the internal structured data model a social platform uses to understand entities, relationships, and topics within its ecosystem
- **Shipped (158):** A platform knowledge graph is the internal structured data model a social platform uses to understand entities, relationships, and topics within its ecosystem
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `platform-native-seo.mdx`  ·  B
- **Old (160):** Platform-native SEO is the practice of optimizing content specifically for the search and discovery systems of individual social and content platforms — YouT...
- **Candidate A (219):** Platform-native SEO is the practice of optimizing content specifically for the search and discovery systems of individual social and content platforms rather than applying generic web SEO principles across all channels.
- **Candidate B (150):** Platform-native SEO is the practice of optimizing content specifically for the search and discovery systems of individual social and content platforms
- **Shipped (150):** Platform-native SEO is the practice of optimizing content specifically for the search and discovery systems of individual social and content platforms
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `positioning-statement.mdx`  ·  B
- **Old (160):** A positioning statement is a concise internal declaration of a brand's market position — defining the target audience, the category the brand competes in, th...
- **Candidate B (86):** A positioning statement is a concise internal declaration of a brand's market position
- **Shipped (86):** A positioning statement is a concise internal declaration of a brand's market position
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `post-training.mdx`  ·  B
- **Old (160):** Post-training refers to the processes applied to a foundation model after initial pre-training — including fine-tuning on task-specific data, reinforcement l...
- **Candidate B (94):** Post-training refers to the processes applied to a foundation model after initial pre-training
- **Shipped (94):** Post-training refers to the processes applied to a foundation model after initial pre-training
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `practitioner-voice.mdx`  ·  verbatim
- **Old (160):** Practitioner voice is a writing style characterized by direct, specific, experience-based authority — the tone of someone who has done the work rather than r...
- **Shipped (171):** Practitioner voice is a writing style characterized by direct, specific, experience-based authority — the tone of someone who has done the work rather than reported on it.
- **Why:** Opening sentence ≤200; used verbatim.

### `pre-training.mdx`  ·  B
- **Old (160):** Pre-training is the initial phase of large language model development in which the model is trained on a massive, general-purpose dataset — typically a large...
- **Candidate A (237):** Pre-training is the initial phase of large language model development in which the model is trained on a massive, general-purpose dataset to develop general language understanding and world knowledge before any task-specific fine-tuning.
- **Candidate B (137):** Pre-training is the initial phase of large language model development in which the model is trained on a massive, general-purpose dataset
- **Shipped (137):** Pre-training is the initial phase of large language model development in which the model is trained on a massive, general-purpose dataset
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `preferred-source-program.mdx`  ·  B
- **Old (160):** A preferred source program is a formal arrangement between a content publisher and an AI platform in which the publisher's content is given priority retrieva...
- **Candidate B (165):** A preferred source program is a formal arrangement between a content publisher and an AI platform in which the publisher's content is given priority retrieval status
- **Shipped (165):** A preferred source program is a formal arrangement between a content publisher and an AI platform in which the publisher's content is given priority retrieval status
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `preferred-source.mdx`  ·  special (content change)
- **Old (160):** Google evaluates websites for topic authority through signals such as E-E-A-T — Experience, Expertise, Authoritativeness, and Trustworthiness — to determine ...
- **Shipped (159):** A preferred source is a website or publisher that a search engine or AI system consistently favors and cites for a given topic, based on demonstrated authority
- **Why:** Genuine self-definition defect: the opening ## Definition sentence described Google/E-E-A-T and never defined the term. Body sentence rewritten (term as subject, nuance preserved and reordered after); description trimmed to a positive ≤200 form (the negation clause "rather than a formal designation" stays in the body only, to avoid a weak snippet).

### `prerendering.mdx`  ·  B
- **Old (160):** Prerendering is a technique in which a server pre-generates fully rendered HTML versions of JavaScript-heavy pages, making complete content — including struc...
- **Candidate A (201):** Prerendering is a technique in which a server pre-generates fully rendered HTML versions of JavaScript-heavy pages, making complete content available to crawlers without requiring JavaScript execution.
- **Candidate B (167):** Prerendering is a technique in which a server pre-generates fully rendered HTML versions of JavaScript-heavy pages, making complete content — including structured data
- **Shipped (167):** Prerendering is a technique in which a server pre-generates fully rendered HTML versions of JavaScript-heavy pages, making complete content — including structured data
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `primary-source.mdx`  ·  A
- **Old (160):** A primary source is original, firsthand documentation of a subject — including original research, official reports, legal documents, direct data, or first-pe...
- **Candidate A (157):** A primary source is original, firsthand documentation of a subject as opposed to secondary sources that interpret, summarize, or comment on primary material.
- **Candidate B (170):** A primary source is original, firsthand documentation of a subject — including original research, official reports, legal documents, direct data, or first-person accounts
- **Shipped (157):** A primary source is original, firsthand documentation of a subject as opposed to secondary sources that interpret, summarize, or comment on primary material.
- **Why:** Candidate A (paired-interruption removal) states the complete definition; B would drop the predicate or sever the clause.

### `prominence-signal.mdx`  ·  B
- **Old (160):** A prominence signal is any piece of evidence that indicates an entity is well-known, widely-referenced, or significant within its domain — including inbound ...
- **Candidate B (136):** A prominence signal is any piece of evidence that indicates an entity is well-known, widely-referenced, or significant within its domain
- **Shipped (136):** A prominence signal is any piece of evidence that indicates an entity is well-known, widely-referenced, or significant within its domain
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `prompt-engineering.mdx`  ·  verbatim
- **Old (160):** Prompt engineering is the practice of designing and refining the inputs to an AI model — questions, instructions, context, and formatting — to produce more a...
- **Shipped (194):** Prompt engineering is the practice of designing and refining the inputs to an AI model — questions, instructions, context, and formatting — to produce more accurate, useful, or specific outputs.
- **Why:** Opening sentence ≤200; used verbatim.

### `prompt-research.mdx`  ·  verbatim
- **Old (160):** Prompt research is the practice of analyzing the specific prompts and questions users submit to AI tools — used to inform content strategy for AI search opti...
- **Shipped (166):** Prompt research is the practice of analyzing the specific prompts and questions users submit to AI tools — used to inform content strategy for AI search optimization.
- **Why:** Opening sentence ≤200; used verbatim.

### `prompt-to-purchase.mdx`  ·  B
- **Old (160):** Prompt-to-purchase is the emerging buyer journey pattern in which a user moves directly from an AI-generated response to a purchase decision — using an AI as...
- **Candidate B (140):** Prompt-to-purchase is the emerging buyer journey pattern in which a user moves directly from an AI-generated response to a purchase decision
- **Shipped (140):** Prompt-to-purchase is the emerging buyer journey pattern in which a user moves directly from an AI-generated response to a purchase decision
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `prompt-visibility.mdx`  ·  B
- **Old (160):** Prompt visibility is a brand's presence in AI-generated responses to specific, relevant prompts — measured by how frequently the brand is mentioned, how prom...
- **Candidate B (95):** Prompt visibility is a brand's presence in AI-generated responses to specific, relevant prompts
- **Shipped (95):** Prompt visibility is a brand's presence in AI-generated responses to specific, relevant prompts
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `prompted-citation.mdx`  ·  A
- **Old (160):** A prompted citation is a brand mention that appears in an AI-generated response when the query directly asks about the brand — 'what does Plate Lunch Collect...
- **Candidate A (198):** A prompted citation is a brand mention that appears in an AI-generated response when the query directly asks about the brand as opposed to organic mentions that arise from category or topic queries.
- **Candidate B (189):** A prompted citation is a brand mention that appears in an AI-generated response when the query directly asks about the brand — "what does Plate Lunch Collective do," "tell me about [brand]"
- **Shipped (198):** A prompted citation is a brand mention that appears in an AI-generated response when the query directly asks about the brand as opposed to organic mentions that arise from category or topic queries.
- **Why:** Candidate A (paired-interruption removal) states the complete definition; B would drop the predicate or sever the clause.

### `proprietary-data.mdx`  ·  B
- **Old (160):** Proprietary data is information collected, measured, or analyzed by a brand that is not publicly available elsewhere — including internal benchmarks, client ...
- **Candidate B (116):** Proprietary data is information collected, measured, or analyzed by a brand that is not publicly available elsewhere
- **Shipped (116):** Proprietary data is information collected, measured, or analyzed by a brand that is not publicly available elsewhere
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `proximity-signal.mdx`  ·  B
- **Old (160):** A proximity signal is any piece of data that indicates a business's geographic relationship to a user or a query — including GPS coordinates, address data, s...
- **Candidate B (112):** A proximity signal is any piece of data that indicates a business's geographic relationship to a user or a query
- **Shipped (112):** A proximity signal is any piece of data that indicates a business's geographic relationship to a user or a query
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `query-expansion.mdx`  ·  verbatim
- **Old (160):** Query expansion is the process by which an AI system broadens or reformulates a user's query to retrieve a wider set of relevant documents before generating ...
- **Shipped (168):** Query expansion is the process by which an AI system broadens or reformulates a user's query to retrieve a wider set of relevant documents before generating a response.
- **Why:** Opening sentence ≤200; used verbatim.

### `query-understanding.mdx`  ·  verbatim
- **Old (160):** Query understanding is the process by which a search engine or AI system interprets the meaning, intent, and context of a user's query before generating a re...
- **Shipped (164):** Query understanding is the process by which a search engine or AI system interprets the meaning, intent, and context of a user's query before generating a response.
- **Why:** Opening sentence ≤200; used verbatim.

### `quote-ready-sentence.mdx`  ·  B
- **Old (160):** A quote-ready sentence is a self-contained statement that can be extracted from its surrounding context and used as a citation without losing meaning — typic...
- **Candidate B (149):** A quote-ready sentence is a self-contained statement that can be extracted from its surrounding context and used as a citation without losing meaning
- **Shipped (149):** A quote-ready sentence is a self-contained statement that can be extracted from its surrounding context and used as a citation without losing meaning
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `rdfa.mdx`  ·  B
- **Old (160):** RDFa (Resource Description Framework in Attributes) is an HTML5 extension for embedding structured linked data within web page content — one of three Google-...
- **Candidate B (134):** RDFa (Resource Description Framework in Attributes) is an HTML5 extension for embedding structured linked data within web page content
- **Shipped (134):** RDFa (Resource Description Framework in Attributes) is an HTML5 extension for embedding structured linked data within web page content
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `real-time-retrieval.mdx`  ·  verbatim
- **Old (160):** Real-time retrieval is the capability of an AI search tool to fetch and incorporate live web content at query time — rather than relying solely on static pre...
- **Shipped (172):** Real-time retrieval is the capability of an AI search tool to fetch and incorporate live web content at query time — rather than relying solely on static pre-training data.
- **Why:** Opening sentence ≤200; used verbatim.

### `real-time-web-access.mdx`  ·  verbatim
- **Old (160):** Real-time web access is the capability of an AI system to retrieve and incorporate live web content at the time of a query — as opposed to relying solely on ...
- **Shipped (178):** Real-time web access is the capability of an AI system to retrieve and incorporate live web content at the time of a query — as opposed to relying solely on static training data.
- **Why:** Opening sentence ≤200; used verbatim.

### `reddit-citation.mdx`  ·  hand-write
- **Old (160):** A Reddit citation is a reference to a brand, product, or piece of content within a Reddit post, comment, or thread that can be indexed, retrieved, and used a...
- **Shipped (181):** A Reddit citation is a reference to a brand, product, or piece of content within a Reddit post, comment, or thread that can be indexed, retrieved, and used as evidence by AI systems
- **Why:** Opening sentence >200 with only comma boundaries; hand-written to ≤200, reviewed and approved.

### `regional-entity.mdx`  ·  verbatim
- **Old (160):** A regional entity is the structured representation of a geographic region — a state, island chain, district, or multi-city area — within a knowledge graph or...
- **Shipped (172):** A regional entity is the structured representation of a geographic region — a state, island chain, district, or multi-city area — within a knowledge graph or schema system.
- **Why:** Opening sentence ≤200; used verbatim.

### `relevance-signal.mdx`  ·  A
- **Old (160):** A relevance signal is any factor — including keyword usage, semantic context, entity associations, and structured data — that indicates to a search engine or...
- **Candidate A (123):** A relevance signal is any factor that indicates to a search engine or AI system that content is pertinent to a given query.
- **Candidate B (118):** A relevance signal is any factor — including keyword usage, semantic context, entity associations, and structured data
- **Shipped (123):** A relevance signal is any factor that indicates to a search engine or AI system that content is pertinent to a given query.
- **Why:** Candidate A (paired-interruption removal) states the complete definition; B would drop the predicate or sever the clause.

### `retention-marketing.mdx`  ·  B
- **Old (160):** Retention marketing is the set of strategies and tactics designed to keep existing customers engaged, satisfied, and purchasing — including loyalty programs,...
- **Candidate B (127):** Retention marketing is the set of strategies and tactics designed to keep existing customers engaged, satisfied, and purchasing
- **Shipped (127):** Retention marketing is the set of strategies and tactics designed to keep existing customers engaged, satisfied, and purchasing
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `retrieval-frequency.mdx`  ·  B
- **Old (160):** Retrieval frequency is how often a specific piece of content or source is retrieved by AI systems across a defined set of relevant queries — measured by the ...
- **Candidate B (138):** Retrieval frequency is how often a specific piece of content or source is retrieved by AI systems across a defined set of relevant queries
- **Shipped (138):** Retrieval frequency is how often a specific piece of content or source is retrieved by AI systems across a defined set of relevant queries
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `retrieval-layer.mdx`  ·  B
- **Old (160):** The retrieval layer is the component of an AI search system responsible for finding and returning relevant content from an index in response to a query — sit...
- **Candidate B (151):** The retrieval layer is the component of an AI search system responsible for finding and returning relevant content from an index in response to a query
- **Shipped (151):** The retrieval layer is the component of an AI search system responsible for finding and returning relevant content from an index in response to a query
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `retrieval-manipulation.mdx`  ·  B
- **Old (160):** Retrieval manipulation is the attempt to artificially influence which content is retrieved by AI systems in response to specific queries — through techniques...
- **Candidate B (136):** Retrieval manipulation is the attempt to artificially influence which content is retrieved by AI systems in response to specific queries
- **Shipped (136):** Retrieval manipulation is the attempt to artificially influence which content is retrieved by AI systems in response to specific queries
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `retrieval-pipeline.mdx`  ·  B
- **Old (160):** A retrieval pipeline is the sequence of steps an AI system takes to find, rank, and return relevant content in response to a query — including query embeddin...
- **Candidate B (130):** A retrieval pipeline is the sequence of steps an AI system takes to find, rank, and return relevant content in response to a query
- **Shipped (130):** A retrieval pipeline is the sequence of steps an AI system takes to find, rank, and return relevant content in response to a query
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `revenue-marketing.mdx`  ·  B
- **Old (160):** Revenue marketing is a philosophy and practice that ties marketing activity directly to revenue outcomes — measuring marketing's contribution to pipeline, co...
- **Candidate B (104):** Revenue marketing is a philosophy and practice that ties marketing activity directly to revenue outcomes
- **Shipped (104):** Revenue marketing is a philosophy and practice that ties marketing activity directly to revenue outcomes
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `rich-result.mdx`  ·  A
- **Old (160):** A rich result is an enhanced search result that displays additional visual or interactive elements — such as star ratings, images, FAQs, prices, or event dat...
- **Candidate A (145):** A rich result is an enhanced search result that displays additional visual or interactive elements enabled by structured data markup on the page.
- **Candidate B (159):** A rich result is an enhanced search result that displays additional visual or interactive elements — such as star ratings, images, FAQs, prices, or event dates
- **Shipped (145):** A rich result is an enhanced search result that displays additional visual or interactive elements enabled by structured data markup on the page.
- **Why:** Candidate A (paired-interruption removal) states the complete definition; B would drop the predicate or sever the clause.

### `rich-snippet.mdx`  ·  verbatim
- **Old (160):** A rich snippet is an enhanced search result that displays additional information — such as ratings, prices, or event dates — pulled from structured data mark...
- **Shipped (172):** A rich snippet is an enhanced search result that displays additional information — such as ratings, prices, or event dates — pulled from structured data markup on the page.
- **Why:** Opening sentence ≤200; used verbatim.

### `search-everywhere-optimization.mdx`  ·  B
- **Old (160):** Search everywhere optimization is the practice of optimizing a brand's presence across all surfaces where users search for information — including Google, AI...
- **Candidate A (205):** Search everywhere optimization is the practice of optimizing a brand's presence across all surfaces where users search for information rather than focusing exclusively on traditional search engine results.
- **Candidate B (134):** Search everywhere optimization is the practice of optimizing a brand's presence across all surfaces where users search for information
- **Shipped (134):** Search everywhere optimization is the practice of optimizing a brand's presence across all surfaces where users search for information
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `search-intent.mdx`  ·  B
- **Old (160):** Search intent is the primary goal or purpose behind a user's search query — classified into informational (seeking to learn), navigational (seeking a specifi...
- **Candidate B (73):** Search intent is the primary goal or purpose behind a user's search query
- **Shipped (73):** Search intent is the primary goal or purpose behind a user's search query
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `self-contained-paragraph.mdx`  ·  verbatim
- **Old (160):** A self-contained paragraph is a paragraph that communicates a complete idea without requiring the reader — or an AI extraction system — to reference surround...
- **Shipped (184):** A self-contained paragraph is a paragraph that communicates a complete idea without requiring the reader — or an AI extraction system — to reference surrounding paragraphs for context.
- **Why:** Opening sentence ≤200; used verbatim.

### `semantic-authority.mdx`  ·  B
- **Old (160):** Semantic authority is the degree to which a brand or source is recognized by AI systems as an authoritative voice on a specific topic domain — built through ...
- **Candidate B (140):** Semantic authority is the degree to which a brand or source is recognized by AI systems as an authoritative voice on a specific topic domain
- **Shipped (140):** Semantic authority is the degree to which a brand or source is recognized by AI systems as an authoritative voice on a specific topic domain
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `semantic-completeness.mdx`  ·  B
- **Old (160):** Semantic completeness is the degree to which a piece of content covers all the concepts, sub-questions, and related terms that a thorough treatment of its to...
- **Candidate B (169):** Semantic completeness is the degree to which a piece of content covers all the concepts, sub-questions, and related terms that a thorough treatment of its topic requires
- **Shipped (169):** Semantic completeness is the degree to which a piece of content covers all the concepts, sub-questions, and related terms that a thorough treatment of its topic requires
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `semantic-html.mdx`  ·  B
- **Old (160):** Semantic HTML is the use of HTML elements that convey meaning about the structure and content of a page — using elements like article, section, header, nav, ...
- **Candidate B (103):** Semantic HTML is the use of HTML elements that convey meaning about the structure and content of a page
- **Shipped (103):** Semantic HTML is the use of HTML elements that convey meaning about the structure and content of a page
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `semantic-relevance.mdx`  ·  B
- **Old (160):** Semantic relevance is the degree to which content is contextually and conceptually related to a query or topic — assessed not by keyword matching but by mean...
- **Candidate B (110):** Semantic relevance is the degree to which content is contextually and conceptually related to a query or topic
- **Shipped (110):** Semantic relevance is the degree to which content is contextually and conceptually related to a query or topic
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `semantic-seo.mdx`  ·  B
- **Old (160):** Semantic SEO is an SEO approach focused on building comprehensive topical coverage and semantic relationships between concepts — optimizing for meaning, enti...
- **Candidate B (126):** Semantic SEO is an SEO approach focused on building comprehensive topical coverage and semantic relationships between concepts
- **Shipped (126):** Semantic SEO is an SEO approach focused on building comprehensive topical coverage and semantic relationships between concepts
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `semantic-triple.mdx`  ·  verbatim
- **Old (160):** A semantic triple is a fundamental unit of knowledge representation in the form of subject–predicate–object — for example, 'Plate Lunch Collective – is locat...
- **Shipped (173):** A semantic triple is a fundamental unit of knowledge representation in the form of subject–predicate–object — for example, "Plate Lunch Collective – is located in – Hawaii."
- **Why:** Opening sentence ≤200; used verbatim.

### `sentiment-analysis.mdx`  ·  verbatim
- **Old (160):** Sentiment analysis is the computational process of identifying and categorizing the emotional tone of text — positive, negative, or neutral — toward a brand,...
- **Shipped (184):** Sentiment analysis is the computational process of identifying and categorizing the emotional tone of text — positive, negative, or neutral — toward a brand, product, topic, or entity.
- **Why:** Opening sentence ≤200; used verbatim.

### `sentiment-signal.mdx`  ·  B
- **Old (160):** A sentiment signal is a measurable indicator of the emotional tone of content about a brand — positive, neutral, or negative — used by AI systems to assess b...
- **Candidate A (203):** A sentiment signal is a measurable indicator of the emotional tone of content about a brand used by AI systems to assess brand reputation and trustworthiness when generating characterizations of a brand.
- **Candidate B (124):** A sentiment signal is a measurable indicator of the emotional tone of content about a brand — positive, neutral, or negative
- **Shipped (124):** A sentiment signal is a measurable indicator of the emotional tone of content about a brand — positive, neutral, or negative
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `serp-feature.mdx`  ·  A
- **Old (160):** A SERP feature is any non-standard element displayed on a search results page — such as featured snippets, knowledge panels, image packs, local packs, People...
- **Candidate A (134):** A SERP feature is any non-standard element displayed on a search results page that enhances or replaces traditional blue-link results.
- **Candidate B (189):** A SERP feature is any non-standard element displayed on a search results page — such as featured snippets, knowledge panels, image packs, local packs, People Also Ask boxes, or AI Overviews
- **Shipped (134):** A SERP feature is any non-standard element displayed on a search results page that enhances or replaces traditional blue-link results.
- **Why:** Candidate A (paired-interruption removal) states the complete definition; B would drop the predicate or sever the clause.

### `serp-volatility.mdx`  ·  verbatim
- **Old (160):** SERP volatility is the degree of fluctuation in search engine results page rankings over time — used as an indicator of algorithm updates, competitive shifts...
- **Shipped (186):** SERP volatility is the degree of fluctuation in search engine results page rankings over time — used as an indicator of algorithm updates, competitive shifts, or content quality changes.
- **Why:** Opening sentence ≤200; used verbatim.

### `share-of-intent.mdx`  ·  verbatim
- **Old (160):** Share of intent is the proportion of user queries expressing a specific intent — a purchase consideration, a research goal, a problem to solve — in which a b...
- **Shipped (196):** Share of intent is the proportion of user queries expressing a specific intent — a purchase consideration, a research goal, a problem to solve — in which a brand appears in AI-generated responses.
- **Why:** Opening sentence ≤200; used verbatim.

### `share-of-model.mdx`  ·  B
- **Old (160):** Share of model is the percentage of relevant AI-generated responses in which a brand is mentioned or cited, relative to the total mentions or citations of al...
- **Candidate B (182):** Share of model is the percentage of relevant AI-generated responses in which a brand is mentioned or cited, relative to the total mentions or citations of all brands in that category
- **Shipped (182):** Share of model is the percentage of relevant AI-generated responses in which a brand is mentioned or cited, relative to the total mentions or citations of all brands in that category
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `share-of-retrieval.mdx`  ·  B
- **Old (160):** Share of retrieval is the proportion of retrieval events for a defined topic or query category that return a specific brand's content — measuring how much of...
- **Candidate B (133):** Share of retrieval is the proportion of retrieval events for a defined topic or query category that return a specific brand's content
- **Shipped (133):** Share of retrieval is the proportion of retrieval events for a defined topic or query category that return a specific brand's content
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `short-form-video-seo.mdx`  ·  B
- **Old (160):** Short-form video SEO is the practice of optimizing videos under 60–90 seconds on platforms like TikTok, Instagram Reels, and YouTube Shorts for discovery thr...
- **Candidate B (194):** Short-form video SEO is the practice of optimizing videos under 60–90 seconds on platforms like TikTok, Instagram Reels, and YouTube Shorts for discovery through platform search and AI retrieval
- **Shipped (194):** Short-form video SEO is the practice of optimizing videos under 60–90 seconds on platforms like TikTok, Instagram Reels, and YouTube Shorts for discovery through platform search and AI retrieval
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `site-authority.mdx`  ·  B
- **Old (160):** Site authority is the aggregate measure of a website's credibility and trustworthiness as assessed by search engines and AI systems — built from inbound link...
- **Candidate B (131):** Site authority is the aggregate measure of a website's credibility and trustworthiness as assessed by search engines and AI systems
- **Shipped (131):** Site authority is the aggregate measure of a website's credibility and trustworthiness as assessed by search engines and AI systems
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `sitelinks.mdx`  ·  verbatim
- **Old (160):** Sitelinks are additional links to internal pages of a website displayed beneath the main result in Google Search — typically shown for branded queries on aut...
- **Shipped (176):** Sitelinks are additional links to internal pages of a website displayed beneath the main result in Google Search — typically shown for branded queries on authoritative domains.
- **Why:** Opening sentence ≤200; used verbatim.

### `snippet-optimization.mdx`  ·  B
- **Old (160):** Snippet optimization is the practice of structuring content to maximize the likelihood of being selected as a featured snippet or AI-extracted passage — usin...
- **Candidate B (150):** Snippet optimization is the practice of structuring content to maximize the likelihood of being selected as a featured snippet or AI-extracted passage
- **Shipped (150):** Snippet optimization is the practice of structuring content to maximize the likelihood of being selected as a featured snippet or AI-extracted passage
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `social-content-infrastructure.mdx`  ·  hand-write
- **Old (160):** Social content infrastructure is the systematic architecture of a brand's social media presence — designed to function as a durable retrieval surface rather ...
- **Shipped (189):** Social content infrastructure is the systematic architecture of a brand's social media presence, designed to function as a durable retrieval surface rather than a series of individual posts
- **Why:** Opening sentence >200 with only comma boundaries; hand-written to ≤200, reviewed and approved.

### `social-corpus.mdx`  ·  A
- **Old (160):** The social corpus is the aggregate body of social media content — posts, videos, comments, profiles, threads — that has been indexed by AI systems and is ava...
- **Candidate A (170):** The social corpus is the aggregate body of social media content that has been indexed by AI systems and is available for retrieval when generating social-sourced answers.
- **Candidate B (108):** The social corpus is the aggregate body of social media content — posts, videos, comments, profiles, threads
- **Shipped (170):** The social corpus is the aggregate body of social media content that has been indexed by AI systems and is available for retrieval when generating social-sourced answers.
- **Why:** Candidate A (paired-interruption removal) states the complete definition; B would drop the predicate or sever the clause.

### `social-discoverability.mdx`  ·  hand-write
- **Old (160):** Social discoverability is the degree to which a brand's social media content surfaces in response to relevant queries through platform-native search, AI-gene...
- **Shipped (181):** Social discoverability is the degree to which a brand's social media content surfaces in response to relevant queries through platform-native search and AI-generated recommendations
- **Why:** Opening sentence >200 with only comma boundaries; hand-written to ≤200, reviewed and approved.

### `social-entity-signal.mdx`  ·  B
- **Old (160):** A social entity signal is any structured or semi-structured piece of information about an entity that appears on a social platform — including profile bios, ...
- **Candidate A (210):** A social entity signal is any structured or semi-structured piece of information about an entity that appears on a social platform that AI systems use to build or corroborate their understanding of that entity.
- **Candidate B (130):** A social entity signal is any structured or semi-structured piece of information about an entity that appears on a social platform
- **Shipped (130):** A social entity signal is any structured or semi-structured piece of information about an entity that appears on a social platform
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `social-search.mdx`  ·  A
- **Old (160):** Social search is the use of social media platforms — TikTok, YouTube, Instagram, Reddit, Pinterest, LinkedIn — as primary search interfaces, where users ente...
- **Candidate A (197):** Social search is the use of social media platforms as primary search interfaces, where users enter queries and receive results from platform-native content rather than from traditional web indexes.
- **Candidate B (108):** Social search is the use of social media platforms — TikTok, YouTube, Instagram, Reddit, Pinterest, LinkedIn
- **Shipped (197):** Social search is the use of social media platforms as primary search interfaces, where users enter queries and receive results from platform-native content rather than from traditional web indexes.
- **Why:** Candidate A (paired-interruption removal) states the complete definition; B would drop the predicate or sever the clause.

### `source-diversity-score.mdx`  ·  B
- **Old (160):** Source diversity score is a measure of how many distinct, independent sources are citing or referencing a brand across AI-generated responses — assessing whe...
- **Candidate B (141):** Source diversity score is a measure of how many distinct, independent sources are citing or referencing a brand across AI-generated responses
- **Shipped (141):** Source diversity score is a measure of how many distinct, independent sources are citing or referencing a brand across AI-generated responses
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `sparse-retrieval.mdx`  ·  verbatim
- **Old (160):** Sparse retrieval is a method of information retrieval that matches documents to queries based on keyword frequency and overlap — using techniques like TF-IDF...
- **Shipped (167):** Sparse retrieval is a method of information retrieval that matches documents to queries based on keyword frequency and overlap — using techniques like TF-IDF and BM25.
- **Why:** Opening sentence ≤200; used verbatim.

### `sprint-methodology.mdx`  ·  verbatim
- **Old (160):** Sprint methodology is an approach to executing marketing work in defined, time-boxed periods — with clear objectives, deliverables, and review milestones at ...
- **Shipped (180):** Sprint methodology is an approach to executing marketing work in defined, time-boxed periods — with clear objectives, deliverables, and review milestones at the end of each sprint.
- **Why:** Opening sentence ≤200; used verbatim.

### `strategic-counsel.mdx`  ·  verbatim
- **Old (160):** Strategic counsel is advisory engagement at the executive level — providing strategic direction, decision-making frameworks, and senior perspective without d...
- **Shipped (185):** Strategic counsel is advisory engagement at the executive level — providing strategic direction, decision-making frameworks, and senior perspective without direct operational execution.
- **Why:** Opening sentence ≤200; used verbatim.

### `structured-answer.mdx`  ·  B
- **Old (160):** A structured answer is a response format in which information is organized using clear headings, bullet points, numbered lists, or tables — making it easy fo...
- **Candidate B (137):** A structured answer is a response format in which information is organized using clear headings, bullet points, numbered lists, or tables
- **Shipped (137):** A structured answer is a response format in which information is organized using clear headings, bullet points, numbered lists, or tables
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `structured-snippet.mdx`  ·  verbatim
- **Old (160):** A structured snippet is a type of rich result that displays a table or list of specific attributes about a product, service, or entity — enabled by structure...
- **Shipped (171):** A structured snippet is a type of rich result that displays a table or list of specific attributes about a product, service, or entity — enabled by structured data markup.
- **Why:** Opening sentence ≤200; used verbatim.

### `subgraph.mdx`  ·  verbatim
- **Old (160):** A subgraph is a subset of a larger knowledge graph focused on a specific entity or topic domain — used by AI systems to reason about relationships within a b...
- **Shipped (172):** A subgraph is a subset of a larger knowledge graph focused on a specific entity or topic domain — used by AI systems to reason about relationships within a bounded context.
- **Why:** Opening sentence ≤200; used verbatim.

### `sxo.mdx`  ·  B
- **Old (160):** Search experience optimization (SXO) is the practice of optimizing both the search visibility of content and the user experience of the content itself — comb...
- **Candidate B (150):** Search experience optimization (SXO) is the practice of optimizing both the search visibility of content and the user experience of the content itself
- **Shipped (150):** Search experience optimization (SXO) is the practice of optimizing both the search visibility of content and the user experience of the content itself
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `synthetic-brand-signal.mdx`  ·  A
- **Old (160):** A synthetic brand signal is an entity or content signal about a brand that was created artificially — through paid placements disguised as editorial content,...
- **Candidate A (184):** A synthetic brand signal is an entity or content signal about a brand that was created artificially rather than earned through genuine third-party coverage and authentic user activity.
- **Candidate B (99):** A synthetic brand signal is an entity or content signal about a brand that was created artificially
- **Shipped (184):** A synthetic brand signal is an entity or content signal about a brand that was created artificially rather than earned through genuine third-party coverage and authentic user activity.
- **Why:** Candidate A (paired-interruption removal) states the complete definition; B would drop the predicate or sever the clause.

### `technical-crawlability.mdx`  ·  B
- **Old (160):** Technical crawlability is the ability of search engine and AI crawlers to access, navigate, and fully read a website's content — affected by server configura...
- **Candidate B (126):** Technical crawlability is the ability of search engine and AI crawlers to access, navigate, and fully read a website's content
- **Shipped (126):** Technical crawlability is the ability of search engine and AI crawlers to access, navigate, and fully read a website's content
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `technical-seo.mdx`  ·  A
- **Old (160):** Technical SEO is the practice of optimizing a website's infrastructure — server configuration, site speed, crawlability, indexability, structured data implem...
- **Candidate A (175):** Technical SEO is the practice of optimizing a website's infrastructure to ensure that search engines and AI crawlers can access, understand, and index its content effectively.
- **Candidate B (187):** Technical SEO is the practice of optimizing a website's infrastructure — server configuration, site speed, crawlability, indexability, structured data implementation, and rendering method
- **Shipped (175):** Technical SEO is the practice of optimizing a website's infrastructure to ensure that search engines and AI crawlers can access, understand, and index its content effectively.
- **Why:** Candidate A (paired-interruption removal) states the complete definition; B would drop the predicate or sever the clause.

### `technology-audit.mdx`  ·  B
- **Old (160):** A technology audit is a systematic review of a company's existing marketing technology stack — assessing tool redundancy, integration gaps, data quality, and...
- **Candidate B (92):** A technology audit is a systematic review of a company's existing marketing technology stack
- **Shipped (92):** A technology audit is a systematic review of a company's existing marketing technology stack
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `thought-leadership.mdx`  ·  B
- **Old (160):** Thought leadership content is original, perspective-driven content that advances a conversation in a field — offering a distinctive point of view, a novel fr...
- **Candidate B (106):** Thought leadership content is original, perspective-driven content that advances a conversation in a field
- **Shipped (106):** Thought leadership content is original, perspective-driven content that advances a conversation in a field
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `tiktok-search.mdx`  ·  verbatim
- **Old (160):** TikTok's in-app search functionality has become a significant discovery surface — particularly among younger demographics — for product, brand, how-to, and l...
- **Shipped (170):** TikTok's in-app search functionality has become a significant discovery surface — particularly among younger demographics — for product, brand, how-to, and local queries.
- **Why:** Opening sentence ≤200; used verbatim.

### `tiktok-seo.mdx`  ·  B
- **Old (160):** TikTok SEO is the practice of optimizing video content on TikTok to appear in TikTok's native search results — using keyword-rich captions, spoken keywords i...
- **Candidate B (108):** TikTok SEO is the practice of optimizing video content on TikTok to appear in TikTok's native search results
- **Shipped (108):** TikTok SEO is the practice of optimizing video content on TikTok to appear in TikTok's native search results
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `title-tag.mdx`  ·  B
- **Old (160):** A title tag is an HTML element specifying the title of a web page — displayed in browser tabs, search engine results, and used by AI systems as a primary con...
- **Candidate B (65):** A title tag is an HTML element specifying the title of a web page
- **Shipped (65):** A title tag is an HTML element specifying the title of a web page
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `topic-cluster.mdx`  ·  hand-write
- **Old (160):** A topic cluster is a content architecture in which a central pillar page covers a broad topic comprehensively, supported by a set of cluster pages covering r...
- **Shipped (173):** A topic cluster is a content architecture in which a central pillar page covers a broad topic comprehensively, supported by cluster pages covering related subtopics in depth
- **Why:** Opening sentence >200 with only comma boundaries; hand-written to ≤200, reviewed and approved.

### `topic-entity.mdx`  ·  verbatim
- **Old (160):** A topic entity is a structured representation of a concept, subject, or area of knowledge within a knowledge graph — distinct from people, organizations, and...
- **Shipped (165):** A topic entity is a structured representation of a concept, subject, or area of knowledge within a knowledge graph — distinct from people, organizations, and places.
- **Why:** Opening sentence ≤200; used verbatim.

### `topic-modeling.mdx`  ·  verbatim
- **Old (160):** Topic modeling is a machine learning technique that identifies the underlying themes or topics present in a collection of documents by analyzing patterns of ...
- **Shipped (176):** Topic modeling is a machine learning technique that identifies the underlying themes or topics present in a collection of documents by analyzing patterns of word co-occurrence.
- **Why:** Opening sentence ≤200; used verbatim.

### `topical-authority.mdx`  ·  B
- **Old (160):** Topical authority is the degree to which a website, brand, or source is recognized by AI systems and search engines as a credible, comprehensive, and expert ...
- **Candidate B (192):** Topical authority is the degree to which a website, brand, or source is recognized by AI systems and search engines as a credible, comprehensive, and expert source on a specific subject domain
- **Shipped (192):** Topical authority is the degree to which a website, brand, or source is recognized by AI systems and search engines as a credible, comprehensive, and expert source on a specific subject domain
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `topical-completeness.mdx`  ·  B
- **Old (160):** Topical completeness is the degree to which a brand's content portfolio covers all the significant questions, subtopics, and related concepts within its clai...
- **Candidate B (178):** Topical completeness is the degree to which a brand's content portfolio covers all the significant questions, subtopics, and related concepts within its claimed area of expertise
- **Shipped (178):** Topical completeness is the degree to which a brand's content portfolio covers all the significant questions, subtopics, and related concepts within its claimed area of expertise
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `topical-depth.mdx`  ·  B
- **Old (160):** Topical depth is the degree to which a piece of content addresses its subject with thoroughness, precision, and expert-level detail — going beyond surface-le...
- **Candidate B (131):** Topical depth is the degree to which a piece of content addresses its subject with thoroughness, precision, and expert-level detail
- **Shipped (131):** Topical depth is the degree to which a piece of content addresses its subject with thoroughness, precision, and expert-level detail
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `topical-gap.mdx`  ·  B
- **Old (160):** A topical gap is a question, subtopic, or related concept within a brand's claimed domain of expertise that is not addressed by any existing piece of the bra...
- **Candidate B (169):** A topical gap is a question, subtopic, or related concept within a brand's claimed domain of expertise that is not addressed by any existing piece of the brand's content
- **Shipped (169):** A topical gap is a question, subtopic, or related concept within a brand's claimed domain of expertise that is not addressed by any existing piece of the brand's content
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `topical-map.mdx`  ·  B
- **Old (160):** A topical map is a structured inventory of all the questions, subtopics, and related concepts within a brand's claimed area of expertise — organized by clust...
- **Candidate B (136):** A topical map is a structured inventory of all the questions, subtopics, and related concepts within a brand's claimed area of expertise
- **Shipped (136):** A topical map is a structured inventory of all the questions, subtopics, and related concepts within a brand's claimed area of expertise
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `tourism-marketing.mdx`  ·  B
- **Old (160):** Tourism marketing is the set of strategies and tactics used to attract visitors to a destination — including destination branding, content marketing, influen...
- **Candidate B (96):** Tourism marketing is the set of strategies and tactics used to attract visitors to a destination
- **Shipped (96):** Tourism marketing is the set of strategies and tactics used to attract visitors to a destination
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `transcript-optimization.mdx`  ·  B
- **Old (160):** Transcript optimization is the practice of editing auto-generated or raw transcripts of video and audio content to improve their accuracy, entity clarity, an...
- **Candidate B (176):** Transcript optimization is the practice of editing auto-generated or raw transcripts of video and audio content to improve their accuracy, entity clarity, and keyword structure
- **Shipped (176):** Transcript optimization is the practice of editing auto-generated or raw transcripts of video and audio content to improve their accuracy, entity clarity, and keyword structure
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `trust-signal.mdx`  ·  verbatim
- **Old (160):** A trust signal is any element of a website, content piece, or brand's digital presence that indicates credibility and reliability to search engines, AI syste...
- **Shipped (177):** A trust signal is any element of a website, content piece, or brand's digital presence that indicates credibility and reliability to search engines, AI systems, and human users.
- **Why:** Opening sentence ≤200; used verbatim.

### `trustrank.mdx`  ·  B
- **Old (160):** TrustRank is an algorithm that measures the trustworthiness of a web page based on its proximity to known authoritative seed pages — used to combat spam and ...
- **Candidate B (130):** TrustRank is an algorithm that measures the trustworthiness of a web page based on its proximity to known authoritative seed pages
- **Shipped (130):** TrustRank is an algorithm that measures the trustworthiness of a web page based on its proximity to known authoritative seed pages
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `ugc.mdx`  ·  verbatim
- **Old (160):** User-generated content (UGC) is content created by users on platforms such as Reddit, YouTube, review sites, and social media — including reviews, forum post...
- **Shipped (194):** User-generated content (UGC) is content created by users on platforms such as Reddit, YouTube, review sites, and social media — including reviews, forum posts, videos, and community discussions.
- **Why:** Opening sentence ≤200; used verbatim.

### `unprompted-citation.mdx`  ·  B
- **Old (160):** An unprompted citation is a brand mention that appears in an AI-generated response without the user specifically asking about the brand — occurring because t...
- **Candidate B (135):** An unprompted citation is a brand mention that appears in an AI-generated response without the user specifically asking about the brand
- **Shipped (135):** An unprompted citation is a brand mention that appears in an AI-generated response without the user specifically asking about the brand
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `unstructured-entity-signal.mdx`  ·  B
- **Old (160):** An unstructured entity signal is any reference to or information about an entity that appears in natural language text rather than in structured data formats...
- **Candidate B (157):** An unstructured entity signal is any reference to or information about an entity that appears in natural language text rather than in structured data formats
- **Shipped (157):** An unstructured entity signal is any reference to or information about an entity that appears in natural language text rather than in structured data formats
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `user-intent.mdx`  ·  verbatim
- **Old (160):** User intent is the underlying goal or need that motivates a user's search query — classified into informational, navigational, transactional, or commercial i...
- **Shipped (178):** User intent is the underlying goal or need that motivates a user's search query — classified into informational, navigational, transactional, or commercial investigation intents.
- **Why:** Opening sentence ≤200; used verbatim.

### `value-proposition.mdx`  ·  verbatim
- **Old (160):** A value proposition is the clear statement of the specific benefit a brand delivers to its customers — what it does, for whom, and why it is better than the ...
- **Shipped (170):** A value proposition is the clear statement of the specific benefit a brand delivers to its customers — what it does, for whom, and why it is better than the alternatives.
- **Why:** Opening sentence ≤200; used verbatim.

### `vector-database.mdx`  ·  verbatim
- **Old (160):** A vector database is a specialized database that stores content as high-dimensional numerical vectors — mathematical representations of meaning — rather than...
- **Shipped (166):** A vector database is a specialized database that stores content as high-dimensional numerical vectors — mathematical representations of meaning — rather than as text.
- **Why:** Opening sentence ≤200; used verbatim.

### `video-chapter-optimization.mdx`  ·  B
- **Old (160):** Video chapter optimization is the practice of dividing a long-form video into labeled chapters with descriptive titles — using YouTube's chapter feature or e...
- **Candidate A (220):** Video chapter optimization is the practice of dividing a long-form video into labeled chapters with descriptive titles to improve navigation, search relevance, and AI retrieval of specific segments within longer content.
- **Candidate B (181):** Video chapter optimization is the practice of dividing a long-form video into labeled chapters with descriptive titles — using YouTube's chapter feature or equivalent platform tools
- **Shipped (181):** Video chapter optimization is the practice of dividing a long-form video into labeled chapters with descriptive titles — using YouTube's chapter feature or equivalent platform tools
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `video-description-seo.mdx`  ·  B
- **Old (160):** Video description SEO is the practice of writing YouTube, TikTok, and other platform video descriptions to include target keywords, named entities, related t...
- **Candidate B (194):** Video description SEO is the practice of writing YouTube, TikTok, and other platform video descriptions to include target keywords, named entities, related topics, and explicit content summaries
- **Shipped (194):** Video description SEO is the practice of writing YouTube, TikTok, and other platform video descriptions to include target keywords, named entities, related topics, and explicit content summaries
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `video-indexation.mdx`  ·  B
- **Old (160):** Video indexation is the process by which a search engine or AI system crawls, processes, and adds a video to its retrieval index — making the video's content...
- **Candidate B (128):** Video indexation is the process by which a search engine or AI system crawls, processes, and adds a video to its retrieval index
- **Shipped (128):** Video indexation is the process by which a search engine or AI system crawls, processes, and adds a video to its retrieval index
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `visibility-gap.mdx`  ·  B
- **Old (160):** A visibility gap is the difference between a brand's current AI search visibility and its potential or target visibility for a defined set of queries — ident...
- **Candidate B (149):** A visibility gap is the difference between a brand's current AI search visibility and its potential or target visibility for a defined set of queries
- **Shipped (149):** A visibility gap is the difference between a brand's current AI search visibility and its potential or target visibility for a defined set of queries
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `visitor-economy.mdx`  ·  verbatim
- **Old (160):** The visitor economy encompasses all economic activity generated by people traveling to and within a destination — including spending on accommodations, food,...
- **Shipped (198):** The visitor economy encompasses all economic activity generated by people traveling to and within a destination — including spending on accommodations, food, experiences, transportation, and retail.
- **Why:** Opening sentence ≤200; used verbatim.

### `web-annotation.mdx`  ·  verbatim
- **Old (160):** Web annotation is the practice of adding structured metadata or markup to web content to make its meaning and context explicit for AI systems and linked data...
- **Shipped (171):** Web annotation is the practice of adding structured metadata or markup to web content to make its meaning and context explicit for AI systems and linked data applications.
- **Why:** Opening sentence ≤200; used verbatim.

### `weight-model.mdx`  ·  verbatim
- **Old (160):** In the context of language models, weights are the numerical parameters learned during training that encode the model's knowledge, associations, and behavior...
- **Shipped (169):** In the context of language models, weights are the numerical parameters learned during training that encode the model's knowledge, associations, and behavioral patterns.
- **Why:** Opening sentence ≤200; used verbatim.

### `wikipedia.mdx`  ·  verbatim
- **Old (160):** Wikipedia is the free online encyclopedia that constitutes a significant portion of LLM training data and serves as a primary entity authority source for kno...
- **Shipped (171):** Wikipedia is the free online encyclopedia that constitutes a significant portion of LLM training data and serves as a primary entity authority source for knowledge graphs.
- **Why:** Opening sentence ≤200; used verbatim.

### `word-embedding.mdx`  ·  verbatim
- **Old (160):** Word embedding is a technique for representing words as numerical vectors in a high-dimensional space, where words with similar meanings are positioned close...
- **Shipped (167):** Word embedding is a technique for representing words as numerical vectors in a high-dimensional space, where words with similar meanings are positioned close together.
- **Why:** Opening sentence ≤200; used verbatim.

### `zero-click-brand-awareness.mdx`  ·  B
- **Old (160):** Zero-click brand awareness is the brand recognition and association that accumulates when users encounter a brand in AI-generated responses without clicking ...
- **Candidate B (187):** Zero-click brand awareness is the brand recognition and association that accumulates when users encounter a brand in AI-generated responses without clicking through to the brand's website
- **Shipped (187):** Zero-click brand awareness is the brand recognition and association that accumulates when users encounter a brand in AI-generated responses without clicking through to the brand's website
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

### `zero-click-search.mdx`  ·  A
- **Old (160):** A zero-click search is a search session in which the user's query is answered directly on the results page — by a featured snippet, knowledge panel, AI Overv...
- **Candidate A (156):** A zero-click search is a search session in which the user's query is answered directly on the results page without the user clicking through to any website.
- **Candidate B (183):** A zero-click search is a search session in which the user's query is answered directly on the results page — by a featured snippet, knowledge panel, AI Overview, or other SERP feature
- **Shipped (156):** A zero-click search is a search session in which the user's query is answered directly on the results page without the user clicking through to any website.
- **Why:** Candidate A (paired-interruption removal) states the complete definition; B would drop the predicate or sever the clause.

### `zero-shot-learning.mdx`  ·  hand-write
- **Old (160):** Zero-shot learning is a machine learning paradigm in which a model performs tasks it was not explicitly trained on — relying on generalized knowledge from pr...
- **Shipped (171):** Zero-shot learning is a machine learning paradigm in which a model performs tasks it was never explicitly trained to do, relying on generalized knowledge from pre-training
- **Why:** Opening sentence >200 with only comma boundaries; hand-written to ≤200, reviewed and approved.

### `zero-shot-prompting.mdx`  ·  B
- **Old (160):** Zero-shot prompting is a prompting technique in which an LLM is asked to perform a task without being given any examples — relying entirely on its pre-traine...
- **Candidate B (120):** Zero-shot prompting is a prompting technique in which an LLM is asked to perform a task without being given any examples
- **Shipped (120):** Zero-shot prompting is a prompting technique in which an LLM is asked to perform a task without being given any examples
- **Why:** Candidate B (trim at trailing appositive); main clause is the complete definition, discarded tail is elaboration.

