# Columns Present in 2021 but NOT in 2023:

- SEQUENCE_NO → Seems renamed to SEQ_NO in 2023
- TOINC (appears lower down in 2023)
- BWEIGHT
- RFACT_POP
- PCINC
- PPCINC (seems duplicated but appears lower in 2023 list)

# Columns Present in 2023 but NOT in 2021:

- SEQ_NO (renamed from SEQUENCE_NO)
- MEM_RFACT
- PERCAPITA
- PRPCINC
- RPCINC_NIR
- W_REGN_NIR
- Renamed Columns:
- SEQUENCE_NO (2021) → SEQ_NO (2023)
- TOINC (2021) appears in a lower position in 2023.

# Analysis

- Rename SEQUENCE_NO in 2021 to SEQ_NO
- REMOVE BWEIGHT
- RFACT -> FAMILY_WEIGHT
  - 2021: RFACT
  - 2023: RFACT
- RFACT_POP -> POPULATION_WEIGHT
  - 2021: RFACT_POP
  - 2023: MEM_RFACT
- Rename PERCAPITA in 2023 to PCINC
- Remove 2023 PPCINC
- Rename 2023's PRPCINC to PPCINC
- Remove 2023's RPCINC and rename RPCINC_NIR to RPCINC
- Remove 2023's W_REGN and rename W_REGN_NIR to W_REGN