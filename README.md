# Geological Mapping

Two geological mapping projects combining **GIS, geological interpretation, field data collection and cartographic visualization**.

The repository contains an individual geological mapping project for the **Podhale Basin** and a collaborative field mapping project covering the **Szczawa–Zasadne** area in the Polish Carpathians.

## Projects

### 1. Podhale Basin Geological Map

**Individual project — Michał Kuśnierz**

Geological mapping and spatial interpretation of a section of the **Podhale Basin**, completed using ArcGIS Pro.

The project involved:

- interpretation and digitization of geological boundaries,
- representation of geological units and stratigraphy,
- structural measurements and orientation of geological layers,
- geological calculations supporting map construction,
- integration of geological information with topographic data,
- preparation of the final cartographic layout.

The resulting map distinguishes the Lower Chochołów Beds and the Lower and Upper Zakopane Beds and presents interpreted geological boundaries together with structural measurements.

#### Deliverables

- [Geological map of the Podhale Basin](podhale-basin/maps/geological_map_podhale.pdf)
- [Geological calculations](podhale-basin/calculations/geological_calculations.xlsx)
- `Podhale.aprx` — ArcGIS Pro project

---

### 2. Szczawa–Zasadne Geological Mapping

**Collaborative field mapping project**

Detailed geological mapping of approximately **3.2 km²** in the Szczawa–Zasadne area of the Polish Carpathians at a scale of **1:10,000**.

The project combined traditional geological fieldwork with modern GIS-based data acquisition and cartographic methods.

#### Fieldwork

Geological data were collected directly in the field using **ArcGIS Field Maps**.

Field activities included:

- identification of lithostratigraphic units and geological outcrops,
- collection of geological observation points,
- structural measurements,
- mapping of geological boundaries,
- observations of tectonic structures,
- identification of landslides and other geomorphological features,
- verification of existing geological information against field observations.

#### GIS and Cartographic Processing

The collected field observations were subsequently processed in **ArcGIS Pro**.

The workflow included:

- organization and processing of field data,
- digitization and vectorization,
- spatial interpretation of geological units,
- reconstruction of geological boundaries,
- integration of structural measurements,
- preparation of a detailed geological map.

The final interpretation identifies units of the **Bystrica Unit of the Magura Nappe**, representing formations ranging from the Late Cretaceous to the Lower Eocene.

The mapped area also displays a complex tectonic structure, including thrusting and a system of transverse faults.

#### Deliverables

- [Geological map of Szczawa–Zasadne](szczawa-zasadne/maps/geological-map-szczawa-zasadne.pdf)
- [Geological mapping report](szczawa-zasadne/documentation/geological-mapping-report.pdf)
- `Szczawa.aprx` — ArcGIS Pro project

#### Authors

- Kamila Bodziony
- Kamila Dziewa
- Mateusz Grodzki
- **Michał Kuśnierz**
- Jan Potaśniczak

Fieldwork and project development: **6–13 July 2026**

## Technologies and Methods

- **ArcGIS Pro**
- **ArcGIS Field Maps**
- GIS and spatial data processing
- geological mapping
- field data collection
- structural geological measurements
- geological interpretation
- vectorization and digitization
- cartographic visualization

## Repository Structure

```text
geological-mapping/
├── podhale-basin/
│   ├── calculations/
│   │   └── geological_calculations.xlsx
│   ├── maps/
│   │   └── geological_map_podhale.pdf
│   └── project/
│       └── Podhale.aprx
├── szczawa-zasadne/
│   ├── documentation/
│   │   └── geological-mapping-report.pdf
│   ├── maps/
│   │   └── geological-map-szczawa-zasadne.pdf
│   └── project/
│       └── Szczawa.aprx
└── README.md
```

## About

Both projects were developed as part of geological mapping courseworks at **AGH University of Science and Technology**.

The repository demonstrates two complementary aspects of geological GIS work: individual geological interpretation and cartographic preparation in the Podhale project, and collaborative field-to-GIS geological mapping in the Szczawa–Zasadne project.
