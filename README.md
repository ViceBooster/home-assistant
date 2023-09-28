# Home Assistant Configurations
Repository for blueprints, automations, and other integrations tailored for Home Assistant.

With limited examples available online, I've decided to share some of the blueprints and automations I've developed for Home Assistant. I hope they prove helpful to others navigating the platform.

## Blueprints

### Team Score
[View Blueprint](https://github.com/ViceBooster/home-assistant/blob/main/teamtracker/blueprints/team-score.yaml)

When a team scores, this blueprint activates. It creates a scene, saves the states of your selected lights, flashes in the team's colors, and plays a designated media file from a given URL. After the celebration, it restores the lights to their prior state. This blueprint relies on the [`ha-teamtracker`](https://github.com/vasqued2/ha-teamtracker/) integration.

### Game Starting Alert
[View Blueprint](https://github.com/ViceBooster/home-assistant/blob/main/teamtracker/blueprints/game-starting.yaml)

This blueprint provides timely announcements leading up to the start of a game. It alerts users at 60, 30, and 10 minutes prior to kickoff (or tip-off, start, etc.), flashing in the team's colors and playing a specific media file from a URL to heighten the anticipation. Just like the Team Score blueprint, this too requires the [`ha-teamtracker`](https://github.com/vasqued2/ha-teamtracker/) integration.
