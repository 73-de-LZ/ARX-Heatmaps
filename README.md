# ARX-Heatmaps
html/.js plots from radiosonde_auto_rx log files

ARX Heatmaps – Visualization Tool for RadiosondeAutoRX Logs
This HTML/JavaScript-based tool helps you visualize data from your Radiosonde Auto RX logs.

The main.html file will create or update a local IndexedDB in your browser, which will then be used to generate various plots and visualizations.

📌 How to Use
1. Prepare Your Data
Copy the log files from your RadiosondeAutoRX folder into a new folder.

Also include a copy of the station.cfg file in the same folder.

⚠️ If you have a large number of log files (e.g., more than 2000), process them in batches:

Copy a portion of the logs to the folder.

Open main.html in your browser and update the database.

Repeat the process by replacing the logs with the next batch and updating the database again.

Do this until all logs have been processed.

2. Update the Database
Open main.html in your browser.

Click Update Database to process and store data in your browser's IndexedDB.

You can repeat this step periodically to add newly generated logs.

3. Generate and View Plots
Choose the desired plot type.

Enter the required parameters.

Enjoy exploring your data visually!

