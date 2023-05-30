## Welcome to the team 🙌
| Name | Description | Documentation |
| ---- | ----------- | ------------- |
| [RideTrackerApp](https://github.com/RideTracker/RideTrackerApp) | An Expo application to serve the Ride Tracker app. |
| [RideTrackerPages](https://github.com/RideTracker/RideTrackerPages) | A Cloudflare Pages projects to serve the front page of Ride Tracker. |
| [RideTrackerService](https://github.com/RideTracker/RideTrackerService) | A Cloudflare Workers project to serve as an API for the Ride Tracker app. |
| [RideTrackerClient](https://github.com/RideTracker/RideTrackerClient) | A TypeScript package to provide a low-level API client for the Ride Tracker service. | https://docs.client.ridetracker.app/ |
| | |
| [AvatarService](https://github.com/RideTracker/AvatarService) | A Cloudflare Workers project to serve an API for avatars. |
| [AvatarClient](https://github.com/RideTracker/AvatarClient) | A TypeScript package to provide a low-level API client for the avatar service. |
| [AvatarAssets](https://github.com/RideTracker/AvatarAssets) | A project to manage the source assets for the avatar service. |
| | |
| [RouteService](https://github.com/RideTracker/RouteService) | A Cloudflare Pages project to embed a 3d rendered route integrations. |

_Warning: the documentations are currently on the world-wide-web, do not pass sensitive information in any comments._

## Naming conventions for repositories:
- "Services" are workers or pages projects that are **not used by customers directly.**
- "Pages" are workers or pages projects that **are used by customers directly.**
- "App" is an application that are used by customers directly, for example the Ride Tracker app.
- "Client" is a package that accompany an internal service, for example the Ride Tracker client for the Ride Tracker service.

## Naming conventions for Cloudflare:
- Services and Pages are prefixed with ridetracker and each SnakeCase word is seperated by dashes.
- Images are prefixed with RideTracker, followed by the Capitalized service name, followed by the image name or an UUID, seperators should be dashes and not spaces.

## Architecture
<img src="https://github.com/RideTracker/.github-private/assets/78360666/92fe8b59-b343-4a5d-9381-36968f32f3b4">

## Branding
| Description | Color |
| ----------- | ----- |
| Brand | Purple (`#BB87FC`) |
| Backgrounds | Dark gray-blue (`#171A23`) |
See organization logo for representation.
<!--


**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
👀 Contribution guidelines - how do team members dive in?
👩‍💻 Useful resources - where do you keep your docs? Is there anything else the team should know?
🍪 Fun facts - what is your team's favorite snack?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
