# Data Analytics and Preprocessing - Kepler Exoplanet Dataset

This project is part of our college presentation on **"Data Analytics and Preprocessing"**, where we explore and process the **Kepler Exoplanet Dataset** to gain insights into exoplanets — planets outside our solar system.

---

## 📊 Objective

Our aim is to demonstrate how real-world datasets are preprocessed for analysis and modeling. We used the Kepler dataset as it represents authentic scientific data and challenges like missing values, domain-specific jargon, and noisy entries.

---

## 🌌 About the Dataset

The **Kepler Mission** by NASA was designed to find Earth-like planets orbiting other stars. The dataset includes information about thousands of stars and planetary candidates discovered by the Kepler telescope.

We have **renamed the original columns** to make them more descriptive. Below is a table explaining each column in plain English.

---

## 🗂️ Column Descriptions

| Column Name                          | Description |
|--------------------------------------|-------------|
| `KOIName`                            | Unique ID for the Kepler Object of Interest (planet candidate). |
| `KeplerName`                         | Official Kepler name for confirmed planets. |
| `Exoplanet_Archive_Disposition`     | Final status: Confirmed, Candidate, or False Positive. |
| `Disposition_Using_KeplerData`      | Preliminary status based on Kepler data analysis. |
| `DispositionScore`                  | Confidence score (0 to 1) for the planet's classification. |
| `NotTransit_LikeFPFlag`             | Flag indicating if it’s a non-transit false positive. |
| `StellarEclipse_FP_Flag`            | Flag for eclipsing binary stars misclassified as planets. |
| `CentroidOffsetFPFlag`              | Flag for false positives due to offset in light centroid. |
| `EphemerisMatchIndicatesContaminationFPFlag` | Flag indicating contamination from another star with similar timing. |
| `OrbitalPeriod_days`                | Number of days the planet takes to orbit its star. |
| `OrbitalPeriodUpper_days`           | Upper error bound for orbital period. |
| `OrbitalPeriodLower_days`           | Lower error bound for orbital period. |
| `TransitEpoch_BKJD`                 | Time of the first observed transit (in BKJD - Barycentric Kepler Julian Date). |
| `TransitEpoch_Lower`                | Lower error bound for transit epoch. |
| `TransitEpoch_Upper`                | Upper error bound for transit epoch. |
| `ImpactParamete`                    | Measures how centrally the planet crosses the star (0=center, 1=edge). |
| `ImpactParameter_Lower`            | Lower error bound for impact parameter. |
| `ImpactParameter_Upper`            | Upper error bound for impact parameter. |
| `TransitDuration_hrs`              | How long the transit lasts (in hours). |
| `TransitDuration_Lower`            | Lower error bound for transit duration. |
| `TransitDuration_Upper`            | Upper error bound for transit duration. |
| `TransitDepth_ppm`                 | Brightness dip during the transit, in parts per million. |
| `TransitDepth_Lower`               | Lower error bound for transit depth. |
| `TransitDepth_Upper`               | Upper error bound for transit depth. |
| `PlanetaryRadius_Earthradii`       | Estimated radius of the planet in Earth radii. |
| `PlanetaryRadius_Lower`            | Lower error bound for planetary radius. |
| `PlanetaryRadius_Upper`            | Upper error bound for planetary radius. |
| `EquilibriumTemperature_K`         | Estimated surface temperature of the planet (in Kelvin). |
| `EquilibriumTemperature_Lower`     | Lower error bound for equilibrium temperature. |
| `EquilibriumTemperature_Upper`     | Upper error bound for equilibrium temperature. |
| `InsolationFlux_Earthflux`         | Stellar energy the planet receives, relative to Earth. |
| `InsolationFlux_Lower`             | Lower error bound for insolation flux. |
| `InsolationFlux_Upper`             | Upper error bound for insolation flux. |
| `TransitSignal_to_Noise`           | Signal-to-noise ratio for the transit detection. |
| `TCE_PlanetNumber`                 | Planet candidate number in the system. |
| `TCE_DeliverName`                  | Internal name for the Kepler data delivery used. |
| `StellarEffectiveTemperature_K`    | Estimated surface temperature of the host star (in Kelvin). |
| `StellarEffectiveTemp_Lower`       | Lower error bound for stellar temperature. |
| `StellarEffectiveTemp_Upper`       | Upper error bound for stellar temperature. |
| `StellarSurfaceGravity`            | Gravity at the star’s surface (logarithmic scale). |
| `Stellar_SurfaceGravity_Lower`     | Lower error bound for surface gravity. |
| `Stellar_SurfaceGravity_Upper`     | Upper error bound for surface gravity. |
| `StellarRadius_Solarradii`         | Radius of the star in terms of Sun’s radius. |
| `StellarRadius_Lower`              | Lower error bound for stellar radius. |
| `StellarRadius_Upper`              | Upper error bound for stellar radius. |
| `RA_deg`                            | Right Ascension – horizontal position of the star (like longitude). |
| `Dec_deg`                           | Declination – vertical position of the star (like latitude). |
| `Kepler_band[mag]`                 | Brightness of the star measured in Kepler’s photometric band. |

---

## 🛠️ Tools Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook
- Scikit-learn (for scaling/encoding)
- CSV format (dataset)

---

## 📌 Key Learning Outcomes

- Cleaned and prepared a scientific dataset for analysis.
- Learned how to interpret domain-specific columns using documentation and metadata.
- Performed feature engineering for further modeling and predictions.

---

## 🔗 References

- [NASA Kepler Mission](https://www.nasa.gov/mission_pages/kepler/overview/index.html)
- [Exoplanet Archive Documentation](https://exoplanetarchive.ipac.caltech.edu/)
- [Kepler Data Column Definitions](https://exoplanetarchive.ipac.caltech.edu/docs/API_kepcandidate_columns.html)

---

## 🙌 Acknowledgments

Thanks to NASA and the Exoplanet Archive team for publicly sharing this dataset and to our college faculty for the opportunity to work on this fascinating topic.

---

*Prepared as part of our academic presentation on "Data Analytics and Preprocessing".*
