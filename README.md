# md380-390 codeplug

MD380-90_All_AU_DMR+analog+CB 
Comprehensive Australian codeplugs for TYT MD-380 and MD-390 
This was originally developed by Matt, VK2MRC for the Goulburn and Southern Tablelands Amateur Radio Club. Anyone building on this Codeplug or forking, please acknowledge Matt VK2MRC and Det VK2KVP

<b>Hotspot/Dongle Frequencies:</b> Australian band plan assigns the following 70cm frequencies for Internet gateways:
- 439.125 (used for the DVm channels to suit DVmega and other MMDVM hotspots.)
- 439.150 (used for the DV4 channels to suit DV4mini)
- 439.175 (not allocated, but used in this codeplug for Z channels ZUMspot or CHINspot)

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

<b>Using Reflectors for DMR+ on MMDVM Repeaters.<b>
  As with MMDVM hotspots, When using MMDVM repeaters to connect to DMR Plus talkgroups, use TG8. Then to change reflectors, enter the Private Call reflector code and transmit for a few seconds. An announcement through the DMR Gateway will confirm the active reflector. For convenience, this codeplug includes programming of the keypad fast dial keys as follows Key0->4800 (linked to VK-DRM TG505), Key1->4801 (linked to VK-DMR TG3801), Key2->4802 (linked to VK-DMR TG3802), and so on up to key 7, then Key8->4851 (linked to VK-DMR TG3851 NZ) and Key9->4000 Reflector Disconnect.

<b>Release Notes - MD380-80_All_AU_DMR+analog+CB_v15</b>
- Added VK-DMR repeaters: VK2RWI, VK4RBT, VK4RLU, VK4RSL, VK6RPT, VK6RLX, VK2RYS
- Renamed DMR channels with prefix of repeater call sign
- Renamed Brandmeister talk groups with prefix bm
- Removed Brandmeister repeaters not on repeater status list at http://125.63.63.112/status/list.htm as at 02Aug18
- Removed listings for callsigns not registered with ACMA as repeaters.
- Added XLS file listing repeaters included in this codeplug.


<b>Release Notes - MD380-80_All_AU_DMR+analog+CB_v13</b>



<b>Release Notes - MD380-80_All_AU_DMR+analog+CB_v13</b>
- Created Digital Rx Group for each Digital Contacts talk group and assigned corresponding Rx Group for each Digital Contact. This is to avoid other talk groups breaking through on a QSO. Promiscuous mode can be used to monitor multiple TGs.
- Removed channels with private calls which were intended for changing DMR+ reflectors. This is better done using direct entry or programmed speed dial.

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
