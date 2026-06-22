# Flight Sales Analytics Dashboard (Metabase)

Built an end-to-end analytics solution for a real-world OTA flight booking dataset using PostgreSQL + Metabase.

---
Dashboard Video Link:
https://drive.google.com/file/d/123Qs0tqXatrgdi85BWoHRv8zlvMlY6Fd/view?usp=sharing

---
<img width="1840" height="814" alt="Screenshot 2026-06-22 151908" src="https://github.com/user-attachments/assets/1a898be2-5e1f-4325-bf6c-ddcc511f41f9" />
---

## Dataset
Industry-level OTA (Online Travel Agency) transaction data was used for analysis, including:
- Booking and transaction details (`booking_id`, `booking_status`, `category`)
- Customer and traveller information (`sell_region`, `number_of_traveller`)
- Travel timeline analysis (`booking_date`, `departure_date`, `return_date`)
- Airline and route performance (`airline`, `route`, `route_type`, `segment`)
- Location analytics (`departure_location`, `destination_location`)
- Revenue and pricing metrics (`base_fare`, `tax`, `customer_payable`, `net_revenue`)
- Profitability analysis (`markup_percentage`, `markup_amount`, `commission_amount`)
- Payment tracking (`payment_gateway`, `payment_status`, `received_amount`)
- Currency and GMV analysis (`currency_code`, `total_gmv_usd`)
- Supplier and operational insights (`supplier_name`, `gds`, `pcc`, `flight_type`)

---

## Project Work
- Connected and integrated dataset with PostgreSQL and Metabase
- Developed 20+ business-driven SQL insights
- Designed 2 interactive analytical dashboards

---

## Dashboard Coverage
- Profitability by airline & route  
- Airline revenue share  
- Booking trends (airline & route-wise)  
- Monthly revenue trends  
- Booking status distribution and more

---

# Business Performance Summary

## Airlines Performance
- Airline **BS is the top performer**, with the highest revenue share (50.95%) and profit (149,641).
- **SQ** comes second (29.88% revenue share, 87,744 profit).
- **BG** is third (14.39% revenue share, 42,267 profit).

## Revenue & Currency
- Total revenue is **4.5M**.
- About **98.6% of revenue is in SGD**, showing heavy reliance on one currency.

## Bookings Overview
- Total bookings: **14,536**
- Bookings are concentrated in a few routes, meaning demand is not evenly spread.

## Payment Performance
- **98.75% of bookings are fully paid**, showing strong payment collection.
- Very few partial payments are recorded.

## Pricing Performance
- **Normal pricing performs better**, generating more profit (169,417) from fewer bookings (5,365).
- Low pricing has more bookings (9,171) but lower profit (124,262).

## Revenue Breakdown
- Commission revenue is strong at **236,051.13**.
- Negative markup (-76,829) reduces overall profit.
- Bonuses add **47,096** to earnings.

## Customer Insights
- Top customers contribute significantly to revenue.
- The top customer made **138 bookings and 2,978 profit**.

## Payment Methods
- **HITPAY**: Highest total profit (171,533 from 11,064 bookings).
- **SG_BANK**: Highest profit per booking (52.9 average, 91,298 total profit).

## Growth Trend
- Revenue shows strong growth starting from **late 2024**.

## Routes Performance
- Top routes generate most of the profit.
- Lower-performing routes contribute very little.

---

## Outcome
Delivered a structured BI solution to understand revenue drivers, risks, and business performance.
