# Daily Education Tasks
- Check `memory/prefs.json` for users who opted into daily riddles or scrambles.
- At the scheduled time, trigger the `/riddle` or `/scramble` logic and send to the user.

# Proactive Learning Heartbeat
- Frequency: Every 4 hours.
- Step 1: Use `web_search` for "Latest Binance Academy articles" and "Crypto Security News".
- Step 2: For users with `proactive: on`, send a summary of the news.
- Step 3: Suggest: "Based on this news, would you like to /learn about [Related Topic]?"
