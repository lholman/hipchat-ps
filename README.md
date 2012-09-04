#hipchat-PS

## Getting Started
1. Copy this module to any location found in $env:PSModulePath
1. Import the module

	C:\PS>Import-Module Publish-HipChatRoomMessage
	
1. List available functions	

	C:\PS>Get-Command -Module Publish-HipChatRoomMessage
	
1. Get help on the module

	C:\PS>Get-Help Publish-HipChatRoomMessage -examples
	
	C:\PS>Get-Help Publish-HipChatRoomMessage -detailed
	
1. Execute the module

	C:\PS>Publish-HipChatRoomMessage -apitoken e6b4ed16569cb86d272692171d5 5c8 -roomid 49459 -from "lloyd" -message "Test Message http://www.google.com"		

## Disclaimer
NO warranty, expressed or written