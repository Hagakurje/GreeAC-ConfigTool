# Gree Config Tool
Based on https://github.com/emtek-at/GreeAC-ConfigTool
Changes:
* update .net core from 2.2 to 3.1

With this little tool you can change the Host to which the Gree WIFI Modules connect to.

##### Build
`dotnet publish -c Release -o out`

##### Execute
`dotnet out/ConfigTool.dll`

After changing the Hostname power off and on the Devices to activate the new setting. If you see the Requests in the DummyServer Output you can block the Devices in your Firewall.