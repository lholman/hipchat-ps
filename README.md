# Getting Started
* Copy this module to any location found in $env:PSModulePath
* Import the module
	Import-Module Publish-HipChatRoomMessage
* List available functions	
	Get-Command -Module Publish-HipChatRoomMessage
* Get help on the module
	Get-Help Publish-HipChatRoomMessage -examples
	Get-Help Publish-HipChatRoomMessage -detailed
* Execute the module
	Publish-HipChatRoomMessage -apitoken e6b4ed16569cb86d272692171d5 5c8 -roomid 49459 -from "lloyd" -message "Test Message http://www.google.com"		
