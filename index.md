![zplanner](./zplannerlogo.png)
# zPlanner Docs

## Description

zPlanner is a tool that is designed to monitor disk change rates to VMware virtual machines. zPlanner leverages the PowerCLI interface to get data from vCenter and store it in a local MySQL database. This data is then manipulated and presented using Grafana.

The intended purpose of zPlanner is to help architect the number of Zerto Cloud Appliances that are required as well as how much bandwidth is needed to replicate a workload.

zPlanner is a combination of two parts, there is code that makes zPlanner work (which comes from this GitHub Repo), as well as a virtual machine that has the required packages to run the code from GitHub. In order to deploy zPlanner you should download the zPlanner appliance and it will download the latest zPlanner updates during configuration.

## Support

It should be noted that zPlanner is not supported by Zerto Support. It is a free tool created by [Justin Paul](https://github.com/recklessop), and supported on a best effort basis. To request support you have three options:

1. [Open zPlanner GitHub Issue](https://github.com/zerto-ta-Public/zplanner/issues)
    - Used for issues pretaining to what zPlanner does (or doesnt) do
    - Recommended for feature requests, bugs, and larger asks.
2. Open a documentation issue
    - If you spot an issue with the zPlanner documentation you can submit a pull request on this repo
3. [JPaul.me Drift Chat](http://jpaul.me)
    - For shorter requests or quick questions please use the Drift chat box on my blog.


## Contributing

* Submit a pull request
* open an issue

## Further information about zPlanner

`zPlanner` is a tool to collect workload statistics and determine WAN replication requirements. Please refer to [Justin's IT Blog](https://jpaul.me/zplanner/) to get started. The `zPlanner` docs website is generated by `docfx`!

## Disclaimer

### Simple version

zPlanner is written and maintained by me, not Zerto. zPlanner uses read-only access to your vCenter server and has been rigorously tested to make sure it won’t hurt anything. However, use it at your own risk. I take no responsibility if you hurt your environment with it.

Feel free to view all of the code that zPlanner uses on it's [Github repo](http://github.com/Zerto-TA-Public/zPlanner) and decide for yourself if it’s safe to use.

### Lawyer Version

zPlanner is not supported under any Zerto support program or service. The author and Zerto further disclaim all implied warranties including, without limitation, any implied warranties of merchantability or of fitness for a particular purpose.

In no event shall Zerto, its authors or anyone else involved in the creation, production or delivery of zPlanner be liable for any damages whatsoever (including, without limitation, damages for loss of business profits, business interruption, loss of business information, or other pecuniary loss) arising out of the use of or the inability to use zPlanner or documentation, even if the author or Zerto has been advised of the possibility of such damages. The entire risk arising out of the use or performance of zPlanner and documentation remains with you.