##### Corrected data preprocessing tables:
- interpreter (need_want_interpreter): Yes and No seem inverted

- hispanic (hispanicorigin_no): t should be mapped to No instead of Yes

- marital_status (maritalstatus): deleted extra useless file “data_conversion_map.xlsx”

- med_intervention (medicationintervention): looks like 0-No should be 9-No?

- meds_iv_adm (HIJKMNO-discharge-treativmedsdis): should be meds_iv_dc?

- vent_cpap_adm (HIJKMNO-discharge-treatcpapdis): should be vent_cpap_dc?

- pressure_ulcer_dc (HIJKMNO-discharge-pressureulcersdisch): misstyped as adm

- bathe_adm (GG-adm-showerbatheadm): somehow they are at column C/D, not A/B

- bathe_dc (GG-dc-showerbathedc): somehow they are at column C/D, not A/B

- toileting_goal (GG-adm-toiletinghygienegoal): some how it does not start from row 1
##### Assumptions:

- hispanic: we should probably combine this variable with the unable to respond and decline to respond, and anyone who did not have one of those boxes checked should be a "No".