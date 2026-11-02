# 🚗 Uber Rides Analysis Dashboard (Power BI)

An interactive Power BI dashboard that analyzes Uber ride bookings: rider behavior, revenue, vehicle performance, locations, and customer ratings, including completed and canceled trips.

![Home](
<img width="1345" height="753" alt="Screenshot 2026-11-02 180045" src="https://github.com/user-attachments/assets/e1109b76-f145-41f4-a873-d59b3e7c3dc0" />
<img width="1346" height="798" alt="Screenshot 2026-11-02 180131" src="https://github.com/user-attachments/assets/94109128-ba71-4531-8463-ec293d86fed9" />
<img width="1342" height="796" alt="Screenshot 2026-11-02 180203" src="https://github.com/user-attachments/assets/e2e02658-9d07-426c-b155-8f824823b12b" />
<img width="1346" height="802" alt="Screenshot 2026-11-02 182944" src="https://github.com/user-attachments/assets/7aa6dcdd-0232-40a3-8d75-d8ea779ea5b7" />
<img width="1342" height="796" alt="Screenshot 2026-11-02 180307" src="https://github.com/user-attachments/assets/8a21c4ae-29b6-446f-b041-a7127253a568" />
<img width="1343" height="796" alt="Screenshot 2026-11-02 180456" src="https://github.com/user-attachments/assets/35344571-8818-41c5-b5ca-da90cac1e1a9" />
)

## 📌 Project Overview
The dashboard helps answer key business questions:
- How many bookings were completed vs. lost?
- Which vehicle types and payment methods generate the most revenue?
- Who are the first-time, returning, and regular riders?
- Why are rides canceled?
- When and where is demand the highest?

## 📊 Key Metrics
| KPI | Value |
|---|---|
| Completed Bookings | 93K |
| Total Bookings | 149K |
| Revenue | 52M |
| Total Distance | 3M |
| Unique Customers | 104K |
| Avg Customer Rating | 4.40 |
| Avg Driver Rating | 4.23 |

## 🗂️ Dashboard Pages
| Page | What it shows |
|---|---|
| **Home** | Landing page with navigation to all pages |
| **Overview** | KPIs, monthly/quarterly completed bookings and revenue, revenue by vehicle type, top pickup/drop locations, rider and driver ratings |
| **Vehicle** | Per-vehicle booking count, revenue, contribution, and monthly trend |
| **Revenue** | Revenue by customer, vehicle, and payment method, with monthly/quarterly trends |
| **Rider** | First-time, return, and regular riders, payment methods, cancellation reasons, and customer detail table |
| **Location** | Monthly distance, distance by vehicle, busiest time slots, and busiest areas |

## 🔍 Key Insights
- **Auto** is the top revenue generator (13M), followed by Bike (11M) and Go Mini (10M).
- **UPI** is the most used payment method (23M revenue), ahead of Cash (13M).
- Peak demand is in the evening (**06 PM – 09 PM**).
- Khandsa is the top pickup location and Ashram is the top drop location.
- A large share of canceled rides has no recorded reason (Blank), which is a data-quality gap worth fixing at the source.

## ✨ Features
- Vehicle-type slicer with image icons
- Month / Quarter toggle using bookmarks
- Page navigation buttons
- Custom time-slot sorting (DAX)
- Cancellation analysis by customer / driver / incomplete

## 🛠️ Tools & Skills
- **Power BI Desktop**: data modeling, visuals, bookmarks, navigation
- **DAX**: calculated columns and measures (e.g., Time Slot, Time Slot Sort)
- **Data Modeling**: date table, relationships
- **Dataset**: Uber ride bookings (~150,000 rows)
