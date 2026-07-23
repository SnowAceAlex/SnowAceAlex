<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=21&duration=2600&pause=900&color=3FB950&center=true&vCenter=true&width=680&height=45&lines=visitor%40snowace%3A~%24+whoami;Bui+Cong+Vinh+%E2%80%94+full-stack+engineer;web+%C2%B7+mobile+%C2%B7+blockchain;visitor%40snowace%3A~%24+_" alt="visitor@snowace:~$ whoami — Bui Cong Vinh, full-stack engineer" />
</div>

<div align="center">
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white&labelColor=161B22" alt="TypeScript" />
<img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white&labelColor=161B22" alt="NestJS" />
<img src="https://img.shields.io/badge/.NET_8-512BD4?style=flat-square&logo=dotnet&logoColor=white&labelColor=161B22" alt="dotnet 8" />
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white&labelColor=161B22" alt="Next.js" />
<img src="https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black&labelColor=161B22" alt="React Native" />
<img src="https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white&labelColor=161B22" alt="Solidity" />
<img src="https://komarev.com/ghpvc/?username=SnowAceAlex&color=3FB950&style=flat-square&label=visitors" alt="Profile visitor count" />
</div>

<br>

```bash
visitor@snowace:~$ whoami

  Bui Cong Vinh  ·  @SnowAceAlex
  Full-stack engineer — web, mobile, and blockchain

visitor@snowace:~$ cat about.txt

  I build products end to end, and I do not stop at the framework boundary.

  On a normal week that means a NestJS + Prisma API, a Next.js App Router
  front end, an Expo app sharing the same types, and — when the problem
  calls for it — a Solidity contract with a zk circuit behind it.

  I like the unglamorous parts: transaction boundaries, idempotency,
  cache invalidation, and what happens when the network drops halfway
  through a request.

visitor@snowace:~$ _
```

<br>

## `$ tree ~/.stack`

<div align="center">

<img src="https://skillicons.dev/icons?i=ts,js,cs,java,python,solidity,nextjs,react,tailwind,nestjs,dotnet,nodejs,express,prisma,postgres,redis,docker,aws,firebase,git,linux,vercel&perline=11" alt="Tech stack icons" />

</div>

```bash
visitor@snowace:~$ tree ~/.stack

~/.stack
├── languages/
│   ├── TypeScript                # daily driver, strict mode everywhere
│   ├── JavaScript
│   ├── C# / .NET 8               # enterprise backend on ABP Framework
│   ├── Java                      # OOP, data structures and algorithms
│   ├── Python                    # tooling, graphics, scripting
│   ├── Solidity                  # smart contracts
│   ├── Circom                    # zero-knowledge circuits
│   └── SQL
│
├── frontend/
│   ├── Next.js 16                # App Router, Server Components, Turbopack
│   ├── React 19
│   ├── Tailwind CSS v4           # with shadcn/ui, Radix UI, Ant Design
│   ├── TanStack Query            # server state
│   ├── Zustand                   # client state, persisted
│   ├── React Hook Form + Zod     # typed, validated forms
│   ├── Framer Motion, Recharts
│   ├── i18next / next-intl       # multi-language apps
│   └── Vite, Mapbox GL
│
├── mobile/
│   ├── React Native 0.81
│   ├── Expo 54                   # dev builds, native modules, EAS
│   ├── NativeWind                # Tailwind on native
│   ├── React Navigation          # native stack + bottom tabs
│   ├── Firebase FCM + Notifee    # push notifications
│   └── Google / Apple Sign-In, SecureStore
│
├── backend/
│   ├── NestJS 11                 # modular DI, guards, interceptors
│   ├── .NET 8 + ABP              # DDD, layered, modular monolith
│   ├── SignalR                   # real-time sockets
│   ├── Node.js + Express
│   ├── Prisma 7                  # schema, migrations, seeding
│   ├── PostgreSQL                # the default answer
│   ├── Redis                     # caching + distributed rate limiting
│   ├── JWT, Passport, bcrypt     # auth done properly
│   └── Swagger, Helmet, class-validator
│
├── web3/
│   ├── Hardhat, Foundry          # compile, test, deploy
│   ├── snarkjs + Groth16         # proof generation and verification
│   ├── Poseidon, Merkle trees    # privacy-preserving data structures
│   ├── wagmi + viem              # typed EVM clients
│   ├── MetaMask
│   └── Solana
│
└── tooling/
    ├── Docker + docker compose   # reproducible local stacks
    ├── AWS S3, Firebase Admin
    ├── Bun, pnpm, npm
    ├── Jest                      # unit + e2e, 85% coverage gates
    ├── Lighthouse CI             # performance budgets in CI
    ├── ESLint, Prettier, Husky, lint-staged
    └── Git, GitHub Actions, Vercel
```

<br>

## `$ ls -la ~/projects`

```bash
visitor@snowace:~$ ls -la ~/projects

drwxr-xr-x   techno-smart/          # Next.js · Sanity · Stripe — full-stack commerce
drwxr-xr-x   Lancelot/              # TypeScript · Solana — hackathon build, deployed
drwxr-xr-x   CVBuilder-BE/          # Node · Express — resume builder API
drwxr-xr-x   spa-management-be/     # Node · Express — booking system backend
drwxr-xr-x   Social-Media-Project/  # JavaScript — social platform
drwxr-xr-x   Portfolio-Website/     # JavaScript — personal site
drwxr-xr-x   MineSweeper-DSA/       # Java — algorithms and game logic

visitor@snowace:~$ cd techno-smart && cat README.md
```

<details>
<summary><b><code>techno-smart/</code></b> — full-stack commerce platform</summary>

<br>

A complete e-commerce application, not a tutorial clone. Product catalog, integrated
blog, authenticated accounts, persistent cart, and a working Stripe checkout.

| | |
|---|---|
| **Framework** | Next.js — App Router + Server Components |
| **Language** | TypeScript (97.5% of the codebase) |
| **Content** | Sanity headless CMS |
| **Auth** | Clerk |
| **Payments** | Stripe, including webhook handling |
| **State** | Zustand with localStorage persistence |
| **UI** | Tailwind CSS · Radix UI · Framer Motion |

→ [`SnowAceAlex/techno-smart`](https://github.com/SnowAceAlex/techno-smart)

</details>

<details>
<summary><b><code>Lancelot/</code></b> — Solana hackathon build</summary>

<br>

A full-stack Web3 application built for a Solana hackathon and shipped to production.
Separate frontend and backend, 100+ commits, deployed and publicly reachable.

| | |
|---|---|
| **Language** | TypeScript (74%) · JavaScript |
| **Chain** | Solana |
| **Structure** | Split frontend / backend |
| **Status** | Live on Vercel |

→ [`SnowAceAlex/Lancelot-Solana-Hackathon`](https://github.com/SnowAceAlex/Lancelot-Solana-Hackathon)

</details>

<details>
<summary><b><code>CVBuilder-BE/</code></b> — resume builder API</summary>

<br>

Backend service for a CV/resume building tool. REST API on Node.js, forked by another
developer to build against.

→ [`SnowAceAlex/CVBuilder-BE`](https://github.com/SnowAceAlex/CVBuilder-BE)

</details>

<details>
<summary><b><code>MineSweeper-DSA/</code></b> — algorithms in Java</summary>

<br>

Minesweeper implemented as a data structures and algorithms exercise — flood fill for
cascading reveals, adjacency counting, and grid state management.

→ [`SnowAceAlex/MineSweeper-DSA`](https://github.com/SnowAceAlex/MineSweeper-DSA)

</details>

<br>

## `$ current projects`

```bash
visitor@snowace:~$ current projects

[1]  running   land-registry-zkp
                # Thesis — privacy-preserving land use rights registry.
                # Merkle trees + Groth16 zero-knowledge proofs on Ethereum.
                # circom · Hardhat · snarkjs · NestJS · Next.js · PostgreSQL

[2]  running   production booking platform  (backend + mobile)
                # .NET 8 / ABP · SignalR · PostgreSQL · Redis
                # React Native / Expo · Next.js · TanStack Query
                # Real-time availability, multi-environment releases,
                # 85% test coverage gates. My focus: transaction integrity,
                # offline retry, and the race conditions nobody sees coming.

[3]  running   NestJS + Expo production boilerplate
                # Monorepo template: NestJS 11 + Prisma 7 + Redis + S3,
                # Expo 54 mobile with push, auth, and IAP wired up.
```

<br>

## `$ neofetch --github`

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats-eight-sable.vercel.app/api?username=SnowAceAlex&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&bg_color=0D1117&title_color=3FB950&text_color=C9D1D9&icon_color=58A6FF" />
  <img src="https://github-readme-stats-eight-sable.vercel.app/api?username=SnowAceAlex&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&bg_color=FFFFFF&title_color=1A7F37&text_color=1F2328&icon_color=0969DA" alt="GitHub stats for SnowAceAlex" height="165" />
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats-eight-sable.vercel.app/api/top-langs/?username=SnowAceAlex&layout=compact&hide_border=true&langs_count=6&bg_color=0D1117&title_color=3FB950&text_color=C9D1D9" />
  <img src="https://github-readme-stats-eight-sable.vercel.app/api/top-langs/?username=SnowAceAlex&layout=compact&hide_border=true&langs_count=6&bg_color=FFFFFF&title_color=1A7F37&text_color=1F2328" alt="Most used languages" height="165" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=SnowAceAlex&hide_border=true&background=0D1117&stroke=30363D&ring=3FB950&fire=58A6FF&currStreakLabel=3FB950&sideLabels=C9D1D9&currStreakNum=C9D1D9&sideNums=C9D1D9&dates=8B949E" />
  <img src="https://streak-stats.demolab.com?user=SnowAceAlex&hide_border=true&background=FFFFFF&stroke=D0D7DE&ring=1A7F37&fire=0969DA&currStreakLabel=1A7F37&sideLabels=1F2328&currStreakNum=1F2328&sideNums=1F2328&dates=656D76" alt="Contribution streak" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=SnowAceAlex&bg_color=0D1117&color=C9D1D9&line=3FB950&point=58A6FF&area=true&hide_border=true" />
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=SnowAceAlex&bg_color=FFFFFF&color=1F2328&line=1A7F37&point=0969DA&area=true&hide_border=true" alt="Contribution activity graph" width="820" />
</picture>

</div>

<br>

## `$ ./contact.sh`

```bash
visitor@snowace:~$ ./contact.sh --list

  [1]  github      github.com/SnowAceAlex
  [2]  facebook    fb.com/snowaceasw
  [3]  instagram   instagram.com/snowace_

visitor@snowace:~$ exit
```

<div align="center">
<br>

<a href="https://github.com/SnowAceAlex"><img src="https://img.shields.io/badge/GitHub-161B22?style=for-the-badge&logo=github&logoColor=C9D1D9" alt="GitHub" /></a>
<a href="https://www.facebook.com/snowaceasw"><img src="https://img.shields.io/badge/Facebook-161B22?style=for-the-badge&logo=facebook&logoColor=58A6FF" alt="Facebook" /></a>
<a href="https://www.instagram.com/snowace_"><img src="https://img.shields.io/badge/Instagram-161B22?style=for-the-badge&logo=instagram&logoColor=E1306C" alt="Instagram" /></a>

<br><br>

<sub><code>logout · Connection to snowace closed.</code></sub>

</div>
