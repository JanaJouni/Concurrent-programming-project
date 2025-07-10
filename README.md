# Concurrent-programming-project

# Decay Simulation - How to Run

1. Install Docker Desktop: https://www.docker.com/products/docker-desktop/
   - Make sure Docker is running before proceeding.

2. Unzip this folder in C:\cp (create cp folder)

3. Double-click on `run_decay.bat`

4. Wait for the simulation to complete.
   - It sleeps for 10 seconds so you can open VisualVM if needed.

5. When done, check the generated file and charts will be available:
   `final_results.csv`

note: If you want to monitor with VisualVM:
   - Open it (C:\cp\visualvm_22\bin\VisualVM) during the 10 second sleep period 
   - right-click on local and add JMX connection and put the port number 9010
   - when connected press in monitor 
