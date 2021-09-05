# Ven's Stock Revamp

*This part pack replaces several of the stock textures and models, hopefully making them more beautiful in the process.*

![Left: stock; Right: revamped](https://raw.githubusercontent.com/Kerbas-ad-astra/Stock-Revamp/master/comparison.png)

Left: stock Kerbal X.  Right: Kerbal X with Ven's Stock Revamp.

## Features

- Most parts in the base game (i.e. not from Making History or any future expansions) get completely replaced, but there are a handful of exceptions:
	- Spaceplane parts are generally left alone.  (The "Wheesley", "Whiplash", and "Panther" engines get some decorative turbomachinery added to the front of them.)
	- Squad's revamped fuel tanks, adapters, and probe cores are still available as variants (though Ven's models are now the default variant for them).
	- Some of Squad's revamped thrusters and pods are left alone, since they have new functionality and look nice enough.
- New parts are added fill some gaps in the stock range, including half-sized deployable solar panels, structural girders in multiple sizes and configurations, and a range of Oscar 0.625m fuel tanks.

A full gallery of parts is available on Imgur: https://imgur.com/a/L8rpP

## Dependencies

Ven's Stock Revamp depends on [**Module Manager**](https://forum.kerbalspaceprogram.com/index.php?/topic/50533-140-17x-module-manager-403-august-9th-2019-right-to-ludicrous-speed/&tab=comments#comment-720814), a compatible version of which is bundled in the zip file.

## FAQ (First Anticipated Question)

- Is this mod compatible with ReStock?
	- Not as-downloaded.  However, if you delete the PathPatches and Squad subfolders, you can keep the new parts that Ven made and let ReStock have its way with the stock parts.

## Download and install

- [**GitHub**](https://github.com/Kerbas-ad-astra/Stock-Revamp/releases)

From there, just unzip the "VenStockRevamp" folder into your GameData directory.

Please let me know in [**the forum thread**](https://forum.kerbalspaceprogram.com/index.php?/topic/189732-19x-vens-stock-revamp-resurrected-v1151-nattering-nodes-of-negativism-02020-mar-15/) or on [**the GitHub issue tracker**](https://github.com/Kerbas-ad-astra/Stock-Revamp/issues) if you find any issues!

## Version history and changelog

- 1.9.6, KSP 1.2
	- Last update by Ven.
- 1.10.0, KSP 1.4 development
	- Support for localisation
	- +PART patches expanded into full PART nodes (so that parts added by VSR are properly identified as such by Filter Extension)
	- Added support for inflatable crew module feature
	- Adjusted node positions of Ven's new Poodle model so that 'upgraded' vehicles don't have the bell sticking down into the decoupler below.
		- Moved old VSR Poodle model to new O-80 "Gale" Service Engine part (size 2 monoprop engine).
	- Re-enabled revamped wheel models (thanks @Enceos)
	- Re-enabled giant SpaceX-style landing gear (thanks @notquitehalf)
	- Added Part Variant support to Ven's engine models with optional tankbutts.
	- Added Ven's textures and models as default variants of aerodynamic fairings and Rockomax (size 2) tanks.
	- Added VSRexclude switch -- set "VSRexclude = true" in a part config and VSR will not swap its stock model(s) for Ven's versions.
	- Balanced CryoX and soft fuel tanks for updates to CryoTanks.
	- Adjusted node positions of several models to fit better and reduce thrust offset.
	- Restored Ven's old aerospike model on top of Porkjet's.
	- Lights no longer illuminate planets from orbit.
- 1.11.0, KSP 1.5 development
	- Added fuel to Rockomax-48 fuel tank...
	- Added Ven's models as default variants of revamped Mk1 pod, Stayputnik, OKTO, OKTO2, QBE, HECS, HECS2, and RoveMate probe cores, and FL-T (size 1) fuel tanks.
	- Added new RT-10-G SRB to use Ven's model (with gimbals).
- 1.12.0, KSP 1.6 development
	- Added Ven's models as default variants of revamped multicouplers, Rockomax and FL-T adapters, and nose cones (Aerodynamic Nose Cone and Protective Nose Cone Mk7).
		- Added new ADTP-3-2-H part, as a special lightweight hollow adapter between size 2 and 3 parts.  (Squad's revamped model is a fuel tank, so Ven's model doesn't apply to it.)
		- Fixed Rockomax tanks.
	- Ven's old Poodle model returns to revamp Squad's revamped Poodle model.
		- Marked O-80 "Gale" service engine as deprecated (TechHidden = true), to be removed in a future update.
	- Ven's engine models now overwrite Squad's revamped Poodle, Spark, Terrier, RT-5, and RT-10 engine models.
		- RT-10-G SRB removed.
	- Adjusted node and fairing positions of Skipper, Poodle, LV-T30, and LV-T45 models, to reduce interference with other parts.
	- Adjusted node positions of heat shields (and Ven's Mk1 pod model) to fit better with flat-bottomed parts.
	- Changed the transform names of the vernier thrusters on the Size2MedEngine (RE-D7 "Bollard"), so they can have separate thrusts and FX groups.
- 1.13.0, KSP 1.7 development
	- Suppressed Squad's new engine models in KSP 1.7 (24-77, Ant, Spider, RV-105, Place-Anywhere 7, Vernor).
	- Updated USI-LS patch to USI-LS 1.1.
	- Rearranged files so that users can delete all of the new parts (Part Bin) or revamps of stock parts (PathPatches & Squad).
- 1.14.0, 02019 11 11 "Terminal Guidance"
	- A proper release!
	- Adapted to new models in 1.8 (new variants of Mk7 Nose cone and S3 fuel tanks, suppressed Squad's new service bay models).
	- Fixed a bad node location on the 1.25m Heat Shield.
- 1.14.1, 02019 11 12 "Mercury Delayed"
	- Restored models and texture for short Rockomax decoupler and TR-8A radial decoupler.
- 1.14.2, 02019 11 16 "MoDeL DoEs NoT eXiSt"
	- Fixed config and restored texture for Inline RCS Block.
- 1.15.0, 02020 03 15 "I Prefer The Real Revamp"
	- Adapted to new models in KSP 1.9 (Skipper, Mainsail, Thumper)
- 1.15.1, 02020 03 15 "Nattering Nodes of Negativism"
	- Fixed node orientation on Mk1 pod, and also adjusted node height slightly.
- 1.16.0, 02021 09 05 "Too Much Space In Space"
	- Updated to new models and variants in KSP 1.10, 1.11, and 1.12.
		- No longer revamping RV-105 RCS thruster (Squad's revamps are fine enough, and Ven's model isn't set up to be flexible with variants)
		- RT-1 "Cricket", RT-2 "Grasshopper", and RockoMAX models (from Ven's new parts) are now also applied to the stock FM1 "Mite", F3S0 "Shrimp", and S2-33 "Clydesdale" respectively.  The RT-1, RT-2, and RockoMAX are now marked as 'TechHidden'.
		- Ven's Mk 5 Strip Light is also now 'TechHidden' because there's a better striplight (that actually emits light!) in the stock game.
	- Renamed "Part Bin" subfolder to "PartBin", to accommodate Module Manager patches
	- Localized SpaceX-style landing leg (missed this one back in VSR 1.10)
	- Fixed Nose Cone Mk7 patch.
	- Fixed some config errors in LV-T15 "Dachsund" and LV-900 "Beagle" engines.
	- Fixed loading errors from IVA props.  (Gated RPM modules behind "NEEDS" blocks, deleted unfinished models.)
	- Restored a few missing textures.
	- Fixed RT-20 "Sickle" model and adjusted node location accordingly.
	- Fixed model location on BACC Thumper.
	- Set up inventory configs for Ven's new parts.
	- End of line.

## Roadmap

One of these days, I'd like to make a white alternate texture for Ven's strut and fuel duct (like stock), but so far I haven't made anything that looks good.

## Credits

The vast majority of the models are by Ven.  EmbersArc/Enceos fixed up the revamped rover wheels, and some configuration fixes were supplied by notquitehalf.  The majority of the configuration fixes were committed by yours truly.

And of course, thanks are owed to Squad for making part models that are worth revamping.  :wink:

## License

Ven's Stock Revamp (v1.10+) is copyright 2021 Kerbas_ad_astra.  Part configuration files, Module Manager patches, models, and textures are released under the [CC-BY 4.0 International](https://creativecommons.org/licenses/by/4.0/legalcode) license (or any later version).