This code adds up all the temperature values and divides by the number of readings to find the average 
# Room-1-Sensor-Data-and-Basic-Operations 
temperatures = [23.5, 25.0, 22.0, 26.5, 24.5]
# Calculate the sum of temperatures
total = 0
for temp in temperatures:
    total += temp
# Calculate the average by dividing total by the number of temperatures
average_temp = total / len(temperatures)
# Print the average temperature
print(f"The average temperature is: {average_temp}")
