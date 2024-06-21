PURIS
The Predictive Unit Real-Time Information Service (PURIS) for Short Term Demand and Capacity Management
Overview

The project is made of a backend and a frontend. Look into the respective folders and their documentation to get information about prerequirements and getting started guides.
Dependencies

Beside the dependencies provided in the Helm Chart, the following dependencies have been tested for R24.05 to run PURIS:
Application 	App Version 	Chart Version
Tractus-X Connector 	0.7.1 	0.7.1
Digital Twin Registry 	0.4.3 	0.4.11
Known Knows
Data Sovereignty

Currently, edc assets are always configured to match exactly one kind policy. These policies can be defined during deployment (see Admin Guide). Data is offered to each partner, who has been added to the PURIS FOSS's master data pool depending on the business relationship (partner is a customer / supplier).

For productive use, the following features should be implemented:

    configuration of contracts including accepting and refusing contracts via UI
    more user-friendly configuration of contracts including bi-lateral contracts

License

The project is licensed under the Apache License Version 2.0. For details on the licensing terms, see the LICENSE file.
Notice for Docker Image

Below you can find the information regarding Docker Notice for this frontend.

    Frontend
    Backend

NOTICE

This work is licensed under the Apache-2.0.

    SPDX-License-Identifier: Apache-2.0
    SPDX-FileCopyrightText: 2024 Contributors to the Eclipse Foundation
    Source URL: https://github.com/eclipse-tractusx/puris
