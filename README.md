# ARX Heatmaps – Visualization Tool for RadiosondeAutoRX Logs

This HTML/JavaScript tool helps you visualize data from your **Radiosonde Auto RX** logs.  
The `main.html` file creates or updates a local **IndexedDB** in your browser, which stores the data for plotting.

---

## 📌 How to Use

### 1. Prepare Your Data

- Copy the log files from your `RadiosondeAutoRX` folder into a new folder.
- Include a copy of the `station.cfg` file in the same folder.

> ⚠️ **If you have many log files (e.g., over 2000), process them in batches:**
> - Copy a portion of the logs.
> - Open `main.html` and update the database.
> - Replace with the next batch and repeat the process.
> - Do this until all logs are imported into the DB.

---

### 2. Update the Database

- Open `main.html` in your browser.
- Click **Update Database** to process and store the data.
- You can repeat this step anytime to add new logs.

---

### 3. Generate and View Plots

- Choose the desired plot type.
- Enter the required parameters.
- Visualize and explore your data!

---

## 💡 Contribute

Want to add new plots or features?  
Contribute on GitHub:  
🔗 [https://github.com/73-de-LZ/ARX-Heatmaps](https://github.com/73-de-LZ/ARX-Heatmaps)
