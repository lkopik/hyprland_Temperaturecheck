# hyprland_Temperaturecheck
if you want see temperature... use my config
![изображение](https://github.com/lkopik/hyprland_Temperaturecheck/assets/81908442/663735a6-ac3f-4a5c-8f40-105b64b7e886)
![изображение](https://github.com/lkopik/hyprland_Temperaturecheck/assets/81908442/87462ee5-b442-4c89-b0eb-4fa103e7eb5e)!

!!!BUT YOU CANT SEE THE POWER_PROFILE IF YOU USE MY CONFIG!!!


# INSTALL

sudo su

cd /home/USER/.config/HyprV/waybar/scripts

mv power_profile power_profile.save

git clone https://github.com/lkopik/hyprland_Temperaturecheck.git

mv hyprland_Temperaturecheck/power_profile /home/USER/.config/HyprV/waybar/scripts/power_profile

chmod +x power_profile

reboot
