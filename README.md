# rss_master
 RSS feed aggregator with summary generation in a single file

 ## Usage
 Just specify the channel list and settings in the ini-file (see below)

 ## Examples
 ```ini
 [COMMON]
 UseKeywordsFilter = False
 Keywords = IT, Microsoft, Google
 NewsDaysOld = 30
 NewsRecordsLimit = 30
 Title = RSS MASTER
 FileName = news
 AutoOpen = True

 [FEED LIST]
 MailRu = https://news.mail.ru/rss/main/90/
 МЁD = https://www.youtube.com/feeds/videos.xml?channel_id=UCpfefG1t0k2FJ8mevWHhp0g
 VC = https://vc.ru/feed
 Habr = https://habr.com/ru/rss/all/all/
 3DNews = https://3dnews.ru/news/rss/
 4PDA = http://4pda.ru/feed/
 ```
 ## Remarks
 You can also generate an RSS feed of YouTube feeds: see the example above. Note that different RSS sources may produce a limited number of news items, so the NewsRecordsLimit and NewsDaysOld parameters may not always work.
