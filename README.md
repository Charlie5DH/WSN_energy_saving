# WSN_energy_saving
Energy saving methods for WSNs.

## Data

In `Data/` is the data from the module used for making predictions.  There are 3 `.csv` files.

- 34.B2.9F.A9.csv contains the entire data from the module.
- Mod_5Min_resampled.csv is the same data resampled to 5 Minutes using the mean.
- Resampled_Shorted.csv is the data resampled to 5 Minutes using the mean, from 2018-10-01 to 2019-05-01, which was the period used in the paper. See next image.

![](D:\Repositories\WSN_energy_saving\Images\Measures_from_sensors.png)

If you want to use a different date range or sampling frequency, use the `34.B2.9F.A9.csv`. 

Otherwise just use `Resampled_Shorted.csv`, which is the same data we used in the paper.