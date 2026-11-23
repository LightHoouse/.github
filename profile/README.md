<p align="center"><img src="https://raw.githubusercontent.com/LightHoouse/.github/main/profile/assets/lighthouse.svg" alt="Lighthouse" width="100"></p>
<h1 align="center">Find your next step.</h1>
<p align="center">A personal lab assistant that helps students learn computer tasks at their own pace. 🔦</p>
<p align="center"><a href="https://github.com/LightHoouse/LightHouse-App/releases">Windows downloads</a> · <a href="https://github.com/LightHoouse/LightHouse-App">Desktop app</a> · <a href="https://github.com/LightHoouse/LightHosue-Backend">Backend</a> · <a href="https://github.com/LightHoouse/LightHouse-AI">AI service</a></p>

## Learning, one step at a time

Computer labs move quickly. Lighthouse is being built to help students find the next step without waiting for an assistant to reach their desk. Students keep control of their mouse and keyboard.

- **A guide beside your work.** The Windows preview includes a control panel and a click-through text overlay.
- **Connected support.** The backend stores lab records and delivers guide commands over MQTT with TLS.
- **Grounded suggestions.** The AI service retrieves recorded steps and selects a reference; it does not invent selectors or coordinates.

## Repositories

| Repository | Purpose |
| --- | --- |
| [LightHouse-App](https://github.com/LightHoouse/LightHouse-App) | Electron desktop panel, text guide, and Windows installer |
| [LightHosue-Backend](https://github.com/LightHoouse/LightHosue-Backend) | TypeScript API, MongoDB persistence, MQTT gateway, and Coolify deployment |
| [LightHouse-AI](https://github.com/LightHoouse/LightHouse-AI) | Python retrieval, step selection, guardrails, and evaluation |

## Where we are

Lighthouse is an early prototype. Desktop startup and text guidance are tested; the backend is deployed. AI is tested offline but has not been deployed. Live UI targeting, action recording, step completion checks, classroom dashboards, and the complete classroom flow are still in development.

Successful desktop builds are published as Windows **prereleases**, with checksums and a link to their test run. These are unsigned preview installers, not a completed classroom product.

## Team Utopia

Built by Calvin Wu, Williams Sandjaya, Vallerie Anne Jose, and Andrian Pratama for the *Smarter Campus and Learning* case.

## Contributing

Open an issue in the relevant repository with the steps to reproduce a problem or a concrete learning scenario. Keep student data, screenshots containing personal information, and credentials out of public reports.
