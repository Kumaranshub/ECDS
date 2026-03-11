
                                                                                 
   ███████╗███████╗███╗   ██╗████████╗██╗███╗   ██╗███████╗██╗                    
   ██╔════╝██╔════╝████╗  ██║╚══██╔══╝██║████╗  ██║██╔════╝██║                    
   ███████╗█████╗  ██╔██╗ ██║   ██║   ██║██╔██╗ ██║█████╗  ██║                    
   ╚════██║██╔══╝  ██║╚██╗██║   ██║   ██║██║╚██╗██║██╔══╝  ██║                    
   ███████║███████╗██║ ╚████║   ██║   ██║██║ ╚████║███████╗███████╗               
   ╚══════╝╚══════╝╚═╝  ╚═══╝   ╚═╝   ╚═╝╚═╝  ╚═══╝╚══════╝╚══════╝               
                                                                                 
                               
                                                                                 
   SENTINEL — Secure Entity Network for Threat Intelligence & Enforcement Layer 
                                                                                 
                    
                                                                                
SECTION 01 — MISSION BRIEF

SENTINEL is a multi-source real-time intelligence fusion platform designed
for national security and law enforcement operations.

The system integrates investigative data from multiple operational systems
into a unified intelligence graph, enabling investigators to reconstruct
criminal networks, detect hidden associations, and respond to emerging
threats in real time.

SENTINEL combines graph analytics, machine learning risk scoring,
geospatial intelligence, and automated alerting to convert fragmented
data streams into actionable intelligence.

The platform is designed for sovereign deployment — fully on-premise,
air-gap capable, and built to operate within Singapore’s national
security infrastructure.

Core operational objective:

Transform raw data into operational intelligence.


SECTION 02 — SYSTEM STATUS

![Build](https://img.shields.io/badge/BUILD-STABLE-355e3b?style=flat-square)
![Python](https://img.shields.io/badge/PYTHON-3.11+-355e3b?style=flat-square)
![FastAPI](https://img.shields.io/badge/FASTAPI-0.110-355e3b?style=flat-square)
![React](https://img.shields.io/badge/REACT-18-355e3b?style=flat-square)
![Neo4j](https://img.shields.io/badge/NEO4J-5.x-355e3b?style=flat-square)
![Kafka](https://img.shields.io/badge/KAFKA-3.6-355e3b?style=flat-square)
![License](https://img.shields.io/badge/LICENSE-RESTRICTED-8b0000?style=flat-square)
![Clearance](https://img.shields.io/badge/CLEARANCE-SECURITY%2B-8b0000?style=flat-square)


SECTION 03 — OPERATIONAL CAPABILITIES

LIVE ENTITY GRAPH
Dynamic criminal network visualisation linking individuals,
devices, vehicles, locations, and financial activity.

PATTERN OF LIFE ANALYSIS
Timeline reconstruction of subject activity including
movement, communications, and financial behaviour.

ML RISK SCORING ENGINE
Machine learning threat score (0–100) generated
from behavioural indicators and network relationships.

ENTITY RESOLUTION
Cross-database identity matching using phonetic
similarity and probabilistic linkage algorithms.

GEOINT LAYER
Real-time geospatial visualisation of vehicle movement,
border crossings, and surveillance feeds.

COMMUNICATION ANALYSIS
Call metadata and device activity used to reconstruct
communication networks.

AUTOMATED ALERT ENGINE
Rule-based and anomaly-detection alerts generated
when suspicious behavioural patterns are detected.

CASE MANAGEMENT
Structured investigation workflow including evidence
tracking, officer collaboration, and prosecution export.

IMMUTABLE AUDIT TRAIL
Every query, search, and record access logged with
cryptographic integrity verification.


SECTION 04 — SYSTEM ARCHITECTURE

DATA SOURCES
SPF SYSTEMS | ICA BORDER CONTROL | LTA VEHICLE REGISTRY
MAS FINANCIAL INTELLIGENCE | TELECOM METADATA
SURVEILLANCE NETWORK | CORPORATE REGISTRY | COURT SYSTEMS

INGESTION LAYER
Source connectors normalise incoming data streams
and publish events through Apache Kafka pipelines.

INTELLIGENCE ENGINE
Machine learning services compute entity risk scores,
perform entity resolution, and analyse behavioural patterns.

GRAPH SERVICE
Neo4j graph database models relationships between
people, organisations, vehicles, devices, and locations.

ALERT ENGINE
Event-driven monitoring system identifies anomalies
and sends alerts to investigators in real time.

CORE API
FastAPI service layer providing secure access to
entities, cases, alerts, and analytics services.

AUTHENTICATION GATEWAY
Role-based access control with MFA and clearance
segmentation for operational security.

OPERATIONS INTERFACE
React-based dashboard displaying entity graphs,
case files, geospatial intelligence, and alerts.


SECTION 05 — INTEGRATED DATA SOURCES

SPF SYSTEMS
Crime reports, suspects, investigation records.

ICA BORDER SYSTEMS
Entry/exit logs and immigration movement history.

LTA REGISTRY
Vehicle ownership and registration data.

MAS FINANCIAL INTELLIGENCE
Suspicious transaction reporting and AML data.

TELECOM METADATA
Call detail records and tower location data.

SURVEILLANCE NETWORK
CCTV and ANPR feeds.

ACRA CORPORATE REGISTRY
Companies, directors, beneficial ownership structures.

COURT SYSTEMS
Case status, warrants, and judicial proceedings.


SECTION 06 — TECHNOLOGY STACK

BACKEND

FastAPI
Neo4j Graph Database
PostgreSQL
Apache Kafka
Redis
Elasticsearch
MinIO Object Storage

INTELLIGENCE ENGINE

XGBoost
PyTorch
scikit-learn
spaCy NLP
Graph Data Science algorithms

FRONTEND

React
TypeScript
Redux Toolkit
D3.js graph visualisation
Deck.gl geospatial rendering

INFRASTRUCTURE

Docker
Kubernetes
Terraform
GitHub Actions
Prometheus monitoring
Grafana dashboards
HashiCorp Vault secrets management


SECTION 07 — DEPLOYMENT OPTIONS

GOVERNMENT COMMERCIAL CLOUD
Sovereign cloud infrastructure deployment.

ON-PREMISE GOVERNMENT DATA CENTRE
Secure rack deployment within controlled facilities.

AGENCY FEDERATION
Separate deployments across agencies with controlled
cross-agency intelligence sharing.


SECTION 08 — QUICK START

git clone https://github.com/your-org/sentinel.git
cd sentinel

cp config/.env.example .env

docker compose up -d

python scripts/migrate.py

cd frontend
npm install
npm run dev

Access UI

http://localhost:3000


SECTION 09 — REPOSITORY STRUCTURE

sentinel/

docs/
architecture
deployment
security

infra/
docker
kubernetes
terraform

services/
core-api
intel-engine
graph-service
alert-engine
ingestion-service
audit-service
auth-service

frontend/
components
pages
store
services
hooks

scripts/
setup
migration
seed

config/
environment templates


SECTION 10 — SECURITY DIRECTIVES

All operator accounts require MFA.

Secrets must never be committed to the repository.

All access events are logged in the immutable audit trail.

Production deployments require security review
before operational activation.

This system processes intelligence-grade data and is
restricted to authorised personnel.


SECTION 11 — COMPLIANCE

Personal Data Protection Act (PDPA)

Criminal Procedure Code

Computer Misuse Act

Official Secrets Act

All data handling and investigative workflows
must comply with applicable Singapore law.


SECTION 12 — CONTRIBUTING

All contributions require:

Passing CI tests
Peer code review
Security review for authentication or data access changes
Architecture Decision Records for major changes


SECTION 13 — LICENSE

RESTRICTED — NOT FOR PUBLIC DISTRIBUTION

This software is restricted to authorised government
and law enforcement personnel.

Unauthorised access or distribution may constitute
an offence under the Computer Misuse Act.

© 2026 All Rights Reserved
