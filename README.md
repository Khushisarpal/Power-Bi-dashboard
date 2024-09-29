# Power-Bi-dashboard
## Project Overview
### This project presents a Hardware Inventory Dashboard built-in Power BI, which provides a comprehensive overview of inventory devices allocated across various departments. The dashboard allows users to explore key metrics such as the count of serviceable devices, lost devices, free devices, and total allocated devices. It also tracks device distribution across departments and their allocation trends over the years, offering insights into inventory management for hardware resources.
**Note**: For security reasons, I have not included the live dashboard. Instead, a JPG picture of the dashboard has been provided to showcase the design and layout.
## Features
Overview of Inventory Devices:

- **Overview of Inventory Devices:**
  - **Total Serviceable Devices**: Displays the total count of devices available for service (e.g., desktops, cameras, phones).
  - **Lost Devices**: Shows the number of devices lost from the inventory.
  - **Free Devices**: Devices that are unallocated or in stock.
  - **Allocated Devices**: Devices that are currently in use by departments.

- **Distribution of Devices across Departments:**
  - Visual representation of the count of devices distributed across different departments, including IT, Finance, Consulting, and more.
  - Devices are categorized by type, including **Access Point**, **Camera**, **Desktop**, **External HDD**, and more.
  
- **Device Allocation Status:**
  - A pie chart visualizing the breakdown of device statuses (Allocated, Free, Discarded, Active).
  
- **Device Allocation Trend Over Time:**
  - A bar chart showing the total number of allocated devices per year, providing insights into inventory growth or usage trends.
  
- **Date Filters & Drilldowns:**
  - Date ranges to filter data based on the purchase or allocation date.
  ## Data Sources

The data consists of hardware inventory records, including:
- Device type (e.g., Desktop, Camera, External HDD)
- Department using the device
- Status of the devices (Allocated, Free, Active, Discarded)
- Dates of purchase and allocation
- Historical data on the allocation of devices over the years
  ## Technologies Used

- **Power BI**: The main tool used to create the dashboard, offering interactive visualizations and business intelligence capabilities.
- **Power Query**: For transforming and cleaning data to prepare it for analysis.
- **DAX (Data Analysis Expressions)**: Used to create custom measures and aggregations for the visuals.
  ## Key Metrics

- **Count of Serviceable Devices**: Total devices available for allocation.
- **Total Lost Devices**: Number of devices reported as lost.
- **Total Free Devices**: Devices not currently allocated.
- **Total Allocated Devices**: Devices actively in use across departments.
- **Device Allocation Trends**: Track the increase in device allocation year by year.
- **Department Distribution**: Breakdown of devices per department by type.
  ## License

This project is licensed under the MIT License.
