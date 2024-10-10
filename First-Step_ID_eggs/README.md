## Inbreeding depression in egg characteristics of wild barn owls ##

Here you will find all the information and workflow for the first-step project in UNIL supervised by Anna Hewett and directed by Jerome Goudet. 

## Ideal workflow ##

1) Compile mutliple dataframes into a 'master dataframe' from which we can run the models
2) Begin with simple linear mixed models on egg width, egg length and egg weight. Play around with including just mother inbreeding coefficient or father inbreeding coefficient and then both
3) Run a Bi-/Multivariate linear mixed model where we fit all traits together in one. (depending on time)

## Useful R functions ##
- join(), inner_join(), left_join(), right_join() : 
- select() : selects the specified columns from the dataframe
- group_by() : group by a varable, useful for then creating new columns or counting instances of things

