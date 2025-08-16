
- [Project summary](#project-summary)
  - [The issue we are hoping to solve](#the-issue-we-are-hoping-to-solve)
  - [How our technology solution can help](#how-our-technology-solution-can-help)
  - [Our idea](#our-idea)
- [Technology implementation](#technology-implementation)
  - [IBM watsonx product(s) used](#ibm-ai-services-used)
  - [Other IBM technology used](#other-ibm-technology-used)
  - [Solution architecture](#solution-architecture)
- [Presentation materials](#presentation-materials)
  - [Solution demo video](#solution-demo-video)
  - [Project development roadmap](#project-development-roadmap)
- [Additional details](#additional-details)
  - [How to run the project](#how-to-run-the-project)
  - [Live demo](#live-demo)
- [About this template](#about-this-template)
  - [Contributing](#contributing)
  - [Versioning](#versioning)
  - [Authors](#authors)
  - [License](#license)
  - [Acknowledgments](#acknowledgments)

_INSTRUCTIONS: Below are the suggested sections to include in your README file to make sure your project is well documented. You can remove this instruction text._

## Project summary
This project proposes an AI-Driven Urban Renewal Platform that leverages IBM Watsonx.ai, IBM Cognos Analytics, and AutoCAD to transform unsafe mud-built slums into sustainable, concrete-based formal settlements. The solution combines predictive analytics, generative AI, and engineering design to create safe housing, optimize resources, and provide transparent monitoring aligned with UN SDG 11 (Sustainable Cities and Communities).

### The issue we are hoping to solve
Informal settlements in many urban centers:
Are built from mud and non-durable materials, leaving residents vulnerable to floods, fires, and building collapse.
Lack basic infrastructure such as sanitation, drainage, and reliable energy.
Suffer from overcrowding, unplanned growth, and poor governance in resource allocation.
Are rarely integrated into official urban planning systems, making them invisible in long-term development agendas.
The challenge is to transition slums into resilient, affordable, and inclusive formal housing without mass displacement and with measurable sustainability outcomes.

### How our technology solution can help
Our solution integrates AI, engineering design, and analytics to deliver evidence-based, transparent, and scalable housing transformation:
Watsonx.ai

Analyzes satellite images, census data, and IoT inputs to identify slum boundaries, density, and growth patterns.
Predicts population migration trends and calculates future material demand.
Uses generative AI to produce multiple redevelopment layouts (low-rise, modular, mixed-use).

AutoCAD

Translates AI-optimized layouts into detailed engineering blueprints and BIM-ready models.
Ensures compliance with local building codes, seismic safety, and environmental constraints.
Produces 3D visualizations to engage communities and support participatory decision-making.

IBM Cognos Analytics

Monitors budget expenditure, funding source accountability, and project KPIs (time, cost, quality).
Tracks material usage vs. AI predictions to detect inefficiencies early.
Reports on environmental indicators (CO₂ reduction, % green space maintained, renewable energy adoption).
Provides dashboards for government, NGOs, and the public, ensuring transparency and trust.


### Our idea
   We envision a closed-loop urban redevelopment pipeline where data, design, and decision-making flow seamlessly:

Data-driven Planning: Watsonx.ai identifies high-priority slum zones, forecasts future growth, and simulates housing layouts.
Engineering Design: AutoCAD imports these layouts to create construction-ready plans with integrated roads, drainage, and utilities.
Transparent Monitoring: Cognos Analytics provides real-time dashboards to track resources, progress, and sustainability outcomes.
Community Engagement: AI-generated “before/after” 3D models and Cognos transparency portals foster trust and acceptance.





## Technology implementation

### IBM watsonx product(s) used

_INSTRUCTIONS: Included here is a list of IBM watsonx products. Remove any products you did not use. Leave only those included in your solution code. In your official submission on the Call for Code Global Challenge web site, you are required to provide details on where and how you used each IBM watsonx product so judges can review your implementation. Remove these instructions._

**Featured watsonx products**

- [watsonx.ai](https://www.ibm.com/products/watsonx-ai) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
- The watsonx.ai was use
- Watsonx.ai – Predictive Planning & Generative Modeling

Inputs: Satellite imagery (12 km²), census data (85,000 residents), growth rate (3.8% annually).

Outputs:

GIS-compatible redevelopment maps.
Predicted material demand (3,500 tons concrete/month, 750 tons steel/month).
AI-generated redevelopment scenarios (low-rise apartments: 18,000 units, modular housing: 22,000 units).


### Other IBM technology used

IBM Cognos Analytics – Monitoring, Reporting & Transparency

Material usage vs. AI predictions: Concrete predicted 3,500 tons, actual 3,650 tons → +4.3% variance.
Budget accountability: $120M committed; $77.2M spent (64.3% utilization).
Construction KPIs: Structural framework planned 75% complete, actual 70%, quality score 8.5/10.
Environmental impact: Optimized concrete mix reduced CO₂ by 20.5%, green space increased from 5% to 12% of land.
 
**Additional IBM AI services (Remove any that you did not use)**

- [Watson Machine Learning](https://cloud.ibm.com/catalog/services/watson-machine-learning) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
Watson Machine learning  was an associated service when using the watsonx. ai
 AutoCAD – Detailed Engineering & Infrastructure Design
Converts Watsonx.ai plans into BIM-ready construction drawings.
Models 20,500 housing units across 8.5 km² with 32 km of roads and 18 green spaces.
Produces 3D before/after renderings for community validation

### Solution architecture

<img width="2000" height="1125" alt="image" src="https://github.com/user-attachments/assets/ebc3cca3-bf87-4cf9-8c10-8f08bd6990b9" />






## Presentation materials

_INSTRUCTIONS: The following deliverables should be officially posted to your My Team > Submissions section of the [Call for Code Global Challenge resources site](https://cfc-prod.skillsnetwork.site/), but you can also include them here for completeness. Replace the examples seen here with your own deliverable links._

### Solution demo video
### 
[![Watch the video](https://youtu.be/5fjDoKyZgPg)

### Project development roadmap

The project currently does the following things.

- Feature 1. Use of watsonx.ai for generation of new content and use watsonx.governance for examining coppyright infringement
- Feature 2. Use of watsonx.ai ( for prediction and creation of responses from data obtained from Maximo Application Suite , Environmental Intelligence Suite and Envizi) and watsonx. orchestrate (automation of repetitive tasks). The results are placed into the IBM Cognos Analyics for deriving further data insights 


In the future we plan to use watsonx. data  for data management and other IBM technologies such as watson discover for intelligent document processing 

See below for our proposed schedule on next steps after Call for Code 2024 submission.
### https://drive.google.com/file/d/1tV-6Blomms2woXUWXRhw3Q3s8BatA8xW/view?usp=sharing
![Roadmap]()

## Additional details

_INSTRUCTIONS: The following deliverables are suggested, but **optional**. Additional details like this can help the judges better review your solution. Remove any sections you are not using._

### How to run the project

INSTRUCTIONS: In this section you add the instructions to run your project on your local machine for development and testing purposes. You can also add instructions on how to deploy the project in production.
The project is run by use of Watsonx.ai and Watsonx. governance, other areas where the solution could be deployed is in the Cognos analytics

### Live demo


You can find a running system to test at...

See our [description document](./docs/DESCRIPTION.md) for log in credentials.

---

_INSTRUCTIONS: You can remove the below section from your specific project README._

## About this template

### Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

### Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags).

### Authors


- ** John Maina** - _Initial work_ - [PurpleBooth](https://)

### License

This project is licensed under the Apache 2 License - see the [LICENSE](LICENSE) file for details.

### Acknowledgments

- Based on [Billie Thompson's README template](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2).
