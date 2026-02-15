Title: assignment_2_QSAR_data_curation
Target Name: "KRAS"
Number of bioactivity records:5760
Short description of the data curation workflow:
The workflow starts with target identification by searching the ChEMBL database for the protein of interest, KRAS. From the returned results, the most relevant target entry is selected using its unique ChEMBL target identifier.
Next, bioactivity data retrieval is performed for the selected KRAS target. The activity records are filtered to include only those with a standard activity type of IC₅₀, ensuring that all measurements represent the same pharmacological endpoint.
The filtered results are then converted into a structured dataframe for inspection. At this stage, the dataset is checked for the unique activity types and prepared for further cleaning, standardization, and downstream analysis such as descriptor calculation, modeling, or QSAR studies.
