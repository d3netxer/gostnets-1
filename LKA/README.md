#### Sri Lanka Road Optimization
This notebook is part of a world bank tourism project for Sri Lanka. The analysis measures driving travel time from airports to district capitals to toursim destinations, and identifies high-use roads for rehabilitation.

#### Workflow
- part 1: OD Airport to major cities
- part 2: OD Major cities to one another
- part 3: OD Major cities to tourism destinations
- part 4*: OD using mapbox traffic api OR mapbox roads data w/ traffic (2-3x for different times of day)
- part 5*: Identify optimal edges for road rehabilitation (traffic travel time is divergent)
- part 6*: OD - simulate road improvements with adjusted cost
- part 7*: identify possible edges for improvement (highest value for money). 
#### *To-do
