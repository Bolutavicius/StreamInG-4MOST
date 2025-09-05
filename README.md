# StreamInG-4MOST
Stellar Streams in the Inner Galaxy with S-PLUS and 4MOST

## Abstract: 
xxx

## Dataset Description

This dataset contains astronomical targets selected for observation with the 4MOST spectrograph (4-metre Multi-Object Spectroscopic Telescope). The file XXX includes a compilation of YYY candidate members of stellar streams, selected using S-PLUS and Gaia, with their celestial coordinates, magnitudes, and other properties relevant for spectroscopic observations.

## FITS File Structure

The main file XXX contains a binary table with multiple columns describing the properties of the target objects. The data is formatted according to 4MOST requirements for observation proposals.

## Column Descriptions

| Index | Name | Description | Type |
|-------|------|-------------|------|
| 0 | INDEX | Row index in the table | Long |
| 1 | NAME | Object identifier | String |
| 2 | RA | Right ascension (J2000) in degrees | Double |
| 3 | DEC | Declination (J2000) in degrees | Double |
| 4 | PMRA | Proper motion in RA (mas/year) | Double |
| 5 | PMDEC | Proper motion in DEC (mas/year) | Double |
| 6 | EPOCH | Position epoch | Double |
| 7 | RESOLUTION | Required spectral resolution | Long |
| 8 | SUBSURVEY | Subsurvey identifier | String |
| 9 | TEMPLATE | Spectral template to be used | String |
| 10 | RULESET | Observation ruleset | String |
| 11 | EXTENT_FLAG | Object extent flag | Long |
| 12 | EXTENT_PARAMETER | Extent parameter | Double |
| 13 | EXTENT_INDEX | Extent index | Double |
| 14 | MAG_TYPE | Photometric magnitude system | String |
| 15 | MAG | Object magnitude | Double |
| 16 | MAG_ERR | Magnitude error | Double |
| 17 | DATE_EARLIEST | Earliest observation date | Long |
| 18 | DATE_LATEST | Latest observation date | Long |
| 19 | CADENCE | Observation cadence | Long |
| 20 | REDDENING | Reddening (E(B-V)) | Double |
| 21 | REDSHIFT_ESTIMATE | Estimated redshift | Double |
| 22 | REDSHIFT_ERROR | Estimated redshift error | Double |
| 23 | TEMPLATE_REDSHIFT | Template redshift | Double |
| 24-32 | CAL_MAG_* | Calibrated magnitudes in different bands | Double |
| 33 | CLASSIFICATION | Object classification (GAL = galaxy) | String |
| 34 | COMPLETENESS | Observation completeness | Double |
| 35 | PARALLAX | Object parallax | Double |

## Scientific Context

This catalog was compiled as part of a project studying stellar streams accreted from dwarf satellites of the Milky Way. These objects are targets for the 4MOST telescope, a high-resolution multi-object spectrograph installed.

4MOST will conduct several spectroscopic surveys, and this catalog was prepared as part of a proposal for supplementary observation time. All targets comply with the specific requirements of 4MOST for scientific proposals, including the standard target catalog format.

## Target Selection Criteria

XXX


### Figures

### fig

![description.](link)
