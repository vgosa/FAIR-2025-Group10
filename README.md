# FAIR 2025-2026 Group 10

This repository contains the code and documentation for the FAIR 2025-2026 Group 10 project.

## Dataset Overview
The dataset used in this project is sourced from [Kaggle - Fitness Tracker Dataset](https://www.kaggle.com/datasets/smayanj/fitness-tracker-dataset) under the [CC0: Public Domain](https://creativecommons.org/publicdomain/zero/1.0/) license. It includes simulated fitness and wellness data from several types of wearable devices, covering various health metrics such as heart rate, sleep timings, step counts and more.

## Metadata Overview
The dataset is accompanied by metadata files that provide explicit definitions for the Dataset and Distribution schemas, as well as the metadata records for the dataset and the two distributions (available in CSV and RDF-Turtle formats). The schemas and metadata records were generated using the [FAIR Data Point](https://www.fairdatapoint.org/) tool. The location of these files is in the `metadata` directory.

## Shape Graph
The shape graph for the dataset is available in the `metadata` directory in the `shapes.ttl` file. The SHACL code can be used to validate the dataset against the defined shapes using a SHACL validation tool.

## Visualizations
### Semantic Model
![Semantic Model in dot format](https://raw.githubusercontent.com/vgosa/FAIR-2025-Group10/main/visualization/rdf_skeleton.png)

### RDF Instance Visualisation
![Visualization of an instance in our FAIRified dataset](https://raw.githubusercontent.com/vgosa/FAIR-2025-Group10/main/visualization/rdf_visual_representation.png)
