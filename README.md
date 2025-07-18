# Optimize_Opentron-Win-edit-



#### GUIDELINES 
1. To pipet liquid inside liquid in flat bottom (BCA) or conical bottom (PCR), the z must be set between 0 - 0.3
   - p50_multi.distribute(5,
                        temp_adapter[tube],
                        [plate2[i].bottom(z=0.1) for i in destination_wells],
                        rate = speed,
                        mix_before=(1, 10),
                        disposal_vol=5)  # Distributing to three consecutive columns
3. waw 
