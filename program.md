---

title: Program (Tentative)

---
<h2>March 25, Day 1</h2>

<b> Day 1: Increasing enforcement efficiency </b>

09:00 Welcome 

09:15 <b> Machine learning for environmental monitoring. </b> 

Authors: Elinor Benami (Virginia Tech), Miyuki Hino (UNC Chapel Hill), Nina Brooks (Boston University)

Suggested Presenter: Elinor Benami

Public agencies aiming to enforce environmental regulation have limited resources to achieve their objectives. We demonstrate how machine-learning methods can inform the efficient use of these limited resources while accounting for real-world concerns, such as gaming the system and institutional constraints. Here, we predict the likelihood of a facility failing a water-pollution inspection and propose alternative inspection allocations that would target high-risk facilities. Implementing such a data-driven inspection allocation could detect over seven times the expected number of violations than current practices. When we impose constraints, such as maintaining a minimum probability of inspection for all facilities and accounting for state-level differences in inspection budgets, our reallocation regimes double the number of violations detected through inspections. Leveraging increasing amounts of electronic data can help public agencies to enhance their regulatory effectiveness and remedy environmental harms. Although employing algorithm-based resource allocation rules requires care to avoid manipulation and unintentional error propagation, the principled use of predictive analytics can extend the beneficial reach of limited resources.

10:00
Title: <b> Are the inspections going to “waste”? </b> A national field test of machine learning vs. expert judgement to improve EPA regulatory compliance 

Authors: Katherine Meckel (UC-San Diego), Jesse Buchsbaum (UChicago), Michael Greenstone (UChicago) 

Suggested presenter: Katherine Meckel (UC-San Diego) 

Abstract: Machine learning has the potential to improve targeting of regulatory inspections in theory, but this potential has been untested in practice. We directly test machine learning against human decision-making, first developing a model to predict severe violations of hazardous waste regulation, then conducting a field test of the model’s performance. The inspections chosen by the machine learning model identified 79% more severe violations than those selected by humans. These results provide evidence of the efficiency gains that machine learning can offer in regulatory compliance, highlighting the need to explore the adoption of such tools.  

10:45 Coffee Break

11:00  
Title: <b> Using Machine Learning Models to Enhance Violation Detection of EPA Regulated Facilities </b>

Authors: Jesse Buchsbaum, Michael Greenstone, Rajat Kochhar, Olga Rostapshova (UChicago) 

Suggested presenter: Jesse Buchsbaum (University Of Chicago) 

Abstract: A predictive analytics model can make the targeting of inspections more efficient in terms of achieving higher violation discovery rates. We develop an ML model that focuses on violations related to provisions in the Clean Air Act (CAA) and National Pollutant Discharge Elimination System (NPDES). The project leverages extensive data on historical inspection, violation, enforcement, and compliance data to predict where violations are most likely to occur within the large and less inspected universe of EPA regulated facilities.  

12:00 Lunch  

13:30 Title: <b> "What’s Missing in Environmental (Self-)Monitoring: Evidence from Strategic Shutdowns of Pollution Monitors" </b>

Authors: Eric Zou (University of Michigan), Yingfei Mu (National Bureau of Economic Research) and Edward Rubin (University of Oregon)

Regulators often rely on regulated entities to self-monitor compliance, potentially creating strategic 
incentives for endogenous monitoring. This paper builds a framework to detect whether local governments 
skip air pollution monitoring when they expect air quality to deteriorate. The core of our method tests 
whether the timing of monitor shutdowns coincides with the counties’ air quality alerts – public advisories 
based on local governments’ own pollution forecasts. Applying the method to a monitor in Jersey City, NJ, 
suspected of a deliberate shutdown during the 2013 “Bridgegate” traffic jam, we find a 33% reduction of 
this monitor’s sampling rate on pollution-alert days. Building on large-scale inference tools, we then apply 
the method to test more than 1,300 monitors across the U.S., finding 14 metro areas with clusters of 
monitors showing similar strategic behavior. We assess geometric imputation and remote-sensing 
technologies as potential solutions to deter future strategic monitoring.

14:15
Title: <b> Improving Methane Emissions Monitoring and Enforcement using Predictive Analytics for Inspection Targeting  </b>

Authors: Thomas Covert, Ludovica Gazze, Michael Greenstone, and Olga Rostapshova  

Suggested presenter: Ludovica Gazze (University of Warwick)  

Abstract: Regulating methane, a greenhouse gas with 80 times the short-term global warming potential of carbon dioxide, is at the forefront of the global agenda to address climate change. In the United States, methane emissions are particularly pernicious at oil and gas (O&G) facilities, from which an estimated 2.3% of gross natural gas production (13 billion kilograms of methane) leaks each year. We partnered with Colorado Department of Public Health and Environment (CDPHE) to build a supervised machine learning model to predict the likelihood that upstream O&G facilities in Colorado would leak natural gas. This model leveraged previously unlinked administrative data, O&G permitting and inspection histories, monthly O&G production data, meteorological conditions, oil and gas prices, and demographic data to predict unauthorized emissions.  Over the last two years, CDPHE has used the ML model output to target inspection sites; consequently, inspectors have observed a substantial increase in the number of emissions events they observed during inspections.  

15:00 Coffee Break

15:15
Title: A Machine Learning Approach to Methane Emissions Mitigation in the Oil and Gas Industry  

Authors: Jiayang Wang (University of Texas at Austin), Selvaprabu Nadarajah (University of Illinois at Chicago), Jingfan Wang (Stanford University), Arvind P Ravikumar (University of Texas at Austin) 

Suggested Presenter: Arvind P Ravikumar (University of Texas at Austin) 

Abstract: Reducing methane emissions from the oil and gas sector is a key component of climate policy in the United States. Methane leaks across the supply chain are stochastic and intermittent, with a small number of sites (‘super-emitters’) responsible for a majority of emissions. Thus, cost-effective emissions reduction critically relies on effectively identifying the super-emitters from thousands of well sites and millions of miles of pipelines. Conventional approaches such as walking surveys using optical gas imaging technology are slow and time-consuming. In addition, several variables contribute to the formation of leaks such as infrastructure age, production, weather conditions, and maintenance practices. Here, we develop a machine learning algorithm to predict high-emitting sites that can be prioritized for follow-up repair. Such prioritization can significantly reduce the cost of surveys and increase emissions reductions compared to conventional approaches. Our results show that the algorithm using logistic regression performs the best out of several algorithms. The model achieved a 70% accuracy rate with a 57% recall and a 66% balanced accuracy rate. Compared to the conventional approach, the machine learning model reduced the time to achieve a 50% emissions mitigation target by 42%. Correspondingly, the mitigation cost reduced from $85/t CO2e to $49/t CO2e.  
  
16:00 Presentation from Industry (Such as Planet Labs, Google, etc.)

17:00 End of Day 1

<h2>March 26, Day 2</h2>

Day 2: Big Data for Enforcement and Design of environmental regulations  

Presentation 5  

09:00
Title: Using Remote Sensing Technology to Reduce Heavy Duty Truck Emissions in California  

Authors: Fiona Burlig (UChicago), Ludovica Gazze (University of Warwick), Michael Greenstone (UChicago), and Olga Rostapshova (UChicago) 

Suggested presenter: Fiona Burlig (UChicago) 

Abstract: The transportation sector accounts for 29 percent of the total GHG emissions in the US. The California Air Resources Board (CARB) piloted an innovative technology, Portable Emissions Acquisition System (PEAQS), that can measure vehicle emissions in real time. This can allow regulators to identify high-emitting trucks and target enforcement actions more effectively. We designed an RCT to assess the impact of this technology to study whether enforcement programs guided by remote sensing technology can cost-effectively improve compliance and reduce emissions. High-emitting trucks were randomly assigned to either the control group or to one of two enforcement interventions: (1) a low-cost compliance documentation intervention targeted at individual trucks, and (2) a high-cost audit intervention targeted at truck fleets. In the low-cost treatment intervention, trucks were informed that they are likely in violation of California’s emissions standards and asked to provide compliance documentation. In the audit treatment, fleets with high-emitting trucks were subjected to comprehensive audits covering their entire truck population, with assured penalties if they do not prove compliance. We have enrolled 4,867 unique trucks in the low-cost documentation intervention and 70 unique fleets in the high-cost audit intervention. Data collection is expected to run for the next year. We also intend to measure changes in vehicle registrations across state borders, to observe the extent to which truck operators may employ regulatory evasion as an unintended consequence of the intervention.  

10:00
Title: Local Pollution Externalities from Driving: Evidence from Roadway Vehicle Sensors   

Authors: Andrew R. Waxman (University of Texas at Austin), Ruozi Song (World Bank), Rajat Kochhar (University of Chicago), Antonio M. Bento (University of Southern California) 

Suggested Presenter: Ruozi Song (World Bank) 

Abstract: This paper seeks to understand the localized effect of automobile congestion on air pollution. We causally identify this effect by leveraging air pollution sensors on Google Street View cars, combining the pollution readings with fine grain speed and vehicle density observations on Los Angeles Highways.  Our results indicate that pollution is highest at very low (<20km/h) and very high speeds (>60km/h), a result driven by lowered en2gine efficiency. We show that higher pollution occurs at very low and very high speeds due to lowered engine efficiency. Given the success to date of reducing pollution via tailpipe emission standards, we show that the magnitude of our effects points to the need to focus more attention by policymakers on vehicle speeds for further mitigation of health impacts from vehicle emissions. Our results have important implications for understanding human health effects of anti-congestion policies, speed limits and point to a need to better regulate sources of fine particulate matter pollution from tires and brakes.  

11:00 Hackathon: Building an environmental enforcement project
Ideation as a group/Team Forming

12:00 Lunch

13:00 Hackathon in Teams

17:00 End of Day 2

<h2>March 27, Day 3</h2>

09:00 Presentation of Hackathon ideas

10:00
Title: Enhancing environmental enforcement with near real-time monitoring: Likelihood-based detection of structural expansion of intensive livestock farms

Authors: Ben Chugg (Stanford University), Brandon Anderson (Stanford University), Seiji Eicher (Stanford University), Sandy Lee (Stanford University), Daniel E. Ho (Stanford University)

Suggested Presenter: Daniel E. Ho (Stanford University)

Abstract:
Much environmental enforcement in the United States has historically relied on either self-reported data or physical, resource-intensive, infrequent inspections. Advances in remote sensing and computer vision, however, have the potential to augment compliance monitoring by detecting early warning signs of noncompliance. We demonstrate a process for rapid identification of significant structural expansion using Planet’s 3 m/pixel satellite imagery products and focusing on Concentrated Animal Feeding Operations (CAFOs) in the US as a test case. Unpermitted building expansion has been a particular challenge with CAFOs, which pose significant health and environmental risks. Using new hand-labeled dataset of 145,053 images of 1,513 CAFOs, we combine state-of-the-art building segmentation with a likelihood-based change-point detection model to provide a robust signal of building expansion (AUC = 0.86). A major advantage of this approach is that it can work with higher cadence (daily to weekly), but lower resolution (3 m/pixel), satellite imagery than previously used in similar environmental settings. It is also highly generalizable and thus provides a near real-time monitoring tool to prioritize enforcement resources in other settings where unpermitted construction poses environmental risk, e.g. zoning, habitat modification, or wetland protection.

10:45 Coffee Break

11:00 
Title: Detecting Environmental Violations with Satellite Imagery in Near Real Time: Land Application under the Clean Water Act

Authors: Ben Chugg (Stanford University), Nicolas Rothbacher (Stanford University), Alex Feng (Stanford University), Xiaoqi Long (California Institute of Technology), Daniel E. Ho (Stanford University)

Suggested Presenter: Nicolas Rothbacher

Abstract: This paper introduces a new, highly consequential setting for the use of computer vision for environmental sustainability. Concentrated Animal Feeding Operations (CAFOs) (aka intensive livestock farms or “factory farms”) produce significant manure and pollution. Dumping manure in the winter months poses significant environmental risks and violates environmental law in many states. Yet the federal Environmental Protection Agency (EPA) and state agencies have relied primarily on self-reporting to monitor such instances
of “land application.” Our paper makes four contributions. First, we introduce the environmental, policy, and agricultural setting of CAFOs and land application. Second, we provide a new dataset of high-cadence (daily to weekly) 3m/pixel satellite imagery from 2018-20 for 330 CAFOs in Wisconsin with hand labeled instances of
land application (n=57,697). Third, we develop an object detection model to predict land application and a system to perform inference in near real-time. We show that this system effectively appears to detect land application (PR AUC = 0.93) and we uncover several outlier facilities which appear to apply regularly and excessively. Last, we estimate the population prevalence of land application events in Winter 2021/22. We show that the prevalence of land application is much higher than what is self-reported by facilities. The system can be used by environmental regulators and interest groups, one of which piloted field visits based on this system this past winter. Overall, our application demonstrates the potential for AI-based computer vision systems to solve major problems in environmental compliance with near-daily imagery.

11:45
Title: Results from Applying Satellite Imagery for Environmental Enforcement

Suggested Presenter: Aaron Margolis (EPA)

Abstract: Results from applying "Detecting Environmental Violations with Satellite Imagery in Near Real Time" to detect violations.

12:30 End of Program
