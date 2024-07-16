# SEAFLOW (SEAsonal FLOW forecasts toolbox)

Over the last decade, numerical weather prediction systems have improved their forecasting performance at longer lead times, ranging from 1 to several months ahead (Bauer et al., 2015; Alley et al., 2019). The water management sector may benefit considerably from these advances. 

To increase relevance for water resource management, <b>seasonal meteorological forecasts can be translated into Seasonal Flow Forecasts (SFFs) via a hydrological model.</b> SFFs can be provided and evaluated at different temporal and spatial resolutions: a coarser resolution, e.g., magnitude of total next-month runoff over a certain region (Prudhomme et al., 2017; Arnal et al., 2018) or a finer resolution, e.g., daily/weekly flow at a particular river section over the next month (Crochemore et al., 2016; Lucatero et al., 2018). 

<b>This toolbox is designed to simulate SFFs and Ensemble Streamflow Prediction (ESP).</b> The necessary data for simulating SFFs can be obtained from <b>SEAFORM (SEAsonal FORcasts Management toolbox, https://github.com/uobwatergroup/seaform)</b>. For hydrological modeling, <b>this toolbox uses the conceptual Tank model</b> developed by Sugawara in Japan in 1961 (Sugawara et al., 1986, 1995). This model is widely applied in many countries, including South Korea (Ou et al., 2017; Goodarzi et al., 2020).

Using this toolbox, you can <b>automatically calibrate and validate the model</b>, then <b>generate flow ensembles of ESP and SFFs</b>. Additionally, it allows for <b>assessing the skill of SFFs</b> benchmarked against ESP and <b>visualizing the results</b>.

<img src="util/images/SEAFLOW_module.jpg" width="1050" height="1000">


Let's get started by downloading all the Jupyter Notebook files and folders (including util, assessment folders)

If you find any errors or any comments on this tool, <b>please email me(ocean47ys@gmail.com).</b>
