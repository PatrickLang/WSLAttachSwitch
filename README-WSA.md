

Setup Steps

1. Create a virtual switch


Launch

1. Start an Android app
1. Find the network by GUID with hnsdiag - it's going to be a transparent network
1. Run WSLAttachSwitch.exe <guid>
1. Hope it can handle the IP address change


If WSLAttachSwitch.exe is started too early, it seems to break WSA. Use the "Turn Off" button in the Windows Subsystem for Android to shut it down, then try again