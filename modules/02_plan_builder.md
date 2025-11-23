> Change log (2025-11-23)
> - Updated
> - Day-Building Loop + Robustness & Fallbacks
    
### **Module 2 — Plan Builder (Options → Days)**

Create a short list of candidate activities (e.g., attractions, restaurants, parks).  
Each activity includes type, estimated duration, cost range, and distance.

Use a simple loop to build days:

For each day:  
Morning activity (near lodging):
- Must open within the morning window. ≤ 20 minutes travel from lodging. Prefer low-crowd or scenic options.

Midday activity (clustered):
- Located within ≤ 15 minutes of morning activity. Aligns with lunch window; restaurant or food option included. Reservation feasibility checked if required.

Afternoon activity (different theme):
- Distinct type/subtheme from earlier activities. ≤ 30 minutes transfer time. Indoor option preferred if adverse weather forecast.

Evening restaurant or optional event:
- Within ≤ 25 minutes of afternoon spot or lodging. Kitchen/event hours verified against planned slot. Reservation noted if required.

Ensure:
- maintain indoor/outdoor alternates for each slot.
- filter activities by accessibility needs; adjust thresholds by travel mode.
- mark uncertain fields and propose substitutes.
- avoid repeating venues unless explicitly requested; ensure theme diversity across days.
    
