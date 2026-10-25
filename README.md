# EDS 223 Homework Assignment #2: Mapping and Visualizing Disadvantaged Communities in Los Angeles County

### Purpose: 

This repo houses code and visualizations for analyses performed on HOLC, EJScreen, and LA County crash data. 

### Repository Structure: 

```
EDS223-HW2
├── data
│   ├── ejscreen
│   │   ├── EJSCREEN_2023_BG_Columns.xlsx
│   │   ├── EJSCREEN_2023_BG_StatePct_with_AS_CNMI_GU_VI.gdb
│   │   │   ├── a00000001.freelist
│   │   │   ├── a00000001.gdbindexes
│   │   │   ├── a00000001.gdbtable
│   │   │   ├── a00000001.gdbtablx
│   │   │   ├── a00000001.TablesByName.atx
│   │   │   ├── a00000002.gdbtable
│   │   │   ├── a00000002.gdbtablx
│   │   │   ├── a00000003.gdbindexes
│   │   │   ├── a00000003.gdbtable
│   │   │   ├── a00000003.gdbtablx
│   │   │   ├── a00000004.CatItemsByPhysicalName.atx
│   │   │   ├── a00000004.CatItemsByType.atx
│   │   │   ├── a00000004.FDO_UUID.atx
│   │   │   ├── a00000004.freelist
│   │   │   ├── a00000004.gdbindexes
│   │   │   ├── a00000004.gdbtable
│   │   │   ├── a00000004.gdbtablx
│   │   │   ├── a00000004.horizon
│   │   │   ├── a00000004.spx
│   │   │   ├── a00000005.CatItemTypesByName.atx
│   │   │   ├── a00000005.CatItemTypesByParentTypeID.atx
│   │   │   ├── a00000005.CatItemTypesByUUID.atx
│   │   │   ├── a00000005.gdbindexes
│   │   │   ├── a00000005.gdbtable
│   │   │   ├── a00000005.gdbtablx
│   │   │   ├── a00000006.CatRelsByDestinationID.atx
│   │   │   ├── a00000006.CatRelsByOriginID.atx
│   │   │   ├── a00000006.CatRelsByType.atx
│   │   │   ├── a00000006.FDO_UUID.atx
│   │   │   ├── a00000006.freelist
│   │   │   ├── a00000006.gdbindexes
│   │   │   ├── a00000006.gdbtable
│   │   │   ├── a00000006.gdbtablx
│   │   │   ├── a00000007.CatRelTypesByBackwardLabel.atx
│   │   │   ├── a00000007.CatRelTypesByDestItemTypeID.atx
│   │   │   ├── a00000007.CatRelTypesByForwardLabel.atx
│   │   │   ├── a00000007.CatRelTypesByName.atx
│   │   │   ├── a00000007.CatRelTypesByOriginItemTypeID.atx
│   │   │   ├── a00000007.CatRelTypesByUUID.atx
│   │   │   ├── a00000007.gdbindexes
│   │   │   ├── a00000007.gdbtable
│   │   │   ├── a00000007.gdbtablx
│   │   │   ├── a00000039.freelist
│   │   │   ├── a00000039.gdbindexes
│   │   │   ├── a00000039.gdbtable
│   │   │   ├── a00000039.gdbtablx
│   │   │   ├── a00000039.horizon
│   │   │   ├── a00000039.I49AREALAND_1.atx
│   │   │   ├── a00000039.I49AREALAND.atx
│   │   │   ├── a00000039.I49AREAWATER.atx
│   │   │   ├── a00000039.I49ID.atx
│   │   │   ├── a00000039.spx
│   │   │   ├── EJSCREEN - Shortcut.lnk
│   │   │   ├── gdb
│   │   │   └── timestamps
│   │   └── ejscreen-tech-doc-version-2-2.pdf
│   ├── mapping-inequality
│   │   ├── mapping-inequality-los-angeles.json
│   │   └── mapping-inequality-new-haven.json
│   └── SWITRS_LA
│       └── Crashes.csv
├── HW2.pdf
├── HW2.qmd
└── README.md
```
### Data Access:
Data accessed through the restructured EJScreen tool as the former website no longer exists: [EJScreen Website.](https://www.epa.gov/ejscreen) Google drive link for ease of access to the EJScreen dataset: [EJScreen Dataset](https://drive.google.com/file/d/1nG6Nj1bXfzQFOVMO8Km3eNy4SWu1YcIQ/view?usp=sharing)

### Authors: 
Mark Oregel

### References and Acknowledgements: 
**Data Citation**: 
U.S. Environmental Protection Agency (EPA), 2023. EJScreen Technical Documentation. Accessed: October 8th, 2025. 
**Link:** https://drive.google.com/file/d/1nG6Nj1bXfzQFOVMO8Km3eNy4SWu1YcIQ/view?usp=sharing