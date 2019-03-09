# PartnerPortalHubSpotIntegration
Integration between Microsoft PartnerPortal and HubSpot

Creates a solution to add a lead from partnerportal.azure.com to HubSpot.

An APIKEY from HubSpot is required.
<p align="center">
  <img src="hubspotapikey.jpg" width="350" title="hover text">
</p>

To add the Logic App to your Azure subscription click below link:

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fsvandenhoven%2FPartnerPortalHubSpotIntegration%2Fmaster%2FLogicAppARM%2FLogicApp.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

After deployment go to the edit blade of the logic app and copy the url of the Request Trigger Action. Use this URL in the https://partnerportal.azure.com Lead Configuration as HTTPS endpoint.
<p align="center">
  <img src="httprequest.png" width="350" title="hover text">
</p>