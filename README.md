## Hotel Reservation Dashboard
______________________________________________________________________________________________________________________
<img width="901" height="503" alt="0Landingpage" src="https://github.com/user-attachments/assets/3ee2e523-657a-459f-8d23-74ad04502df5" />

## Dashboard 1
<img width="900" height="503" alt="2 D1" src="https://github.com/user-attachments/assets/88fa1f32-c29d-4c0c-9c66-5350d7bfcfcb" />
<img width="898" height="502" alt="1 D1" src="https://github.com/user-attachments/assets/18b1d5b9-ec34-4c4e-9061-cd642f13cf35" />

This dashboard is designed to analyze hotel revenue performance across multiple dimensions: time, nationality, booking channels, and payment methods. It highlights both realized revenue and lost revenue, giving stakeholders visibility into conversion issues and opportunities for improvement.

**Key Insights:**

•	Revenue Growth: Overall revenue increased slightly compared to last month (around +1.0%), showing steady performance.

•	Lost Revenue: A significant 36.37% of potential revenue is lost, flagged with a warning about low booking conversion.

•	Revenue by Nationality: A world map highlights which countries contribute most to revenue, helping identify strong and weak markets.

•	Booking Channels: Corporate, Direct, Online (Booking/Expedia), and Walk In channels are compared for net vs lost revenue.

•	Payment Methods: Credit Card, Cash, and Bank Transfer are analyzed for both earned and lost revenue, showing where leakage occurs.
___________________________________________________________________________________________________________________________________________
**Decoding Visuals with Tooltips:**
<img width="895" height="510" alt="7 MAP- TOOLTIP" src="https://github.com/user-attachments/assets/2369fc36-99dd-4424-a977-582039295b46" />
<img width="903" height="504" alt="8 BAR CHART- TOOLTIP" src="https://github.com/user-attachments/assets/13c23d3d-e274-4384-95a8-d81d7772f8b6" />
<img width="899" height="507" alt="9 COLUMN  CHART- TOOLTIP" src="https://github.com/user-attachments/assets/217a19d6-c487-4f72-b547-e39d90a19221" />
<img width="320" height="280" alt="4 tooltip" src="https://github.com/user-attachments/assets/166e097a-9b6b-4700-b63e-d0b2891097cd" />

____________________________________________________________________________________________________________________________________
**Revenue Performance**

•	Overall Growth: Multiple months show revenue increases ranging from +$900K to +$3.8M, though one period reflects a decline of -$3.9M.

•	Net vs Lost Revenue: Net revenue consistently hovers around $30M–$32M per channel, while lost revenue remains high at $18M–$20M per channel.

•	Lost Revenue Rate: Approximately 36% of potential revenue is lost, flagged as a critical issue due to low booking conversion.
_____________________________________________________________________________________________________________________________________
**Revenue by Nationality**

•	Strong contributions from countries like USA, Canada, UK, Germany, India, China, Australia, Brazil, and Russia.

•	Example: Russia shows +1.4% growth in net revenue but also a +1.7% increase in lost revenue, highlighting mixed performance.
_______________________________________________________________________________________________________________________________
**Booking Channels**

•	Corporate, Direct, Online (Booking/Expedia), Walk-In channels all generate similar net revenue (~$30M–$32M).

•	Lost revenue across channels is consistently high (~$18M–$20M), indicating inefficiencies across the board.

•	Corporate bookings show slight growth (+0.9% net revenue vs last month) but also rising lost revenue (+1.0%).
_____________________________________________________________________________________________________________________________
**Payment Methods**

•	Credit Card: ~$52M net revenue, ~$29M lost revenue. Slight improvement in net revenue (+1.0%) but lost revenue remains significant.

•	Cash: ~$52M net revenue, ~$25M lost revenue.

•	Bank Transfer: ~$30M net revenue, ~$30M lost revenue (a balanced but concerning ratio).
_______________________________________________________________________________________________________________________
**Key Insights**

•	Conversion Challenge: The persistent 36% lost revenue signals urgent need for improving booking conversion strategies.

•	Channel Inefficiency: Despite healthy net revenue, all booking channels suffer from parallel high lost revenue.

•	Payment Method Risks: Bank transfers show equal net and lost revenue, suggesting reliability issues in this mode.

•	Nationality Trends: Certain markets (e.g., Russia) show growth in realized revenue but also rising lost revenue, requiring targeted interventions.

-------------------------------------------------------------------------------------------------------------------------------

## Dashboard 2
<img width="904" height="502" alt="3 D2" src="https://github.com/user-attachments/assets/7f41f18b-38dc-43fb-ad10-ab8e69edb2f1" />
<img width="900" height="500" alt="5 HEATMAP- RESERVED BOOKINGS WITH TOOLTIP" src="https://github.com/user-attachments/assets/788f7764-a45f-4d8d-9f9f-2b0b9fc2d291" />
<img width="899" height="531" alt="6 HEATMAP- CANCELLED BOOKINGS WITH TOOLTIP" src="https://github.com/user-attachments/assets/07eaca0c-2c6c-4cac-86c7-35f73ee4768c" />
<img width="320" height="280" alt="4 tooltip" src="https://github.com/user-attachments/assets/bec64327-9f29-4f64-8673-5949d5b5581b" />

Here’s a consolidated summary of the most recent three Hotel Reservation Dashboards you uploaded, focusing on bookings, cancellations, and revenue performance:
________________________________________
**Bookings Overview**

•	Total Bookings: 92K, showing strong growth: 

o	+71.8% vs Last Year (54K)

o	+1.0% vs Last Month (91K)

•	Seasonal Trends: 

o	Summer: ~15.2K reserved, ~7.4K cancelled

o	Winter: ~14.8K reserved, ~8.1K cancelled

o	Spring: ~13K–13.9K reserved, ~9.4K cancelled

o	Autumn: ~13K reserved, ~10K cancelled (highest cancellation ratio)
________________________________________
**Yearly & Monthly Trends**

•	Yearly Cancellation vs Reservation: 

o	2022: Very low reservations (~2K) but very high cancellations (~25K).

o	2023: ~24K reserved vs ~25K cancelled (almost equal).

o	2024: ~30K reserved vs ~9K cancelled (major improvement).

•	Top Reservation Months: June (~5.3K) and July (~5.6K).

•	Top Cancellation Months: February (~1.9K) and June (~2K).

•	Monthly Line Graphs: Show cancellations peaking early in the year, while reservations rise mid-year.
________________________________________
**Revenue Insights**

•	Revenue Realized: 

o	Net Revenue ranges around $1.9M–$2M.

o	Mixed trends: one dashboard shows a +19.9% increase vs last month, another shows a -4.6% decline.

•	Revenue Lost: 

o	Fluctuates between $675K–$901K.

o	In some months, lost revenue rose sharply (+31.8%), while in others it declined (-15%), showing inconsistent booking retention.
________________________________________
**Key Consolidated Insights**

•	Bookings are growing steadily, with strong year-over-year improvement.

•	Cancellations remain a major challenge, especially in Autumn and early months (Feb, Jan, Jun).

•	Revenue performance is volatile: while net revenue sometimes improves, lost revenue spikes in parallel, eroding gains.

•	Positive trend in 2024: reservations are rising and cancellations dropping compared to prior years, signaling progress.
__________________________________________________________________________________________________________________________________________
## DAX
```
Calendar = 

    VAR _MinYear = YEAR(MIN('Dataset'[Booking Date]))
    VAR _MaxYear = YEAR(MAX('Dataset'[Booking Date]))
    RETURN
    ADDCOLUMNS(
        FILTER(
        CALENDARAUTO(),
        YEAR([Date])>= _MinYear && 
        YEAR([Date])<= _MaxYear
        ),
        "Year", YEAR([Date]),
        "Month Number", MONTH([Date]),
        "Month Long", FORMAT([Date],"mmmm"),
        "Month Short", FORMAT([Date],"MMM"),
        "Qtr", "Q" & QUARTER([Date]),
        "Year Qtr", YEAR([Date]) & " Q" & QUARTER([Date]),
        "Days",DAY([Date]),
        "Week Number", WEEKDAY([Date],2),
        "Weekday Long", FORMAT([Date], "DDDD"),
        "Weekday Short", FORMAT([Date], "DDD"),
        "WeekType", IF(WEEKDAY([Date],2)<6,"Weekday","Weekend"),
        "End of Month", EOMONTH([Date],0),
        "Start of Month", EOMONTH([Date],-1)+1,

        -- This is for some Season,
        "Season",
        SWITCH(
            TRUE(),
            MONTH([Date]) IN { 12, 1,2}, "Winter",
            MONTH([Date]) IN { 3, 4,5}, "Spring",
            MONTH([Date]) IN { 6, 7,8}, "Summer",
            MONTH([Date]) IN { 9, 10,11}, "Autumn"
        ),

        -- Those are some Holidays in my country. You can match the date to the holidays in your Country.
        "Is New Year's Day", IF(MONTH([Date]) = 1 &&
        DAY([Date]) = 1, TRUE(), FALSE()),
        "Is Labour Day", IF(MONTH([Date]) = 5 &&
        DAY([Date]) = 1, TRUE(), FALSE()),
        "Is Democracy Day",IF(MONTH([Date]) = 6 &&
        DAY([Date]) = 12, TRUE(), FALSE()),
        "Is Nigerian Independence Day",IF(MONTH([Date]) = 10 &&
        DAY([Date]) = 1, TRUE(), FALSE()),
        "Is Christmas Day",IF(MONTH([Date]) = 12 &&
        DAY([Date]) = 25, TRUE(), FALSE()),
        "Is Boxing Day", IF(MONTH([Date]) = 2 &&
        DAY([Date]) = 26, TRUE(), FALSE())

    )
```
```
Cancelled Bookings = CALCULATE([Total reservations], 'Dataset'[Cancellation Status]="Yes")
```
```
Caption Cancelled bookings = 
CONCATENATEX(
    TOPN(
        2,
        SUMMARIZE(
            FILTER('Calendar', [Cancelled Bookings] <> BLANK()),
            'Calendar'[Month Short],
            "cancelled Reservations", [Cancelled Bookings]
        ),
        [cancelled Reservations], ASC
    ),
    'Calendar'[Month Short] & " | " & FORMAT([cancelled Reservations], "#,##K"),
    UNICHAR(10), FORMAT([cancelled Reservations], "#,##K")
)
```
```
Caption Lost Revenue = 
VAR _pct=[pct of lost Revenue]
RETURN
SWITCH(
    TRUE(),
    _pct<=0.05,"Excellent! Outstanding Booking Conversion",
    _pct<=0.10,"Good! High booking Booking",
    _pct<=0.20,"Fair! Consider Improving",
    "Needs Attention! Low booking Conversion"
    )
```
```
Caption Reserved bookings = 
CONCATENATEX(
    TOPN(
        2,
        SUMMARIZE(
            FILTER('Calendar', [Reserved Bookings] <> BLANK()),
            'Calendar'[Month Short],
            "checkin Reservations", [Reserved Bookings]
        ),
        [checkin Reservations], DESC
    ),
    'Calendar'[Month Short] & " | " & FORMAT([checkin Reservations], "#,##K"),
    UNICHAR(10), FORMAT([checkin Reservations], "#,##K")
)
```
```
CF Caption Lost Revenue = 
VAR _pct=[pct of lost Revenue]
RETURN
SWITCH(
    TRUE(),
    _pct<=0.05,"#4caf50",
    _pct<=0.10,"#bbc4a",
    _pct<=0.20,"#ffc107",
    "#d64550"
    )
```
```
CF MoM Booking = 
VAR _MoMchange= DIVIDE([Total reservations]-[LM Bookings],[LM Bookings])

RETURN
IF(_MoMchange>0, 1,0)
```
```
CF YoY Booking = 
VAR _MoMchange= DIVIDE([Total reservations]-[LY Bookings],[LY Bookings])

RETURN
IF(_MoMchange>0, 1,0)
```
```
LM Bookings = CALCULATE([Total reservations], DATEADD('Calendar'[Date],-1,MONTH))
```
```
LY Bookings = CALCULATE([Total reservations], DATEADD('Calendar'[Date],-1,YEAR))
```
```
MoM change Booking = 
VAR _Arrowup= UNICHAR(10548)
VAR _Arrowdown= UNICHAR(10549)
VAR _MoMchange= DIVIDE([Total reservations]-[LM Bookings],[LM Bookings])
VAR _Format= FORMAT(_MoMchange,"0.0 %")

RETURN
IF(_MoMchange>0, _Arrowup& "+" &_Format,_Arrowdown&_Format)
```
```
pct of lost Revenue = 
 VAR _pct= DIVIDE([Lost Revenue], [Gross Revenue])
 RETURN
 IF(_pct=BLANK(),0, _pct)
```
```
Reserved Bookings = CALCULATE([Total reservations], 'Dataset'[Cancellation Status]="No")
```
```
Tooltip Title 01 = 
VAR _nationality= SELECTEDVALUE('Dataset'[Nationality])
VAR _bookingchannel= SELECTEDVALUE('Dataset'[Booking Channel])
VAR _paymentmethod= SELECTEDVALUE('Dataset'[Payment Method])
RETURN
SWITCH(
    TRUE(),
    _nationality<>BLANK(), _nationality,
    _bookingchannel<>BLANK(),_bookingchannel,
    _paymentmethod<> BLANK(),_paymentmethod,
    "Other"
    )
```
```
Tooltip Title 02 = 
VAR _nationality= SELECTEDVALUE('Dataset'[Nationality])
VAR _bookingchannel= SELECTEDVALUE('Dataset'[Booking Channel])
VAR _paymentmethod= SELECTEDVALUE('Dataset'[Payment Method])
RETURN
SWITCH(
    TRUE(),
    _nationality<>BLANK(), "Customer nationality:",
    _bookingchannel<>BLANK(),"Customer Booking channel:",
    _paymentmethod<> BLANK(),"Customer payment method:",
    "Other"
    )
```
```
Total reservations = COUNTROWS('Dataset')
```
```
YoY Change Bookings = 
VAR _Arrowup= UNICHAR(10548)
VAR _Arrowdown= UNICHAR(10549)
VAR _MoMchange= DIVIDE([Total reservations]-[LY Bookings],[LY Bookings])
VAR _Format= FORMAT(_MoMchange,"0.0 %")

RETURN
IF(_MoMchange>0, _Arrowup& "+" &_Format,_Arrowdown&_Format)
```

**Gross revenue**
```
CF Flip Card = 
VAR _GrossRevenue=[Gross Revenue]
VAR _LM = [LM Gross Revenue]
RETURN
IF(_GrossRevenue>_LM, 1,0)
```
```
CF Gross Revenue = 
VAR _MoMchange= DIVIDE([Gross Revenue]-[LM Gross Revenue],[LM Gross Revenue])

RETURN
IF(_MoMchange>0, 1,0)
```
```
Gross Revenue = sumx('Dataset', 'Dataset'[Total Amount ($)]+'Dataset'[Extra Services Costs ($)])
```
```
Gross Revenue Flip Card = 
VAR _GrossRevenue= [Gross Revenue]
VAR _LM= [LM Gross Revenue]
VAR _Variance= _GrossRevenue-_LM
VAR _Format= FORMAT(_Variance,"$#,##")

RETURN
IF(_GrossRevenue>_LM, "+"& _Format,"-"&_Format)
```
```
LM Gross Revenue = CALCULATE([Gross Revenue], DATEADD('Calendar'[Date],-1, MONTH))
```
```
MoM Change Gross Revenue = 
VAR _Arrowup= UNICHAR(10548)
VAR _Arrowdown= UNICHAR(10549)
VAR _MoMchange= DIVIDE([Gross Revenue]-[LM Gross Revenue],[LM Gross Revenue])
VAR _Format= FORMAT(_MoMchange,"0.0 %")

RETURN
IF(_MoMchange>0, _Arrowup& "+" &_Format,_Arrowdown&_Format)
```
```
Title GR = 
VAR _selectedmonth= SELECTEDVALUE('Calendar'[Month Short])
RETURN
IF(_selectedmonth<>BLANK(), 
_selectedmonth  & " Gross Revenue",
 "Multiple Month selected"
)
```
```
Title GR2 = 
VAR _MoMchange= DIVIDE([Gross Revenue]-[LM Gross Revenue],[LM Gross Revenue])

RETURN
IF(_MoMchange>0,"Went Up ▲ by","Went down ▼ by")
```

**Lost Revenue**

```
CF Flip Lost revenue Card = 
VAR _LostRevenue=[Lost Revenue]
VAR _LM = [LM Lost Revenue]
RETURN
IF(_LostRevenue>_LM, 1,0)
```
```
CF Lost Revenue = 
VAR _MoMchange= DIVIDE([Lost Revenue]-[LM Lost Revenue],[LM Lost Revenue])

RETURN
IF(_MoMchange>0, 1,0)
```
```
LM Lost Revenue = CALCULATE([Lost Revenue], DATEADD('Calendar'[Date],-1, MONTH))
```
```
Lost Revenue = CALCULATE([Gross Revenue], 'Dataset'[Cancellation Status]="Yes")
```
```
Lost Revenue Flip Card = 
VAR _LostRevenue= [Lost Revenue]
VAR _LM= [LM Lost Revenue]
VAR _Variance= _LostRevenue-_LM
VAR _Format= FORMAT(_Variance,"$#,##")

RETURN
IF(_LostRevenue>_LM, "+"& _Format,"-"&_Format)
```

```
MoM Change Lost Revenue = 
VAR _Arrowup= UNICHAR(10548)
VAR _Arrowdown= UNICHAR(10549)
VAR _MoMchange= DIVIDE([Lost Revenue]-[LM Lost Revenue],[LM Lost Revenue])
VAR _Format= FORMAT(_MoMchange,"0.0 %")

RETURN
IF(_MoMchange>0, _Arrowup& "+" &_Format,_Arrowdown&_Format)
```
```
Title LR = 
VAR _selectedmonth= SELECTEDVALUE('Calendar'[Month Short])
RETURN
IF(_selectedmonth<>BLANK(), 
_selectedmonth  & " Lost Revenue",
 "Multiple Month selected"
)
```
```
Title LR2 = 
VAR _MoMchange= DIVIDE([Lost Revenue]-[LM Lost Revenue],[LM Lost Revenue])

RETURN
IF(_MoMchange>0,"Went Up ▲ by","Went down ▼ by")
```
**Net Revenue**
```
CF Flip net revenue Card = 
VAR _NetRevenue=[Net Revenue]
VAR _LM = [LM Net Revenue]
RETURN
IF(_NetRevenue>_LM, 1,0)
```
```
CF Net Revenue = 
VAR _MoMchange= DIVIDE([Net Revenue]-[LM Net Revenue],[LM Net Revenue])

RETURN
IF(_MoMchange>0, 1,0)
```
```
LM Net Revenue = CALCULATE([Net Revenue], DATEADD('Calendar'[Date],-1, MONTH))
```
```
MoM Change Net Revenue = 
VAR _Arrowup= UNICHAR(10548)
VAR _Arrowdown= UNICHAR(10549)
VAR _MoMchange= DIVIDE([Net Revenue]-[LM Net Revenue],[LM Net Revenue])
VAR _Format= FORMAT(_MoMchange,"0.0 %")

RETURN
IF(_MoMchange>0, _Arrowup& "+" &_Format,_Arrowdown&_Format)
```
```
Net Revenue = CALCULATE([Gross Revenue], 'Dataset'[Cancellation Status]="No")
```
```
Net Revenue Flip Card = 
VAR _netRevenue= [Net Revenue]
VAR _LM= [LM Net Revenue]
VAR _Variance= _netRevenue-_LM
VAR _Format= FORMAT(_Variance,"$#,##")

RETURN
IF(_netRevenue>_LM, "+"& _Format,"-"&_Format)
```
```
Title NR = 
VAR _selectedmonth= SELECTEDVALUE('Calendar'[Month Short])
RETURN
IF(_selectedmonth<>BLANK(), 
_selectedmonth  & " Net Revenue",
 "Multiple Month selected"
)
```
```
Title NR2 = 
VAR _MoMchange= DIVIDE([Net Revenue]-[LM Net Revenue],[LM Net Revenue])

RETURN
IF(_MoMchange>0,"Went Up ▲ by","Went down ▼ by")
```

