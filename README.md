# TechSci AI Hub 👋

<!-- TODO: Rebrand [TechSci AI Hub]: Original item was 'GitHub stars shield (https://img.shields.io/github/stars/open-webui/open-webui?style=social)' - Requires rewrite. (URL needs to point to new repo & verify stats) -->
![GitHub stars](https://img.shields.io/github/stars/TechSci-AI-Hub/TechSci-AI-Hub?style=social)
<!-- TODO: Rebrand [TechSci AI Hub]: Original item was 'GitHub forks shield (https://img.shields.io/github/forks/open-webui/open-webui?style=social)' - Requires rewrite. (URL needs to point to new repo & verify stats) -->
![GitHub forks](https://img.shields.io/github/forks/TechSci-AI-Hub/TechSci-AI-Hub?style=social)
<!-- TODO: Rebrand [TechSci AI Hub]: Original item was 'GitHub watchers shield (https://img.shields.io/github/watchers/open-webui/open-webui?style=social)' - Requires rewrite. (URL needs to point to new repo & verify stats) -->
![GitHub watchers](https://img.shields.io/github/watchers/TechSci-AI-Hub/TechSci-AI-Hub?style=social)
<!-- TODO: Rebrand [TechSci AI Hub]: Original item was 'GitHub repo size shield (https://img.shields.io/github/repo-size/open-webui/open-webui)' - Requires rewrite. (URL needs to point to new repo & verify stats) -->
![GitHub repo size](https://img.shields.io/github/repo-size/TechSci-AI-Hub/TechSci-AI-Hub)
<!-- TODO: Rebrand [TechSci AI Hub]: Original item was 'GitHub language count shield (https://img.shields.io/github/languages/count/open-webui/open-webui)' - Requires rewrite. (URL needs to point to new repo & verify stats) -->
![GitHub language count](https://img.shields.io/github/languages/count/TechSci-AI-Hub/TechSci-AI-Hub)
<!-- TODO: Rebrand [TechSci AI Hub]: Original item was 'GitHub top language shield (https://img.shields.io/github/languages/top/open-webui/open-webui)' - Requires rewrite. (URL needs to point to new repo & verify stats) -->
![GitHub top language](https://img.shields.io/github/languages/top/TechSci-AI-Hub/TechSci-AI-Hub)
<!-- TODO: Rebrand [TechSci AI Hub]: Original item was 'GitHub last commit shield (https://img.shields.io/github/last-commit/open-webui/open-webui?color=red)' - Requires rewrite. (URL needs to point to new repo & verify stats) -->
![GitHub last commit](https://img.shields.io/github/last-commit/TechSci-AI-Hub/TechSci-AI-Hub?color=red)
[![Discord](https://img.shields.io/badge/Discord-TechSci_AI_Hub-blue?logo=discord&logoColor=white)](https://discord.gg/5rJgQTnV4s)
[![](https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=%23fe8e86)](https://github.com/sponsors/tjbck)

<!-- TODO: Rebrand [TechSci AI Hub]: Original item was 'extensible link (https://docs.openwebui.com/features/plugin/)' - Requires rewrite. (Point to new docs) -->
**TechSci AI Hub is an [extensible](https://docs.openwebui.com/features/plugin/), feature-rich, and user-friendly self-hosted AI platform designed to operate entirely offline.** It supports various LLM runners like **Ollama** and **OpenAI-compatible APIs**, with **built-in inference engine** for RAG, making it a **powerful AI deployment solution**.

![TechSci AI Hub Demo](./demo.gif)

> [!TIP]  
> <!-- TODO: Rebrand [TechSci AI Hub]: Original item was 'Enterprise Plan link (https://docs.openwebui.com/enterprise)' - Requires rewrite. (Point to new docs) -->
> <!-- TODO: Rebrand [TechSci AI Hub]: Original item was 'Sales email (mailto:sales@openwebui.com)' - Requires rewrite. (Update email address) -->
> **Looking for an [Enterprise Plan](https://docs.openwebui.com/enterprise)?** – **[Speak with Our Sales Team Today!](mailto:sales@openwebui.com)**
>
> Get **enhanced capabilities**, including **custom theming and branding**, **Service Level Agreement (SLA) support**, **Long-Term Support (LTS) versions**, and **more!**

<!-- TODO: Rebrand [TechSci AI Hub]: Original item was 'TechSci AI Hub Documentation link (https://docs.openwebui.com/)' - Requires rewrite. (Point to new docs) -->
For more information, be sure to check out our [TechSci AI Hub Documentation](https://docs.openwebui.com/).

## Project Status - Phase 3: Functional Next.js App

TechSci AI Hub is currently undergoing a significant refactor and rebrand from its origins. We are in **Phase 3**, focusing on building a functional application with a **Next.js frontend** and **Supabase backend**.

**Key features developed in Phase 3 (MVP Stage):**
- User Authentication (Magic Link, OAuth with Supabase)
- Real-time Streaming Chat Interface
- Initial UI Rewrite using ShadCN UI components and Tailwind CSS
- Placeholder pages for Chat History, Usage, and Settings
- Basic CI workflow and Jest/React Testing Library setup

## Tech Stack (Phase 3)

- **Frontend:** Next.js (App Router, React, TypeScript)
- **UI:** ShadCN UI, Tailwind CSS
- **Backend:** Supabase (Auth, Postgres DB, Storage)
- **LLM Interaction:** Vercel AI SDK, OpenAI API (or other compatible LLMs)

## Key Features of TechSci AI Hub ⭐

- 🚀 **Effortless Setup**: Install seamlessly using Docker or Kubernetes (kubectl, kustomize or helm) for a hassle-free experience with support for both `:ollama` and `:cuda` tagged images. (Note: Docker/Kubernetes setup will be updated for Next.js architecture)

- 🤝 **Ollama/OpenAI API Integration**: Effortlessly integrate OpenAI-compatible APIs for versatile conversations alongside Ollama models. Customize the OpenAI API URL to link with **LMStudio, GroqCloud, Mistral, OpenRouter, and more**.

- 🛡️ **Granular Permissions and User Groups**: By allowing administrators to create detailed user roles and permissions, we ensure a secure user environment. This granularity not only enhances security but also allows for customized user experiences, fostering a sense of ownership and responsibility amongst users. (Planned for full implementation)

- 📱 **Responsive Design**: Enjoy a seamless experience across Desktop PC, Laptop, and Mobile devices.

- 📱 **Progressive Web App (PWA) for Mobile**: Enjoy a native app-like experience on your mobile device with our PWA, providing offline access on localhost and a seamless user interface. (Planned)

- ✒️🔢 **Full Markdown and LaTeX Support**: Elevate your LLM experience with comprehensive Markdown and LaTeX capabilities for enriched interaction.

- 🎤📹 **Hands-Free Voice/Video Call**: Experience seamless communication with integrated hands-free voice and video call features, allowing for a more dynamic and interactive chat environment. (Future Phase)

- 🛠️ **Model Builder**: Easily create Ollama models via the Web UI. Create and add custom characters/agents, customize chat elements, and import models effortlessly through <!-- TODO: Rebrand [TechSci AI Hub]: Original item was 'TechSci AI Hub Community link (https://openwebui.com/)' - Requires rewrite. (Point to new community site) -->[TechSci AI Hub Community](https://openwebui.com/) integration. (Backend functionality to be integrated with Next.js frontend)

- 🐍 **Native Python Function Calling Tool**: Enhance your LLMs with built-in code editor support in the tools workspace. Bring Your Own Function (BYOF) by simply adding your pure Python functions, enabling seamless integration with LLMs. (Backend functionality to be integrated)

- 📚 **Local RAG Integration**: Dive into the future of chat interactions with groundbreaking Retrieval Augmented Generation (RAG) support. This feature seamlessly integrates document interactions into your chat experience. You can load documents directly into the chat or add files to your document library, effortlessly accessing them using the `#` command before a query. (Backend functionality to be integrated)

- 🔍 **Web Search for RAG**: Perform web searches using providers like `SearXNG`, `Google PSE`, `Brave Search`, `serpstack`, `serper`, `Serply`, `DuckDuckGo`, `TavilySearch`, `SearchApi` and `Bing` and inject the results directly into your chat experience. (Backend functionality to be integrated)

- 🌐 **Web Browsing Capability**: Seamlessly integrate websites into your chat experience using the `#` command followed by a URL. This feature allows you to incorporate web content directly into your conversations, enhancing the richness and depth of your interactions. (Backend functionality to be integrated)

- 🎨 **Image Generation Integration**: Seamlessly incorporate image generation capabilities using options such as AUTOMATIC1111 API or ComfyUI (local), and OpenAI's DALL-E (external), enriching your chat experience with dynamic visual content. (Backend functionality to be integrated)

- ⚙️ **Many Models Conversations**: Effortlessly engage with various models simultaneously, harnessing their unique strengths for optimal responses. Enhance your experience by leveraging a diverse set of models in parallel.

- 🔐 **Role-Based Access Control (RBAC)**: Ensure secure access with restricted permissions; only authorized individuals can access your Ollama, and exclusive model creation/pulling rights are reserved for administrators. (To be fully implemented with Supabase RLS)

- 🌐🌍 **Multilingual Support**: Experience TechSci AI Hub in your preferred language with our internationalization (i18n) support. Join us in expanding our supported languages! We're actively seeking contributors!

- 🧩 **Pipelines, TechSci AI Hub Plugin Support**: Seamlessly integrate custom logic and Python libraries into TechSci AI Hub using [Pipelines Plugin Framework](https://github.com/techsci-ai-hub/pipelines). Launch your Pipelines instance, set the OpenAI URL to the Pipelines URL, and explore endless possibilities. [Examples](https://github.com/techsci-ai-hub/pipelines/tree/main/examples) include **Function Calling**, User **Rate Limiting** to control access, **Usage Monitoring** with tools like Langfuse, **Live Translation with LibreTranslate** for multilingual support, **Toxic Message Filtering** and much more. (Backend functionality to be integrated)

- 🌟 **Continuous Updates**: We are committed to improving TechSci AI Hub with regular updates, fixes, and new features.

Want to learn more about TechSci AI Hub's features? Check out our <!-- TODO: Rebrand [TechSci AI Hub]: Original item was 'TechSci AI Hub documentation link (https://docs.openwebui.com/features)' - Requires rewrite. (Point to new docs) -->[TechSci AI Hub documentation](https://docs.openwebui.com/features) for a comprehensive overview!

## Sponsors 🙌

#### Emerald

<table>
  <tr>
    <td>
      <a href="https://n8n.io/" target="_blank">
        <!-- TODO: Rebrand [TechSci AI Hub]: Original item was 'Sponsor logo n8n (https://docs.openwebui.com/sponsors/logos/n8n.png)' - Requires rewrite. (New image URL or remove) -->
        <img src="https://docs.openwebui.com/sponsors/logos/n8n.png" alt="n8n" style="width: 8rem; height: 8rem; border-radius: .75rem;" />
      </a>
    </td>
    <td>
      <a href="https://n8n.io/">n8n</a> • Does your interface have a backend yet?<br>Try <a href="https://n8n.io/">n8n</a>
    </td>
  </tr>
  <tr>
    <td>
      <!-- TODO: Rebrand [TechSci AI Hub]: Original item was 'Sponsor link warp.dev (https://warp.dev/open-webui)' - Requires rewrite. (Update link if Warp rebrands their page) -->
      <a href="https://warp.dev/open-webui" target="_blank">
        <!-- TODO: Rebrand [TechSci AI Hub]: Original item was 'Sponsor logo Warp (https://docs.openwebui.com/sponsors/logos/warp.png)' - Requires rewrite. (New image URL or remove) -->
        <img src="https://docs.openwebui.com/sponsors/logos/warp.png" alt="Warp" style="width: 8rem; height: 8rem; border-radius: .75rem;" />
      </a>
    </td>
    <td>
      <!-- TODO: Rebrand [TechSci AI Hub]: Original item was 'Sponsor link warp.dev (https://warp.dev/open-webui)' - Requires rewrite. (Update link if Warp rebrands their page) -->
      <a href="https://warp.dev/open-webui">Warp</a> • The intelligent terminal for developers
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://tailscale.com/blog/self-host-a-local-ai-stack/?utm_source=TechSciAIHub&utm_medium=paid-ad-placement&utm_campaign=TechSciAIHub-Docs" target="_blank">
        <!-- TODO: Rebrand [TechSci AI Hub]: Original item was 'Sponsor logo Tailscale (https://docs.openwebui.com/sponsors/logos/tailscale.png)' - Requires rewrite. (New image URL or remove) -->
        <img src="https://docs.openwebui.com/sponsors/logos/tailscale.png" alt="Tailscale" style="width: 8rem; height: 8rem; border-radius: .75rem;" />
      </a>
    </td>
    <td>
      <a href="https://tailscale.com/blog/self-host-a-local-ai-stack/?utm_source=TechSciAIHub&utm_medium=paid-ad-placement&utm_campaign=TechSciAIHub-Docs">Tailscale</a> • Connect self-hosted AI to any device with Tailscale
    </td>
  </tr>
</table>

---

We are incredibly grateful for the generous support of our sponsors. Their contributions help us to maintain and improve our project, ensuring we can continue to deliver quality work to our community. Thank you!

## How to Install (Next.js Version - Current Development) 🚀

This section describes how to set up and run the **current development version** of TechSci AI Hub, which uses Next.js and Supabase. For instructions on the legacy Svelte/Python backend version, please refer to [Legacy Version Documentation](LEGACY_README.md) (TODO: Create this file if needed).

### Prerequisites
- Node.js (version 20.x recommended)
- pnpm (recommended package manager: `npm install -g pnpm`)
- Supabase account (for database and authentication)
- OpenAI API Key (or other compatible LLM provider API key)

### Setup
1.  **Clone the repository:**
    ```bash
    git clone https://github.com/TechSci-AI-Hub/TechSci-AI-Hub.git # TODO: Update with actual new repo URL if different
    cd TechSci-AI-Hub
    ```
    *Ensure you are on the correct branch for Phase 3 development (e.g., `feat/phase-3-functional` or the main development branch if merged).*

2.  **Install dependencies:**
    ```bash
    pnpm install --frozen-lockfile
    ```
    This will also run `patch-package` if any patches are defined.

3.  **Set up environment variables:**
    *   Copy the example environment file: `cp .env.example .env.local`
    *   Update `.env.local` with your actual Supabase URL, Supabase Anon Key, OpenAI API Key, and any other required variables.
        ```env
        # Supabase
        NEXT_PUBLIC_SUPABASE_URL=your-supabase-url
        NEXT_PUBLIC_SUPABASE_ANON_KEY=your-supabase-anon-key
        # For server-side Supabase client (optional, can use public for some operations)
        # SUPABASE_SERVICE_ROLE_KEY=your-supabase-service-role-key

        # OpenAI
        OPENAI_API_KEY=your-openai-api-key

        # Other variables as needed...
        ```

4.  **Run Supabase Migrations (if applicable):**
    *   If you have database migrations to set up your Supabase tables (e.g., using `supabase/migrations`), apply them.
        ```bash
        # npx supabase login (if using Supabase CLI)
        # npx supabase link --project-ref <your-project-id>
        # npx supabase db push (or reset if needed for a clean start)
        ```
    *   *TODO: Add detailed Supabase schema setup instructions or link to relevant docs once finalized.*

5.  **Run the development server:**
    ```bash
    pnpm dev
    ```
    The application should now be running on `http://localhost:3000` (or your configured port).

---
*Legacy (Svelte/Python Backend) Installation instructions have been moved or will be removed. Please refer to the project's previous state if needed.*
---

### Troubleshooting

<!-- TODO: Rebrand [TechSci AI Hub]: Original item was 'TechSci AI Hub Documentation link (https://docs.openwebui.com/troubleshooting/)' - Requires rewrite. (Point to new docs) -->
Encountering connection issues? Our [TechSci AI Hub Documentation](https://docs.openwebui.com/troubleshooting/) has got you covered. For further assistance and to join our vibrant community, visit the [TechSci AI Hub Discord](https://discord.gg/5rJgQTnV4s).


## What's Next? 🌟

Discover upcoming features on our roadmap in the <!-- TODO: Rebrand [TechSci AI Hub]: Original item was 'TechSci AI Hub Documentation link (https://docs.openwebui.com/roadmap/)' - Requires rewrite. (Point to new docs) -->[TechSci AI Hub Documentation](https://docs.openwebui.com/roadmap/).
Check out our [Architecture Overview](docs/architecture.md) to understand the system design.

## License 📜

<!-- TODO: Rebrand [TechSci AI Hub]: The license section needs significant rewrite. "Open WebUI License" name and the branding preservation clause must be updated. -->
This project is licensed under the [TechSci AI Hub License](LICENSE), a revised BSD-3-Clause license. You receive all the same rights as the classic BSD-3 license: you can use, modify, and distribute the software, including in proprietary and commercial products, with minimal restrictions. The only additional requirement is to preserve the "Open WebUI" branding, as detailed in the LICENSE file. For full terms, see the [LICENSE](LICENSE) document. 📄

## Support 💬

If you have any questions, suggestions, or need assistance, please open an issue or join our
[TechSci AI Hub Discord community](https://discord.gg/5rJgQTnV4s) to connect with us! 🤝

## Star History

<!-- TODO: Rebrand [TechSci AI Hub]: Original item was 'Star history chart (https://star-history.com/#open-webui/open-webui&Date)' - Requires rewrite. (URL needs to point to new repo & verify chart works) -->
<a href="https://star-history.com/#TechSci-AI-Hub/TechSci-AI-Hub&Date">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=TechSci-AI-Hub/TechSci-AI-Hub&type=Date&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=TechSci-AI-Hub/TechSci-AI-Hub&type=Date" />
    <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=TechSci-AI-Hub/TechSci-AI-Hub&type=Date" />
  </picture>
</a>

---

Created by [Timothy Jaeryang Baek](https://github.com/tjbck) - Let's make TechSci AI Hub even more amazing together! 💪
