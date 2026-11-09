# Eduardo Olvera

CS student at Arizona State (Barrett Honors), with a concurrent master's in AI. Two software engineering internships so far, at Expedia Group and FOX Technology. Most of what I like building sits where a product meets live data: streaming pipelines, cloud infrastructure, and lately putting language models behind interfaces people actually use.

📍 Phoenix, AZ · [LinkedIn](https://linkedin.com/in/eduardo-olv) · eolverallama@gmail.com

---

## Projects

### [Email Automation Intelligence Dashboard](https://github.com/Edd1es/email-automation-dashboard)

`React` `Node.js` `Express` `Flask` `Python` `SQL` `Groq API` `Docker`

A full-stack outbound email system. It pulls recipients from Google Sheets and Gmail, drafts personalized messages through Groq's inference API, sends them, and reports delivery and engagement on a live dashboard. The architecture is a React and Vite frontend, an Express gateway, and a Flask API over a SQLite schema built around campaigns, recipients, and engagement events, with Docker Compose to run the whole thing.

I built it to find out what it actually takes to put a language model inside a product rather than just prompting one. The model turned out to be the easy part. The hard work was everything around it: getting data out of external sources in a usable shape, deciding what context to hand the model, and figuring out how you'd even know when the output was confidently wrong.

**→ [Source and setup instructions](https://github.com/Edd1es/email-automation-dashboard)**

---

### FOX Under Monitor Display App

`Python` `React` `TypeScript` `AWS` `WebSocket`

Built during my 2025 internship at FOX Technology. A canvas-style web app where users compose layouts from dynamic widgets (text, logos, weather, location, images) and live metadata gets pushed to Crestron-enabled conference room displays over a WebSocket API, keeping every connected screen in sync as layouts change. Fully serverless on API Gateway, Lambda, DynamoDB, S3, and Secrets Manager.

It ended up being used daily by engineers and executives monitoring critical FOX video streams. I also built the event-driven pipelines behind it on Kinesis and Lambda, ingesting large-scale video metadata at sub-second latency and improving throughput by about 30%.

*Internal FOX software, so no public source, but I'm happy to walk through the architecture.*

---

### Vrbo Property Page Redesign

`Kotlin` `Spring Boot` `GraphQL` `TypeScript` `React`

Built during my 2026 internship at Expedia Group. I owned a feature of the property-page redesign end to end, from the technical spike through the GraphQL schema, the Kotlin and Spring Boot backend, and the TypeScript and React web client, with one schema serving web, iOS, and Android.

Since it shipped into a live booking flow, the whole change sat behind an A/B experiment with the control path unchanged, and I backed it with 140+ unit tests against a 90% coverage gate plus validation against production data before rollout. I had never written Kotlin or used GraphQL before that summer.

*Proprietary, so no public source, but likewise happy to talk through it.*

---

## Tools I work in

**Languages** Python · TypeScript · JavaScript · Java · Kotlin · SQL · C · C++

**Frameworks** React · Node.js · Express · Flask · Spring Boot · GraphQL

**Infrastructure** AWS (Lambda, Kinesis, DynamoDB, S3, API Gateway) · GCP · Docker · Git
