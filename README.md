# Discreete Dual Output DC Power Supply
This is a Custom Designed dual output DC power supply that provides 12V and 5V outputs.

## Working
The circuit takes AC input from Wall Socket and steps it down to 12V then this AC voltage is rectified be 1N4007 Diodes. This 12V DC voltage then goes to a capacitor which decreases the noise and the voltage goes to about 17V. then this voltage is passed through capacitors and zener diodes to provide the 12V and 5V outputs.

## Simulation
This Project is Simulated and Tested in Multisim. It worked fine there and supplied constant voltage under Load.



## PCB and Connections
I designed a Custom PCB for this project.

|Schematics|Tracks|
| :---: | :---: |
| ![schemetics](/Images/Schematics.JPG) | ![Tracks](/Images/pcb.JPG) |

## BOM

| Name | Purpose | Quantity | Total Cost (USD) | Link | Distributor |
| :---: | :---: | :---: | :---: | :---: | :---: |
| Transperency sheets | Printing PCB design | 1 | 8 | [Transperency sheets](https://stationers.pk/products/transparency-sheets?srsltid=AfmBOoo0qg_GjBXsgpL0SoCESp01tAI8nJvPUPbaVxZx4DztRgOZabL1) | Stationers |
| Copper Clad Board | Making PCB | 1 | 7 | [Copper Clad Board](https://epro.pk/product/double-sided-pcb-12x12-in-pakistan/) | Epro |
| Capacitors | Reducing Noise | 3 | 10 |  | AliExpress |
| Resistor | Resistance | 4 | 8 | [Resistor](https://www.aliexpress.com/item/1005006898731441.html?spm=a2g0o.productlist.main.2.5adb174e6BrR4E&algo_pvid=a8b488c6-4e8d-4539-8e68-136df8322c2e&algo_exp_id=a8b488c6-4e8d-4539-8e68-136df8322c2e-1&pdp_ext_f=%7B%22order%22%3A%2218454%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21PKR%21700.27%21540.04%21%21%2115.19%2111.71%21%40213ba0c517805536286016955e1c85%2112000038655131992%21sea%21PK%212961473668%21X%211%210%21n_tag%3A-29919%3Bd%3A7347b7cd%3Bm03_new_user%3A-29895%3BpisId%3A5000000208499468&curPageLogUid=xK5nH0KMlH7Z&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005006898731441%7C_p_origin_prod%3A) | AliExpress |
| 12v Transformer | Stepping Down 220V to 12V | 1 | 7 | [12v Transformer](https://www.aliexpress.com/item/1005002190993881.html?spm=a2g0o.productlist.main.3.5ab7c57cYfLk9E&algo_pvid=73899792-524f-4ba5-b0be-0d52e075c67c&algo_exp_id=73899792-524f-4ba5-b0be-0d52e075c67c-2&pdp_ext_f=%7B%22order%22%3A%2269%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21PKR%212058.51%211933.56%21%21%216.59%216.19%21%40212e520d17805533749515631efcd4%2112000019002828064%21sea%21PK%212961473668%21X%211%210%21n_tag%3A-29919%3Bd%3A7347b7cd%3Bm03_new_user%3A-29895&curPageLogUid=AV8pa8Zxzb4a&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005002190993881%7C_p_origin_prod%3A) | AliExpress |
| 1n5407 | Diode | 1 | 5.9 | [1n5407](https://www.aliexpress.com/item/1005005485365222.html?spm=a2g0o.productlist.main.1.368665a2Kra7P6&algo_pvid=32606de9-9aea-4d42-ae9b-a578256993a0&algo_exp_id=32606de9-9aea-4d42-ae9b-a578256993a0-0&pdp_ext_f=%7B%22order%22%3A%2254%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21PKR%211917.94%211568.09%21%21%216.14%215.02%21%402151e6dc17805527475088759e359e%2112000033269855528%21sea%21PK%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A7347b7cd%3Bm03_new_user%3A-29895%3BpisId%3A5000000203713833&curPageLogUid=w31Z33jQx7jN&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005005485365222%7C_p_origin_prod%3A) | AliExpress |
| Diode | Rectifier | 1 | 3.6 | [Diode](https://www.aliexpress.com/item/1005012369097375.html?spm=a2g0o.productlist.main.3.e8886f76qmjBun&algo_pvid=c9794048-4184-407d-bd0b-0edbe400970a&algo_exp_id=c9794048-4184-407d-bd0b-0edbe400970a-2&pdp_ext_f=%7B%22order%22%3A%221%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21PKR%213746.13%211045.14%21%21%2181.26%2122.67%21%40212a70c017805519689011413e223e%2112000058193885987%21sea%21PK%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A7347b7cd%3Bm03_new_user%3A-29895%3BpisId%3A5000000208221885&curPageLogUid=psqZq8pejmBE&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005012369097375%7C_p_origin_prod%3A) | AliExpress |
