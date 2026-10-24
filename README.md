# Michele Domenico Vittozzi

[Italiano](#italiano) · [English](#english)

## Italiano

Lavoro tra tecnologia e ristorazione da oltre dieci anni. Costruisco sistemi che usano l'AI per lavori veri, con risultati che si possono controllare.

- **COO di WaitHero**, Torino: software e media per la ristorazione.
- **Co-founder e CPO di Ecco**.
- **Fondatore di EXX S.R.L.**, consulenza strategica per startup e ristorazione: [exxservices.com](https://exxservices.com).

### Cosa costruisco

Gran parte del lavoro sta in repository privati. Qui sotto trovi cosa fanno e come sono fatti, senza il codice.

**Omni Radar** · privato
Pipeline in Python che produce contenuti LinkedIn B2B verificati alla fonte. Gli LLM fanno da revisori ciechi, ma il codice non si fida dei loro verdetti: riscarica ogni pagina citata e cerca la frase parola per parola, confronta gli hash tra dati e render, tiene un registro d'audit a catena di hash e si ferma se un validatore non coincide con la versione in git. 19 script, circa 9.100 righe, 16 file di test.

**Second Brain · knowledge base per agenti** · privato
Base di conoscenza in markdown, versionata con git, scritta per essere letta da agenti LLM come contesto durevole: indice come catalogo, collegamenti tra pagine, metadati strutturati e un controllo automatico di link e struttura. Non è un RAG: il recupero è guidato dall'indice e dai link, non dagli embedding.

**Ecco · code virtuali** · privato
Piattaforma di code virtuali multiple per esercenti, prototipata e integrata nel sistema preesistente insieme a nuove funzionalità con Google Wallet. Ho lavorato sulla logica di gestione delle code, sulla sua validazione in simulazione e sulle notifiche al cliente direttamente sul telefono.

**Prevenire.ai** · privato
Prototipo per un progetto di prevenzione sanitaria: area per specialisti, partner e pazienti, prenotazione degli appuntamenti e un assistente AI basato su Gemini, in italiano e in inglese. Next.js, Supabase, Vercel.

**Sito EXX** · privato
Il sito di EXX, con le sue pratiche di sicurezza e privacy: DMARC in reject, cookie policy e consenso GA4.

**Calcolatore da RAL a netto** · pubblico
Prototipo per il task tecnico di Jet HR: dalla retribuzione lorda al netto in busta paga, Italia 2026, con 21 giurisdizioni, 10 CCNL e familiari a carico. Parametri separati dal codice e test di allineamento.
[v1](https://github.com/Bafffo/jethr-calcolatore-netto) · [v2](https://github.com/Bafffo/jethr-calcolatore-netto-v2)

### Strumenti

Python, JavaScript e TypeScript, Next.js, PHP e Laravel, Supabase, Vercel, Anthropic Claude (API, Claude Code, MCP, workflow agentici), Google Gemini, Amazon Bedrock, Google Vertex AI, git.

### Contatti

[exxservices.com](https://exxservices.com)

## English

I have worked between technology and hospitality for more than ten years. I build systems that put AI to real work, with results you can check.

- **COO at WaitHero**, Turin: software and media for restaurants.
- **Co-founder and CPO at Ecco**.
- **Founder of EXX S.R.L.**, strategy consulting for startups and restaurants: [exxservices.com](https://exxservices.com).

### What I build

Most of my work lives in private repositories. Below is what each one does and how it is built, without the code.

**Omni Radar** · private
A Python pipeline that produces B2B LinkedIn content verified against its sources. LLMs act as blind reviewers, but the code does not take their verdicts on trust: it downloads every cited page again and looks for the exact quote, compares hashes between data and render, keeps a hash-chained audit ledger and stops if a validator differs from the version in git. 19 scripts, about 9,100 lines, 16 test files.

**Second Brain · knowledge base for agents** · private
A git-versioned markdown knowledge base, written to be read by LLM agents as durable context: an index that works as a catalogue, links between pages, structured metadata and an automated check of links and structure. It is not RAG: retrieval is driven by the index and the links, not by embeddings.

**Ecco · virtual queues** · private
A platform for multiple virtual queues at venues, prototyped and integrated into the existing system together with new Google Wallet features. I worked on the queue management logic, on validating it through simulation and on notifying customers directly on their phones.

**Prevenire.ai** · private
A prototype for a preventive healthcare project: areas for specialists, partners and patients, appointment booking and an AI assistant based on Gemini, in Italian and English. Next.js, Supabase, Vercel.

**EXX website** · private
The EXX website, with its security and privacy practices: DMARC set to reject, cookie policy and GA4 consent.

**Gross-to-net salary calculator** · public
A prototype for the Jet HR technical task: from gross salary to take-home pay, Italy 2026, with 21 jurisdictions, 10 national collective agreements (CCNL) and dependants. Parameters kept separate from the code, with alignment tests.
[v1](https://github.com/Bafffo/jethr-calcolatore-netto) · [v2](https://github.com/Bafffo/jethr-calcolatore-netto-v2)

### Tools

Python, JavaScript and TypeScript, Next.js, PHP and Laravel, Supabase, Vercel, Anthropic Claude (API, Claude Code, MCP, agentic workflows), Google Gemini, Amazon Bedrock, Google Vertex AI, git.

### Contact

[exxservices.com](https://exxservices.com)
