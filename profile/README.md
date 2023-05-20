<p align="center">

![Infrastructure diagram](https://github.com/RideTracker/.github-private/assets/78360666/65a5243c-a36a-4b17-b16b-8eb3dca01a03)

</p>

## Welcome to the team 🙌
| Name | Description |
| ---- | ----------- |
| [RideTrackerApp](https://github.com/RideTracker/RideTrackerApp) | An Expo project to serve the Ride Tracker App. |
| [RideTrackerPages](https://github.com/RideTracker/RideTrackerPages) | A Cloudflare Pages projects to serve the front page of https://ridetracker.app |
| [RideTrackerService](https://github.com/RideTracker/RideTrackerService) | A Cloudflare Workers project to serve as an API for the Ride Tracker App. |
| [RideTrackerClient](https://github.com/RideTracker/RideTrackerClient) | A TypeScript package to provide low-level API clients for all services. |
| [RouteService](https://github.com/RideTracker/RouteService) | A Cloudflare Pages project to embed a 3d rendered route integrations. |
| [AvatarService](https://github.com/RideTracker/AvatarService) | A Node.js project to manage and upload avatar packages for the avatar editor. |
| [AvatarImageService](https://github.com/RideTracker/AvatarImageService) | A web server to generate server-rendered avatars through the avatar service. |

## Naming conventions for repositories:
- "Services" are workers or pages projects that are **not used by customers directly.**
- "Pages" are workers or pages projects that are used by customers directly, for example https://ridetracker.app.
- "App" is an application that are used by customers directly, for example the RideTrackerApp.
- "Package" is a package that accompany an internal service, for example the ApiClientPackage.

## Naming conventions for Cloudflare:
- Services and Pages are prefixed with `ridetracker-` and each SnakeCase word is seperated by dashes, e.g. `ridetracker-pages`.

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
👀 Contribution guidelines - how do team members dive in?
👩‍💻 Useful resources - where do you keep your docs? Is there anything else the team should know?
🍪 Fun facts - what is your team's favorite snack?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
