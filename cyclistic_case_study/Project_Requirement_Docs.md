# Project Requirements Document: Cyclistic

Cyclistic’s Customer Growth Team is developing a business plan for the upcoming year. They want to understand customer bike usage and identify demand at different station locations. The dataset includes millions of rides, so they need a dashboard summarizing key insights. Customer-driven business plans are more successful than those based solely on internal observations. The executive view should include aggregated data points to help leadership understand customer usage on Cyclistic. 

Key Dependencies:

This project requires customer data approval from the Director of Customer Data. Additionally, the product data teams, including bike trip durations and bike identification numbers, must approve to ensure accurate data interpretation.

Primary Contacts:

* Adhira Patel
* Megan Pirato
* Rick Andersson
* Tessa Blackwell 

Stakeholder requirements:

The dashboard must help Cyclistic decision-makers understand customer bike usage and demand at different locations, considering factors that influence demand at different times, to continuously improve and effectively market products.
 ● A table or map visualization showing starting and ending station locations aggregated by location. R
● A visualization showing popular destination locations based on total trip minutes. R
● A visualization focusing on summer 2015 trends. D
● A visualization showing year-over-year trip growth. R
● Gather insights about station congestion. N
● Gather insights about total trips across locations. R
● Gather insights about peak usage by time of day, season, and weather impact. R

Success criteria:

- Specific: BI insights must clearly identify product characteristics and customer bike usage, impacting demand at station locations.
- Measurable: Each trip should be evaluated using starting and ending locations, duration, time of day, season, and weather.
- Action-oriented: Outcomes must prove or disprove the impact of location, time, season, and weather on user demand, enabling Cyclistic to refine product development.
- Relevant: Metrics must support the primary question: How can we build a better Cyclistic experience?
- Time-bound: Analyze data spanning at least a year to see seasonality’s impact on usage, with multiple-month data capturing peak and valley trends. 

User Journeys: Enhancing the Bike-Share Experience
The primary objective of Cyclistic is to elevate the overall bike-share experience for its customers. An in-depth analysis of trip trends will empower decision-makers to gain insights into the current usage patterns of Cyclistic bikes and identify opportunities for enhancing the customer experience. 

Assumptions: The dataset includes latitude and longitude of stations but does not provide additional geographic aggregation details such as zip codes, neighborhood names, or boroughs. The team will provide a separate database containing this information.

The weather data provided does not specify the time of precipitation occurrence. It is possible that precipitation occurred during off-peak hours on certain days. However, for the purpose of this dashboard, it is reasonable to assume that any precipitation that occurred on the day of the trip could have an impact.

Beginning bike trips at a location will be impossible if there are no available bikes at a station. Therefore, we may need to consider other factors for demand. 

Compliance and Privacy: The dataset must not contain any personal information such as names, email addresses, phone numbers, or physical addresses. Users provide this data as part of their device activation, but it is not essential for the project’s functionality. Anonymization of users is crucial to prevent any potential biases.

Accessibility: The dashboards should provide text alternatives, including large print and text-to-speech capabilities. 

Roll-out Plan:

Stakeholder Request:
The stakeholders have requested a comprehensive Business Intelligence (BI) tool to be completed within six weeks.

Week 1:
- Dataset Assignment: The dataset will be assigned to the team.
- Initial Design Validation: The initial design for the fields and BikeIDs will be validated to ensure alignment with the project requirements.

Week 2-3:
- SQL and ETL Development: The team will focus on developing SQL queries and ETL processes.

Week 3-4:
- Finalization of SQL: The SQL queries will be finalized.
- Dashboard Design: The dashboard design will be completed.
- First Draft Review with Peers: The dashboard will be reviewed and feedback will be provided by peers.

Week 5-6:
- Dashboard Development and Testing: The team will continue developing the dashboard and conducting thorough testing to
