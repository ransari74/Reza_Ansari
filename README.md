# Processing INRIX Data
INRIX provides user the high resolution traffic data. These data are huge in size, so, reading, cleaning, and processing it makes time. In this tutorial we provide coding to read, clean and extract data you needed from INRIX data using Pandas. However, due to the copy right law, I can not provides any sample of INRIX data in github. In the following we will elaborate on the output of INRIX traffic data shape. 

''INRIX Roadway Analytics data downloader reports include the columns listed below.  For additional information, please visit https://analytics.inrix.com/help 
 
Note that speed values display in either mph or kmh, based on the user preference as set in the ‘My Account’ section of Roadway Analytics.
 
Date Time	Timestamp in local time
Segment ID	INRIX XD segment ID
UTC Date Time	Timestamp in UTC
Speed(mph or kmh)	Estimated harmonic mean speed
Historic Average Speed(mph or kmh) 	Historical average speed for that hour of the day and day of the week
Ref Speed(mph or kmh)	The ‘free flow speed’. The speed driven on this road when it is  wide open, based on INRIX historical data.  Note that this is not legal speed limit.
Travel Time (Minutes)	The travel time in minutes
CValue 	The confidence value is an integer ranging from 0 to 100 inclusive that indicates the confidence that INRIX has in the correctness of a real-time speeds
Pct Score30	Percentage of the segment minutes based on actual speeds data for the time period.
Pct Score20	Percentage of the segment minutes based on historic average speed.
Pct Score10	Percentage of the segment minutes based on the reference ‘free flow’ speed.
''
