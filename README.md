# ARX Heatmaps – Visualization Tool for RadiosondeAutoRX Logs

This HTML/JavaScript tool helps you visualize data from your **Radiosonde Auto RX** logs.  
The `main.html` file creates or updates a local **IndexedDB** in your browser, which stores the data for plotting.

## Example plots:
<div style="display: flex; flex-wrap: wrap;">
    <img src="/Example_plots/SNR-ALT_AZ (1).png" alt="SNR-ALT_AZ 1" width="200" style="margin: 10px;">
    <img src="/Example_plots/SNR-ALT_AZ (2).png" alt="SNR-ALT_AZ 2" width="200" style="margin: 10px;">
    <img src="/Example_plots/SNR-ALT_AZ (3).png" alt="SNR-ALT_AZ 3" width="200" style="margin: 10px;">
    <img src="/Example_plots/SNR-ALT_AZ (4).png" alt="SNR-ALT_AZ 4" width="200" style="margin: 10px;">
    <img src="/Example_plots/SNR-ALT_AZ (5).png" alt="SNR-ALT_AZ 5" width="200" style="margin: 10px;">
    <img src="/Example_plots/SNR-ALT_DIST (1).png" alt="SNR-ALT_DIST 1" width="200" style="margin: 10px;">
    <img src="/Example_plots/SNR-ALT_DIST (2).png" alt="SNR-ALT_DIST 2" width="200" style="margin: 10px;">
    <img src="/Example_plots/SNR-ALT_DIST (3).png" alt="SNR-ALT_DIST 3" width="200" style="margin: 10px;">
    <img src="/Example_plots/SNR-ALT_DIST (4).png" alt="SNR-ALT_DIST 4" width="200" style="margin: 10px;">
    <img src="/Example_plots/SNR-ALT_DIST (5).png" alt="SNR-ALT_DIST 5" width="200" style="margin: 10px;">
    <img src="/Example_plots/SNR-ALT_DIST (6).png" alt="SNR-ALT_DIST 6" width="200" style="margin: 10px;">
    <img src="/Example_plots/SNR-EL_AZ.png" alt="SNR-EL_AZ" width="200" style="margin: 10px;">
</div>

## 📌 How to Use

### 1. Prepare Your Data

- Copy the log files from your `RadiosondeAutoRX` folder into a local folder.
- Include a copy of the `station.cfg` file in the same folder.
- Copy all .html files from this repository to a different local folder on your PC.

> ⚠️ **If you have many log files (e.g., over 2000), process them in batches:**
> - Copy a portion of the logs.
> - Open `main.html` and update the database.
> - Add the next batch and repeat the process.
> - Do this until all logs are imported into the DB.

---

### 2. Update the Database

- Open `main.html` in your browser.
- Click **Update Database** to process and store the data.
- You can repeat this step anytime to add new logs.

---

### 3. Generate and View Plots

- Choose the desired plot type.
- Change the required parameters.
- Visualize and explore your data!

---

## 💡 Contribute

Want to add new plots or features?  
Contributons or suggestions are welcome!

