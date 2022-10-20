# Contribution to basso-continuo-dataset

For contributing to this dataset, please follow this procedure:

1. Pick a piece containing a figured bass line (if unsure, please refer to the table
   at the bottom ot this document), ideally with 0 to 2 additional parts.
2. Make sure the piece has not been added to the repository (refer to README.md) yet.
3. Using MuseScore 3, enter the piece into the software with the figured
   bass line using MuseScore's figured bass function
   (refer to https://musescore.org/en/handbook/3/figured-bass).
4. Save as both uncompressed MuseScore 3 file (name.mscx) and MusicXML (name.musicxml).
5. Check again that the MusicXML file and the MuseScore file contain the same
   information.
6. The file name must follow the following convention:
   * `[composer]_[piece identifier].xyz`
7. Make a pull request.

Recommended pieces:

| number of additional parts | composer          | piece(s)                                              | description                                                                                                                               | hyperlink                                                                                              |
|----------------------------|-------------------|-------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------|
| 0                          | Francesco Durante | Regole                                                | Partimento rules, very beginner-friendly for first-time contributors. Please save under the convention `durante_regole_[page number].xyz` | https://partimenti.org/partimenti/collections/durante/durante_regole.pdf                               |
| 1                          | Arcangelo Corelli | 12 Violin Sonatas Op.5                                | Please save under the convention `corelli_op5_[concerto number]_[movement number].xyz`                                                    | https://imslp.org/wiki/12_Violin_Sonatas%2C_Op.5_(Corelli%2C_Arcangelo)                                |
| 1-2                        | Francois Couperin | Concerts Royaux                                       | Please save under the convention `couperinf_concertsroyaux_[concert number]_[movement number].xyz`                                        | https://imslp.org/wiki/Concerts_royaux_(Couperin%2C_Fran%C3%A7ois)                                     |
| 1-2                        | Francois Couperin | Les Goûts-réunis (ou Nouveaux Concerts)               | Please save under the convention `couperinf_nouveauxconcerts_[concert number]_[movement number].xyz`                                      | https://imslp.org/wiki/Les_go%C3%BBts-r%C3%A9unis%2C_ou_Nouveaux_concerts_(Couperin%2C_Fran%C3%A7ois)  |
| 1                          | J.S. Bach         | Sonatas for Violin and Basso Continuo (BWV 1021-1026) | Please save under the convention `bachjs_bvw[BWV number]_[movement number].xyz`                                                           | https://imslp.org/wiki/Sonatas_for_Violin_and_Basso_Continuo,_BWV_1021-1026_(Bach,_Johann_Sebastian)  |
