PODAAC OSCAR Satellite Data:
Ocean Surface Current Analyses Real-time (OSCAR) Surface Currents - Near Real Time 0.25 Degree (Version 2.0)

OSCAR User Guide:
https://deotb6e7tfubr.cloudfront.net/s3-edaf5da92e0ce48fb61175c28b67e95d/podaac-ops-cumulus-docs.s3.us-west-2.amazonaws.com/oscar/open/L4/oscar_v2.0/docs/oscarv2guide.pdf?A-userid=None&Expires=1720541802&Signature=QoVTdqo2c-NthxlccYHch5IT8QP~3Z5hRfY4M~2MzYyIJAFqQ6pBPQyK0Gt856uXtt2MSYTJsiJbNCImiNVF8yAT3dKBSVUhSBwkeVenGV~e6sYykU3d4~4t115wuQIBQEp7PFSLXfKKFT3qSNQhrgLvYkcihi~0~D57dqw-FTfZypF4MAUSDhgAFwOQKVwSV0fZXYvFgqpfXPni-wcMEfEzL6gFjLAAqRtrx0n1Q18G2qs1S0mXLRAd2qNrgjkScJx2ETFFl4dkbdxEPYbTrUcXMHcSWyb3icUlAk-gvsigxtqMRMudFSMJoDITZIALIJEOM0oNAVm-d--w2fBW3g__&Key-Pair-Id=KX5J11OFWFB3T

Data Info:
Ocean surface currents in this data set are measured for the top 30m of the water column and are averaged to provide an estimate of the current at 15m of depth. The OSCAR NRT program records data daily and uploads files in "near real time", any of these files can be processed by this script. Downloaded any oscar file into the "oscar_data" file which is found in the "project" file, then update the file path in lines 26 and 31 and the script should run smoothly. The program will output a tidy data excel file into the project file.

Variables:

lat - lattitude, degrees north

Lon - longitude, degrees east

u   - zonal total surface current, eastward sea velocity, m s-1

v   - meridional total surface current, northward sea velocity, m s- 1

ug  - zonal geostrophic surface current, m s-1

vg  - meridional geostrophic surface current, m s-1
