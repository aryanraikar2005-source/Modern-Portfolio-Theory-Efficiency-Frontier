# Modern-Portfolio-Theory-Efficiency-Frontier
Modern Portfolio Theory model in Excel — computes efficient frontier and optimal risk-return portfolio using Solver.
📊 What if textbook theories could actually guide real investment decisions?
 
That thought struck me during an Advanced Financial Management lecture on Modern Portfolio Theory (Markowitz Theory)— a framework that shows how to balance risk and return through smart diversification.
 
Instead of stopping at formulas, I wondered: 
👉 Can I build a working portfolio using this theory — with real stock data, Excel, and no shortcuts? 
💡 With a blueprint shared during lectures by CA Abhishek Zaware, I gave it a shot. 
📈 The result? A model built on market data, logic, and a whole lot of Excel — and suddenly, the theory came alive. 
 
🧠 The Big Question This Theory
Answers:
 
"How can I invest in multiple stocks in a way that reduces overall risk — without sacrificing returns?" 

Sounds ideal, right?
 
So, I rolled up my sleeves and tested it out using just: 
✅ Microsoft Excel 
✅ Formulas 
✅ Solver Add-in 
No fancy software, just pure curiosity (and patience 😅). 
 
 
💼 The Portfolio: 
I chose 5 Indian blue-chip stocks: 
• HDFC Bank 
• TCS 
• Larsen & Toubro 
• Reliance Industries 
• Maruti Suzuki
 
Using daily price data (2005–2025), I calculated: 
📊 Daily returns 
📉 Volatility using STDEV.P 
📈 Beta with Sensex using SLOPE 
📆 CAGR using RATE and geometric mean 
📌 Covariance matrix using COVARIANCE.P 
🧠 Variance-Covariance matrix for portfolio optimization 
 
🧮 Then Came the Solver Magic: 
With constraints set for expected returns, I used Solver to find: 
🎯 The optimal weights for each stock that minimize risk.
 
From this, I built the Efficiency Frontier — a curve that shows the most optimal portfolios for different levels of risk. 
📌 Upper part of the curve?? That’s where portfolios offer more return for the same risk.
 
 
🔍 Why This Meant So Much:
 
• ✅ It proved that textbook theories can drive real insights 
• ✅ It showed that Excel can do more than people assume 
• ✅ And most importantly, it reminded me that 
📚 “Understanding is greater than memorizing.”
