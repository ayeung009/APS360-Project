| Dataset | Description |
| :--- | :--- |
| ```Logic Gates Detection.v12i.coco``` | Contains the online data from the Roboflow database. The cleaning process is outlined in ```roboflow_review (4).csv``` |
| ```self_generated_data``` | Contains the data I generated myself, along with useful statistics about this data. All data is stored in ```labels.csv``` |
| ```final_merged_dataset``` | Contains the finalized dataset used for the training, testing, and validation of the models. It is the combination of the cleaned and repurposed Roboflow data and the self generated data. All data in this dataset is cleaned with no duplicates or errors. All data is stored in ```final_labels.csv``` |
