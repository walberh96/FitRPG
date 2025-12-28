# FitRPG

FitRPG is a fitness-focused role-playing game experience that turns workouts into quests, rewards, and progression. The project is being remade with a modern stack to support web, mobile, and wearable experiences.

## Vision
- Combine fitness tracking with RPG mechanics (levels, loot, quests, and achievements).
- Offer a cohesive experience across web, mobile, and wearable devices.
- Provide social and competitive features such as leaderboards and cooperative challenges.

## Technology Plan
- **Backend:** ASP.NET Core for APIs, authentication, and game logic services.
- **Frontend (mobile & web):** React Native for the phone app and the web app.
- **Wearable:** Native Android implementation via Android Studio for the Samsung Watch 7 companion app.

## Current Status
The codebase currently contains a starter ASP.NET Core project (see `FitRPG/Program.cs`). The full game systems, data models, and UI are planned but not yet implemented.

## High-Level Architecture (planned)
- **API Services:** ASP.NET Core handling authentication, player profiles, workout ingestion, quest progression, and reward calculations.
- **Clients:**
  - React Native app for mobile and web clients consuming the API.
  - Native Android client for Samsung Watch 7 as the wearable companion.
- **Data & Integrations:** Fitness data ingestion endpoints designed to integrate with device sensors and external fitness platforms.

## Roadmap (initial)
1. Define core domain models (player, stats, quests, inventory, workouts).
2. Stand up ASP.NET Core API skeleton with authentication and basic player profile endpoints.
3. Scaffold React Native app consuming the API and displaying core stats/quests.
4. Build a native Android watch companion for Samsung Watch 7 and integrate with the API.
5. Expand gameplay loops (quests, rewards, achievements) and social features (leaderboards, parties).
6. Add analytics, testing, and deployment pipelines.

## Getting Started (current project)
- Requirements: .NET 8 SDK.
- To run the existing starter API locally:
  ```bash
  dotnet run --project FitRPG/FitRPG.csproj
  ```

As the remake progresses, this README will be updated with more detailed setup, architecture diagrams, and platform-specific instructions.
