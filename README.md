![Lang](https://img.shields.io/badge/lang-FR-blue)
![IA](https://img.shields.io/badge/focus-IA%20%2F%20LLM-purple)
![Contributions](https://img.shields.io/badge/PRs-welcome-brightgreen)
![Status](https://img.shields.io/badge/status-liste%20vivante-orange)

# Amazing AI tools - fr

> Une sélection d’outils autour de l’IA (LLM, agents, RAG, no-code, etc.), avec un focus pratique.
> Ressource vivante : les contributions sont les bienvenues ✨

---

## Légende des labels

- `cloud` – service hébergé
- `self-host` – installable chez soi / sur serveur
- `open-source` – code source disponible
- `no-code` / `low-code` – conçu pour non-dev ou dev pressés
- `gratuit` – offre gratuite solide
- `freemium` – gratuit avec limites, plans payants au-delà
- `payant` – principalement payant / entreprise

---

## Sommaire

- [Amazing AI tools - fr](#amazing-ai-tools---fr)
  - [Légende des labels](#légende-des-labels)
  - [Sommaire](#sommaire)
  - [Modèles \& plateformes LLM](#modèles--plateformes-llm)
  - [IA locales / self-host](#ia-locales--self-host)
  - [Prompt engineering \& observabilité](#prompt-engineering--observabilité)
  - [Automatisation \& workflows](#automatisation--workflows)
  - [Agents \& orchestrateurs](#agents--orchestrateurs)
  - [Image, vidéo \& audio](#image-vidéo--audio)
  - [Dev \& no-code assistés par IA](#dev--no-code-assistés-par-ia)
  - [RAG \& bases vectorielles](#rag--bases-vectorielles)
  - [Productivité \& assistants généralistes](#productivité--assistants-généralistes)
  - [Contribution](#contribution)

---

## Modèles & plateformes LLM

- **[OpenAI](https://openai.com)** `cloud` `api` `payant`
  Modèles GPT (texte, image, audio, vision), API, assistants, outils de modération.

- **[Anthropic](https://www.anthropic.com)** `cloud` `api` `payant`
  Modèles Claude (raisonnement, long contexte), très bons pour l’analyse de docs.

- **[Google AI Studio (Gemini)](https://ai.google.dev)** `cloud` `api` `freemium`
  Modèles Gemini (texte, image, audio, vidéo) via console web ou API.

- **[Mistral AI](https://mistral.ai)** `cloud` `open-source` `api` `freemium`
  Modèles légers & open-source (Mistral, Mixtral, Codestral) + API hébergée.

- **[DeepSeek](https://www.deepseek.com/en)** `cloud` `open-source` `api` `freemium`
  Modèles LLM low-cost (V3, R1, Janus…), app, API, versions open-source.

- **[xAI / Grok](https://x.ai)** `cloud` `api` `freemium`
  Modèles Grok intégrés à X (Twitter), orientés temps réel.

- **[Cohere](https://cohere.com)** `cloud` `api` `payant`
  Modèles pour le search, le RAG et les cas d’usage entreprise.

---

## IA locales / self-host

- **[Ollama](https://ollama.ai)** `self-host` `open-source` `gratuit`
  Lance des modèles LLM localement (Mac / Linux / Windows) avec une simple commande.

- **[LM Studio](https://lmstudio.ai)** `desktop` `gratuit`
  Interface desktop pour télécharger, tester et comparer des LLM en local.

- **[Jan](https://jan.ai)** `desktop` `open-source` `gratuit`
  Alternative locale à ChatGPT, avec modèles et historique stockés en local.

- **[Text Generation WebUI](https://github.com/oobabooga/text-generation-webui)** `self-host` `open-source`
  Interface web très complète pour héberger et tester des modèles de génération de texte.

---

## Prompt engineering & observabilité

- **[Promptmetheus](https://promptmetheus.com)** `cloud` `desktop` `freemium`
  IDE pour le prompt engineering : datasets, tests, évaluations, multi-modèles, intégrations n8n/Make/Zapier.

- **[PromptLayer](https://www.promptlayer.com)** `cloud` `freemium`
  “Workbench” pour suivre, versionner et évaluer les prompts / appels API en prod.

- **[LangSmith](https://www.langchain.com/langsmith)** `cloud` `payant`
  Observabilité, traçage et évaluation pour apps construites avec LangChain.

- **[promptfoo](https://www.promptfoo.dev)** `open-source` `self-host`
  Outil de test / régression pour prompts (datasets, scoring, comparaison de modèles).

---

## Automatisation & workflows

- **[n8n](https://n8n.io)** `open-source` `self-host` `cloud` `freemium`
  Automatisation visuelle, parfait pour orchestrer des appels LLM, webhooks et APIs.

- **[Make](https://www.make.com)** `cloud` `no-code` `freemium`
  Plateforme d’automatisation visuelle pour connecter APIs + IA sans code.

- **[Zapier](https://zapier.com)** `cloud` `no-code` `freemium`
  Automatisation “classique” avec beaucoup d’intégrations SaaS, modules IA inclus.

- **[LangFlow](https://www.langflow.org)** `open-source` `self-host`
  Builder visuel pour graphes d’IA (RAG, agents simples) basé sur LangChain.

- **[Flowise](https://flowiseai.com)** `open-source` `self-host`
  Alternative à LangFlow pour designer des flux RAG / agents via UI node-based.

---

## Agents & orchestrateurs

- **[LangGraph](https://langchain.com/langgraph)** `cloud` `open-source`
  Orchestrateur d’agents basé sur des graphes pour workflows complexes et long-running.

- **[CrewAI](https://www.crewai.com)** `open-source` `self-host`
  Framework d’agents “multi-rôles” pour faire collaborer plusieurs IA sur une même tâche.

- **[Microsoft AutoGen](https://microsoft.github.io/autogen/)** `open-source`
  Framework pour créer des systèmes multi-agents (IA ↔ IA ↔ outils).

- **[OpenAI Swarm](https://github.com/openai/swarm)** `open-source`
  Mini-framework officiel pour orchestrer plusieurs “workers” IA légers.

---

## Image, vidéo & audio

- **[Midjourney](https://www.midjourney.com)** `cloud` `payant`
  Génération d’images artistiques de haute qualité via Discord.

- **[Flux (Black Forest Labs)](https://blackforestlabs.ai)** `cloud` `open-source` `freemium`
  Modèles d’image haut de gamme (FLUX.1, etc.), API et modèles téléchargeables.

- **[Stable Diffusion](https://stability.ai)** `open-source` `self-host` `cloud`
  Suite de modèles génératifs open-source pour l’image (SDXL, etc.).

- **[Leonardo AI](https://leonardo.ai)** `cloud` `freemium`
  Génération d’images + outils de production (textures, assets jeux, etc.).

- **[Runway](https://runwayml.com)** `cloud` `payant`
  Montage vidéo, génération vidéo, effets IA pour créateurs.

- **[Pika](https://pika.art)** `cloud` `freemium`
  Génération vidéo courte (clips, cinématiques) à partir de texte / images.

- **[HeyGen](https://www.heygen.com)** `cloud` `payant`
  Avatars vidéo IA, lip-sync multilingue et clones de voix.

- **[ElevenLabs](https://elevenlabs.io)** `cloud` `api` `freemium`
  Synthèse vocale de haute qualité, clonage de voix, sound effects.

---

## Dev & no-code assistés par IA

- **[V0](https://v0.dev)** `cloud` `no-code` `freemium`
  Génération d’UI (React/Tailwind) à partir de prompts, orienté dev front.

- **[Bubble](https://bubble.io)** `cloud` `no-code` `freemium`
  Plateforme no-code historique pour apps web, avec capacités IA.

- **[Lovable](https://lovable.dev)** `cloud` `no-code` `freemium`
  “AI software engineer” pour générer des apps full-stack et les pousser sur GitHub.

- **[Bolt.new](https://bolt.new)** `cloud` `freemium`
  Environnement en ligne pour prototyper rapidement des apps front/back avec IA.

- **[Replit Agent](https://replit.com/agent)** `cloud` `freemium`
  Assistant pour coder, exécuter et déployer depuis le navigateur.

---

## RAG & bases vectorielles

- **[Pinecone](https://www.pinecone.io)** `cloud` `api` `payant`
  Base vectorielle managée, optimisée pour le RAG en production.

- **[Weaviate](https://weaviate.io)** `open-source` `self-host` `cloud`
  Moteur de search vectoriel, open-source, avec version hébergée.

- **[Qdrant](https://qdrant.tech)** `open-source` `self-host` `cloud`
  Base de données vectorielle performante et simple à déployer.

- **[Supabase Vector](https://supabase.com)** `open-source` `self-host` `cloud`
  Extension vectorielle sur Postgres, intégrée dans l’écosystème Supabase.

---

## Productivité & assistants généralistes

- **[Notion AI](https://www.notion.so/product/ai)** `cloud` `payant`
  Résumés, génération de contenu et refactor directement dans Notion.

- **[Microsoft Copilot](https://copilot.microsoft.com)** `cloud` `freemium`
  Assistant IA intégré à l’écosystème Microsoft (Office, Windows, etc.).

- **[Arc Search](https://arc.net)** `desktop` `mobile` `gratuit`
  Navigateur + moteur de “browsing IA” orienté recherche et synthèse de pages web.

---

## Contribution

Les contributions sont bienvenues 🎉

1. Forkez le dépôt.
2. Ajoutez / modifiez un outil dans :
   - `README.md` (section + labels cohérents)
   - `tools.json` (même schéma que dans le dépôt)
3. Ouvrez une Pull Request avec :
   - une courte description de l’outil,
   - la catégorie envisagée,
   - pourquoi il mérite sa place dans la liste.

Objectif : garder une liste **utile, compacte et vraiment utilisée**, pas un annuaire géant.
