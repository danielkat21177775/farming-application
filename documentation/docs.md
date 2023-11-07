#


* [ ] **dfdfdf**




The following small block of code represents what we will do:


The code  block below indicates what we will do: 

```
# First let's create the stok_id; stok_nommer columns of the blok inligting dataset;

stok_id = 1:sum(blok_rye_dat$Vines)

message("This is how much vines we have on the farm")

length(stok_id)



stok_nommer = list()

for(i in 1:nrow(blok_rye_dat)){

stok_nommer[[i]] = rep(times = blok_rye_dat$Vines[i] /  blok_rye_dat$vines_per_vak[i] , 1:blok_rye_dat$vines_per_vak[i])

}


stok_nommer = unlist(stok_nommer, use.names = FALSE)   # unlisting vector
```
