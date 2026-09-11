# Let's do the Timehawk again! 🦅⏱️

![Build Status](https://img.shields.io/badge/build-barely_passing-yellow)
![DataStore](https://img.shields.io/badge/datastore-leaking-red)
![Uptime](https://img.shields.io/badge/uptime-sometimes-orange)
![License](https://img.shields.io/badge/license-MIT-blue)
![Coffee](https://img.shields.io/badge/coffee-dangerously_low-brown)

Timehawk is an automation platform designed to do your job for you so you can spend more time optimising your ergonomic chair settings and staring into the existential void. It swoops down, grabs your repetitive tasks in its talons, and drops them directly into a volcano. 

> "I deployed Timehawk on Friday. By Monday, I was promoted to Senior Architect. I don't even know what I do anymore." 
> — *An actual, totally real user*

## 🚀 Core Features

*   **Aggressive Automation:** If it takes more than 3 seconds to do manually, Timehawk will spend 4 weeks automating it.
*   **Scapegoat Protocol:** Automatically blames DNS or a junior developer when a pipeline inevitably fails.
*   **Phantom Typing:** Simulates keyboard clicks in Slack so your boss thinks you're drafting a massive architectural manifesto.
*   **Stateful Chaos:** Stores all its anxiety directly in your datastore for maximum persistence.

---

## 🛠️ Installation & Deployment

Because we are professionals, we don't just `npm install` locally and pray. We deploy to the platform. Here is the highly rigorous, battle-tested deployment process:

1. **Log onto the platform:** Authenticate through 4 layers of SSO just to stare at the dashboard.
2. **Pull the latest changes:** Yank the newest commits from the repository (expect merge conflicts; embrace the merge conflicts). 
3. **Navigate to the App:** Click through at least 6 vaguely named sub-menus until you find the Timehawk instance.
4. **Redeploy the changes:** Smash that big, shiny `Redeploy` button. 
5. **Hold onto your butt:** Watch the logs scroll by at the speed of light and pretend you know what they mean.

---

## 🗄️ Datastore Configuration

Forget `.env` files—we're playing in the big leagues now. Timehawk pulls its configuration directly from your datastore. Add these keys to your instance variables before the platform throws a tantrum.

| Datastore Key | Type | Default | Description |
| :--- | :--- | :--- | :--- |
| `hawk.aggression.level` | Integer | `9001` | How hard it attacks your backlog. Anything over 100 is generally considered a safety hazard. |
| `hawk.blame.target_uid` | String | `"juniordev_01"` | The User ID of the person Timehawk will auto-tag in Slack when a deployment craters. |
| `hawk.retries.delusional` | Boolean | `true` | If true, Timehawk will keep hitting the same 500 error endpoint expecting a different result. |
| `hawk.slack.phantom_mode` | Boolean | `true` | Keeps your Slack dot green while you take a 3-hour lunch. |
| `hawk.memory.leak_allowance` | Float | `0.85` | Percentage of system RAM Timehawk is allowed to horde like a dragon protecting its gold. |

---

## 🤝 Contributing

We welcome pull requests! However, please ensure your code passes the test suite. We don't actually know how to run the test suite, but it's the principle of the thing. 

1. Clone the repo.
2. Break something fundamental.
3. Submit a PR with a very confident, jargon-heavy description ("*Refactored asynchronous datastore state reconciliation*").