# Banxi_Paleomagnetism

Repository for the data and code associated with:

Park, Y., Swanson-Hysell, N. L., Xian, H., Zhang, S., Condon, D. J., Fu, H., and Macdonald, F. A., in review, Tonian paleomagnetism from South China permits an inclusive Rodinia or Bitter Springs Stage true polar wander, but not both.

Any questions regarding the code, data, or paper can be directed to yuempark@berkeley.edu.

**Note regarding nomenclature:**

During the development phase of these analyses, the name we were assigning to the Xiajiang Group changed from 'the Banxi Group' to 'the Xiajiang Group'. Although the use of these terms varies in the literature (see published article), for the purposes of the code within this notebook they refer to the same set of pre-Sturtian Neoproterozoic strata in the Guizhou province of South China.

Each subdirectory contains the data and code associated with the name of the folder. The two Jupyter notebooks (running Python kernels) that contain the code that is most central to this study are:

* `./Paleomagnetism/Banxi_site_analysis.ipynb`
    * This notebook develops the new paleomagnetic pole for the Xiajiang Group.
* `./Compilations/Code/APWP_Analysis.ipynb`
    * This notebook compiles Tonian paleomagnetic poles from South China and other nearby cratons to assess various paleogeographic models.

Euler rotations for two plausible Tonian paleogeographic models presented in this study can be found here:

* `./Compilations/GPlates/running_mean.rot`
    * Paleogeographic model that does not incorporate hypothesized Bitter Springs Stage true polar wander, and uses running mean poles to reconstruct the location of South China.
* `./Compilations/GPlates/SChina_nexus.rot`
    * Paleogeographic model that does incorporate hypothesized Bitter Springs Stage true polar wander. This model uses all available poles to reconstruct the location of South China and Rodinia.
