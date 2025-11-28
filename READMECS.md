Flight to the Future: Predicting Drone Delivery Potential and Infrastructure Gaps for Critical Aid in Rural West Virginia

A NewForce Data Analytics Capstone Project by Walter Lovett

Overview

Flight to the Future is a data analytics capstone project that examines how drone technology can bridge critical infrastructure gaps in rural West Virginia. By analyzing food access, healthcare shortages, disaster vulnerability, and terrain barriers, this project builds a Drone Need Index (DNI) that identifies where drone-assisted delivery would have the greatest humanitarian impact.

The project focuses on rural Appalachian communities—particularly those isolated by geography, limited broadband, medical provider shortages, and high food insecurity. The result is a data-driven roadmap for where drones should fly first during emergencies or in ongoing service delivery.

Project Goals

Identify counties in West Virginia with the highest combined risk using food desert data, healthcare access scores, and disaster loss estimates.

Build a Drone Need Index to quantify and visualize priority areas.

Develop Power BI dashboards that communicate accessibility gaps and logistical needs.

Create geospatial visualizations and route simulations to demonstrate how drones can bypass terrain barriers.

Provide actionable insights for nonprofits, emergency planners, and rural health organizations.

Tools & Technologies

Python (Pandas, GeoPandas, Matplotlib)

Power BI

Power Query

Geospatial Data Visualization

FRED/EAL Data, USDA Food Access Data, HRSA HPSA Data

Google Earth Studio (drone route animation)

GitHub for version control

Key Visuals & Analysis Components
1. Risk Matrix (Power BI)

A ranked table displaying:

Food Desert Tracts

Disaster Estimated Annual Loss (EAL)

Medical Need Index (MNI)

Composite Risk Score

Counties are sorted by EAL, highlighting regions with elevated vulnerability.

2. Drone Need Index (Python + Power BI)

A combined metric built from:

Food Access Scores

Medical Need Index (derived from HPSA provider shortages)

FEMA Estimated Annual Loss (EAL)

County-level socioeconomic & geographic constraints

The resulting map provides a clear visual of where drone delivery would have the most impact.

3. TreeMap of Risk Levels

A color-coded TreeMap showing:

Red: High-risk counties

Yellow: Medium risk

Green: Low-risk counties

Blue: Counties not classified as food deserts

This gives an intuitive snapshot of how need varies across the state.

4. Healthcare Access Visualization

A bar chart of the Top 10 HPSA shortage sites in West Virginia—including FCI McDowell and FCI Gilmer—showing where provider shortages are most severe and reinforcing the need for drone-supported delivery of medical supplies.

5. Drone Route Animation

A 26-second simulated flight route created in Google Earth Studio, illustrating an emergency drone delivery path from Charleston to Iaeger.
Demonstrates how drones can bypass terrain barriers and reduce delivery times for isolated communities.

Why Drones?

Rural Appalachian counties face persistent barriers:

Limited broadband and communication infrastructure

Long distances to healthcare providers

Road closures from floods, slides, and winter storms

High food insecurity in mountainous regions

Emergency response delays

The Drone Need Index shows that drones could:

Deliver medications faster

Reach isolated homes during disasters

Support food distribution programs

Provide lightweight medical supplies

Improve access in underserved counties

Methodology

Data Collection

USDA Food Access

HRSA Health Professional Shortage Areas

FEMA EAL (Estimated Annual Loss)

Census socioeconomic data

WV county shapefiles

Data Transformation

Cleaned in Power Query

Normalized HPSA → Medical Need Index (MNI)

Scaled variables for composite scoring

Modeling the Drone Need Index (DNI)

Weighted combination of Food Access + Medical Need + Disaster Exposure

Validation through correlation checks

Visualization

Python geospatial plots

Power BI dashboards

Google Earth Studio route animation

Insights & Takeaways

Counties like McDowell, Kanawha, and Logan show the highest combined risk.

Rural and medically underserved counties align strongly with high Drone Need Index values.

Drones represent a scalable, low-cost support tool for hard-to-reach mountain communities.

Modeling suggests drones could significantly improve emergency response outcomes.
Flight-to-the-Future/
 data/                # Cleaned datasets
 notebooks/           # Python notebooks for mapping & analysis
 powerbi/             # PBIX file for dashboards
 media/               # Drone route animation + PNGs
 README.md            # Project documentation
 outputs/             # Final maps and chartsFuture Improvements

Build predictive models for disaster-related road closures

Integrate DHS or FAA drone regulations

Conduct real flight tests with small UAVs

Incorporate parcel-level accessibility metrics

Connect real nonprofit delivery dataAuthor

Walter Lovett
NewForce Data Analytics Cohort
Focused on rural innovation, humanitarian technology, and drone-enabled logistics.
