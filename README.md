# Lifeline and Emergency Broadband Benefit Participation

This repository contains data from our story, "[Millions of Prequalified Households Are Missing Out on a Crucial Internet Benefit]()."

## Data

`ebb-lifeline.csv` contains recent Emergency Broadband Benefit and Lifeline enrollment counts for all 50 states, Puerto Rico, Washington, D.C., and the U.S. as a whole. Data is presorted by `EBB div Lifeline`, with `USA` data at the bottom.

Data in the file is arranged as follows:

| **Column** | **Description** |
|------------|-----------------|
| **`Location`** | The name of the location. |
| **`Lifeline Subscribers (as of July 2021)`** | The number of Lifeline participants in the location, as outlined on USAC's [Lifeline "Program Data"](https://www.usac.org/lifeline/resources/program-data/) page. |
| **`EBB Participants (as of Aug. 26, 2021)`** | The number of EBB participants in the location, as outlined on USAC's [Emergency Broadband Benefit Program Enrollments and Claims Tracker](https://www.usac.org/about/emergency-broadband-benefit-program/emergency-broadband-benefit-program-enrollments-and-claims-tracker/) page. These counts were pulled from the page on Aug. 26, 2021 (see the [archived version](https://archive.is/lXTNA) of the page from that time.) |
| **`Estimated number of prequalified households that aren't enrolled`** | `Lifeline Subscribers (as of July 2021)` minus `EBB Participants (as of Aug. 26, 2021)`|
| **`EBB div Lifeline`** | `EBB Participants (as of Aug. 26, 2021)` divided by `Lifeline Subscribers (as of July 2021)`. |
