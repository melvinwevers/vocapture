# VOCapture 


Explore to what extent we can use capture / recapture models to determine how many VOC contracts were observed. 

- Are there biases related to rank, time, place? 

## Variable description

|Variable | Description |
|---------|-------------|
|vocop_id |unique record id | 
|place_standardized | standardized place of origin |
|disambiguated person | 0 = no, 1 = yes |
|person_cluster_id | unique cluster for records belonging to same person |
|person_cluster_row | which voyage in cluster of records belonging to same person |
|parent_rank | aggregated rank category |
|rank | rank as indicated on record |
|wage | median wage for parent rank |
|date_begin_contract | date indicating when contract started |
|reason_end_contract | why did person end career |
|could_muster_again | boolean indicating whether person could travel again | 
|outward_voyage_id | id indicating on which ship one travelled |

