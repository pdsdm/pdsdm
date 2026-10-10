<div align="center">

# Hi, I'm Pepe

**I build AI agents and the products around them.**<br/>
By day I work in data at ebury in Madrid. The rest of my time goes into building stuff.

<img src="https://img.shields.io/badge/Madrid-Spain-1f2328?style=flat-square" alt="Madrid, Spain" />

</div>

<br/>

## About me

I work in the data team at **ebury**, a fintech that moves money across borders for businesses. My day is SQL, Python and models that help the business make better decisions. I'm also doing an **MSc in Big Data & Advanced Analytics at ICAI** (Universidad Pontificia Comillas).

Outside of work I build AI agents. Not demos: products with real users, a backend, a database and an interface. The model plans and uses real tools, like a browser, a database or a phone line, and plain code checks what it does before anyone sees the result. Every answer has to come with its evidence, every run has a cost limit, and when the model is not sure, a human decides.

I like to own the whole thing, from the data model to the last pixel of the UI, and to ship it.

## What I'm building

<img align="right" width="72" src="assets/otel.svg" alt="otel" />

### [otel](https://github.com/pdsdm/otel)

<a href="https://tuotel.app"><img src="https://img.shields.io/badge/tuotel.app-007BFF?style=flat-square&logo=googlechrome&logoColor=white" alt="tuotel.app" /></a>
<img src="https://img.shields.io/badge/status-in_development-F59E0B?style=flat-square" alt="In development" />
<img src="https://img.shields.io/badge/agentic-price_seeker-1f2328?style=flat-square" alt="Agentic price seeker" />

An agent that researches Booking prices stay by stay, so independent hotels can sell every room at the right price. Every price it finds comes with its evidence, and anything doubtful goes to a human for review instead of being guessed. On top, a chat answers questions about the collected prices and checks every number it says against the data.

- A browser worker reads each competitor's page every day, for every stay up to 60 days ahead, and keeps a screenshot of what it saw.
- Only the exact room, occupancy and meal plan count, with taxes and mandatory fees included.
- Pricing rules turn the market into a short list of decisions for the day: raise, lower or keep.
- The research agent can browse, read reviews and compare listings to answer questions like *"why is the hotel next door cheaper this weekend?"*.

<sub>React · TypeScript · Supabase · Python · FastAPI · Playwright · Docker</sub>

<br clear="right"/>

<img align="right" width="72" src="assets/feedo.png" alt="Feedo" />

### [Feedo](https://github.com/pdsdm/feedo)

<a href="https://apps.apple.com/es/app/feedo/id6806554868"><img src="https://img.shields.io/badge/App_Store-live-000000?style=flat-square&logo=apple&logoColor=white" alt="Live on the App Store" /></a>
<img src="https://img.shields.io/badge/launched_in-Madrid-1f2328?style=flat-square" alt="Launched in Madrid" />

A social map for restaurants: see where your friends ate and what they'd order again. Live on the App Store, launched in Madrid.

- A map of the places your friends recommend, with filters by area, cuisine and who recommended it.
- Posts with up to five photos and videos, notes and a rating for each dish.
- Your own lists, so the place someone sent you on WhatsApp never gets lost again.
- A level system with weekly streaks and leaderboards, all computed in the database.

<sub>Expo · React Native · TypeScript · Supabase · PostgreSQL</sub>

<br clear="right"/>

## Hackathons

| Event | Project | What we built |
|:--|:--|:--|
| 🇪🇸 **HackSpain 2026**<br/><sub>HappyRobot track</sub> | **[Zhivel](https://github.com/pdsdm/hackspain)** | An agent system that handles a live event crisis: decides, calls, coordinates and replans, with a human approving the key decisions. |
| 🇮🇪 **HackEurope 2026**<br/><sub>Dublin</sub> | **[FactNews](https://github.com/pdsdm/FactNews)** | Checks a news story across many outlets using a council of LLMs and RAG, with a link to the source for each claim. |

## Stack

<p align="center">
  <img src="https://go-skill-icons.vercel.app/api/icons?i=python,pandas,sklearn,pytorch,ts,react,reactnative,fastapi,postgres,supabase,docker,gcp&perline=12" alt="Python, pandas, scikit-learn, PyTorch, TypeScript, React, React Native, FastAPI, PostgreSQL, Supabase, Docker, GCP" />
</p>
