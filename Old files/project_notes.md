# Final_Project

## Importing Data
Age Data Set - I merged all the years into one file and removed the following columns:
'LocationDesc', 'Class', 'Indicator', 'DataSource', 'Data_Value_Unit', 'FootnoteType', 'FootNoteSymbol', 'FootnoteText', 'URL', 'DatasourceAbbr', 'Agency'

Remaining Columns for age2_df:
ID', 'Year', 'LocationAbbr', 'Topic', 'Response',
       'Data_Value_Type', 'Data_Value', 'Data_Value_Footnote_Symbol',
       'Data_Value_Footnote', 'Low_Confidence_Limit',
       'High_Confidence_Limit', 'Sample_Size', 'Stratification',
       'StratificationType', 'IndicatorId', 'LocationOrder',
       'ParentStateDisplayOrder'

The BMI data had the same columns as the age dataset. I removed the same columns. The remaining columns for the bmi2_df are:
ID', 'Year', 'LocationAbbr', 'Topic', 'Response',
       'Data_Value_Type', 'Data_Value', 'Data_Value_Footnote_Symbol',
       'Data_Value_Footnote', 'Low_Confidence_Limit',
       'High_Confidence_Limit', 'Sample_Size', 'Stratification',
       'StratificationType', 'IndicatorId', 'LocationOrder',
       'ParentStateDisplayOrder'

For the diabetes data, same columns and I removed the same columns. The dataframe with removed columns is diabetes2_df.

For the education data, same columns removed. The dataframe with removed columns is education2_df.

For the ethnicity data, same columns removed. The dataframe with removed columns is ethnicity2_df.

For the exercise data, same columns removed. The dataframe with removed columns is exercise2_df.

For the income data, same columns removed. The dataframe with removed columns is income2_df.

For the sex data, same columns removed. The dataframe with removed columns is sex2_df.

For the tobacco data, same columns removed. The dataframe with removed columns is tobacco2_df.

For the hypertension data, same columns removed. Note that only odd years are present. The dataframe with removed columns is hypertension2_df.

For the fast food data, I need to figure out what we are going to use and how before I reduce columns. I imported the files - they are fastfoodrest_df and fastfooddata_df.

For the gym data, the gym dataframe is called gym_df. I did not reduce the columns - need to think about what to use.

## Merging all the different datasets

I merged all these df into one - merged_df since they have all the same columns.
age2_df, bmi2_df, diabetes2_df, education2_df, exercise2_df, income2_df, sex2_df, tobacco2_df, hypertension2_df

I think we will start with the the merged_df for the model and then we will learn some stuff and predict based on these factors. 

We can run a seperate correlation analysis by grouping all the merged_df data by state, and then join the gym and fast food data to than and run an analysis to see trends by state.

