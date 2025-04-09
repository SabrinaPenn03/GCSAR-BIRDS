# GCSAR-BIRDS
Ebirds |>
  group_by(UNITID) |>
  summarise(species_count = n_distinct(SCIENTIFIC.NAME)) #should count the number of species for each UNITID
