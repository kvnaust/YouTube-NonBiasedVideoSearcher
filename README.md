# Non-Biased-Video-Searcher-for-YouTube
Search for YouTube videos without bias from the algorithm or your watch history. 
Sort by relevance, upload date (newest/oldest), view count (lowest/highest), and view duration (shortest/longest). 
Use Google Dorks to refine your search (before:YYYY-MM-DD) (after:YYYY-MM-DD) (quotations).

This search engine relies on YouTube Data API V3 in order to receive data from YouTube. You'll need to get a free API key to use this
search engine. SUPER EASY TO SET UP, I have a tutorial that shows you how to set it all up. A free API key grants you 200 searches a day (10,000 tokens) (50 results per search) which is plenty for the average user. Some users like me want to find really low-viewed videos and obscure keyphrases, so I'd suggest you get multiple API keys. Just use multiple g-mail accounts to set up all the API keys and keep them in a place where you can just pull them from when one runs out. Obviously KEEP YOUR KEYS TO YOURSELF. Everything is local, in the same way everyone has their own library card(s) that they can use to access the books at the library.

Tips:

Quotations: Using quotations will help with receiving very specific results. If your search is too broad, expect a broad scope of results.

(before:YYYY-MM-DD) (after:YYYY-MM-DD): The search results will show you results before / after a specific date

-: take a channel out of the search results if it is clouding up your search ("People" -MrPersonDude) will show you results excluding anything posted by MrPersonDude

Sorting by newest tips: [thing you wanna search] after:YYYY-MM-DD (yesterday's date) will force a deeper search into the last 24 hours

Sorting by oldest tips: [thing you wanna search] before:YYYY-MM-DD will force a deeper search into the older dates

Sorting by lowest view tips: Maxing out the search query (500 results) will force YouTube to show every result, which it initially doesn't
do because it prioritizes the most recent results. This will cost you more tokens but after a few clicks you WILL have the lowest viewed
results. 

Filter YouTube Shorts: The best thing that I could come up for is excluding any video that has a hashtag [#] in the title or description. 
Many shorts have this, BUT NOT ALL OF THEM DO. YouTube Data API V3 doesn't recognize the difference between a long-form video and a short; it will just show you everything.

Exact title match: Whatever you put into the search bar is what you will get (NOT including google dorks). If you search for 
[I am a human being before:2009] You will find videos with the title "I am a human being" posted before 2009. Exact title match. 
This can cost more tokens (searches) because what is happening is it's loading multiple pages and then removing any result that doesn't match your search exactly.
