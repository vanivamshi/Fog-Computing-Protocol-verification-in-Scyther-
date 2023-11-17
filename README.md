# Protocol-verification-in-Scyther
This folder contains various files containing Scyther programs (formal verification of authentication protocols) written in SPDL. The programs simulate the operation, movement, clustering and load distribution between NB-IoT devices and fog nodes for various device specifications (regular and heavy vehicles), fog servers mounted on base stations (service provider-controlled and private fog servers) and cell range (cells and microcells). Details of each of the files are given below.

1] authentication_cell_microcell - authentication of devices moving between cells and microcells

2] authentication_independent_server_verified - authentication of devices in private fog servers using group authentication

3] authentication_independent_server_not_verified - individual authentication of devices in private fog servers. Implemented when "authentication_independent_server_verified" fails

4] handover_cell_independent_server - handover of devices moving between cells and private fog servers

5] handover_microcell - handover of devices moving between cells

6] handover_microcell_base_station - handover of devices moving between cells and microcells

7] secret_generation - generation of authentication secrets when devices turn ON each time
