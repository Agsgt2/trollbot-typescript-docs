# `joined` or `left`
These are both the first arguments for [`onUserAction()`](./README.md)
## OUTPUT
This is the JSON output (on `data` from the 2nd argument):
```json
{
  sid: string;   // The SID of the user
  nick: string;  // The nickname of the user
  color: string; // The color of the user
  home: string;  // The home of the user
  bot: boolean;  // Returns true if it's a bot
}
```
