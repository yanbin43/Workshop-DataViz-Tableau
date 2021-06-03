## 1. Stacked Bar Chart by Daily Cases
- Drag `date` to Columns. Select 'Day (May 8, 2015)' and 'Continuous' from its dropdown menu.
- While pressing 'Ctrl', drag the `date` pill to the Filters card. Select 'Show Filter' from its dropdown menu.
- On the data pane, click on the dropdown menu of `number (my-daily)` and select 'Change to Measure'. Then drag it to Rows.
- On the Marks card, select 'Bar'. 
- Drag `status` to Color on the Marks card. To edit colours, click Color on the Marks card and click Edit Colors.

![stacked bar chart by daily cases](https://github.com/yanbin43/workshop-20210602-dataviz/blob/main/images/daily-bar.JPG)


## 2. Time Series of Daily Cases
- Repeat the steps in #1 above, but on the Marks card, select 'Line'.
- May add `status` to the Filters card.

![time series of daily cases](https://github.com/yanbin43/workshop-20210602-dataviz/blob/main/images/daily-line.JPG)


## 3. Time Series of New Cases by States
- Repeat the steps in #1 above, but use `number (by-state)` instead.
- Add `state` to the Filters card. Click 'Show Filter' and from the filter's dropdown menu, select 'Single Value (list)'.

![time series of new cases by states](https://github.com/yanbin43/workshop-20210602-dataviz/blob/main/images/daily-state.JPG)


## 4. Daily New Cases by States (Bar Chart)
- Drag `number (by-state)` to Columns and `State` to Rows.
- While pressing 'Ctrl', drag `number (by-state)` to Color on the Marks card. Repeat, drag to Label.
- Drag `date` to the Filters card. Select 'Exact Date' from the dropdown menu. Show filter. Change the filter type to 'Single Value (Slider)'.

![daily new cases by state bar](https://github.com/yanbin43/workshop-20210602-dataviz/blob/main/images/daily-state-bar.JPG)


##  5. Daily New Cases by States (Map)
- Drag `state` to the empty canva. You shall see respective state indicators on the Malaysia map.
- Drag `number (by-state)` to Color on the Marks card. Repeat, drag to Label.
- Select 'Map' from the Marks card.
- Create the `date` filter as #4 above.
- Alternatively, select 'Circle' from the Marks card, and drag another `number (by-state)` to 'Size'.

![daily new cases by state map](https://github.com/yanbin43/workshop-20210602-dataviz/blob/main/images/daily-state-map.JPG)
