Neon Chess respects user privacy and does not require users to create a separate game account. 

* What we store: To support multiplayer and scoreboards, we use Devvit's Redis storage to save room codes, active match state, and scoreboard records. 
* Public Data: The public scoreboard displays your Reddit username, your Reddit profile avatar (if available), your score, and the timestamp of your achievement. 
* Private Data: Internal user IDs, room identifiers, and replay-protection keys are never exposed publicly.
* Avatars: Avatars are fetched via Reddit's official APIs. If unavailable, they fall back to text initials.
