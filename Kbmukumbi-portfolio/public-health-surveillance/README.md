# 📡 Public Health Disease Surveillance Architecture

## 🧠 Project Objective
To simulate a real-world public health disease surveillance system using open-source tools and synthetic EHR data, emphasizing interoperability and outbreak tracking.

## 🔧 Tools & Technologies
- **Synthea**: Synthetic patient data generation
- **HAPI-FHIR Server**: HL7 FHIR-compliant data exchange
- **Postman**: API testing for FHIR resources
- **Docker & Ubuntu CLI**: For deployment and system checks
- **FHIR/HL7**: Standards for health data interoperability

## 🔁 System Workflow
1. Generate synthetic EHR patient data using **Synthea**
2. Configure a **centralized HAPI-FHIR server**
3. Create & manage **FHIR resources** (e.g., Practitioner, Condition) using **Postman**
4. Simulate disease outbreaks from 4 hospitals, monitor response codes (201/200)
5. Perform memory & port checks using Linux commands

## 📊 Simulated Outbreak Data
| Hospital        | Pop Served | COVID % | Patients Simulated |
|-----------------|------------|---------|---------------------|
| MGH             | 20,000     | 10%     | 2000                |
| BCMH            | 7,000      | 2%      | 140                 |
| Portage Health  | 9,000      | 0.5%    | 45                  |
| Aspirus         | 5,000      | 0.4%    | 20                  |

## 📂 Included Materials
- `synthea-patient-export/` – generated EHR files
- `architecture_diagram.png` – data flow of hospitals → FHIR Server
- `postman_requests.json` – sample FHIR requests (Practitioner, Condition)
- `ubuntu_cmds.txt` – troubleshooting and monitoring scripts

## 👩🏽‍💻 Contributions (Kudakwashe Mukumbi)
- Led the deployment and testing of the HAPI-FHIR server
- Created FHIR resources in Postman
- Interpreted outbreak simulation and mapped EHR flows

## 🚀 Future Work
- Integrate real-time dashboards
- Link predictive analytics to detected outbreaks
- Expand simulation to include contact tracing

