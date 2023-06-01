# cs
//audio settings
volume "0.0"
bind g +voicerecord

// sensitivity
sensitivity "1.0"

// disable hints for new players
gameinstructor_enable "0"

// radar settings
cl_hud_radar_scale "1.3"
cl_radar_scale "0.7"
cl_radar_always_centered "1"
cl_radar_rotate "1"
cl_radar_icon_scale_min "0.4"

// disable auto weapon switch
cl_autowepswitch "0"

// crosshair settings
cl_crosshair_drawoutline "0"
cl_crosshaircolor "4"
cl_crosshairdot "0"
cl_crosshairgap "-2.5"
cl_crosshairsize "2"
cl_crosshairstyle "4"
cl_crosshairthickness "1"

// viewmodel settings
viewmodel_fov "68"
viewmodel_offset_x "2.5"
viewmodel_offset_y "0"
viewmodel_offset_z "-1.5"
viewmodel_presetpos "3"
viewmodel_recoil "0"
cl_righthand "1"

// bob
cl_viewmodel_shift_left_amt "0"
cl_viewmodel_shift_right_amt "0"
cl_bob_lower_amt "5"
cl_bobamt_lat "0"
cl_bobamt_vert "0"
cl_bobcycle "0.98"

// hud
hud_scaling "0.85"
cl_hud_color "0"
cl_hud_playercount_showcount "1"
cl_hud_playercount_pos "1"
cl_showloadout "1"
cl_hud_healthammo_style "1"
cl_hud_background_alpha "0.8"
cl_hud_bomb_under_radar "0"
safezonex "0.85"
safezoney "1"

// max ping in matchmaking
mm_dedicated_search_maxping "60"

// jumpthrow
bind v "+jump;-attack;-jump"

// grenade binds
bind c "use weapon_molotov; use weapon_incgrenade"
bind 4 "use weapon_smokegrenade"
bind mouse5 "use weapon_flashbang"
bind mouse4 "use weapon_hegrenade"
bind h "use weapon_decoy"

// drop
bind q "drop"

// other key binds
bind f "+lookatweapon"

// mwheel jump
bind mwheelup "+jump"
bind mwheeldown "+jump"
