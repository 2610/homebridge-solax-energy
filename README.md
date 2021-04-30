
<p align="center">

<img src="https://github.com/homebridge/branding/raw/master/logos/homebridge-wordmark-logo-vertical.png" width="150">

</p>
# homebridge-solax-inverter

Work in progress
# homebridge-solax-inverter

request to Solax Inverter


http://<your IP>/api/realTimeData.htm

{"method":"uploadsn","version":"Solax_SI_CH_2nd_20160729_DE01","type":"AL_SE","SN":"XXXXXXXX","Data":[0.2,0.4,270.3,286.6,1.7,256.4,342,34,8.9,10621.4,-54,54,114,53.87,-3.57,-193,54,74,0.0,3152.8,,,,,,,,,,,,,,,,,,,,,,0.00,0.00,,,,,,,,50.01,,,0.0,0.0,0,0.00,0,0,0,0.00,0,8,0,0,0.00,0,8],"Status":"2"}
Live data values

  PV1Current, PV2Current  PV1Voltage  PV2 Voltage   GridCurrent GridVoltage GridPower InnerTemp SolarToday  SolarTotal
  FeedInPower   PV1Power  PV2Power  BatteryVoltage  BatteryCurrent  BatteryPower   BatteryTemp  BatteryCapacity, 
  SolarTotal2 , EnergyToGridEnergyFromGrid ,GridFrequency ,EPSVoltage,EPSCurrent ,EPSFrequency ,status 

http://<your IP>/api/historyData.htm

[9.0,10.6,369.9,205.9,10632.1,1.4,3.6,86.5,50.5,3155.9]

Work in progress

Solax inverter plugin for home bridge


Solax inverter plugin for home bridge
