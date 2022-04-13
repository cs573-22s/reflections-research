# Week 14

My reflection for this week:

## [TimeElide: Visual Analysis of Non-Contiguous Time Series Slices](http://www.cs.ubc.ca/group/infovis/pubs/2021/timeelide/TimeElide_2021.pdf)

Demo link: http://www.cs.ubc.ca/group/infovis/time-elide/

This paper is about a system called TimeElide which is used to analyze non-contiguous time series slices. Usually, we visualize data that are contiguous. However, not all events are contiguous like activity of football players in a season. Football matches does not happen at the same time. Some matches could be played in the morning and some in the evening. Similarly, the players could be substituted in or out within a match. So, to analyze the activity of such non-contiguous time series, they propose this system with a novel visualization technique called sparkbox.

In the sparkbox technique, they combine the box plot bars with line chart in the same visualization. The box plot informs about the rough structure of the data while the line chart gives detail data in a give timeframe. Similarly, the system implements zooming and panning to view the data of a particular region in more detail. 

I feel that the techniques used in this system could be used in my own research project and the class project where I try to explore agreement of multiple base rankings on each candidate in a consensus ranking.