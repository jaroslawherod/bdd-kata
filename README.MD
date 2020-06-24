Snow 
==========

## Task

Your task is to implement SnowRescueService class - this is your System Under Test. Treat all other classes as dependencies.

1. Send sander if temperature will be below 0 C

2. Send snowplow if snowfall exceed 3 mm
	
3. If snowplow fails (SnowplowMalfunctioningException) - send another
		
4. Send two snowplows if snowfall exceed 5 mm

5. If temperature drops below -10 and snowfall exceed 10 mm, send three snowplows, a sander and notify press. 


# Good to know

*Mockito documentation:*
https://javadoc.io/doc/org.mockito/mockito-core/latest/org/mockito/Mockito.html
