# tmi-emote-parse
Load and parse Twitch, [BTTV](https://betterttv.com/), [FFZ](https://www.frankerfacez.com/) and [7TV](https://7tv.app/) emotes and badges from messages for multiple channels. 

Original relies on an unreliable API to get user id, this fork requires you to get it yourself(for example, here: https://www.streamweasels.com/tools/convert-twitch-username-to-user-id/) and call loadAssets(channel, uid, args) instead of loadAssets(channel, args).

Everything else is exactly the same. If you need a full guide, you can find it here: https://github.com/smilefx/tmi-emote-parse.
