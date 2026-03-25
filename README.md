# pdh-pdl-pmh-pml-indicator

Algorithmic trading indicator using Pine Script to identify key market levels and trend direction in US equities
Plots key US market reference levels:
• Previous Day High (Green dotted line – thick)
• Previous Day Low (Red dotted line – thick)
• Pre-Market High (Orange dotted line – thin)
• Pre-Market Low (Blue dotted line – thin)

Includes 8 EMA with trend coloring:
• Green when EMA is above both PDH & PMH
• Red when EMA is below both PDL & PML
• Grey when neutral
Jan 30
Release Notes
PDH / PDL / PMH / PML with EMA 8 Trend

This indicator plots four important intraday reference levels for US stocks:

• PDH (Previous Day High) – Solid Green Line
• PDL (Previous Day Low) – Solid Red Line
• PMH (Pre-Market High) – Dotted Orange Line
• PML (Pre-Market Low) – Dotted Blue Line

Pre-market levels are calculated from 4:00 AM to 9:30 AM New York time.
Previous day levels are calculated from the regular session (9:30 AM to 4:00 PM New York time).

An 8-period EMA is plotted on price and dynamically changes color:

• Turns Green when EMA is above both PDH and PMH (Bullish Bias)
• Turns Red when EMA is below both PDL and PML (Bearish Bias)
• Turns Gray when conditions are not met

All levels remain fixed once calculated and extend only until the end of the trading day with a small buffer, ensuring clean and non-repainting behavior.

Designed specifically for US equities and intraday trading.
