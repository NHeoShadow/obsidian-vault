---
date: 2024-04-22
topics-covered:
  - "MS-4701: MS Subject Overview"
  - "MS-4702: Quantitative Techniques"
presider: Charlwin "Aljon" P. Lee, CPA, CMA
ReSA-subj: MS
---
## Topic Proper
- Preliminaries
	- There will be four meetings for MS:
		- April 22
			- MS-4701: MS Subject Overview
			- MS-4702: Quantitative Techniques
		- April 24
			- MS-4703: Relevant Costing, Linear Programming, and Probability Analysis
		- April 29
			- MS-4704: Capital Budgeting
		- May 14
			- MS-4705: MS Summary Lecture (essential and salient points for all topics under MS)
- MS-4701 (MS Subject Overview)
	- **MS Syllabus for the October 2024 CPA License Examination**
		- Note: that the official name is already Management Services (MS). The word "advisory" has been removed last October 2022 because the following topics were omitted:
			- MS Management Consultancy, Project Feasibility Study, ABC & Activity-Based Management, Strategic Cost Management, PERT-CPM, Code of Ethics, among others
		- There will be 70 MCQ questions, mix of theories and problems (50/50)
			- Usual schedule for CPALE:
				- D1 AM: MS
				- D1 PM: AUD
				- D2 AM: TAX
				- D2 PM: RFBT
				- D3 AM: FAR
				- D3 PM: AFAR
		- On 2028, the subject MS will be converted to BAR
		- Short-game
			- Margin of Safety -> CVP Analysis
			- Cost Centre -> Responsibility Accounting
			- Make or Buy -> Relevant Costing
			- Mix & Yield -> Standard Costing
			- ARR vs IRR -> Capital Budgeting
			- Customer Perspective -> Balanced Scorecard
			- EOQ -> Working Capital Management
				- Inventory Management
			- Baumol Model -> Working Capital Management
				- If EOS is applied with cash balance, it becomes Baumol Model
				- William Baumol invented this model
			- Gordon Model -> Capital Structure & Long-term Financing Decision
				- Gordon Model and Cost of Equity ($K_e$) ?
			- Du Pont Technique -> Financial Statement Analysis
			- Price Elasticity -> Microeconomics
			- Capital Markets -> Financial Markets
				- Financial Markets -> Capital Markets and Money Markets
		- ==*Completion over Mastery*==
		- Management Accounting vs Financial Management
			- 
	- **Philippine CPA Exam vis-a-vis US CMA Exams**
		- 70% of US CMA Exam = 90% of PH CPALE MS
	- **Management Accounting vs Financial Management**
		- ...
	- **Topic Proper**
		- Management Accounting:: the use of accounting information by company management to make rational economic *decisions* in performing its function of *planning*, *organizing*, and *controlling* business operations
			- In planning, organizing, and controlling, an objective basis is required in order to make decisions.
		- Management accounting presents information differently compared to financial accounting.
			- Example: Financial accounting presents income statement in function form, while management accounting presents income statement by behaviour
			- Both draw from *the same* accounting database
			- Cost accounting is a subset of both management and financial accounting
				- ![[Pasted image 20240422094241.png]]
		- Management accounting is *future oriented*
		- *Three Management Functions*, in this same exact order:
			- Planning - deciding on company goals and objectives and figures out how to achieve them.
				- If you fail to plan, you plan to fail
				- Associated terms: road mapping, goal setting
			- Organizing - deciding on how to use company resources to put plans into action.
				- Associated terms: directing and motivating; staffing and subordinating
			- Controlling - deciding on what corrective actions to do should there be any difference between actual results and planned results
				- Associated terms: monitoring; feedback mechanism
			- Decision-making is an inherent function of management as ==**all**== management functions would require a certain level of decision-making; this makes management accounting information useful in all stages of management.
		- Goal of Financial Management - modern managerial finance theory works under the premise that the primary goal of the firm is to maximize *==shareholders' wealth==*, rather than just to maximize profit. The financial manager acts in the shareholders' best interests by making decisions that maximize the *market value* of the company stocks (i.e., wealth creation)
		- Role of Financial Managers - the role of a financial manager may include *financial analysis and planning*, *investment decisions*, *financing and capital structure decisions*, *management of financial resources*, and *risk amnagement*. No single person is tasked for all the responsibilities of a financial manager.
- **MS-4702: Quantitative Techniques**
	- **Economic Order Quantity**
		- Inventory Models
			- How many units to order
				- Factors needed to take into account:
					- Ordering Costs (OC)
						- The more units to order, the less ordering costs a company may incur
					- Carrying Costs (CC)
						- Need to take into account expiration/spoil date of the inventory at hand
					- A balance between ordering costs and carrying costs must be taken into account. Hence, **EOQ**
						- The quantity you should order in order to optimize the ordering and carrying costs incurred.
						- ==See *Equation 1: EOQ*==
						- Another name for EOQ is *Optimal Order Quantity*. Total costs, whatever the output be, will be the lowest possible costs for the given parameters.
						- **@EOQ: CC = OC**
							- [ ] Further investigation is required
			- When to make the order
				- Stockout Costs (SC)
				- Carrying Costs (CC)
				- **Reorder Point**
					- **See Equation 2**
					- Lead time: either normal (average) or maximum
						- Normal (average): 2 days
						- Maximum: 4 days
					- Ensures that there is no extra carrying costs and there is no stockout.
						- Stockouts results to income forfeited.
	- **Learning Curve**
		- otherwise known as *experience curve*, *productivity curve*, or *efficiency curve*
		- It is based on the phenomenon that labour time decreases in a definite pattern as labour operations are repeated. Learning curve describes the *efficiencies* arising from *experience* - with experience comes increased *productivity*.
			- This productivity increases with production size, but at a decreasing rate as diagrammed below
			- The time required to perform a given task becomes progressively shorter, but this is applicable only to the early stages of production.
			- The learning curve is based on statistical findings that as the cumulative output *doubles*, the cumulative *average* labour input time required per unit will be reduced by some percentage, ranging between 10% and 40%.
			- ‼️ The learning curve is usually designated by the complement of the rate of reduction - if the rate of reduction is 20%, then there is an 80% learning curve.
		- Take note of the following words: *average* and *double*
		- [ ] **More notes shall be taken**
		- [ ] 

### Equations
#### Economic Order Quantity (EOQ)

$$ EOQ = \sqrt{\frac{2DO}{C}} $$
whereas:
- $D$ refers to **annual** demand or usage in units
- $O$ refers to costs of placing **one** order
- $C$ refers to cost of carrying one unit for **one year**

| Item Particulars | Formula   | Whereas                                    |
| ---------------- | --------- | ------------------------------------------ |
| Carrying Costs   | (EOQ /2)C | (EOQ /2) is the average inventory in units |
| Ordering Costs   | (D /EOQ)O | (D /EOQ) is the number of orders per year  |
#### Reorder Point

| Item Particulars | Formula                                                                             |
| ---------------- | ----------------------------------------------------------------------------------- |
| Safety Stock     | (lead_m - lead_x) * average daily demand                                            |
| Reorder Point    | lead_m * average daily demand; or<br>(lead_x * average daily demand) + safety stock |
whereas:
- lead_m = maximum lead time
- lead_x = average/normal lead time

## File References

- [[MS-4701 (MS Subject Overview).pdf]]
- [[MS-4702 (Quantitative Techniques).pdf]]