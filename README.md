//Crosshair
cl_crosshaircolor 5;cl_crosshaircolor_r 255;cl_crosshaircolor_b 255;cl_crosshaircolor_g 0;cl_crosshairsize 0.5;
cl_crosshairgap -6;cl_crosshairthickness 1.5;cl_crosshairusealpha 1;cl_crosshairalpha 255;
cl_crosshair_drawoutline 0;cl_crosshairdot 1;cl_crosshairstyle 3

//Optimization
r_drawtracers_firstperson "0"
cl_loadout_colorweaponnames 1
cl_showfps "1"
cl_showpos "1"
cl_forcepreload "1"
cl_freezecameffects_showholiday 0
cl_disablehtmlmotd "1"
cl_bobcycle "0.98" // prefer 2 but 0.98 is enforced by ESEA/ESL
cl_bob_lower_amt "5"
cl_bobamt_lat "0.1"
cl_bobamt_vert "0.1"
cl_disablehtmlmotd "1"
viewmodel_fov 68
viewmodel_presetpos 0
viewmodel_offset_x "2.5"
viewmodel_offset_y "2"
viewmodel_offset_z "-2"

//FPS
fps_max 128
fps_max_menu 60


//Bhopping
alias bhopon "bind MWHEELDOWN +jump;bind MWHEELUP +jump;bind mouse3 bhopoff"
alias bhopoff "bind MWHEELDOWN invnext;bind MWHEELUP invprev;bind mouse3 bhopon"

//Binds
Bind "kp_minus" "toggle voice_scale 0.25 0.5 0.8 1"
Bind "kp_plus" "toggle voice_enable"
Bind "kp_uparrow" "toggle cl_righthand"
Bind "kp_end" "viewmodel_fov 68;viewmodel_offset_x 2.5;viewmodel_offset_y 2;viewmodel_offset_z -2"
Bind "kp_pgdn" "viewmodel_fov 54;viewmodel_offset_x -2;viewmodel_offset_y 2;viewmodel_offset_z .5"

//Crosshair color
alias cenable "cl_crosshaircolor_r 255; cl_crosshaircolor_g 0;cl_crosshaircolor_b 0; cl_crosshair_drawoutline 0;"
alias cdisable "cl_crosshaircolor_r 0; cl_crosshaircolor_g 255; cl_crosshaircolor_b 0; cl_crosshair_drawoutline 0;"

alias +step1 "cenable; alias +mov +step2;"
alias -step1 "cdisable; alias +mov +step1; alias -mov -step1;"

alias +step2 "alias +mov +step3; alias -mov -step2;"
alias -step2a "alias +mov +step1; alias -mov -step1; cdisable;"
alias -step2 "alias +mov +step2; alias -mov -step2a;"

alias +step3 "alias +mov donothing; alias -mov -step3;"
alias -step3a "alias +mov +step2; alias -mov -step2a;"
alias -step3 "alias +mov +step3; alias -mov -step3a;"


alias +mov +step1
alias -mov -step1

alias +fwd "+forward; +mov"
alias -fwd "-forward; -mov"
alias +bck "+back; +mov"
alias -bck "-back; -mov"
alias +lft "+moveleft; +mov"
alias -lft "-moveleft; -mov"
alias +rgt "+moveright; +mov"
alias -rgt "-moveright; -mov"

bind w "+fwd"
bind a "+lft"
bind s "+bck"
bind d "+rgt"

//Assurance
clear
echo "                                     ITERALLYNO                                                      
echo "                                   GLITERALLYNOTHI                                                    
echo "                                  NGLITERALLYNOTHIN                                                      
echo "                                  NGLITERALLYNOTHIN                                                  
echo "                                INGLITERALLYNOTHING                                                  
echo "                                 INGLITERALLYNOTHING                                                  
echo "                                 INGLITERALLYNOTHING                                                  
echo "                                 INGLITERALLYNOTHIN                                 L                
echo "                            YNOT  NGLITERALLYNOT       E                            L                
echo "                         ALLYNOTHINGLITERALLYNOTH     TER                           L                
echo "                        RALLYNOTHINGLITERALLYNOTHINGLITERALLYNOTHINGLITERALLYNOTHINGLIT              
echo "                       ERALLYNOTHINGLITERALLYNOTHINGLITERALLYNOTHINGLITERALLYNOTHINGLITERALLYNOTHING  
echo "                      TERALLYNOTHINGLITERALLYNOTHINGLITERALLYNOTHINGLITERALLYNOTHIN           O      
echo "                     ITERALLYNOTHINGLITERALLYNOTHINGLITERALLYNOTHINGLITE                              
echo "                     ITERALLYNOTHINGLITERALLYNOTHINGLITERALLY  THINGLIT                              
echo "                     ITERALLYNOTHINGLITERALLYNOTHINGLITERALLY  THINGL                                
echo "                    LITERALLYNOTHINGLITERALLYNOTHINGLITERAL   OTHING                                  
echo "                    LITERALLYNOTHINGLITERALLYNOTHINGLITERAL  NOTHINGL                                
echo "                    LITERALLYNOTHINGLITERALLYNOTHINGLITERALLYNOTHINGL                                
echo "                    LITERALLYNOTHINGLITERALLYNOTHINGLITERALLYNOTHINGL                                
echo "                     ITERALLYNOTHINGLITERALLYNOTHINGLITERALLYNOTHIN                                  
echo "                HINGLITERALLYNOTHINGLITERALLYNOTHINGLITERALLYNOTHIN                                  
echo "                HINGLITERALLYNOTHINGLITERALLYNOTHINGLITERALLYNOTHIN                                  
echo "               THINGLITERALLYNOTHINGLITERALLYNOTHINGLITERALLYNOTHI                                    
echo "               THINGLITERALLYNOTHINGLITERALLYNOT    LITERALLYNOTH                                    
echo "               THINGLITERALLYNOTHINGLITERALLYNOTH      ERALLYNO                                      
echo "               THINGLITERALLYNOTHINGLITERALLYNOTHIN                                                  
echo "               THINGLITERALLYNOTHINGLITERALLYNOTHIN                                                  
echo "              OTHINGLITERALLYNOTHINGLITERALLYNOTHIN                                                  
echo "              OTHINGLITERALLYNOTHINGLITERALLYNOTHIN                                                  
echo "                 INGLITERALLYNOTHINGLITERALLYNOTHIN                                                  
echo "                HINGLITERALLYNOTHINGLITERALLYNOTHIN                                                  
echo "                HINGLITERALLYNOTHINGLITERALLYNOTHI                                                    
echo "                HINGLITERALLYNOTHINGLITERALLYNOTHI                                                    
echo "                HINGLITERALLYNOTHINGLITERALLYNOTHI                                                    
echo "                HINGLITERALLYNOTHINGLITERALLYNOTH                                                    
echo "                HINGLITERALLYNOTHINGLITERALLYNO                                                      
echo "                HINGLITERALLYNOTHINGLITERALLYNO                                                      
echo "                 INGLITERALLYNOTHINGLITERALLYNO                                                      
echo "               THINGLITERALLYNOTHINGLITERALLYNO                                                      
echo "               THINGLITERALLYNOTHINGLITERALLYNOT                                                      
echo "               THINGLITERALLYNOTHINGLITERALLYNOTH                                                    
echo "               THINGLITERALLYNOTHINGLITERALLYNOTHI                                                    
echo "               THINGLITERALLYNOTHINGLITERALLYNOTHING                                                  
echo "               THINGLITERALLYNOTHINGLITERALLYNOTHING                                                  
echo "                HINGLITERALLYNOTHINGLITERALLYNOTHINGL                                                
echo "               THINGLITERALLYNO  INGLITERALLYNOTHINGLI                                                
echo "               THINGLITERALLYN      LITERALLYNOTHINGLI                                                
echo "               THINGLITERALLY        ITERALLYNOTHINGLIT                                              
echo "               THINGLITERALL          TERALLYNOTHINGLIT                                              
echo "              OTHINGLITERALL           ERALLYNOTHINGLITE                                              
echo "              OTHINGLITERAL             RALLYNOTHINGLITER                                            
echo "              OTHINGLITERAL              ALLYNOTHINGLITERA                                            
echo "              OTHINGLITERA                LLYNOTHINGLITERA                                            
echo "              OTHINGLITERA                     THINGLITERA                                            
echo "             NOTHINGLITE                       THINGLITERA                                            
echo "            YNOTHINGLITE                       THINGLITERA                                            
echo "           LYNOTHINGLI                        OTHINGLITERA                                            
echo "          LLYNOTHINGL                         OTHINGLITERA                                            
echo "         ALLYNOTHING                          OTHINGLITER                                            
echo "         ALLYNOTHING                          OTHINGLITER                                            
echo "         ALLYNOTHINGL                         OTHINGLITER                                            
echo "        RALLYNOTHING                          OTHINGLITER                                            
echo "        RALLYNOTHIN                           OTHINGLITER                                            
echo "       ERALLYNOTHIN                            THINGLITER                                            
echo "      TERALLYNOTHI                             THINGLITER                                            
echo "      TERALLYNOTH                              THINGLITER                                            
echo "      TERALLYNOTH                               HINGLITER                                            
echo "       ERALLYNOT                                HINGLITER                                            
echo "      TERALLYN                                  HINGLITER                                            
echo "      TERALLY                                   HINGLITER                                            
echo "     ITERALLY                                   HINGLITER                                            
echo "     ITERALLY                                  THINGLITERAL                                          
echo "     ITERALLY                                  THINGLITERALL                                          
echo "    LITERALL                                   THINGLITERALLYNOT                                      
echo "    LITERALLY                                  THINGLITERALLYNOTHI                                    
echo "    LITERALLY                                   HINGLITERALLYNOTHI                                    
echo "    LITERALLY                                                                                        
echo "      TERAL
