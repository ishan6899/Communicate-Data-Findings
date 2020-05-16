# Communicate-Data-Findings
## Dataset I Choose
> I used the Ford GoBike Dataset.
>  There are 1863721 entries,in our dataset with 20 variables. The datset consists of data from over 12 months from January 2018-December 2018
> The variables are as follows:
* duration,start_time,end_time(This is basically the duration info)
* start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude, end_station_longitude(This is basically station info)
* bike_id, user_type, bike_share_for_all_trip(This is the member info. Also it is private)<br>
<b>Apart from that I made some columns which will be usefull for our analysis:</b>
- startdate,startmonth,starthour,startweek

## Main findings from Exploratory Data Analysis and how I put my results in Explanatory Data Analysis

>First I did Univarirate Exploration and found out how the count varies daily,monthly,weekly:
* All winter months have less counts given the fact it is too cold(Nov-Feb)
* Summer months have a relatively larger count. (May-Sept)
* It peaks in October which is the most pleasant month
* Count in weekdays is pretty much high than count in weekends
* In the weekdays Monday has the lowest count. Monday is notorously famous for this
* This shows people mostly use it for office rather than recreation
* It peaks at 8AM and 5PM two of the most common times of office going and coming back resp.
* At late night also some people do love cycling

>I also found out the user type and found out 85% are subscribers
>After that I did bivariate Analysis:
* Mostly it was variation of user type on  days,month,weeks
** Mostly subscribers prefer cycling on weekdays this means Mostly subscirbers are office going ppl
* Generally on weekdays the ratio is maintained(85:15)
* But on weekends there is a spike in customers and a substantial drop in subscribers again pointing out that office ppl are the one's who generally subscribe
* General spike in summer months and october (as estbld earlier)
* Both customers and subscibers increase in summer months and october 
> Lastly I did multivariate analysis and found out that duration varies between various users on days of week and hour of day
> I also found out average duration

### To put these results in explanatory data analysis I formed a flow and presented it as a chain of events. I asked some interesting questions and solved it with the visualisations done earlier

## Feedback
> I took feedback from my mom and dad and they appreciated the flow of things and how one question was predeccesor of another and like that

## Resources Used:
* Stack Overflow- A lot of doubts ranging for syntax of increasing fig size to some numpy questions
* Udacity Data Analyst Course- I referred it too if I had doubts
* Official Documentation of matplotlib and python- It also helped a lot in various places  
