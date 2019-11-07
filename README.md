# LAM TEAM 55

### APPLICATION SETTINGS

~~~~
CONSOLE=NO|YES - for development
AZURE_STORAGE_CONNECTION_STRING=...
BOTFLOW_CONTAINER=<azure blob container name>
MICROSOFT_APP_ID=<GUID>
MICROSOFT_APP_PASSWORD=<PASS>
BOTNAME=<bot loaded by default>
LOGTABLE=<azure table name for conversation logging>

Bot.html should have the directline key changed.
~~~~

An example would be:
~~~~
CONSOLE=NO
AZURE_STORAGE_CONNECTION_STRING=DefaultEndpointsProtocol=https;AccountName=<youraccount>;AccountKey=<youraccountkey>;
BOTFLOW_CONTAINER=botflows
MICROSOFT_APP_ID=<guid>
MICROSOFT_APP_PASSWORD=<the pass>
botId=BotId
BOTNAME=bot1
LOGTABLE=botlog
~~~~
