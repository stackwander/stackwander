![Stackwander — Artificial Intelligence Engineering](assets/stackwander-banner.png)

## Hi there 👋

<!--
**stackwander/stackwander** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

## Projects

A catalog of applications, nested projects, prototypes, learning collections, and reusable templates. Related backend/frontend components and runnable agent lessons are listed separately; ML/DL exercises are summarized by topic. Descriptions reflect the source files and documentation available in this workspace. Imported templates and animation studies are identified as third-party references.

| Project name | Description |
| --- | --- |
| AccessHub (`access-hub`) | Central authentication and fine-grained access management with hierarchical permissions, roles, API keys, TOTP MFA, Google sign-in, and REST/gRPC integration; built with FastAPI, PostgreSQL, and Next.js. |
| AccessHub Test Client (`access-hub/testclient`) | Standalone Next.js consumer app for exercising authentication, MFA, account recovery, and permission checks, with a live request/response log. |
| App Hub (`custom-launch`) | Windows application and website launcher built with .NET MAUI and MVVM; supports categorized bookmarks, search, application icons, favicons, and persistent JSON storage. |
| EcomBot (`ecombot`) | Conversational commerce suite combining a streaming chat interface, LangGraph shopping agent, MCP commerce tools, and a searchable FAQ knowledge base. |
| EcomBot Backend (`ecombot/botbackend`) | FastAPI shopping-agent API using LangGraph and Mistral, with MCP tool discovery, SSE responses, session tokens, conversation memory, and input guardrails. |
| EcomMCP (`ecombot/ecommcp`) | MCP server exposing commerce and order-management tools, OAuth authentication, and FAQ retrieval backed by Pinecone and Cohere. |
| EcomBot RAG Builder (`ecombot/ecomragdbbuilder`) | CSV-to-Pinecone ingestion and semantic-search pipeline with Cohere embeddings and reranking, incremental updates, deduplication, stale-vector cleanup, and retries. |
| EcomBot Frontend (`ecombot/frontend/app`) | React, TypeScript, and Vite chat UI for streaming shopping conversations and displaying the agent's tool activity. |
| EcomBot Voice (`ecombotvoice-s2s`) | English/Urdu voice-commerce assistant using LiveKit and FastAPI, with browser calling, interruptions, commerce tools, and interchangeable speech and realtime-model pipelines. |
| WhatsApp Calls Bridge (`ecombotvoice-s2s/whatsapp_calls`) | Reusable Python integration connecting inbound and outbound WhatsApp Business calls to LiveKit voice agents, with webhook verification, room dispatch, and duplicate-event handling. |
| EcomBot Video Concept (`ecombotvoice-video`) | Architecture-only exploration of a portable voice/video commerce assistant using WebRTC, open models, avatar rendering, RAG, and containerized infrastructure. |
| AI Expense Assist (`expense-app`) | Mobile expense-management project combining an Expo/React Native client, local encrypted ledger, receipt capture, budgets, and optional Firebase identity and synchronization. |
| AI Expense Assist Mobile (`expense-app/frontend`) | Mobile frontend with expense and budget screens, receipt-camera integration, local storage, and an interchangeable backend adapter guided by an OpenAPI contract. |
| AI Expense Assist Firebase Backend (`expense-app/backend-firebase`) | Firebase Auth, Firestore rules, ledger mirroring, configuration, and device-token storage for the expense app; designed without a separate server process. |
| HaulEx (`haulage-project/frontend`) | Next.js frontend prototype of a UK haulage exchange with customer job posting, contractor quotes, vehicle matching, fleet management, and delivery details using mock data. |
| Haulage UI Studies (`haulage-project/code`) | Static dashboard and load-detail prototypes covering active and delivered haulage jobs, accompanied by design notes. |
| Convoy (`agents/haulage-multi-agent/convoy`) | CrewAI and FastAPI fleet-breakdown recovery demo with a React dashboard; dispatcher, planning, compliance, and communications agents compare options, request spend approval, retry execution, and retain preferences. |
| Marcato ERP (`marcato-erp/marcatoerp`) | Composable multi-tenant ERP under development, organized around commerce, warehouse, logistics, finance, tax, security, and AI modules; one modular-monolith artifact supports Solo, Growth, and Scale configurations. |
| Marcato Ops Console (`marcato-erp/marcatoerp/clients/ops_console`) | React/Vite administration shell with themes, tenant module controls, and versioned settings; additional business screens are planned as backend modules develop. |
| Marcato Storefront (`marcato-erp/marcatoerp/clients/storefront`) | Next.js commerce client with product browsing, product details, recommendations, a cart, stock helpers, and order-tracking pages. |
| Cedar Policy Benchmark (`starter-templates/backend-eventdriven-starter/spikes/6-cedar`) | Experimental Node.js benchmark comparing Cedar authorization paths, decision latency, and memory behavior across repeated policy reloads. |
| Ontology Backend (`zbackend-enterprise`) | Python enterprise-backend reference for multi-tenant ontologies and governed agent actions, combining PostgreSQL row isolation, policy checks, approval workflows, audit chains, transactional events, and semantic search. |
| Platform Access Bookmarks (`platformaccess/platformaccess-bookmarks`) | VS Code extension for organizing cloud and developer-console bookmarks, with categorized navigation, browser imports, favicon caching, search-friendly management, and JSON backup/restore. |
| Platform Access Design (`platformaccess/handoff/platformaccess`) | HTML/CSS/JavaScript design handoff for the bookmark extension, retained as the visual prototype rather than a separate production app. |
| Mobile App Starter (`starter-templates/mobile-app-starter`) | Copyable Expo/React Native starter with sign-in, second-factor, registration, recovery, account deletion, shared theming, a fake auth adapter, and a derived-app generator. |
| Event-Driven Backend Starter (`starter-templates/backend-eventdriven-starter`) | TypeScript/NestJS monorepo starter with a catalog reference service, tenant isolation, policy-based authorization, transactional outbox, messaging, API contracts, and observability tooling. |
| Backend API Starter (`starter-templates/backend-api-starter`) | Reserved starter-template folder; currently empty. |
| Web Frontend Starter (`starter-templates/web-frontend-starter`) | Reserved starter-template folder; currently empty. |
| CORSAI Static Site (`my-websites/coreai-simplest`) | Minimal HTML/CSS brand landing page with Firebase Hosting configuration. |
| CoreAI v1 (`my-websites/coreai_v1`) | Next.js agency landing page assembled from a hero, service bento grid, agent-terminal presentation, technology marquee, and contact section. |
| CoreAI v2 (`my-websites/coreai_v2`) | Vite agency marketing site with a Three.js energy-core visual, custom shaders, GSAP scroll animation, responsive navigation, and reduced-motion fallbacks. |
| Portfolio Base (`my-websites/portfolio-base/project`) | React/Vite personal portfolio foundation with configurable services, skills, projects, client logos, videos, gallery, and downloadable resources. |
| AI Engineering Portfolio (`my-websites/portfolio-ai/project`) | React/TypeScript portfolio focused on AI engineering services and projects, using configurable content, an animated wave background, interactive cards, and a lazy-loaded gallery. |
| Leadership Portfolio (`my-websites/portfolio-management/project`) | Engineering and AI leadership profile with capability groups, signature engagements, career history, credentials, and configurable impact metrics. |
| Projects Portfolio (`my-websites/portfolio-projects/project`) | React/Vite showcase organizing personal and company projects into reusable project cards with configurable descriptions and links. |
| Business Portfolio (`my-websites/portfolio-business`) | Reserved website folder; currently empty. |
| Agentic AI Examples (`agents/agentic-ai-examples`) | Six Python examples comparing OpenAI Agents SDK, AutoGen, CrewAI, and LangGraph through tools, handoffs, guardrails, team chat, automated data science, and graph workflows. |
| CrewAI Learning Projects (`agents/crewai-agents`) | Coffee-commerce learning collection with 22 core and nine bonus examples spanning tools, collaboration, memory, flows, human review, evaluation, observability, and a capstone pipeline. |
| LangGraph Learning Projects (`agents/lang-graph-agents`) | Twelve incremental Python agent examples, from a one-node graph through tool use, persistent state, human review, supervisors, map-reduce research, MCP, and peer handoffs. |
| Agentic AI Notes (`agents/markdown-notes`) | Reference notes explaining core agentic-AI terminology and architectural concepts. |
| Python Reference (`python-reference`) | Learning/reference collection covering Python fundamentals, NumPy, pandas, scikit-learn, basic machine learning, and Flask/FastAPI services. |
| Python Language Exercises (`python-reference/01pythonlang`) | Small Python examples for language fundamentals and common programming patterns. |
| NumPy Exercises (`python-reference/02numpy`) | Array-based numerical-computing examples for learning NumPy operations. |
| Pandas Exercises (`python-reference/03pandas`) | Data-analysis examples covering file input, reshaping, joins, cleaning, time series, statistics, categorical data, and ML preparation. |
| Scikit-learn Exercises (`python-reference/04scikitlearn`) | Classification and regression exercises with an assignment notebook and model save/load examples. |
| Machine Learning Basics (`python-reference/05machinelearning`) | Introductory preprocessing and simple linear-regression scripts with sample datasets and concept notes. |
| Python REST Examples (`python-reference/06pythonrest`) | Flask and FastAPI examples demonstrating HTTP APIs and token-based API access. |
| ML/DL Practice (`ml-dl-practice`) | Internal learning/reference collection spanning classical ML, deep learning, generative models, LLM adaptation, MLOps, and robotics; includes original and third-party material. |
| TypeScript Shop p2 (`typescript-0-to-1/backendcleants_p2`) | Earlier learning-project directory; its nested folder currently contains no project source files. |
| Clean TypeScript Shop p4 (`typescript-0-to-1/backendcleants_p4`) | Educational Express/Prisma/MongoDB commerce API with Clean Architecture, users and JWT authentication, Redis-backed login state, and monitoring integrations. |
| Clean TypeScript Shop p5 (`typescript-0-to-1/backendcleants_p5`) | Modular commerce API extending the Express/Prisma/MongoDB approach with validated contracts, transactional order handling, inventory protection, and container deployment. |
| NestJS Shop p6 (`typescript-0-to-1/backend_nest_p6`) | NestJS/TypeORM/PostgreSQL shop API with customers, products, orders, transactional inventory handling, validation, pagination, and idempotent operations. |
| NestJS Secure Shop p6_1 (`typescript-0-to-1/backend_nest_p6_1/backend_nest_p6_1`) | Secure shop API adding staff accounts, role-based access, JWT access tokens, database-backed sessions, and rotating refresh tokens to transactional commerce operations. |
| NestJS Auth Variant p6_1a (`typescript-0-to-1/backend_nest_p6_1/backend_nest_p6_1a`) | Separate shop API variant combining p6 inventory/order safeguards with revocable user sessions, refresh, logout, and authorization behavior. |
| NestJS GraphQL Shop p7 (`typescript-0-to-1/backend_nest_p7/backend_nest_p7`) | NestJS/Apollo/Prisma/PostgreSQL commerce API with code-first GraphQL, accounts, customer ownership checks, and transactional inventory protection. |
| React Dashboard p8 (`typescript-0-to-1/frontend_react_p8/frontend_react_p8`) | Vite/React/Material UI learning frontend combining marketing pages, registration, login, and a customer dashboard; backend contract updates still require integration adjustments. |
| n8n Agent Workflows (`nocode-n8n-flowise/N8NJSON`) | Exported automation workflows for research, email, calendar, project management, sales prospecting, and technical analysis; intended for import into n8n. |
| Flowise Collection (`nocode-n8n-flowise/FlowiseJSON`) | Reserved workflow-export folder; currently empty. |
| CoreUI React Admin (`ui-templates/coreui-free-react-admin-template-main`) | Third-party CoreUI admin template retained for reusable React layouts, navigation, forms, charts, and dashboard components. |
| Corona Admin (`ui-templates/corona-free-dark-bootstrap-admin-template-1.0.0`) | Third-party dark Bootstrap admin dashboard with example pages and UI components. |
| Material Dashboard React (`ui-templates/material-dashboard-react-main`) | Third-party Creative Tim Material Dashboard 2 React template with themed admin layouts and example management screens. |
| Devias Material Kit (`ui-templates/material-kit-react-main`) | Third-party Next.js/React/MUI admin starter with dashboard, customer, integrations, and account-oriented pages. |
| MUI Dashboard App (`ui-templates/mui-dashboard-app`) | Vite/React/TypeScript application hosting the Material UI dashboard template and shared theme components. |
| MUI Starter Templates (`ui-templates/MUI_Starter_templates_free2026`) | Third-party Material UI component templates for a dashboard, blog, checkout, marketing page, sign-in variants, and sign-up. |
| React RealWorld Blog (`ui-templates/react-vite-blogging`) | React/Vite implementation of the RealWorld blogging frontend, demonstrating authentication, article CRUD, and reusable API-driven application patterns. |
| Flux Dashboard (`ui-templates/recreation-1`) | Next.js/TypeScript admin-dashboard recreation with Tailwind, Recharts, shared UI primitives, and light/dark themes. |
| Eliott Portfolio (`ui-templates/recreation-2`) | Static designer/developer portfolio prototype with project listings, case studies, blog index, and article pages. |
| Aurora Dashboard (`ui-templates/recreation-3`) | Standalone React/Vite/TypeScript admin-dashboard recreation with Tailwind and locally bundled assets for offline use. |
| Sakai Vue (`ui-templates/sakai-vue-master`) | Third-party Vue/PrimeVue application template for building admin interfaces and dashboards with Vite. |
| Vite React Admin (`ui-templates/vite-react-ts-admin-template-master`) | Third-party React/TypeScript/Material UI admin template using Vite as a dashboard starting point. |
| TailAdmin Vue (`ui-templates/vue-tailwind-admin-dashboard-main`) | Third-party Vue and Tailwind admin template providing dashboard layouts, charts, forms, and reusable UI elements. |
| NexusAI Landing Page (`ui-templates/nexusai_v1`) | Static AI-agency concept site with animated neural visuals, service sections, case studies, team profiles, and a contact flow. |
| EternaCloud Design Study (`ui-templates/00_ask_ai_like_this/mixconcepts-templates`) | HTML/CSS/JavaScript marketing prototype combining animated visual concepts for a data-center product-management partner. |
| Animation Reference Collection (`ui-templates/00_ask_ai_like_this/animations`) | Third-party CodePen studies for loaders, particles, glass effects, SVG illusions, and GLSL shaders; original attribution is retained in each example's README. |
| Helper Scripts (`helper-scripts`) | Small utilities for converting Word documents to PDF and correcting Git author information. |
| Project Documentation (`Documentation`) | Supporting documentation for AccessHub, EcomBot Voice, and Convoy; companion material for those projects. |
| Film Assets (`movie`) | Creative-media folder containing character reference images and rendered scene clips for a video project. |
| Career Documents (`resume`) | Personal resume, cover-letter, and reference-document collection organized by year; supporting career material. |
| Stackwander Profile (`stackwander`) | GitHub profile README and banner assets, including this project catalog. |
| CrewAI — Hello Crew (`agents/crewai-agents/01_hello_crew`) | Single-agent coffee-tasting example introducing an Agent, Task, Crew, and kickoff. |
| CrewAI — Sequential Crew (`agents/crewai-agents/02_multi_agent_sequential_crew`) | Researcher, writer, and editor pass coffee-product work through sequential tasks. |
| CrewAI — Agent with Tools (`agents/crewai-agents/03_agent_with_tools`) | Market-research exercise using web-search and scraping tools to investigate coffee trends and pricing. |
| CrewAI — Custom Tools (`agents/crewai-agents/04_custom_tool_creation`) | Reusable pricing-calculator and inventory-lookup tools built with typed inputs. |
| CrewAI — Structured Output (`agents/crewai-agents/05_structured_output_pydantic`) | Generates typed product listings using Pydantic rather than unstructured prose. |
| CrewAI — Hierarchical Crew (`agents/crewai-agents/06_hierarchical_process`) | Manager-led product-onboarding exercise demonstrating delegation to specialist agents. |
| CrewAI — Agent Collaboration (`agents/crewai-agents/07_agent_collaboration_delegation`) | Specialist agents delegate work and request information from one another. |
| CrewAI — Crew Memory (`agents/crewai-agents/08_memory_system`) | Customer-support exercise exploring recall across repeated crew interactions. |
| CrewAI — Crew Knowledge/RAG (`agents/crewai-agents/09_knowledge_sources_rag`) | Answers commerce questions using catalog and policy knowledge sources. |
| CrewAI — Task Guardrails (`agents/crewai-agents/10_task_guardrails`) | Validates required product-listing fields and brand tone with retryable task checks. |
| CrewAI — First Flow (`agents/crewai-agents/11_first_flow`) | Event-driven bean-onboarding pipeline introducing flow start and listener steps. |
| CrewAI — Flow State (`agents/crewai-agents/12_flow_state_management`) | Tracks product-onboarding data through structured state and persistence. |
| CrewAI — Routing and Parallel Flows (`agents/crewai-agents/13_conditional_routing_parallel_execution`) | Branches on product quality and joins parallel marketing-generation steps. |
| CrewAI — Crews inside Flows (`agents/crewai-agents/14_crews_inside_flows`) | Orchestrates content and marketing crews as steps in a shared workflow. |
| CrewAI — Human Review (`agents/crewai-agents/15_human_in_the_loop`) | Pauses product publishing for human review and routes rejected content through revision. |
| CrewAI — Planning and Reasoning (`agents/crewai-agents/16_planning_reasoning`) | Catalog-planning exercise exploring agent planning and reasoning settings. |
| CrewAI — Checkpointing and Replay (`agents/crewai-agents/17_checkpointing_replay`) | Demonstrates saving, resuming, and revisiting stages of a multi-step workflow. |
| CrewAI — Crew Training and Testing (`agents/crewai-agents/18_training_testing_crews`) | Examples of feedback-based crew training and repeated output evaluation. |
| CrewAI — Crew MCP Integration (`agents/crewai-agents/19_mcp_server_integration`) | Connects agents to external MCP tools and demonstrates tool selection. |
| CrewAI — Crew Observability (`agents/crewai-agents/20_custom_event_listeners_observability`) | Event-listener example tracking execution timing, token usage, and tool activity. |
| CrewAI — Async Crews and Streaming (`agents/crewai-agents/21_async_execution_streaming`) | Runs product-listing jobs concurrently and consumes streaming crew output. |
| CrewAI — Bean-to-Storefront Capstone (`agents/crewai-agents/22_capstone_production_pipeline`) | Combines intake, grading, listing, pricing review, marketing, and inventory steps with state and observability. |
| CrewAI — Agent Skills (`agents/crewai-agents/B1_skills_skill_md`) | Coffee-grading example supplying reusable domain instructions through a skill file. |
| CrewAI — Multimodal Review (`agents/crewai-agents/B2_file_handling_vision_multimodal`) | Analyzes coffee-package imagery and returns structured design feedback. |
| CrewAI — Multiple LLM Providers (`agents/crewai-agents/B3_custom_llm_configuration`) | Demonstrates selecting different model providers for specialist roles. |
| CrewAI — Grading Tool Package (`agents/crewai-agents/B4_publishing_custom_tool_package`) | Packaged coffee-grading tool with typed behavior, usage example, and tests. |
| CrewAI — YAML Crew Configuration (`agents/crewai-agents/B5_yaml_configuration_crewbase`) | Defines agent roles and tasks in YAML using CrewBase conventions. |
| CrewAI — Crew A2A Example (`agents/crewai-agents/B6_a2a_protocol`) | Local client/server exercise delegating roast analysis to an external agent endpoint. |
| CrewAI — LLM Hooks (`agents/crewai-agents/B7_llm_hooks_prompt_customization`) | Demonstrates prompt templates and hooks around model calls for guidelines and output handling. |
| CrewAI — Scoped Memory (`agents/crewai-agents/B8_advanced_memory`) | Explores team-specific memory scopes and controlled cross-team recall. |
| CrewAI — Crew CLI and Visualization (`agents/crewai-agents/B9_cli_mastery_flow_visualization`) | Demonstrates a runnable flow with CLI-oriented project tooling and flow visualization. |
| LangGraph — Echo Graph (`agents/lang-graph-agents/01_lgecho`) | Minimal state graph introducing nodes, state, compilation, and invocation. |
| LangGraph — Conversational FAQ (`agents/lang-graph-agents/02_lgfaq`) | LLM chat graph passing message history through state for multi-turn conversations. |
| LangGraph — Calculator Agent (`agents/lang-graph-agents/03_lgcalculatoragent`) | Routes tool calls to arithmetic and unit-conversion nodes. |
| LangGraph — Web Search Agent (`agents/lang-graph-agents/04_lgwebsearchagent`) | ReAct-style loop combining web search, arithmetic, and unit conversion. |
| LangGraph — Research Summarizer (`agents/lang-graph-agents/05_lgsearchsummarizer`) | Searches and summarizes iteratively with explicit state and a bounded research loop. |
| LangGraph — Memory-Aware Assistant (`agents/lang-graph-agents/06_lgmemoryawareassist`) | Educational patient-profile example using checkpoints to retain context across sessions. |
| LangGraph — Human-Reviewed Cleanup (`agents/lang-graph-agents/07_lghumaninloop`) | Virtual-filesystem cleanup demo that pauses for review before deleting selected resources. |
| LangGraph — Code Writer (`agents/lang-graph-agents/08_lgcodewriteagent`) | Generates and executes Python, inspects errors, and retries within a bounded structured-output loop. |
| LangGraph — Supervisor Team (`agents/lang-graph-agents/09_lgsupervisormultiagent`) | Routes each task to a researcher, writer, or coder implemented as a separate graph. |
| LangGraph — Map-Reduce Reports (`agents/lang-graph-agents/091_reportmultiagent`) | Fans research into parallel subtopics and synthesizes the results into a report. |
| LangGraph — MCP Agent (`agents/lang-graph-agents/092_lgusingmcp`) | Discovers tools from an external MCP server and uses them in a ReAct graph. |
| LangGraph — Peer Handoffs (`agents/lang-graph-agents/093_lga2aexample`) | Travel-planning example using Command-based handoffs among specialized agent nodes. |
| ML/DL — Notes (`ml-dl-practice/Part 0 - Notes`) | Internal supporting learning notes and reference documents. |
| ML/DL — Data Preprocessing (`ml-dl-practice/Part 1 - Data Preprocessing`) | Preprocessing notebooks and reusable classification/regression templates. |
| ML/DL — Regression (`ml-dl-practice/Part 2 - Regression`) | Simple, multiple, polynomial, support-vector, tree, and random-forest regression exercises. |
| ML/DL — Classification (`ml-dl-practice/Part 3 - Classification`) | Logistic regression, nearest neighbors, SVM, naive Bayes, tree, and random-forest classification exercises. |
| ML/DL — Clustering (`ml-dl-practice/Part 4 - Clustering`) | K-means and hierarchical-clustering notebooks using sample datasets. |
| ML/DL — Association Rules (`ml-dl-practice/Part 5 - Association Rule Learning`) | Apriori and Eclat exercises for discovering co-occurring items. |
| ML/DL — Dimensionality Reduction (`ml-dl-practice/Part 6 - Dimensionality Reduction`) | PCA, linear discriminant analysis, and kernel-PCA exercises. |
| ML/DL — Model Selection and Boosting (`ml-dl-practice/Part 7 - Model Selection & Boosting`) | Cross-validation, grid search, XGBoost, and CatBoost exercises. |
| ML/DL — NLP Basics (`ml-dl-practice/Part 8 - Natural Language Processing`) | Text preprocessing and introductory natural-language classification notebook. |
| ML/DL — Neural Networks (`ml-dl-practice/Part 9 - Deep Learning`) | Introductory artificial-neural-network and convolutional-neural-network notebooks. |
| ML/DL — Bandit Methods (`ml-dl-practice/Part 10 - Reinforcement Learning`) | Upper Confidence Bound and Thompson Sampling exercises. |
| ML/DL — Model Adaptation (`ml-dl-practice/Part 11 - Deep Learning Advanced`) | Transfer learning, frozen backbones, LoRA/QLoRA, distillation, quantization, object detection, and speech-recognition examples. |
| ML/DL — Generative Modeling (`ml-dl-practice/Part 12 - Generative Modeling`) | Commented GAN, VAE, and diffusion-model learning scripts. |
| ML/DL — Self-Supervised Learning (`ml-dl-practice/Part 13 - Self-Supervised Learning`) | Examples exploring representation learning and self-supervised pretext tasks. |
| ML/DL — Advanced Transformers (`ml-dl-practice/Part 14 - Advanced Transformers`) | Architecture exercises exploring transformer mechanisms and vision applications. |
| ML/DL — Advanced LLM/NLP (`ml-dl-practice/Part 15 - LLM and NLP Advanced`) | Examples exploring preference alignment and techniques for adapting language models into assistants. |
| ML/DL — Advanced Computer Vision (`ml-dl-practice/Part 16 - Computer Vision Advanced`) | Exercises extending image classification to segmentation and vision/language tasks. |
| ML/DL — Deep Reinforcement Learning (`ml-dl-practice/Part 17 - Deep Reinforcement Learning`) | Runnable CartPole-oriented examples exploring deep value and policy learning. |
| ML/DL — Training Optimization (`ml-dl-practice/Part 18 - Training Techniques and Optimization`) | Examples of techniques for making neural-network training faster and more memory efficient. |
| ML/DL — MLOps (`ml-dl-practice/Part 19 - MLOps and Production`) | Learning scripts covering model deployment, operation, and monitoring. |
| ML/DL — Emerging Architectures (`ml-dl-practice/Part 20 - Research-Level and Emerging`) | From-scratch explorations of graph learning, meta-learning, automated design, interpretability, and post-transformer models. |
| ML/DL — Robotics and Embodied AI (`ml-dl-practice/Part 21 - Robotics and Embodied AI`) | Robot-learning exercises spanning imitation and reinforcement learning, perception, and modern embodied-AI approaches. |
| ML/DL — Deep Learning Pathway Labs (`ml-dl-practice/Part 22 - Deep Learning Pathway Exercises`) | Seven guided exercises organized around a reusable six-step training loop. |
| ML/DL — NLP Library Notes (`ml-dl-practice/Part 23 - NLP`) | Initial library-reference notes; currently no implemented exercise scripts. |
| AI Interaction Visualizer (`ui-templates/00_ask_ai_like_this/animations/ai-interaction`) | Third-party CodePen reference: cSS interaction-visualization study. |
| AI Loader (`ui-templates/00_ask_ai_like_this/animations/ai-loader`) | Third-party CodePen reference: animated loading-indicator study. |
| Chroma-Glass Orbiter (`ui-templates/00_ask_ai_like_this/animations/chroma-glass-orbiter`) | Third-party CodePen reference: cSS glassmorphism and orbiting-color study with selectable hue-based themes. |
| SVG Blob Loader (`ui-templates/00_ask_ai_like_this/animations/elaborate-svg-blob-loader`) | Third-party CodePen reference: animated SVG blob loading indicator. |
| Faux 3D SVG (`ui-templates/00_ask_ai_like_this/animations/faux-3d-with-svg`) | Third-party CodePen reference: sVG-based visual study creating an apparent three-dimensional effect. |
| Gradient Connections (`ui-templates/00_ask_ai_like_this/animations/gradient-connections`) | Third-party CodePen reference: particle-network experiment drawing gradient connections. |
| Holographic Glitch (`ui-templates/00_ask_ai_like_this/animations/holographic-glitch-css-only`) | Third-party CodePen reference: cSS-only holographic/glitch effect. |
| Liquid Orb Shader (`ui-templates/00_ask_ai_like_this/animations/liquid-gooey-orb-shader`) | Third-party CodePen reference: shader-based animated liquid-orb visual. |
| Living Palette (`ui-templates/00_ask_ai_like_this/animations/living-palette-system`) | Third-party CodePen reference: animated color-palette design study. |
| Not a Mobius Knot (`ui-templates/00_ask_ai_like_this/animations/not-a-mobius-knot`) | Third-party CodePen reference: animated abstract knot visual study. |
| Ocean Day-Cycle Shader (`ui-templates/00_ask_ai_like_this/animations/ocean-shader-6-scene/ocean-shader-6-scene-day-cycle-webgl-glsl`) | Third-party CodePen reference: webGL/GLSL ocean scene transitioning through six lighting and weather settings. |
| Liquid Glass UI Kit (`ui-templates/00_ask_ai_like_this/animations/pure-css-glassmorphism-kit`) | Third-party CodePen reference: cSS design-token and component reference with glass effects, themes, and animations. |
| Star Trek Shader (`ui-templates/00_ask_ai_like_this/animations/star-trek`) | Third-party CodePen reference: spaceflight-inspired fragment-shader visual study. |
