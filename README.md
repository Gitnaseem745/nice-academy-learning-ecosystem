# Learn in Public Ecosystem

Welcome to the **Learn in Public Ecosystem**. This repository serves as a centralized learning hub for Web Developers, Web Designers, and Graphic Designers.

## 🧭 Navigation & Learning Model

This ecosystem is designed to be self-guided. The diagram below illustrates how components interact and how you should consume projects.

```mermaid
flowchart TD
    subgraph Shared["Shared Standards"]
        Guidelines[Guidelines & Rules]
        Templates[Project Templates]
    end

    subgraph Tracks["Role Tracks"]
        WD[Web Developer - Angular]
        FD[Web Designer - Figma]
        GD[Graphic Designer - Canva]
    end

    subgraph UserFlow["Student Learning Flow"]
        Select[Select Role & Level] --> Pick[Pick Project]
        Pick --> Read[Read Guide]
        Read --> Build[Build in Your Repo]
        Build --> Stuck{Stuck?}
        Stuck -- Yes --> CheckSol[Check Solution]
        Stuck -- No --> Continue
        CheckSol --> Continue
        Continue --> Verify[Verify & Review]
        Verify --> Share[Share Publicly]
    end

    Shared -.-> Tracks
    Tracks --> Select
```

## 🚀 Getting Started

1.  **Choose your path**: Navigate to the folder corresponding to your role (`web-developer-angular`, `web-designer-figma`, or `graphic-designer-canva`).
2.  **Select a level**: Start with `beginner` if you are new, or challenge yourself with `advanced` or `hard`.
3.  **Pick a project**: specific project folders contain everything you need.
4.  **Follow the Guide**: Open the `guide/` folder and start with `01-overview.md`.
5.  **Build**: Create your own repository and build the project following the instructions.

## 🤝 Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for details on how to add new projects or improve existing ones.
