<img width="1920" height="1046" alt="Pasted image 20261013004957" src="https://github.com/user-attachments/assets/8ed46e6b-cef2-4a9f-a3b9-0f5487fd3d19" /># MIDI-Keypad
And then your actual MIDI keys will use capacitive touch which just uses exposed copper on the PCB which uses the electrical field from your body to detect presses!
We'll be using these core components, and you should use any amount and combination of them for your design:

EC11 Rotary Encoders
SK6812 MINI-E Neopixels
Bourns Slide Potentiometers
Kailh Choc Low-Profile Switches
<img width="1920" height="1046" alt="Pasted image 20261013004957" src="https://github.com/user-attachments/assets/4c9423cc-dc6d-4945-a496-77675e30f6cd" />
KiCad has tens of thousands of parts for you to use in the editor, but they're still missing a couple which we'll need to install. 
<img width="1085" height="676" alt="Pasted image 20261013020548" src="https://github.com/user-attachments/assets/6c8d3e7a-ee88-4d98-8856-de962aada749" />
I make it very cute!!!
<img width="785" height="661" alt="image" src="https://github.com/user-attachments/assets/3d73c690-9d78-495d-af1b-8b8371670680" />
<img width="1053" height="634" alt="image" src="https://github.com/user-attachments/assets/6edd56f2-c69d-4c82-a38e-4c985b623d2d" />
<img width="1920" height="1048" alt="Pasted image 20261010201242" src="https://github.com/user-attachments/assets/d6ea2f57-ce20-4599-96ea-2a5adb569a44" />
Make it look like a piano 
D1, D2, D3	LED_SK6812MINI-E_3.2x2.8mm_P1.5mm_ReverseMount	3	SK6812MINI-E	$3.36	https://www.aliexpress.us/item/3256807677321116.html?spm=a2g0o.productlist.main.7.607a1c3clvX5x9&algo_pvid=bee2faba-4c6b-4fa4-89c4-5ca66e556568&algo_exp_id=bee2faba-4c6b-4fa4-89c4-5ca66e556568-6&pdp_ext_f=%7B%22order%22%3A%22643%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21CAD%215.30%214.88%21%21%213.65%213.36%21%402101e81117919481938394582e0f6e%2112000042594617264%21sea%21US%213725344934%21X%211%210%21n_tag%3A-29919%3Bd%3Ae2161723%3Bm03_new_user%3A-29895%3BpisId%3A5000000219770668&curPageLogUid=ehnx03TU7wEm&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005007863635868%7C_p_origin_prod%3A
J1	Capacitive Keys	1	Capacitive Touch Buttons		
RV1, RV2	Potentiometer_Bourns_PTA1543_Single_Slide	2	Slider	$3.16	https://www.digikey.com/en/products/detail/bourns-inc/PTA1543-2010CIB103/3781161
SW1, SW2, SW3	Kailh Choc Low-Profile Switches	3	SW_Push	$6.04	https://www.aliexpress.com/item/1005008883418065.html?spm=a2g0o.productlist.main.1.13d14a7e068OmL&algo_pvid=4e5fe6cd-3562-4ef4-ac3e-085a2d4634fe&algo_exp_id=4e5fe6cd-3562-4ef4-ac3e-085a2d4634fe-0&pdp_ext_f=%7B%22order%22%3A%221475%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21CAD%2111.40%212.38%21%21%217.81%211.63%21%402103128917919263557114360e0ebd%2112000047082945007%21sea%21CA%210%21ABX%211%210%21n_tag%3A-29910%3Bd%3A778dde27%3Bm03_new_user%3A-29895%3BpisId%3A5000000218640848&curPageLogUid=CXjsh9TOCyFt&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005008883418065%7C_p_origin_prod%3A
SW4	RotaryEncoder_Alps_EC11E-Switch_Vertical_H20mm	1	RotaryEncoder_Switch_MP	$1.44	https://www.aliexpress.us/item/3256807457768762.html?spm=a2g0o.productlist.main.1.52d22c6as0ZCnv&algo_pvid=9965a6c7-9d4c-44f9-a2d4-a43aa1b0ae45&algo_exp_id=9965a6c7-9d4c-44f9-a2d4-a43aa1b0ae45-0&pdp_ext_f=%7B%22order%22%3A%224739%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&pdp_npi=6%40dis%21USD%211.52%211.40%21%21%211.52%211.40%21%402101e7a317919489056767943e0e88%2112000041630839409%21sea%21US%213725344934%21X%211%210%21n_tag%3A-29919%3Bd%3A1bb91aa6%3Bm03_new_user%3A-29895%3BpisId%3A5000000219770668&curPageLogUid=AOe3dpbqRVrY&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005007644083514%7C_p_origin_prod%3A
U1	Waveshare ESP32-S3-Zero	1	Waveshare ESP32-S3-ZERO	$6.62	https://www.aliexpress.com/item/1005007004089798.html?src=google&gatewayAdapt=4itemAdapt
Total Aliexpress:	$19.59	
Total Digikey:	$12.35	
Total JLCPCB:	$12.29	
Total:	$44.23	
