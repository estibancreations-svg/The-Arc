# THE ARC — Reality Build Decomposition Model v2

**Purpose:** Convert the existing 491-entity world catalog into a construction, operations and lifecycle model that can answer: *What is the Arc made of, how much is required, what depends on what, how is it built, and how is it maintained?*

## 1. Existing foundation reviewed

Stage 1 already contains:
- 491 seeded entities;
- 14 entity classes;
- 134 ARC-01 zones;
- first-pass entity-to-zone assignments;
- structural, mechanical, power, atmospheric, water, civic, digital, mineral/material, plant, terrestrial-animal, aquatic-animal, microbial/fungal, vehicle/robotic and emergency/safety classes;
- a Reality Calculation Framework covering geometry, artificial gravity, atmosphere, water, food, aquatic/green biomes, power, heat, structure, shield mechanics, radiation, supply chain, reliability, propulsion and simulation.

This is sufficient to begin **Stage 2: Quantified Build Decomposition**.

## 2. The required decomposition chain

Every entity must map through:

`SOURCE → PROCESS → STOCK → COMPONENT → SUBSYSTEM → ASSEMBLY → ZONE → OPERATION → MAINTENANCE → RECOVERY`

### SOURCE
Element, ore, mineral, polymer feedstock, biological stock, seed, cell culture, water source, atmospheric gas or imported finished material.

### PROCESS
Extraction, refining, smelting, alloying, polymerization, ceramic firing, composite layup, purification, sterilization, propagation, breeding, tissue culture, fermentation or other transformation.

### STOCK
Standardized usable feedstock: plate, tube, wire, powder, resin, ceramic blank, semiconductor wafer, nutrient stock, seed bank, water reserve, gas reserve, living broodstock.

### COMPONENT
Fastener, bearing, pump, valve, panel, sensor, actuator, cable, membrane, window unit, crop tray, filter, tank, habitat fixture, robotic unit, etc.

### SUBSYSTEM
Water treatment train, atmosphere loop, branch grid, shield drive, ring circulation lane, agricultural rack, medical module, transit segment, emergency system.

### ASSEMBLY
Branch frame, ring segment, shield panel, habitat district, central spine segment, aquatic biome, radiator field, docking structure.

### ZONE
One of the 134 ARC-01 Digital Twin zones.

### OPERATION
Power, water, atmosphere, consumables, heat, labor, control data and biological support required during use.

### MAINTENANCE
Inspection interval, failure mode, repair method, spares, replacement stock, service life, specialized labor and tooling.

### RECOVERY
Reuse, recycling, re-refining, composting, nutrient recovery, water recovery, biological archive or waste disposal.

## 3. Required Stage-2 fields per entity

Add or verify:
- entity_id
- parent_entity_id
- canonical_name
- class / subtype
- zone_id
- quantity
- unit
- dimensions
- unit_mass
- installed_mass
- volume
- material_composition by mass fraction
- source_material_ids
- manufacturing_process_ids
- component_inputs
- dependency_ids
- downstream_dependents
- assembly_stage
- installation_sequence
- labor_hours / automation_hours
- tool/facility requirement
- operating_power
- peak_power
- waste_heat
- water_input/output
- atmosphere_input/output
- consumables
- biological inputs/outputs
- inspection_interval
- MTBF / service life
- spare_ratio
- replacement_rate
- recycling_fraction
- reserve_stock
- failure_modes
- emergency_behavior
- visual_asset_ids
- evidence/source
- confidence
- approval_status

## 4. Biological decomposition

Living systems cannot be treated as decorative assets.

For every plant, animal, aquatic organism, microbe or fungus record:
- taxonomy;
- founding population / seed stock;
- genetic diversity target;
- habitat zone;
- environmental envelope;
- nutrition/feed;
- water;
- oxygen/CO2 exchange;
- reproduction/propagation;
- health/disease controls;
- trophic relationships;
- waste products;
- pollination/decomposition role;
- quarantine;
- minimum viable reserve;
- replacement/recovery plan.

### Output
A **closed ecology dependency graph** showing which species and microbial processes support food, oxygen, waste conversion, water quality, soil fertility and biodiversity.

## 5. Mineral/material decomposition

The final model must not stop at “steel” or “composite.”

For every installed material:
1. finished material;
2. alloy/resin/ceramic formulation;
3. constituent elements/chemicals;
4. source ore/feedstock;
5. refining route;
6. manufacturing route;
7. installed tonnes;
8. annual loss/replacement;
9. recycling fraction;
10. reserve stock;
11. substitute material.

### Output
A **Bill of Materials by finished material and by element**.

## 6. Vegetable / plant decomposition

For every crop/tree/aquatic plant:
- seed/genetic source;
- propagation method;
- planted area;
- growth cycle;
- yield;
- edible fraction;
- water/nutrient demand;
- light/heat load;
- substrate;
- pollination;
- disease reserve;
- biomass waste;
- processing/storage;
- seed reserve.

### Output
Food production, ecological services, oxygen/CO2 contribution and agricultural infrastructure requirements.

## 7. Mechanical / structural decomposition

For every structural and mechanical entity:
- dimensions;
- materials;
- joining method;
- load path;
- rotating/non-rotating state;
- bearing/interface;
- fabrication constraints;
- transport/handling;
- installation order;
- inspection;
- fatigue life;
- replacement strategy.

### Output
A zone-by-zone **construction work breakdown structure**.

## 8. Utility closure

Each zone must reconcile:
- average/peak power;
- waste heat;
- potable/process/aquatic/weather/fire/thermal water;
- oxygen and CO2;
- humidity;
- waste;
- food;
- data/control;
- emergency reserve.

No zone graduates to quantified status while inputs/outputs are unbalanced without an explicit external dependency.

## 9. Construction sequence model

Provisional ARC-01 build sequence:
1. resource extraction/refining capacity;
2. primary non-rotating spine/core;
3. rotating hub/bearing interfaces;
4. primary ring/quadrant structure;
5. five branch primary frames;
6. pressure/radiation/debris envelope;
7. power + thermal backbone;
8. atmosphere and water trunk systems;
9. shield tracks/drives/panels;
10. branch utilities and transit;
11. buildings/industrial/fabrication zones;
12. under-panel aquatic/reclamation infrastructure;
13. agriculture + soil/substrate;
14. ecological seeding;
15. civic/residential fit-out;
16. vehicle/robotics deployment;
17. staged population introduction;
18. commissioning + failure testing;
19. reserves/spares/self-repair capability;
20. mission propulsion/attitude integration.

This sequence remains provisional until propulsion, source-resource location and final geometry are locked.

## 10. Reality gates

- **R0 Canon:** visual/function identity fixed.
- **R1 Dimensioned:** major dimensions/volumes assigned.
- **R2 Massed:** quantity + mass assigned.
- **R3 Composed:** material/biological composition assigned.
- **R4 Connected:** dependencies and utility flows closed.
- **R5 Manufacturable:** process/tool/facility route known.
- **R6 Maintainable:** service/spares/recovery route known.
- **R7 Constructible:** installation sequence + interfaces validated.
- **R8 Simulated:** nominal and failure-state simulation passes.

## 11. Immediate quantitative locks required

Highest-value numbers to choose/extract next:
1. ARC-01 overall diameter;
2. axial length;
3. each branch usable length/width;
4. ring diameters/depths;
5. shield area/thickness/travel arc;
6. under-panel ocean area/depth;
7. design population;
8. target gravity;
9. atmospheric pressure/composition;
10. primary power architecture;
11. mission duration;
12. radiation design environment;
13. source-resource strategy;
14. propulsion architecture;
15. emergency reserve duration.

## 12. Production connection

The same Stage-2 data should drive:
- screenplay location continuity;
- VFX/model dimensions;
- prop/set fabrication;
- production design;
- game/VR environment scale;
- engineering visualizations;
- story conflicts grounded in real dependencies.

The Digital Twin becomes the single world truth: **a visual object, story object, engineering entity and construction entity share one ID.**
