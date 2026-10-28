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



        Designator        Footprint                                             Quantity              Value                              Total Cost          Part
        
        D1, D2, D3        LED_SK6812MINI-E_3.2x2.8mm_P1.5mm_ReverseMount            3              SK6812MINI-E                              $3.36	    https://www.aliexpress.us/item/3256807677321116.html?
        J1                Capacitive Keys                                           1              Capacitive Touch Buttons                  $3.33          https://www.amazon.com/MPR121-Capacitive-Buttons-Sensitive-
        RV1, RV2          Potentiometer_Bourns_PTA1543_Single_Slide	            2              Slider                                    $3.16          https://www.digikey.com/en/products/detail/bourns-inc/PTA1543-2010CIB103/3781161
       SW1, SW2, SW3     Kailh Choc Low-Profile Switches                            3              SW_Push                                   $6.04          https://www.aliexpress.com/item/1005008883418065.html?
       SW4               RotaryEncoder_Alps_EC11E-Switch_Vertical_H20mm	            1              RotaryEncoder_Switch_MP                   $1.44          https://www.aliexpress.us/item/3256807457768762.html?
        U1                Waveshare ESP32-S3-Zero                                   1              Waveshare ESP32-S3-ZERO                   $6.62          https://www.aliexpress.com/item/1005007004089798.html?src=google&gatewayAdapt=4itemAdapt

                                                                                                    Total Aliexpress:                         $19.59	   
                                                                                                    Total Digikey:	                       $12.35	
                                                                                                    Total JLCPCB:	                          $12.29	
                                                                                                    Total:                                  	$44.23
