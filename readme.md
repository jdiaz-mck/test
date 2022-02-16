
1.  change conflicting sdmserver ports config at end of sdmserver/applicationdata/sdm-config.yml
2.  change sdmclient config <code>[0/2]</code>
    - [ ] app server
    - [ ] citrix share
3.  change "E:\CLIENT\Orpheus.CLIENT.PROD\servers\SDMServer\ContentManagementInterface" <code>[0/2]</code>
    - [ ] delete all json files
    - [ ] delete curlrequest.bat
4.  [ ] check firewall
5.  [ ] change ports in keycloak aswell <http://pdc01.td3.orpheus.local:8080/auth/admin/master/console/#/realms/vfc-production/clients>
