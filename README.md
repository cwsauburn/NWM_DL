# NWM_DL
A Deep Learning model to predict the Streamflow

This project contains the following underlying data : 


    •raw_data folder : It contains all the raw data required to train and predict the DL models.

    • temporal_DLModels Folder : It contains trained DL models for 0 to 30 forecast day lead data, these models were generated using the temporal representation of the data.

    • spatial_0-15 Folder : It contains trained DL models for 0 to 15 forecast day lead data, these models were generated using the spatial representation of the data.

    • spatial_15-30 Folder : It contains trained DL models for 15 to 30 forecast day lead data, these models were generated using the spatial representation of the data.

    • data_setup_scripts : It contains the scripts which were used to set up the input data to train the DL model for 0 to 30 days lead streamflow data.

    • train&predict_scripts : This folder contains Different Machine Learning scripts which were used to train the model and predict the streamflow of ungauged sites for all the 30 day lead data.

    • temporal_graph_data_scripts : It contains the script for the temporal graphs and the temporal raw data which is used to generate these graphs.

    • spatial_graph_data_scripts : It contains the script for the spatial graphs and the spatial data which is used to generate these graphs.

NOTE: Due to large size of the raw Input data, few files aren't available it can be obtained on request by contacting the authors of the paper. Primary contact: szk0139@auburn.edu.

