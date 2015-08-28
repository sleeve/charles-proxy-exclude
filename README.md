# charles-exclude
While recording a Charles Proxy session for an iOS device there are a lot of background calls that can show up in your recording. The calls range from network carrier update checks, Weather.com and Yahoo stock updates to various Apple and Amazon AWS reachability/service calls. For most recordings I don't need to see all of these background calls. To make it easier to parse recordings I've added most of these calls to my Exlude list.

>######WARNING
>It may be a bit agressive (iCloud/Amazon AWS/Dropbox) for some projects so be sure to double check all of the hosts after >importing to make sure you aren't dropping your calls on the floor. 

## Install
1. Launch Charles Proxy
2. Goto `Proxy > Recording Settings...`
3. Select the `Exclude` tab
4. Click the `Import` button on the bottom left
5. Select the `charles-exclude.xml` and click `Open`. The Exclude locations list should now be populated.
6. Click `OK` to save the Recording Settings
