# ARX Heatmaps – Visualization Tool for RadiosondeAutoRX Logs

This HTML/JavaScript tool helps you visualize data from your **Radiosonde Auto RX** logs.  
The `Main.html` file creates or updates a local **IndexedDB** in your browser, which stores the data for plotting.

## Example plots:
<div style="display: flex; flex-wrap: wrap;">
    <img src="/Example_plots/SNR-ALT_AZ (1).png" alt="SNR-ALT_AZ 1" width="200" style="margin: 10px;">
    <img src="/Example_plots/SNR-ALT_AZ (2).png" alt="SNR-ALT_AZ 2" width="200" style="margin: 10px;">
    <img src="/Example_plots/snr-az-alt-plot-2025-05-14.png" alt="NEW AZ ALT Counts" width="200" style="margin: 10px;">
    <img src="/Example_plots/SNR-ALT_AZ (3).png" alt="SNR-ALT_AZ 3" width="200" style="margin: 10px;">
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

### 2. Update the Database

- Open `Main.html` in your browser.
- Click **Update Database** to process and store the data.
- You can repeat this step anytime to add new logs.

<details>
<summary><strong>* Firefox users:</strong></summary>
<small>

You will need to host the .html files on a local server. To run a simple server:

```
cd /path/to/yourDirectory/with_html_files/
python3 -m http.server 8000
```
Open .html files from:
http://localhost:8000

** Windows and Firefox - you will need Python to be installed.
</small>
</details>

### ⚠️ Troubleshooting Tips

<details>
<summary><strong>⚠️ Manually delete the IndexedDB if there is some issue</strong></summary>
<small>

Sometimes the browser’s local database can get stuck or corrupted. Here's how to clear it:

#### Chrome / Chromium / Edge
- Open Developer Tools (F12 or Ctrl+Shift+I)  
- Go to the **Application** tab  
- In the left sidebar under **Storage**, expand **IndexedDB**  
- Right-click on `RadiosondeDB` and choose **Delete database**

#### Firefox
- Open Developer Tools (F12)  
- Go to the **Storage** tab  
- Expand **IndexedDB** in the sidebar  
- Right-click on `RadiosondeDB` and choose **Delete All**

#### Safari (macOS)
- Enable the **Develop** menu in Safari preferences (Advanced > Show Develop menu)  
- Open Web Inspector (Cmd+Opt+I)  
- Go to the **Storage** tab  
- Expand **IndexedDB**, right-click the database and choose **Delete**

</small>
</details>

### 3. Generate and View Plots

- Choose the desired plot type.
- Change the required parameters.
- Visualize and explore your data!

## 💡 Contribute

Want to add new plots or features?  
Contributions or suggestions are welcome!
