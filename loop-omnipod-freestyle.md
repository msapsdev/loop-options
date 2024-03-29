# iOS + Loop + Spike + Omnipod + Freestyle Libre + MiaoMiao

Requirements:
- Mac + XCode + Apple Developer account
- iPhone (5s or newer. I am using an old 5s and it seems to be working fine)
- Omnipod + Rileylink
- Freestyle Libre + MiaoMiao
- Tidepool account

Steps:
- Follow the instructions on how to compile a custom version of Loop from here:
  https://github.com/cyoung1024/loop/tree/omnipod-spike
  
- Download Impactor and Spike, follow installation instructions from here:
  https://spike-app.com/install-spike-using-cydia-impactor/
  
- Install Tidepool Mobile and set it up to connect to your Tidepool account
- Start Spike on iPhone and setup an Internal (mock) Dexcom server + configure MiaoMiao as transmitter
- Start Loop and proceed with the configuration including Spike as a CGM (available only on the cyoung1024 custom version) and Omnipod as pump
- Allow Loop to write all categories to Apple Health
- Allow Tidepool to read all categories from Apple Health to sync them to Tidepool

Done
