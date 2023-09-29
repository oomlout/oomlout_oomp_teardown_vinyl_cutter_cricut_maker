# Oomp Teardown Vinyl Cutter Cricut Maker
Oomp Teardown Vinyl Cutter Cricut Maker
disassembly youtube  
https://www.youtube.com/watch?v=wyUi8AG-vfo  
https://www.youtube.com/watch?v=6P9s3b0ZLs0
https://www.youtube.com/watch?v=LtGMsMsjEp4
https://www.youtube.com/watch?v=SUNwsj4OF90&t=1s
  
# disassembly

## step: 1 assembled
[![assembled](images/disassembly_1_300.jpg)](images/disassembly_1.jpg)  
before starting

## step: 2 assembled and open
[![assembled and open](images/disassembly_2_300.jpg)](images/disassembly_2.jpg)  
assembled and open

## step: 3 underneath
[![underneath](images/disassembly_3_300.jpg)](images/disassembly_3.jpg)  
remove the four screws under the non slip pads (leave  the other screws)

## step: 4 remove the vanity plate cover
[![remove the vanity plate cover](images/disassembly_4_300.jpg)](images/disassembly_4.jpg)  
remove the top vanity plate cover. it is hot glued down at the top corner (notice broken pice), needs some convincing to come off. Then remove four torx screws

## step: 5 remove the hidden screws
[![remove the hidden screws](images/disassembly_5_300.jpg)](images/disassembly_5.jpg)  
remove the seven hidden screws, need a short screwdriver

## step: 6 remove the top cover
[![remove the top cover](images/disassembly_6_300.jpg)](images/disassembly_6.jpg)  
remove the top cover. careful with the cable connecting the control panel

## step: 7 remove the mechanism
[![remove the mechanism](images/disassembly_7_300.jpg)](images/disassembly_7.jpg)  
remove the six screws attaching the mechanism to the base. remove the ribbon cable for the moving part

# pcb

## front
[![front](images/pcb_1_front_300.jpg)](images/pcb_1_front.jpg)  


# parts_table
| designator | designator_image | oomp_id | note | link | 
| --- | --- | --- | --- | --- | 
| motor1 | [![motor1](images/part_motor1_140.jpg)](images/part_motor1.jpg)  |  | y axis, roller paper forward and back |  | 
| motor2 | [![motor2](images/part_motor2_140.jpg)](images/part_motor2.jpg)  |  | x axis, knife head across |  | 
| u100 | [![u100](images/part_u100_140.jpg)](images/part_u100.jpg)  | [electronic_ic_tqfp_100_mcu_pic32_microchip_pic32mk1024gpk100](https://github.com/oomlout/oomlout_oomp_part_src/tree/main/parts/electronic_ic_tqfp_100_mcu_pic32_microchip_pic32mk1024gpk100/working)<br><br> | mcu, <br>custom labeled pic? <br>100 pin tqfp 12x12 0.4 mm pitch <br>footprint kicad_package_qfp_tqfp_100_12x12mm_p0_4mm<br>symbol kicad_mcu_microchip_pic32_pic32mk1024gpd100_xpt |  | 
| p200 | [![p200](images/part_p200_140.jpg)](images/part_p200.jpg)  | [electronic_header_2_5_mm_jst_xh_8_pin_through_hole](https://github.com/oomlout/oomlout_oomp_part_src/tree/main/parts/electronic_header_2_5_mm_jst_xh_8_pin_through_hole/working)<br><br> | jst xh 8 pin connector  <br>For optical encoders |  | 
| p600 | [![p600](images/part_p600_140.jpg)](images/part_p600.jpg)  | [electronic_header_2_5_mm_jst_xh_6_pin_through_hole](https://github.com/oomlout/oomlout_oomp_part_src/tree/main/parts/electronic_header_2_5_mm_jst_xh_6_pin_through_hole/working)<br><br> | js xh 6 pin<br>For drive motors |  | 
| u600 | [![u600](images/part_u600_140.jpg)](images/part_u600.jpg)  |  | allegro 4954 motor driver | https://www.allegromicro.com/en/products/motor-drivers/brush-dc-motor-drivers/a4954 | 
| u601 | [![u601](images/part_u601_140.jpg)](images/part_u601.jpg)  |  | allegro a4950 motor driver | https://www.allegromicro.com/en/products/motor-drivers/brush-dc-motor-drivers/a4950 | 
| u602 | [![u602](images/part_u602_140.jpg)](images/part_u602.jpg)  |  | allegro a4950 motor driver | https://www.allegromicro.com/en/products/motor-drivers/brush-dc-motor-drivers/a4950 | 
| u1000 | [![u1000](images/part_u1000_140.jpg)](images/part_u1000.jpg)  |  | allegro a4950 motor driver | https://www.allegromicro.com/en/products/motor-drivers/brush-dc-motor-drivers/a4950 | 
