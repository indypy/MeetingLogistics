# AV Checklist

## Equipment

* 2 x ZLX-12 Speakers
* 2 x Speaker Stands
* Sennheiser Case
  * D1 Body Pack
  * EV Microphone
  * Lapel Mic
  * Boom Mic (preferred for speakers)
  * Elgato Game Capture HD60 (Plus USB cable and short HDMI cable)
* 4U Rolling Case
  * Motu AVB Mixer/Interface
  * Behringer ADAT Expansion
  * Sennheiser D1 Base
  * AirPort Express
  * 5 Port Gigabit Switch
  * 8 Port USB Hub
  * PDU
* Clear Case Containing Cables
  * Korg nanoKontrol 2 + USB Cable
  * 2x 3-Prong (Orange) Ext Cords (Nema 5-15 P/R)
  * 3-Prong (Green) Ext Cords to 3 Receptacles (Nema 5-15 P/3port R)
  * 3x 320 C13 (Black) Universal Power Cables
  * 1/8inch Right Angle balanced audio patch cable
  * Male XLR to 1/4inch unbalanced audio cable
  * 2x XLR Male - Female Cable
  * 2x Long HDMI cable
  * 1x Short HDMI cable
  * 2x Cat6 Ethernet Cables
  * Mini Tripod
  * Pouch
    * Seagate 500GB USB 3.0 Drive + Cable
    * 2x Female HDMI -> Apple DP
    * Female HDMI -> DisplayPort
    * Female -> Female HDMI Coupler
    * Male 1/8inch Balanced Audio Cable to Female 2way balanced 1/8inch splitter
    * 1/8inch -> 1/4inch balanced jack-plug adapter
* Screen
  * Conduit plus Feet
  * King Size Sheet
  * Large Paper Clamps
* Projector (Optoma HD26)
* Projector Stand

## Setup Tips

1. Place speakers so the microphone doesn't pick up feedback
1. Place the 4U case close to one of the speakers so you can use the 10' XLR cable directly
1. Run a 50' cable to the other speaker and patch into the short XLR pigtail in the case
1. The Motu doesn't turn on when the case is powered on, you need to hold the power button on it for 3 seconds
1. Connect the AirPort Express to the local WiFi so you can remote control the mixer
   1. Reset the AirPort express with a Pen or Paperclip by holding the reset button for 10 seconds
   1. Launch the **AirPort Utility** on the Mac and it should show up under "Other Wi-Fi Devices"
   1. Make sure to have it "Join another network"
   1. Once it is connected, you can use the Motu and Sennheiser Apps to control the equipment.
   1. NOTE: Some networks disable client-to-client communication and that will make this not possible. We don't have an good alternative for this yet.
1. Connect the USB of the **Game Capture HD60** into the USB Hub in the case
1. Connect the short end of the **Game Capture HD60** to the speaker's laptop and the other end to the projector cable.

## Reminders for the Speaker

* Disable Screen Savers
* Disable Power Savers that would cause the screen to go black
* Ask them to repeat any questions for the recording

## Test Prior to Event

### Capturing Video and Audio
1. Launch **Game Capture HD**
1. Ensure **Commentary** is enabled
1. Ensure the **Commentary** Audio input is set to the **Motu AVB** device
1. Test that the **Commentary** meter is showing activity when speaking into either **Mic 1** or **Mic 2**

### Playing Music
1. Launch **Spotify** on Mac
1. Mac Audio will output on the "From Computer 1-2" control strip

## Don't Forget

1. Hit **Record** on **Game Capture HD**
1. Stop the recording once the speaker has answered all questions.

## Troubleshooting

## If you aren't seeing the Computer Channels on the Motu
For example, you aren't getting audio on the commentary in the capture software, or you can't play music from the Mac to the Motu.

1. Check the **Routing** tab in the Motu interface
1. Ensure the **From Computer** channels are showing up
1. Ensure that they are mapped to the mixer.

If the **From Computer** Channels aren't on the **Routing** tab, most likely there aren't enough inputs configured on the **Device** panel. Make sure the **Number of Inputs** is set for the maxiumum of **48**.

Also, double check that under **Computer Setup** that there are at least 2 (preferably 8) set under each of the **device to computer** settings.
