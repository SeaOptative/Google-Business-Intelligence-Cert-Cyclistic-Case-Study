# Project Requirements Document: Cyclistic

Purpose: 
Cyclistic's Customer Growth Team is developing a business plan for the upcoming year. The team wants to understand how their customers are using their bikes; their top priority is identifying customer demand at different station locations. The dataset includes millions of rides, so the team wants a dashboard that summarizes key insights. Business plans that are driven by customer insights are more successful than plans driven by just internal staff observations. The executive view must include key data points that are summarized and aggregated in order for the leadership team to get a clear vision of how customers are using Cyclistic.
Key dependencies: 
This project will require a dataset of customer data, so the Director of Customer Data will need to approve the request. Approval should also be given by the teams that own specific product data including bike trip duration and bike identification numbers to validate that the data is being interpreted correctly. The primary contacts are Adhira Patel, Megan Pirato, Rick Andersson, and Tessa Blackwell. 
Stakeholder requirements: 
In order to continuously improve and effectively market products, the dashboard must help Cyclistic decision-makers understand how their customers are using the bikes and the demand at different locations, including factors that might influence that demand at different times.  
●	A table or map visualization exploring starting and ending station locations, aggregated by location. R
●	A visualization showing which destination (ending) locations are popular based on the total trip minutes. R
●	A visualization that focuses on trends from the summer of 2015. D
●	A visualization showing the percent growth in the number of trips year over year. R
●	Gather insights about congestion at stations. N
●	Gather insights about the number of trips across all starting and ending locations. R
●	Gather insights about peak usage by time of day, season, and the impact of weather. R

Success criteria: 
Specific: BI insights must clearly identify the specific characteristics of a successful product. They must demonstrate how customers are currently using bikes and what impacts demand at station locations. Measurable: Each trip should be evaluated using starting and ending location, duration, variables such as time of day, season, and weather. For example, do customers use Cyclistic less when it rains? Or does bikeshare demand stay consistent? Does this vary by location and user types (subscribers vs. non-subscribers)? Action-oriented: These outcomes must prove or disprove the theory that location, time, season, and weather impact user demand. Then, the Cyclistic team will use this knowledge to refine future product development. Relevant: All metrics must support the primary question: How can we build a better Cyclistic experience? Time-bound: Analyze data that spans at least one year to see how seasonality affects usage. Exploring data that spans multiple months will capture peaks and valleys in usage. 
User journeys: 
The main purpose of Cyclistic is to provide customers with a better bike-share experience. A deeper dive into trip trends will help decision-makers explore how customers are currently using Cyclistic bikes and how that experience can be improved. 
Assumptions: 
The dataset includes latitude and longitude of stations but does not identify more geographic aggregation details like zip code, neighborhood name, or borough. The team will provide a separate database with this data. 
The weather data provided does not include what time precipitation occurred; it’s possible that on some days, it precipitated during off-peak hours. However, for the purpose of this dashboard, you should assume any amount of precipitation that occurred on the day of the trip could have an impact.
Starting bike trips at a location will be impossible if there are no bikes available at a station, so we might need to consider other factors for demand.
Compliance and privacy: 
The data must not include any personal data such as name, email address, phone number, or physical address. The user provides this data as part of their device activation but is not necessary for this project. It is paramount that the users be anonymized to avoid any bias. 
Accessibility: 
The dashboards should offer text alternatives including large print and text-to-speech.
Roll-out plan: 
The stakeholders have requested a completed BI tool in six weeks:
●	Week 1: Dataset assigned. Initial design for fields and BikeIDs validated to fit the requirements.
●	Weeks 2-3: SQL & ETL development
●	Weeks 3-4: Finalize SQL. Dashboard design. 1st draft review with peers.
●	Weeks 5-6: Dashboard development and testing




