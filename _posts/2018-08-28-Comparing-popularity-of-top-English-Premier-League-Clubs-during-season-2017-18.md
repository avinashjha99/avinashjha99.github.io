---
published: true
---
To compare the popularity of the English Premier League Clubs, I used the data provided by Google Keywords platform. The platform provides a measure of the total interest showed towards a particular entity by people during a selected period. In this case, I pulled out the data for 42 weeks starting 6th August 2017 and ending 20th May 2018. 
First let me present the relative popularity of the teams in the line chart and table then we will continue the discussion by asking some pertinent questions:

<canvas id="myChart" width="400" height="400"></canvas>
<script>
  var ctx = document.getElementById("myChart");
  var myChart = new Chart(ctx,{
  "type": "line",
  "data": {
    "labels": [
      "06 August 2017",
"13 August 2017",
"20 August 2017",
"27 August 2017",
"03 September 2017",
"10 September 2017",
"17 September 2017",
"24 September 2017",
"01 October 2017",
"08 October 2017",
"15 October 2017",
"22 October 2017",
"29 October 2017",
"05 November 2017",
"12 November 2017",
"19 November 2017",
"26 November 2017",
"03 December 2017",
"10 December 2017",
"17 December 2017",
"24 December 2017",
"31 December 2017",
"07 January 2018",
"14 January 2018",
"21 January 2018",
"28 January 2018",
"04 February 2018",
"11 February 2018",
"18 February 2018",
"25 February 2018",
"04 March 2018",
"11 March 2018",
"18 March 2018",
"25 March 2018",
"01 April 2018",
"08 April 2018",
"15 April 2018",
"22 April 2018",
"29 April 2018",
"06 May 2018",
"13 May 2018",
"20 May 2018",
"27 May 2018"

    ],
    "datasets": [
      {
        "label": "Chelsea",
        "fill": false,
        "lineTension": 0.1,
        "backgroundColor": "rgba(0,0,120,0.8)",
        "borderColor": "rgba(0,0,250,0.8)",
        "borderCapStyle": "butt",
        "borderDash": [],
        "borderDashOffset": 0,
        "borderJoinStyle": "miter",
        "pointBorderColor": "rgba(0,0,250,0.8)",
        "pointBackgroundColor": "#fff",
        "pointBorderWidth": 1,
        "pointHoverRadius": 5,
        "pointHoverBackgroundColor": "rgba(75,192,192,1)",
        "pointHoverBorderColor": "rgba(220,220,220,1)",
        "pointHoverBorderWidth": 2,
        "pointRadius": 1,
        "pointHitRadius": 10,
        "data": [
          33,
26,
31,
36,
20,
21,
25,
28,
12,
13,
21,
17,
19,
21,
13,
20,
17,
19,
17,
16,
17,
27,
27,
24,
26,
25,
21,
23,
50,
21,
22,
43,
14,
9,
15,
14,
13,
17,
11,
21,
25,
16,
14       ],
        "spanGaps": false
      },
      
{
        "label": "Arsenal",
        "fill": false,
        "lineTension": 0.1,
        "backgroundColor": "rgba(250,10,10,0.8)",
        "borderColor": "rgba(250,10,10,0.4)",
        "borderCapStyle": "butt",
        "borderDash": [],
        "borderDashOffset": 0,
        "borderJoinStyle": "miter",
        "pointBorderColor": "rgba(250,10,10,0.8)",
        "pointBackgroundColor": "#fff",
        "pointBorderWidth": 1,
        "pointHoverRadius": 5,
        "pointHoverBackgroundColor": "rgba(75,192,192,1)",
        "pointHoverBorderColor": "rgba(220,220,220,1)",
        "pointHoverBorderWidth": 2,
        "pointRadius": 1,
        "pointHitRadius": 10,
        "data": [
          41,
25,
22,
39,
16,
22,
21,
19,
13,
12,
13,
21,
14,
14,
15,
13,
25,
15,
17,
23,
18,
27,
29,
36,
39,
40,
24,
15,
17,
29,
26,
24,
10,
10,
19,
19,
17,
30,
34,
19,
17,
20,
18    ],
        "spanGaps": false
      },
      {
        "label": "Man U",
        "fill": false,
        "lineTension": 0.1,
        "backgroundColor": "rgba(200,10,10,0.8)",
        "borderColor": "rgba(200,10,10,0.8)",
        "borderCapStyle": "butt",
        "borderDash": [],
        "borderDashOffset": 0,
        "borderJoinStyle": "miter",
        "pointBorderColor": "rgba(200,10,10,0.8)",
        "pointBackgroundColor": "#fff",
        "pointBorderWidth": 1,
        "pointHoverRadius": 5,
        "pointHoverBackgroundColor": "rgba(75,192,192,1)",
        "pointHoverBorderColor": "rgba(220,220,220,1)",
        "pointHoverBorderWidth": 2,
        "pointRadius": 1,
        "pointHitRadius": 10,
        "data": [
          54,
51,
39,
35,
26,
25,
37,
31,
18,
29,
28,
28,
24,
25,
21,
26,
30,
28,
38,
33,
30,
33,
27,
56,
42,
35,
20,
27,
29,
30,
40,
38,
16,
18,
30,
21,
32,
18,
28,
19,
32,
18,
20],
        "spanGaps": false
      },
       {
        "label": "Man City",
        "fill": false,
        "lineTension": 0.1,
        "backgroundColor": "rgba(0,0,255,0.4)",
        "borderColor": "rgba(0,0,255,0.4)",
        "borderCapStyle": "butt",
        "borderDash": [],
        "borderDashOffset": 0,
        "borderJoinStyle": "miter",
        "pointBorderColor": "rgba(0,0,255,0.4)",
        "pointBackgroundColor": "#fff",
        "pointBorderWidth": 1,
        "pointHoverRadius": 5,
        "pointHoverBackgroundColor": "rgba(75,192,192,1)",
        "pointHoverBorderColor": "rgba(220,220,220,1)",
        "pointHoverBorderWidth": 2,
        "pointRadius": 1,
        "pointHitRadius": 10,
        "data": [
          9,
7,
14,
7,
10,
10,
9,
13,
5,
7,
13,
10,
12,
10,
6,
8,
12,
15,
25,
14,
13,
16,
12,
20,
10,
14,
8,
12,
12,
20,
17,
10,
5,
7,
37,
31,
8,
7,
6,
8,
6,
4,
4     ],
        "spanGaps": false
      },
      {
        "label": "Liverpool",
        "fill": false,
        "lineTension": 0.1,
        "backgroundColor": "rgba(255,155,0,0.8)",
        "borderColor": "rgba(255,155,0,0.8)",
        "borderCapStyle": "butt",
        "borderDash": [],
        "borderDashOffset": 0,
        "borderJoinStyle": "miter",
        "pointBorderColor": "rgba(255,155,0,0.8)",
        "pointBackgroundColor": "#fff",
        "pointBorderWidth": 1,
        "pointHoverRadius": 5,
        "pointHoverBackgroundColor": "rgba(75,192,192,1)",
        "pointHoverBorderColor": "rgba(220,220,220,1)",
        "pointHoverBorderWidth": 2,
        "pointRadius": 1,
        "pointHitRadius": 10,
        "data": [
          29,
31,
30,
44,
23,
21,
18,
16,
13,
21,
16,
19,
17,
11,
13,
23,
19,
20,
21,
25,
27,
33,
28,
39,
27,
21,
22,
28,
18,
19,
34,
20,
15,
17,
49,
49,
25,
77,
79,
32,
27,
100,
49   ],
        "spanGaps": false
      }
      
    ]
  },
  "options": {}
});

</script>

<style>
  table{
    border-collapse: collapse;
    border-spacing: 0;
    border:2px solid #ff0000;
}

th{
    border:2px solid #000000;
}

td{
    border:1px solid #000000;
}
</style>
Here is the list of most popular teams for every week:

Week # |	Week Ending|	Approximate EPL Match Week|	Most Popular Team of the Week on Google Search
------|-----------|--------|-----------|
Week 1|	06 August 2017|	-	|Man U
Week 2	|13 August 2017	|Match Week 1	|Man U
Week 3	|20 August 2017	|Match Week 2|	Man U
Week 4	|27 August 2017	|Match Week 3|	Liverpool
Week 5	|03 September 2017|	-|	Man U
Week 6	|10 September 2017|	Match Week 4|	Man U
Week 7	|17 September 2017|	Match Week 5|	Man U
Week 8	|24 September 2017|	Match Week 6|	Man U
Week 9	|01 October 2017|	Match Week 7|	Man U
Week 10	|08 October 2017|	-	|Man U
Week 11	|15 October 2017|	Match Week 8|	Man U
Week 12	|22 October 2017|	Match Week 9|	Man U
Week 13	|29 October 2017|	Match Week 10|	Man U
Week 14	|05 November 2017|	Match Week 11|	Man U
Week 15	|12 November 2017|	-	|Man U
Week 16	|19 November 2017|	Match Week 12|	Man U
Week 17	|26 November 2017|	Match Week 13-14|	Man U
Week 18	|03 December 2017|	Match Week 15|	Man U
Week 19	|10 December 2017|	Match Week 16|	Man City
Week 20	|17 December 2017|	Match Week 17-18|	Man U
Week 21	|24 December 2017|	Match Week 19|	Man U
Week 22	|31 December 2017|	Match Week 20-21|	Man U/Liverpool
Week 23	|07 January 2018|	Match Week 22|	Arsenal
Week 24	|14 January 2018|	Match Week 23|	Man U
Week 25	|21 January 2018|	Matche Week 24|	Man U
Week 26	|28 January 2018|	Matche Week 25|Arsenal
Week 27	|04 February 2018|	Match Week 26|	Arsenal
Week 28	|11 February 2018|	Match Week 27|	Liverpool
Week 29	|18 February 2018|	-	|Chelsea
Week 31	|04 March 2018|	Match Week 28	|Man U
Week 32	|11 March 2018|	Match Week 29	|Chelsea
Week 33	|18 March 2018|	Match Week 30	|Man U
Week 34	|25 March 2018|	Match Week 31	|Man U
Week 35	|01 April 2018|	Match Week 32	|Liverpool
Week 36	|08 April 2018|	Match Week 33	|Liverpool
Week 37	|15 April 2018|	Match Week 34|	Man U
Week 38	|22 April 2018|	Match Week 35|	Liverpool
Week 39	|29 April 2018|	Match Week 36|	Liverpool
Week 40	|06 May 2018|	Match Week 37|	Liverpool
Week 41	|13 May 2018|	Match Week 38|	Man U
Week 42	|20 May 2018|	-	|Liverpool

Now let's go straight into questions:

> :question: Which was the most popular and least popular team over the period of 42 weeks?

Man United was indeed the most popular team. However, it was only marginally ahead of Liverpool. Liverpool gained momentum towards the last few weeks and that too by huge margins.

Man City was the least popular team. And that too by huge margin. It was no where near the Chelsea which was at 3rd place. However, Chelsea was only marginally behind Arsenal. 

> :question: Why were Arsenal and Chelsea were topping the charts in the first quarter of 2018?

Arsenal and Chelsea lost of a string of matches during that time. And because of this, coaches from both the teams [Arsène Wenger](https://en.wikipedia.org/wiki/Arsène_Wenger) and [Antonio Conte](https://en.wikipedia.org/wiki/Antonio_Conte) drew huge criticism from media and their fans. This might have led to the rise in popularity of the teams. 
So winning the matches and cups are not always the only strategy to be popular!

> :question: What was the reason behind phenomenal rise in popularity of Liverpool towards the end?

Liverpool had discovered a star in form of Mohammed Salah. He performed consistently during that season and hence his popularity grew. This might have helped Liverpool. In addition to rise of Mohammed Salah, Liverpool performed extremely well in Champion's League defeating big teams like Roma and Manchester United. Also, Liverpool ended the winning streak of Manchester City in English Premiere League.  All this probably sent the popularity of Liverpool through the roof.

> :question: What are other surprising insights from this data from 2017-18?

The most surprising insight has to be the low popularity of Man City despite it's superb performance. The causes of rise of popularity of Liverpool seems to be exactly the reason of low poularity of Man City. Man City is full of expensive players and performs well as a team but no one outstanding star. Also, Man City did not go through Champion's League. Probably the lack of charismatic player and absence from Champions League Final may have withheld rise in popularity of Man City. 

Man City is already trying to circumvent this problem by coming up with a TV documentary showing the success of their season 2017-18. The TV documentary focuses on how [Pep Guardiola](https://en.wikipedia.org/wiki/Pep_Guardiola) built the champion team. Probably, this will project him as the charismatic leader and coach.
