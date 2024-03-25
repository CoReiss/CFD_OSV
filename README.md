# CFD_OSV
Notebook to calculate characteristics of an onset of significant void correlation. 

The figures generated are part of a paper submitted to the International Journal of Multiphase Flow:
Corentin Reiss and Antoine Gerschenfeld and Catherine Colin, Heat Flux Partition based on Onset of Significant Void, HAL archive, Submitted to International Journal of Multiphase Flow, 2024

The following librarys must be installed for the notebook to run: numpy, matplotlib, pandas, CoolProp, pylab

The references used in the OSV_database folder come from the following sources:

Egen 
Egen, R.A., Dingee, D.A., Chastain, J.W., 1957. Vapor formation and behav-ior in boiling heat transfer. Technical Report BMI-1163. Battelle MemorialInst., Columbus, Ohio.

Ferell 
Ferrell,  J.,  1964.   A  Study  of  Convection  Boiling  Inside  Channels.   Tech-nical  Report.  North  Carolina  State  Universitv,  Raleigh,North  Carolina.doi:https://doi.org/10.2172/4598223.

Rouhani
Rouhani, S., 1966.  Void Measurements in the Regions of Sub-Cooled andLow-Quality Boiling Part 1. Low Mass Velocities.  Technical Report AE-238. Aktiebolaget Atomenergi.  URL:https://www.osti.gov/etdeweb/biblio/20949499.
Rouhani, R., 1966.  Void Measurements in the Regions of Sub-Cooled andLow-Quality Boiling Part 2. Higher Mass Velocities. Technical Report AE-239. Aktiebolaget Atomenergi.  URL:https://www.osti.gov/etdeweb/biblio/20949498.

Bartolomei\_1 
Bartolomei,  G.,  Chanturiya,  V.M.,  1967.  Experimental  study of  true  voidfraction  when  boiling  subcooled  water  in  vertical  tubes.   Thermal  Engi-neering 14, 123–128.

Bartolomei\_2
Bartolomei, G., Brantov, V.G., Molochnikov, Y.S., Kharitonov, Y., Solodkii,V.A., Batashova, G., Mikhailov, V.N., 1982. An experimental investigationof true volumetric vapor content with subcooled boiling in tubes. ThermalEngineering 29, 132–135.  doi:https://doi.org/10.2172/1262488.

Staub\_Ch 
Staub,  F.W.,  Walmet,  G.E.,  Neimi,  R.O.,  1969.   Heat  Transfer  and  Hy-draulics:  the  Effects  of  Subcooled  Voids.  Final  Report,  February  1967–June 1969.  Technical Report NYO-3679-8; EURAEC-2120. General Elec-tric  Co.,  Schenectady,  NY  Research  and  Development  Center;  GeneralElectric  Co.,  San  Jose,  Calif.  Atomic  Power  Equipment  Dept.    URL:https://www.osti.gov/biblio/4766327.

Staub\_TuF 
Staub,  F.W.,  Walmet,  G.E.,  Neimi,  R.O.,  1969.   Heat  Transfer  and  Hy-draulics:  the  Effects  of  Subcooled  Voids.  Final  Report,  February  1967–June 1969.  Technical Report NYO-3679-8; EURAEC-2120. General Elec-tric  Co.,  Schenectady,  NY  Research  and  Development  Center;  GeneralElectric  Co.,  San  Jose,  Calif.  Atomic  Power  Equipment  Dept.    URL:https://www.osti.gov/biblio/4766327.

Staub\_TuW 
Staub,  F.W.,  Walmet,  G.E.,  Neimi,  R.O.,  1969.   Heat  Transfer  and  Hy-draulics:  the  Effects  of  Subcooled  Voids.  Final  Report,  February  1967–June 1969.  Technical Report NYO-3679-8; EURAEC-2120. General Elec-tric  Co.,  Schenectady,  NY  Research  and  Development  Center;  GeneralElectric  Co.,  San  Jose,  Calif.  Atomic  Power  Equipment  Dept.    URL:https://www.osti.gov/biblio/4766327.

Martin 
Martin, R., 1969.  Mesure du taux de vide a haute pression dans un canalchauffant.   Ph.D.  thesis.  Centre  d’etudes  nucleaires  de  Grenoble.   INISRN:36002834.

Sabotinov 
Sabotinov,   L.,   1974.Experimental  investigation  of  the  void  fractionat  subcooled  boiling  for  differentheat  flux  profiles  along  the  channel.Ph.D. thesis. Moscow Power Engineering Institute, Chair “NuclearPowerPlants”,Moscow.

Sekoguchi 
Sekoguchi, K., Tanaka, O., Esaki, S., Imasaka, T., 1980.  Prediction of voidfraction in subcooled and low quality boiling regions.  Bulletin of JSME23, 1475–1482.  doi:https://doi.org/10.1299/jsme1958.23.1475.

Edelman 
Edelman, Z., Elias, E., 1981.  Void fraction distribution in low flow rate sub-cooled boiling.  Nuclear Engineering and Design 66, 375–382.  doi:https://doi.org/10.1016/0029-5493(81)90167-9.

Labuntsov 
Labuntsov, D., Lobachev, A., Kol’chugin, B., Zakharova, E., 1984. The mainprinciples of variation in vapour content of equilibrium and non-equilibriumtwophase flows in channels of different geometry. Thermal Engineering 31,506–508.

Zeitoun
Zeitoun, O.M., 1994. Subcooled flow boiling and condensation. Ph.D. thesis.McMaster University.
