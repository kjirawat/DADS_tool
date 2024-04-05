## Data Source
This data set is the statistics of Monthly Payment Transaction Volume processed through Payment Systems and Channels. The number in the data set has a unit of thousand (x1000). It was downloaded from Bank of Thailand web site URL:  https://app.bot.or.th/BTWS_STAT/statistics/BOTWEBSTAT.aspx?reportID=681&language=ENG . It was cleaned and restructured the rows and columns to suitable for graph plotting. 

![payment_sunburst](https://github.com/kjirawat/DADS_tool/assets/158753919/d1c4020c-d41b-4ad1-8ac2-dea3463aaeb2)

## Graph Explanation
As seen in the graph, the [sunburst](https://plotly.com/python/sunburst-charts/) plot can represent hierarchial data which is suitable for the "Payment Type" and "Sub Type" columns in the data set. The area and color of each sector in the chart reveals the conceptual of each payment type volume. The propotional area of a sector compared with another sector show the comparison of each payment type volume.
