# Extreme Management Center DeviceView for FortiGate
>Community maintained content

The DeviceView does use reports in the MyReports directory. Those reports use FlexViews, FlexViews does use MIBs.

1. Make sure all flexviews are working. If not check relevant mibs are imported.
2. Upload reports to the `appdata/OneView/MyReports directory`.
3. Reports -> Reports -> Refresh.

## XMC 8.1.2

Product Family needs to be configured as [FortiGate](sample/VendorProfile.png?raw=true)

| Product  | DeviceView   | FlexView   | Buildin FlexView | Example   |
| -------- | ------------ |:----------:|:----------------:| --------- |
| FortiGate |[System](xml/DeviceViewFortiGateSystem.xml)|FortiGate_SystemInfo, FortiGate_Software, FortiGate_CPU| - |[png](sample/System.png?raw=true)|
| FortiGate |[VDOM](xml/DeviceViewFortiGateVDOM.xml)|FortiGate_VdomInfo, FortiGate_Vdom| - |[png](sample/VDOM.png?raw=true)|
| FortiGate |[Firewall](xml/DeviceViewFortiGateFW.xml)|FortiGate_Firewall| - |[png](sample/Firewall.png?raw=true)|
| FortiGate |[WLAN AP](xml/DeviceViewFortiGateWlanAP.xml)|FortiGate_Wlan_AP, FortiGate_Wlan_AP_HW, FortiGate_Wlan_AP_Stats| - |[png](sample/WlanAP.PNG?raw=true)|
| FortiGate |[WLAN SSID](xml/DeviceViewFortiGateWlanSSID.xml)|FortiGate_Wlan_SSID, FortiGate_Wlan_VAP| - |[png](sample/WlanSSID.PNG?raw=true)|
| FortiGate |[WLAN MU](xml/DeviceViewFortiGateWlanMU.xml)|FortiGate_Wlan_MU| - |[png](sample/WlanMU.PNG?raw=true)|
>Be Extreme
