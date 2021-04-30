# impact-of-analytics-on-core-web-vitals


Test 1: Lighthouse Performance (mobile)
=====================================
The test was performed by Olav Pekeberg on 30. april 2021, between 10:30 and 10:55
Tested manually in Chrome incognito modus, using Lighthouse performance score
The urls were tested in an alternated order, to avoid random impact from the server or network (no-ga-sa-no-ga-sa-...)

No analytics
Tested url: https://www.plankepriser.no/produkt/makita-drill-ddf484rtj-2x50ah-yntvdp/q?&analytics=no-analytics
Results:    [100, 100, 100,  97,  99, 100, 100,  99,  99, 100, ]
Average:    99.4

Google analytics
Tested url: https://www.plankepriser.no/produkt/makita-drill-ddf484rtj-2x50ah-yntvdp/q?&analytics=google-analytics
Results:    [ 98,  98,  98,  93,  98,  98,  97,  97,  97,  96, ]
Average:    97.0

Simple analytics
Tested url: https://www.plankepriser.no/produkt/makita-drill-ddf484rtj-2x50ah-yntvdp/q?&analytics=simple-analytics
Results:    [100, 100, 100, 100,  99, 100, 100, 100, 100, 100, ]
Average:    99.9



Test 2: Google Page Speed (mobile)
=====================================
The test was performed by Olav Pekeberg on 30. april 2021, between 11:05 and 11:20
Tested manually in Chrome incognito modus, using https://developers.google.com/speed/pagespeed/insights/
The urls were tested in an alternated order, to avoid random impact from the server or network (no-ga-sa-no-ga-sa-...)

No analytics
Tested url: https://www.plankepriser.no/produkt/makita-drill-ddf484rtj-2x50ah-yntvdp/q?&analytics=no-analytics
Results:    [98, 99, 98, 99, 98, 98, 98, 97, 99, 98, ]
Average:    98.2

Google analytics
Tested url: https://www.plankepriser.no/produkt/makita-drill-ddf484rtj-2x50ah-yntvdp/q?&analytics=google-analytics
Results:    [89, 90, 90, 90, 91, 87, 90, 88, 87, 87, ]
Average:    88.9

Simple analytics
Tested url: https://www.plankepriser.no/produkt/makita-drill-ddf484rtj-2x50ah-yntvdp/q?&analytics=simple-analytics
Results:    [98, 98, 98, 98, 99, 98, 98, 98, 97, 98, ]
Average:    98.0


