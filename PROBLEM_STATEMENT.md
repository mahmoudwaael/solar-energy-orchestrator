# Problem Statement
## Self-Adaptive Solar Energy Orchestrator

### Context

Palestine experiences frequent and unpredictable electricity grid outages — sometimes lasting hours per day. Many households have invested in solar PV systems with battery backup, but face critical inefficiencies in managing these systems.

### The Problem

Current solar energy management systems suffer from three fundamental limitations:

1. **Rigid Rule-Based Logic**
   Existing inverters and energy management systems use fixed, generic rules that don't adapt to individual household consumption patterns. A family with high evening usage gets the same schedule as one with morning peaks.

2. **No Outage Anticipation**
   When the grid goes down unexpectedly, batteries are often not pre-charged, leaving households without power for critical hours.

3. **Suboptimal Battery Management**
   Without predictive intelligence, batteries undergo unnecessary charge-discharge cycles, reducing their lifespan from 10 years to 5-6 years — doubling the long-term cost.

### Quantified Impact

For an average Palestinian household with a 5 kW solar system and 10 kWh battery:
- **Electricity costs:** ~250-400 NIS/month wasted on non-optimal grid usage
- **Battery replacement:** ~6,000 NIS every 5-6 years instead of 10 years
- **Outage downtime:** 2-4 hours/week of preventable power loss

### Why This Matters

- **Economic:** Households can save 20-35% on monthly bills with proper optimization
- **Environmental:** Better solar utilization reduces reliance on grid (mostly fossil-fuel-based)
- **Resilience:** Critical during conflict periods when grid stability decreases
- **Equity:** Most existing smart solutions are expensive imports — a local Arabic solution democratizes access

### Our Approach

We propose a **Self-Adaptive Solar Energy Orchestrator** — a machine learning system that:
- Learns from 1 month of household data
- Generates personalized 24-hour energy schedules
- Predicts grid outages before they occur
- Maximizes savings while extending battery life

### Success Criteria

The project will be considered successful if it achieves:
- ✅ Solar forecasting MAE < 0.5 kWh
- ✅ Consumption forecasting MAE < 0.4 kWh
- ✅ Outage prediction F1-score > 0.70
- ✅ Estimated cost savings > 20%
- ✅ Working dashboard usable by non-technical users
- ✅ Validation by licensed solar engineer
