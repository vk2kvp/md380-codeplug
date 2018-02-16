# md380-codeplug

MD390_All_AU_DMR+analog+CB 
Comprehensive Australian codeplugs for TYT MD-380 and MD-390 
This was originally developed by Matt, VK2MRC for the Goulburn and Southern Highlands Amateur Radio Club. Anyone building on this Codeplug or forking, please acknowledge Matt VK2MRC and Det VK2KVP

<b>Hotspot/Dongle Frequencies:</b> Australian band plan assigns the following 70cm frequencies for Internet gateways:
- 439.125 (used for the DV4 channels to suit DV4mini)
- 439.1375 (not allocated, but used in this codeplug for Z1 channels ZUMspot or CHINspot)
- 439.150 (used for the DVm channels to suit DVmega and other MMDVM hotspots.)
- 439.1775 (not allocated, but used in this codeplug for Z2 channels ZUMspot or CHINspot)

439.200 is assigned for digital simplex operation.

<b>UHF CB Channels.</b> Note that these radios are not type approved for UHF CB transmision. These frequencies are included in Receive-only mode. 

<b>Testing</b> These codeplugs are provided "as is" without support. Use them at your own risk. They have been tested to work on the following handhelds with the TYT-Toolz firmware loaded. I have not tested them on machines with virgin firmware:
- MD390 with GPS and new vocoder
- MD380 with GPS and new vocoder
- MD380 without GPS and new vocoder

All editing was conducted with G6AMU's codeplug editor. The codeplug was uploaded to each test transceiver using TYT's CPS software "MD-380G WO GPS v1.36". Upload to each of the above handhelds was also successful with v1.34 at http://www.tyt888.com/uploadfile/upfiles/20170321134006.zip

<b>To use these Codeplugs:</b> Before you write these codeplugs to your radio, replace the callsign and DMR ID with your own in General settings.
- Get G6AMU's codeplug editor from http://www.miklor.com/MD380/380-CPEditor.php
- KG5RKI's TyMD380Toolz application is available at https://kg5rki.com/new2/tymd380.html

<b>Release Notes - MD390_All_AU_DMR+analog+CB_v0.6</b>
- Removed Z2 channel set- Moved Z1 channel set to near top of list to aggregate hotspot channels
- Added DVmega and DV4mini Zones to differentiate the hotspots
- Added DMR+ reflectors 4850 (NZ), DCS001V & DSC001X to DV4mini zone and reflectors 4802 NSW, 4805 SA to DVmega & ZUMspot Zones.  Ref for D-star gateway connection using Pi-star at https://dmr-quebec.groups.io/g/DMR-Quebec/attachment/571/0/Connecting%20your%20DMR%20radio%20to%20D_Star%20Rev1a.pdf

<b>Release Notes - MD390_All_AU_DMR+analog+CB_v0.5</b>
- Changed frequency for DVmega channels to 439.150MHz
- Changed channel names for DV4mini DMR+ reflectors to include talkgroup mapping.
- Added Z1 channels on 439.1375 for ZUMspot or CHINspot 1
- Added Z2 channels on 439.1775 for ZUMspot or CHINspot 2

<b>Release Notes - MD390_All_AU_DMR+analog+CB_v0.4</b>
- Fixed VK6RGF changed channel list to Brandmeister network
- Added Zone and Scan List for VK3RBA
- Added Zones for CB41-56 and CB54-80
- Added repeaters: VK2RTH, VK4RBK, VK6ZTG, 
- Removed unused Contact Groups

<b>Release Notes - MD390_All_AU_DMR+analog+CB_v0.3</b>
- Fixed scan lists for 6RDM & 6RLM
- Added DMR+ 4xxx and 9x TGs to Digital Contacts
- Added DVmega chanels to Hotspot zone
- Added DV4mini channels for DMR+ to Hotspot zone
- Sorted zone list and scan lists alpha-numeric
- added repeaters: VK2RMP, VK2RWW, 3SMC (BM), 3RBA (BM).
