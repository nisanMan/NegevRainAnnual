<div style="font-family: Arial; font-size: 12px; line-height: 1.4; max-width: 800px; margin: auto; position: relative;">

  <div style="text-align: right; position: absolute; top: 10px; right: 10px;">
    <a href="https://ims.gov.il/en" target="_blank" rel="noreferrer" title="ims">
      <img src="https://ims.gov.il/themes/imst/ims/images/logo.jpg" alt="ims" width="40" height="40"/>
    </a>
  </div>

  <div style="font-family: Arial; font-size: 12px; line-height: 1.4; max-width: 800px; margin: auto;">

    <p style="font-weight: bold; font-size: 13px; margin-bottom: 12px;">
      This is a data presentation project based on rainfall analysis using Python and Jupyter Notebook.
    </p>

    <h2 style="font-size: 16px; margin-bottom: 8px;">🌧️ Explore Annual Rainfall Patterns in Southern Israel</h2>

    <h3 style="font-size: 14px; margin-top: 16px;">🔍 Overview</h3>
    <p>
      This project explores the annual rainfall patterns across twenty-six meteorological stations in Southern Israel,
      utilizing data from the
      <a href="https://ims.gov.il/he/data_gov" target="_blank">Israel Meteorological Service (IMS)</a>.
      The data was analyzed using Python and various libraries for statistical analysis and data visualization.
    </p>

    <h3 style="font-size: 14px; margin-top: 16px;">📊 Data and Web API</h3>
    <p>
      The project leverages rainfall data which can be explored through the provided Jupyter Notebook.
      You can also access the data and findings via the
      <a href="https://ims.gov.il/he/ObservationDataAPI" target="_blank">Web API</a>,
      but you will need a valid token to access it.
    </p>

    <h3 style="font-size: 14px; margin-top: 16px;">💬 Discussion</h3>
    <p>
      Analyzing rainfall data proves challenging when relying on a single trendline due to substantial correlation within the dataset.
      The data does not fit neatly into a linear trend, and different subsets of years lead to varying slopes in trendlines.
      This is visually demonstrated, as selecting different ranges of years can show either a positive or negative slope.
    </p>
    <p>
      This study challenges the assumption that rainfall patterns are solely influenced by the time period chosen for measurements.
      By calculating all possible trendlines, the project captures the respective slopes over different time periods,
      allowing for a more comprehensive analysis.
      The heatmaps presented in the project visually represent these fluctuating slopes,
      revealing that rainfall amounts in southern Israel have generally declined over time.
    </p>
    <p>
      While examining a 70-year span, the slope of the trendline varies significantly,
      but by focusing on periods of at least 10 years, a consistent downward trend emerges,
      marked by a predominant red hue, particularly in the upper corner.
      This suggests a clear and ongoing decrease in rainfall over time. 
    </p>

    <a style="font-size: 14px; margin-top: 16px;" href="https://public.tableau.com/shared/GN7J29MRK?:display_count=n&:origin=viz_share_link" target="_blank">
      📈 Tableau 📉
    </a>

  </div>
</div>

