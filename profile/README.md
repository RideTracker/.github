## Welcome to the team 🙌
| Name | Description |
| ---- | ----------- |
| [RideTrackerApp](https://github.com/RideTracker/RideTrackerApp) | An Expo project to serve the Ride Tracker App. |
| [RideTrackerPages](https://github.com/RideTracker/RideTrackerPages) | A Cloudflare Pages projects to serve the front page of https://ridetracker.app |
| [RideTrackerService](https://github.com/RideTracker/RideTrackerService) | A Cloudflare Workers project to serve as an API for the Ride Tracker App. |
| [RideTrackerClient](https://github.com/RideTracker/RideTrackerClient) | A TypeScript package to provide a low-level API client for the RideTrackerService. |
| | |
| [RouteService](https://github.com/RideTracker/RouteService) | A Cloudflare Pages project to embed a 3d rendered route integrations. |
| | |
| [AvatarService](https://github.com/RideTracker/AvatarService) | A Node.js project to manage and upload avatar packages for the avatar editor. |
| [AvatarClient](https://github.com/RideTracker/AvatarClient) | A TypeScript package to provide a low-level API client for the AvatarService. |
| [AvatarAssets](https://github.com/RideTracker/AvatarAssets) | A project to manage the source assets for the avatar service. |

## Naming conventions for repositories:
- "Services" are workers or pages projects that are **not used by customers directly.**
- "Pages" are workers or pages projects that are used by customers directly, for example https://ridetracker.app.
- "App" is an application that are used by customers directly, for example the RideTrackerApp.
- "Client" is a package that accompany an internal service, for example the RideTrackerClient accompanies the RideTrackerService.

## Naming conventions for Cloudflare:
- Services and Pages are prefixed with `ridetracker-` and each SnakeCase word is seperated by dashes, e.g. `ridetracker-pages`.

<p align="center">
  <img src="https://github.com/RideTracker/.github-private/assets/78360666/7602c7e9-9a73-48bb-857c-3027edf44b0d">
</p>

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
👀 Contribution guidelines - how do team members dive in?
👩‍💻 Useful resources - where do you keep your docs? Is there anything else the team should know?
🍪 Fun facts - what is your team's favorite snack?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
