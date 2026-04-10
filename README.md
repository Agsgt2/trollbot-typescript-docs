# trollbot-typescript
docs for trollbot-typescript
## Getting Started
To start a new bot, you must use the `createBot` function.
```ts
import { createBot } from "trollbot-typescript"

let bot = createBot("clanker", "grey")
```
### Ping Example
```ts
bot.onMessage((data)=>{
  const [msg, nick] = [he.decode(data.msg), he.decode(data.nick)]
  if (msg == "!ping"){
    bot.send("Pong!")
  }
})
```
