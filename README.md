# Twitch-Project
I quickly analyze the information from Twitch, this information contains more than 800,000 rows
Twitch is the world’s leading video platform and community where millions of people and thousands of
interests collide in a beautiful explosion of video games, pop culture, and conversation. 
Its live and on-demand video platform forms the backbone of a distribution network for video game broadcasters 
including professional players, tournaments, leagues, developers and gaming media organizations.

We have two files:

- [x] [`stream.csv`](stream.csv)  
- [x] [`chat.csv`](chat.csv)  

The `stream.csv` has the following fields:

Headers | Description |
--- | --- |
`time` | date and time (YYYY-MM-DD HH:MM:SS)
`device_id` | device ID
`login` | login ID
`channel` | streamer name
`country` | country name abbreviation
`player` | streamed device
`game` | game name
`stream_format` | stream quality
`subscriber` | is the viewer a subscriber? (true/false)

The `chat.csv` has the following fields:

Headers | Description |
--- | --- |
`time` | date and time (YYYY-MM-DD HH:MM:SS)
`device_id` | device ID
`login` | login ID
`channel` | streamer name
`country` | country name abbreviation
`player` | chat device
`game` | game name

---

