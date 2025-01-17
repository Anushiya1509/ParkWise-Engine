# **ParkWise-Engine**

## **Design Requirements**

### **Core Features**
1. **Fee Calculation**
   - Calculate parking fees based on:
     - Vehicle entry and exit times.
     - Time of day (daytime vs. nighttime rates).
     - Weekend vs. weekday rates.

2. **Dynamic Rate Management**
   - Allow administrators to define and update rates dynamically.
   - Support different rates for:
     - Daytime vs. nighttime.
     - Weekdays vs. weekends.

3. **API Endpoints**
   - Provide REST APIs for:
     - Calculating parking fees (`/calculate-fee`).
     - Managing rates (`/update-rate`).
     - Fetching usage reports (`/usage-report`).

4. **Scalability**
   - Support multiple parking lots or zones.
   - Handle concurrent fee calculations efficiently.
