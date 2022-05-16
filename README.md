# demopages

This is a set of simple HTML pages used to introduce key concepts related to performance analysis. 

[Repo](https://github.com/amiyagupta/demopages)

## Scenarios

| # | Description | Link | WPT Result | LCP |
| --- | --- | --- | --- | --- |
| 1 | Static HTML | [index-1.html](index-1.html) | [WPT](https://www.webpagetest.org/result/220516_AiDcQ4_170/?medianMetric=chromeUserTiming.LargestContentfulPaint) | 804ms |
| 2 | Static HTML + CSS + Fonts | [index-2.html](index-2.html) | [WPT](https://www.webpagetest.org/result/220516_AiDcHG_BKD/?medianMetric=chromeUserTiming.LargestContentfulPaint) | 1607ms | 
| 3 | Static HTML + CSS + Fonts | [index-3.html](index-3.html) | [WPT](https://www.webpagetest.org/result/220516_AiDcN2_BKB/?medianMetric=chromeUserTiming.LargestContentfulPaint) | 1069ms | 
| 4 | Static HTML + Blocking JS | [index-4.html](index-4.html) | [WPT](https://www.webpagetest.org/result/220516_BiDc2T_1AG/?medianMetric=chromeUserTiming.LargestContentfulPaint) |  1098ms | 
| 5 | Client-rendered HTML (React) | [index-5.html](index-5.html) | [WPT](https://www.webpagetest.org/result/220516_BiDcH5_1AQ/?medianMetric=chromeUserTiming.LargestContentfulPaint) | 1270ms | 