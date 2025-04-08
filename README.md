# ERA5 Data Download Guide

I used atmospheric data

This guide provides step-by-step instructions on how to download ERA5 reanalysis data from the European Centre for Medium-Range Weather Forecasts (ECMWF) website.

## 📥 Steps to Download ERA5 Reanalysis Data

1. Go to the official ECMWF website: [https://www.ecmwf.int/](https://www.ecmwf.int/)
2. Log in or register for a free account.
3. Scroll down to **Forecast charts and Data** and click **Datasets**.
4. Under **Popular**, choose **ERA5 (Archived data)**.
5. Click on **Climate Data Store**.
6. Scroll down and select **Complete ERA5 global atmospheric reanalysis**.
7. On the “Complete ERA5 global atmospheric reanalysis” page, click the link:
   - **ERA5 catalogue entries for regridded data**
8. You will be redirected to the **ERA5 hourly data on single levels from 1940 to present** page.
9. Click the **Download** tab.
10. Choose your desired parameters and set the geographical area.
11. Log in again if prompted and **accept the license terms**.
12. Click **Submit Form**.
13. Wait a few minutes — your data will be processed and then made available for download.

---

## ✅ Notes

- Data is often provided in GRIB format. Use tools like `cfgrib` in Python to convert GRIB to CSV or other formats.
- Large requests may take longer to process — consider using the CDS API for batch downloads.
