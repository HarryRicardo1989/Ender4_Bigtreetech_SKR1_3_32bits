# Ender4_Bigtreetech_SKR1_3_32bits
Configuração completa para a Adaptação da SKR1.3 na Ender4 com Display original

#define BAUDRATE 115200   
#define MOTHERBOARD BOARD_BIGTREE_SKR_V1_3
#define BED_MAXTEMP      150  

#define HEATER_0_MAXTEMP 280

//Motor Drivers Definition
#define X_DRIVER_TYPE  TMC2208  
#define Y_DRIVER_TYPE  TMC2208 
#define Z_DRIVER_TYPE  TMC2208  
#define E0_DRIVER_TYPE TMC2208 

// The size of the print bed
#define X_BED_SIZE 220  //Ricardo
#define Y_BED_SIZE 220  //Ricardo

//Leveling BED
#define PROBE_MANUALLY
#define MESH_BED_LEVELING

// Preheat Constants
#define PREHEAT_1_LABEL       "PETG"
#define PREHEAT_1_TEMP_HOTEND 240   
#define PREHEAT_1_TEMP_BED     60   
#define PREHEAT_1_FAN_SPEED     0 

#define PREHEAT_2_LABEL       "ABS"
#define PREHEAT_2_TEMP_HOTEND 230  
#define PREHEAT_2_TEMP_BED    115  
#define PREHEAT_2_FAN_SPEED     0 

//Language Config
#define LCD_LANGUAGE pt_br

//Display Config
#define REPRAP_DISCOUNT_SMART_CONTROLLER
