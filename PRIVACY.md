# SubLounge Privacy Policy

**Effective date: November 6, 2026**

Please read this SubLounge-specific Privacy Policy together with the [SubLounge Terms and Conditions](https://github.com/mmgarg/sublounge-policies/blob/main/TERMS.md) before joining a chat. These documents explain the app’s posting flow, moderation features, and data handling.

This policy explains what SubLounge processes when you use its Reddit community chat.

## Information processed

- **Reddit account and comments:** SubLounge uses the Reddit identity available to the app to submit a message as your account. Your username, comment text, timestamp, and Reddit comment link may be shown with the chat message.
- **Chat support data:** To display recent chat history and support replies, mentions, reactions, and unread activity, SubLounge stores a limited copy of recent messages in Devvit Redis. Message records can include the author name, text, timestamp, Reddit comment permalink, flair, media URL, link, reply reference, reactions, pinned state, and an author- or moderator-set NSFW label. The chat history is capped at 100 messages per chat; older entries are displaced as new messages arrive.
- **Notifications and preferences:** SubLounge may store up to 50 recent mention or reply activity items per recipient, along with read state and the recipient's notification mute preference for that chat. Moderators can set a chat room title, which is stored for the Reddit post.
- **Moderator controls and message labels:** Chat settings (such as lock, cooldown, message limits, attachment availability, and participation thresholds) are stored in Devvit Redis for the chat. Pin and sensitive-media labels are stored with the chat message. Minimum karma and account-age checks read the Reddit account’s public karma totals and creation date when the user sends a message; these values are used for the check and are not copied into the chat record.
- **Local browser storage:** The app may use browser local storage for a first-use disclosure acknowledgement and local preference migration. This is not used for advertising or cross-site tracking.
- **GIF search:** If you search for a GIF, the search phrase and the app's KLIPY API key are used in a server request to KLIPY. Your Reddit username and chat message are not included in that request. Search results and selected GIF media are supplied by KLIPY.

## Where information goes

Messages you send are published as Reddit comments from your Reddit account. Attached images and selected GIFs are uploaded to Reddit and included in the comment. Reddit processes and displays this content under its own policies. KLIPY receives GIF search phrases. SubLounge does not currently use advertising or third-party analytics.

SubLounge uses Devvit/Reddit infrastructure, including Redis, to operate the app. Data is available to Reddit and to the app's authorized services as needed to provide the feature. Community moderators may see chat content and reports and may use Reddit's moderation tools.

## Retention and controls

The Redis chat copy is limited to the latest 100 messages per chat and is displaced as newer messages arrive; it does not have a fixed time-based expiry. Notification activity is limited to the latest 50 items per recipient, while read-state, mute preferences, and room moderation settings are kept to provide those features. The app does not currently provide a control to delete these Redis copies directly. You can use Reddit's controls for your comment, or contact the developer to request help with app-stored data.

You can mute reply and mention alert notifications in the chat. This changes the app's alert behavior; it does not remove the message or prevent the in-chat unread indicator from appearing. You can avoid sending information by not submitting a message or GIF search.

## Children's privacy and policy updates

SubLounge is intended for people who may use Reddit under Reddit's applicable age requirements. We do not knowingly seek personal information from children. This policy may be updated when the app changes; the effective date above will be revised when that happens.

## Contact

For privacy questions or requests about app-stored data, contact the developer at [u/Potato-Patahto](https://www.reddit.com/user/Potato-Patahto/) through Reddit.

