# -wrm_reduction
A function to calculates the Percentage Weighted RMS (WRM) Reduction for a long time series data

Args:
    
    original_data: pandas column name of the original time series data
    reduced_data: pandas column name of the reduced time series data
    formal error (or standard deviation): pandas column name of the formal error for each data point
    
    Returns:
    WRM reduction: percentage of WRM reduction
