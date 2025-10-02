# lok_sabha-
Lok Sabha 2024 Election Dashboard
Overview
This project is an interactive dashboard built in Python that visualizes the results of the Lok Sabha 2024 elections. It provides insights into party performance, state-wise seat distribution, vote margins, and predicts the likely government formation based on the majority of seats.
The dashboard allows users to explore the election data interactively with filters for states, parties, and alliances.
Features
Top 10 Parties by Seats
Displays a horizontal bar chart showing parties with the highest number of seats.
State-wise Seats Distribution
Horizontal bar chart showing the number of Lok Sabha seats per state and union territory.
Seven Sister States Analysis
Bar chart showing seat distribution for the Northeastern states: Arunachal Pradesh, Assam, Manipur, Meghalaya, Mizoram, Nagaland, and Tripura.
Party-wise Seats by State
Stacked horizontal bar chart showing which party won how many seats in each state.
Alliance-wise Seats Distribution
Pie chart displaying the seat share of major alliances (NDA, INDIA, Others).
Vote Margin Analysis
Shows the largest victory margins in constituencies, highlighting the competitive races.
Predicted PM / Majority Party
Determines which party or alliance has enough seats to form a government and predicts the likely PM candidate.
Interactive Filters
Filter results by state using a sidebar dropdown.

Technologies Used
Python 3.x
Libraries:
pandas – Data manipulation
matplotlib – Visualization

Dataset
File: election_result_2024.csv
Columns (expected):
state_name – Name of the state
constituency_name – Name of the constituency
candidate_name – Candidate who contested
party_name – Political party of the candidate
votes – Total votes received
rank – Candidate rank in the constituency (1 = winner)
Note: Ensure the dataset is cleaned and contains only valid numeric vote counts.


Future Enhancements
Add vote share percentage for each party and constituency.
Include interactive maps using Plotly or Folium to visualize state-wise seat distribution geographically.
Add coalition-based predictions with real-time vote margin updates.
Integrate live election results from official sources.

Author
Name: REETIKA SINGH
Email: reetikasingh004@gmail.com
