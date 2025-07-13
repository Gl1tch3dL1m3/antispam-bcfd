# AntiSpam System in BCFD
This system punishes users for spamming. After 4 messages in 5 seconds, they receive a warn. After 3 warns, they'll be muted and their warns will be reset.

### Implementation
You must copy-paste JSONs in the following order. **Otherwise it won't work!**

1. (all your commands and other stuff)
2. ++reset.json
3. ignoresadmins.json
4. countsmessages.json
5. mutesmembers.json

These JSONs must be at the bottom. Otherwise your commands might not work.

The `++reset` command syntax:
++reset \[user tag\]

It just resets the user's warnings.
