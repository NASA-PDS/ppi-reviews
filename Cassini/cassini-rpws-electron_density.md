# cassini-rpws-electron_density bundle

This is a new bundle produced in PDS4 form, requiring a full review.

The last column should include links to issues.

The liens Excel spreadsheet for just this bundle is
[cassini-rpws-electron_density.xlsx]().

| # | Status | Type | Comment | Assigned | Reviewer | Notes |
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| 1 | Open | Bundle | Need to obtain a DOI for this bundle | PDS | Chen | |
| 2 | Fixed | Data | In the CSV file headers the units label for the FREQ_L_EQUALS_ZERO column has a typo (is "[Hz}", should be "[Hz]"). | Data Provider | Pulupa | ljg |
| 3 | Open | Document | For a user (like myself) who is not very familiar with the details of the operating modes and trajectory of the Cassini spacecraft during the various phases of the mission, it would be very useful to include references to key instrument and science papers which would help to interpret the data. | Data Provider | Pulupa | wsk to provide references to papers  ljg to find format |  wsk-done
| 4 | Open | Document | What is the source for the FREQ_FCE data? Measured magnetometer data, or a model? The FCE data tends to change in discrete steps–is this due to limited resolution of the magnetic field? | Data Provider | Pulupa | Comes from measured MAG data --often 1-min resolution explains discrete steps |
| 5 | Open | Document | I was able to find references to the "SATURN_SLS" coordinate systems, but it would be useful to directly link those references in the data set description. | Data Provider | Pulupa | SPICE longitude |
| 6 | Open | Document |It would be very useful to include in the data set description some links to papers which make use of these data sets. For a new user, replicating a published figure is often an easy way to gain familiarity and confidence with a new data set. A link to a general overview paper which describes the phases of the Cassini mission would also be helpful–guiding an unfamiliar user to understand when Cassini was in favorable conditions to make good measurements of electron density with RPWS.  The README file for the QTN data set is a good example–there are links to several papers and a brief description of the technique, and some discussion of limitations of the data. | Data Provider | Pulupa | wsk provided reference list to Persoon et al. papers  wsk to look at readme file and possibly produce a dataset.cat-like file |
| 7 | Open | Document |  The SPICE kernels used to calculate the ephemeris data included in the data should be documented. Ideally these should be included as internal references (Reference_List/Internal_Reference) in the individual data files. Alternatively a list could be included with the bundle documentation (i.e. Readme). | Data Provider | Mafi | cwp to ask Joe for metakernel |
| 8 | Open | Document: Readme | The "Related PDS Products" section should include PDS3 data set IDs or PDS4 LIDs for the referenced data | Data Provider | Mafi | wsk to add these references parent data sets to dataset.cat-like file |

## Documents

See the online [document directory](https://space.physics.uiowa.edu/pds/cassini-rpws-electron_density/document/).  The _primary_ vs _secondary_ member thing is making Larry worry whether or not mission, spacecraft, or even instrument documents should be here; these should certainly not be primary members of this bundle or collection.

## Miscellaneous

Joe Mafi once frowned at mixing dashes and underscores in this bundle name, but Larry feels that if "-" is a field separator, then "\_" is a reasonable word separator.  (Chris prefers the reverse, with "\_" the field separator and "-" the word separator.)


