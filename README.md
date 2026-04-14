# Telegram Audience Parser with Deskgram 2

![Audience Parser Main](assets/screenshots/collect-audience__main__en.png)

Audience Parser is a Deskgram 2 module for collecting users from Telegram groups and chats. It helps you prepare a user base for messaging, invite scenarios, and segmentation using filters based on activity, hidden status, profile photo, Premium, and other signals.

[Deskgram 2 Hub](https://github.com/Deskgram-2/deskgram-2-telegram-automation-en) · [Website](https://deskgram2.com/) · [Telegram Bot](https://t.me/DG2welcomebot) · [Web Preview](https://deskgram2.com/web-preview)

## About the module

| Parameter | What is inside |
|---|---|
| Main task | Parsing users from Telegram groups and chats |
| Filters | Online status, hidden status, profile photo, Premium, stories |
| Output | Exportable user base for next-step workflows |
| Useful for | Preparing bases for direct messaging and invite flows |
| Related modules | Direct Messaging, Invite, Accounts Panel |

## What it can do

- collect users from Telegram groups and chats;
- work with public and private sources;
- filter the audience by activity-related signals;
- exclude bots;
- export the parsed result into files;
- prepare a cleaner base for the next modules.

## Quick start

1. Set the list of chats or groups to parse.
2. Configure filters and collection mode.
3. Define performance settings.
4. Choose the export format.
5. Assign accounts and launch the task.

## Natural next steps after collection

- [Direct Messaging](https://github.com/Deskgram-2/telegram-direct-messaging-deskgram-en) if the collected base should move into private outreach.
- [Invite Tool](https://github.com/Deskgram-2/telegram-invite-tool-deskgram-en) if the base is meant for channel or group growth.
- [Account Manager](https://github.com/Deskgram-2/telegram-account-manager-deskgram-en) if you need to organize the working account layer first.
- [Join Groups](https://github.com/Deskgram-2/telegram-join-groups-deskgram-en) if the environment should be prepared before the next stage.

## How this page fits broader English workflows

- [Proxy Manager](https://github.com/Deskgram-2/telegram-proxy-manager-deskgram-en) if the parser depends on a clean infrastructure layer.
- [Automation Settings](https://github.com/Deskgram-2/telegram-automation-settings-deskgram-en) if the environment should be configured before execution starts.
- [Task Manager](https://github.com/Deskgram-2/telegram-task-manager-deskgram-en) if you want the collection and the next execution step visible in one place.

## Interface highlights

### Filters

![Audience Filters](assets/screenshots/collect-audience__filters__en.png)

### Logs and progress

![Audience Logs](assets/screenshots/collect-audience__logs__en.png)

## When it is especially useful

- when you need a user base for private messaging;
- when you are building an audience collection and invite flow;
- when filtering quality matters more than collecting everyone;
- when you want data export for the next stage.

## Why it is more convenient than manual collection

| Manual approach | Audience Parser in Deskgram 2 |
|---|---|
| You inspect users one by one | Collection is automated |
| Active and inactive users are harder to separate | Filters help segment the base |
| Scaling across many chats is difficult | Load is spread across accounts |
| Data is hard to move into the next tools | Export is part of the workflow |
| There is little process visibility | Progress, logs, and result states are visible |

## What to choose: Audience Parser, Comment Audience Parser, or Active Chat Users Parser

| If your goal is | Better fit |
|---|---|
| Build a broad user base from groups and chats | [Audience Parser](https://github.com/Deskgram-2/telegram-audience-parser-deskgram-en) |
| Focus on warmer users from post discussions | [Comment Audience Parser](https://github.com/Deskgram-2/telegram-comment-audience-parser-deskgram) |
| Target users who already write in chats | [Active Chat Users Parser](https://github.com/Deskgram-2/telegram-active-chat-users-parser-deskgram) |
| Build segmented bases for different funnels | Combine all three collection routes |

## Scenario FAQ

### When should the collected base go into direct messaging and when into invite?

Use [Direct Messaging](https://github.com/Deskgram-2/telegram-direct-messaging-deskgram-en) when personal contact is the next step. Use [Invite Tool](https://github.com/Deskgram-2/telegram-invite-tool-deskgram-en) when the goal is community growth from a prepared base.

### Which kind of base usually performs better?

Warmer segments from comments and active discussions often perform better for response-driven workflows. Broader collection is still valuable when you plan to filter further or run a wider funnel.

### What should I do if I do not know which sources to parse yet?

Start with discovery layers such as [Channel Search](https://github.com/Deskgram-2/telegram-channel-search-deskgram) and [Similar Channels](https://github.com/Deskgram-2/telegram-similar-channels-deskgram), then move into parsing once the source set is clearer.

## Related repositories

- [Deskgram 2 Hub](https://github.com/Deskgram-2/deskgram-2-telegram-automation-en)
- [Direct Messaging](https://github.com/Deskgram-2/telegram-direct-messaging-deskgram-en)
- [Join Groups](https://github.com/Deskgram-2/telegram-join-groups-deskgram-en)
- [Invite Tool](https://github.com/Deskgram-2/telegram-invite-tool-deskgram-en)
- [Account Manager](https://github.com/Deskgram-2/telegram-account-manager-deskgram-en)
- [Proxy Manager](https://github.com/Deskgram-2/telegram-proxy-manager-deskgram-en)
- [Automation Settings](https://github.com/Deskgram-2/telegram-automation-settings-deskgram-en)
- [Task Manager](https://github.com/Deskgram-2/telegram-task-manager-deskgram-en)

## FAQ

### Can I collect everyone without filters?

Yes. You can run a broad collection mode if you do not need extra segmentation.

### Can I export the result?

Yes. The module is designed for further use of the collected base.
