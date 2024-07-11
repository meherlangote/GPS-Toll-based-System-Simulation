# GPS-Toll-based-System-Simulation
Simulation of a GPS-based toll system using Python, Folium, Geopy, and Pandas
Overview
This project simulates a toll-based system using Python. The simulation tracks various vehicles as they move through different toll areas, calculates the toll charges based on dynamic pricing, and logs the details of each journey. The data is visualized using folium maps and tabulated using pandas DataFrames.

Features
Dynamic Pricing: Toll rates vary based on vehicle type and time of day, with increased rates during peak hours.
Speed Monitoring: Vehicles are simulated with random speeds, and warnings are logged if they exceed the speed limit.
Data Visualization: A folium map displays toll area locations and vehicle movements, and a pandas DataFrame presents the journey details in a tabular format.

Usage
Define Toll Areas: Specify toll areas with entry and exit points, speed limits, and dynamic pricing rates for different vehicle types.
Initialize Vehicles: Create vehicle instances with unique IDs and types.
Simulate Traffic: Run the simulation for a specified number of steps, logging vehicle movements and calculating tolls.
Visualize Data: Generate a folium map and a pandas DataFrame to visualize the results
Output
The simulation generates a DataFrame showing details of each vehicle's journey, including:

Vehicle ID
Vehicle Type
Toll Area
Distance traveled
Toll Charge
Speed
Speed Warnings
Total Distance
Total Toll

   Vehicle ID Vehicle Type     Toll Area  Distance (km)  Toll Charge (₹)  Speed (km/h)          Speed Warning  Total Distance (km)  Total Toll (₹)
0           1          car  Aurangabad Toll           6.78             30.50       57.53                                  6.78             30.50
1           2        truck  Aurangabad Toll           6.78             61.00       80.11       (Speed Limit Exceeded!)           6.78             61.00
2           3          car    Nashik Toll            1.80              6.30       51.83                                  1.80              6.30
3           4        truck  Aurangabad Toll           6.78             61.00       60.13                                  6.78             61.00
4           5          car    Nashik Toll            1.80              6.30       46.44                                  1.80              6.30


Map Visualization
The folium map shows the entry and exit points of each toll area and the paths taken by the vehicles. The map is saved as toll_areas_mapf.html.

Future Enhancements
Additional Vehicle Types: Expand the simulation to include more vehicle types with different toll rates.
Real-time Data Integration: Integrate real-time traffic and toll data for more accurate simulations.
User Interface: Develop a user-friendly interface for inputting toll area data and viewing simulation results.
Advanced Analytics: Implement advanced analytics and visualization tools for deeper insights into traffic patterns and toll revenue.

Conclusion
This project provides a comprehensive simulation of a toll-based system using Python, folium, geopy, and pandas. It offers dynamic pricing, speed monitoring, and detailed data visualization, making it a valuable tool for analyzing toll road usage and traffic patterns. Future enhancements can further improve its accuracy, usability, and analytical capabilities.
