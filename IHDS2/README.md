# IHDS-II (2011-12)

This folder contains data preparation and derived outputs for the IHDS-II component of the Social Capital and Migration term paper.

## Main datasets

- Household data: IHDS-II DS0002
- Non-resident data: IHDS-II DS0007

## Constructed variables

### Social Capital
Social capital is constructed from ME1-ME12 household organizational membership indicators.

Main measures:
- `social_capital_count`: Number of memberships
- `social_capital_index`: Proportion of organizational memberships

MCA was also performed as an alternative social-capital measure.

### Migration
Non-resident information from DS0007 is aggregated to household level.

Measures include:
- `has_nonresident`
- `nonresident_members`
- interstate migration
- international migration
- other-village migration
- city migration
- metro-city migration

## Status

Social-capital and migration construction completed.
Household controls and final panel harmonization are in progress.
