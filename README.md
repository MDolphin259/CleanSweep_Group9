# This application takes in a floor plan file, breaks it into a square grid, and runs a virtual cleaner through each square.
# On each square, we generate a random amount of dirt and run a cleaning procedure to ensure each square is cleaned of all dirt.
# Walls are checked on each side to ensure we are not moving into a blocked square.
# After each square is cleaned or power is reduced to a certain threshold, the closest charger is identified and the cleaner returns there.
