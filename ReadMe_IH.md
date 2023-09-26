ReadMe

Initial Data Clean - Used lecture material to identify and remove duplicate mouse 'g989'

Summary Statistics - used chatgpt to build out table layout as well as restructure headers. used chatgpt to look up sem() function for standard error of mean

Bar & Pie Charts - used chatgpt for autopct input. i.e. how to derive a "##.#%" output.

Quartiles, Outliers and Boxplots - used bingchat to filter for final_tumor_vol_filtered using the .isin function for target_treatment list

Quartiles, Outliers and Boxplots - heavily relied on bingchat for variable structuring and output print. Used chatgpt to build out for loop with the .loc indexing for appending the treatment_tumor_vol list.
Code line " potential_outliers = final_tumor_vol_filtered[(final_tumor_vol_filtered['Drug Regimen'] == treatment) & ((final_tumor_vol['Tumor Volume (mm3)'] < lower_bound) | (final_tumor_vol['Tumor Volume (mm3)'] > upper_bound))] " was derived from chatgpt

Line & Scatter Plots - used bingchat for structure and parameter help to build similar graph as provided

Correlation and Regression - utilized chatgpt for the correlation_coefficient workaround due to a constant ("ValueError: too many values to unpack (expected 1)"). used the following code addition: correlation_coefficient, "_" = st.pearsonr(.. . "_" helped with the ValueError.