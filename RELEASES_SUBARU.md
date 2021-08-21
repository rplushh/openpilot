2021-08-21
==========
* Merge upstream (0.8.8) / @martinl
  * New driving model with improved laneless performance
    * Trained on 5000+ hours of diverse driving data from 3000+ users in 40+ countries
    * Better anti-cheating methods during simulator training ensure the model hugs less when in laneless mode
    * All new desire ground-truthing stack makes the model better at lane changes
  * New driving monitoring model: improved performance on comma three
  * NEOS 18 for comma two: update packages
  * AGNOS 1.3 for comma three: fix display init at high temperatures
  * Improved auto-exposure on comma three
  * Hyundai Kona Hybrid 2020 support thanks to haram-KONA!
  * Hyundai Sonata Hybrid 2021 support thanks to Matt-Wash-Burn!
  * Kia Niro Hybrid 2021 support thanks to tetious!

2021-08-15
==========
* FPv2 updates
  * 2018 Impreza Limited - UDM / @isaacdchan

2021-08-14
==========
* FPv2 updates
  * 2020 Ascent - UDM / @ndtran

2021-08-04
==========
* Merge upstream (0.8.7) / @martinl
* FPv2 updates
  * 2018 Forester - UDM / @sarvcomp

2021-08-03
==========
* FPv2 updates
  * 2021 Crosstrek Limited - UDM / @AdamSLevy

2021-08-02
==========
* Removed last remaining Subaru FPv1 fingerprints / @martinl
* Minor carstate signal fixes / @martinl

2021-08-01
==========
* Add Legacy 2018+ as separate model, has flipped triver torque signal / @martinl

2021-07-31
==========
* Update LKAS alert filtering for Outback 2020+ and Forester 2021+ / @martinl

2021-07-29
==========
* FPv2 updates
  * 2020 Forester Sport - UDM / @RyanYo

2021-07-26
==========
* FPv2 updates
  * 2018 Crosstrek - UDM / @dnewstat

2021-07-25
==========
* FPv2 updates
  * 2019 Outback - UDM / @Steven C

2021-07-24
==========
* Merge upstream (0.8.6) / @martinl
* Stop and go manual hold support for Global EPB models / @martinl
* Use alternative steering signal for WRX / @martinl
* FPv2 updates
  * 2015 Outback - UDM / @chk_null

2021-07-21
==========
* FPv2 updates
  * 2021 Forester - UDM / @umby24

2021-07-14
==========
* FPv2 updates
  * 2015 Outback 3.6R - UDM / @bitwaster

2021-07-12
==========
* FPv2 updates
  * 2020 Outback 2.4 Touring XT  - UDM / @chrissantamaria
  * 2021 Ascent - UDM / @Sandy

2021-07-10
==========
* FPv2 updates
  * 2020 Outback 2.4 XT Limited - UDM / @KingChalupa
* Disable LKAS alert filtering for Outback 2020

2021-07-07
==========
* FPv2 updates
  * 2017 Impreza - UDM (@Fidel)
  * 2019 Outback Touring 3.6R - UDM (@danyo)
  * 2020 Impreza Premium - UDM (@KeetsScrimalittle)
  * 2020 Forester - UDM / (@TH156UY)

2021-07-06
==========
* Stop and Go support for preglobal Forester, Levorg and WRX (@martinl)

2021-07-04
==========
* Levorg 2016 support (@jpgnz)

2021-07-02
==========
* Removed ASCENT, IMPREZA, OUTBACK FPv1 due to car identification issues (@martinl)

2021-07-01
==========
* FPv2 updates
  * 2019 Forester - UDM (@clockenessmnstr)
  * 2021 Forester - UDM (@gotham)

2021-06-28
==========
* Crosstrek Hybrid 2020 support (WIP) (@martinl)

2021-06-27
==========
* Outback 2020 support (WIP) (@martinl)
* Disable Openpilot disengage on gas press via toggle (@sshane)

2021-06-26
==========
* New subaru-community branch based on subaru-PR-test
* Stock LKAS alerts filtering when openpilot is enabled (@trailtacos)
* Subaru Stop and Go (both EPB and experimental MPB via toggle) (@letsdudiss)
* New ACC set speed unit signals for Global and Pre-global models (@martinl)
