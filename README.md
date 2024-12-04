# Rapid7 Insight VM
----

This pack contains a set of pipelines that consume Rapid7's vulnerability and asset API to pull and parse vulnerability definitions, assets, and vulnerability findings. On the 1st of the month, it will pull 'old' vulnerabilities from assets, including remediated. Otherwise, the default query pulls assets and vulnerabilities that have been modified in the last 24h. 


## Requirements Section

Before you begin, ensure that you have met the following requirements:

* I haven't done regression testing for Cribl versions earlier than 4.9.
* You will likely want the rest collectors and event breaker: https://github.com/Fulcrum-Technology-Solutions/Cribl_Rapid7_Collector_Template


## To Do

* Find a method to put severities in vulnerability findings.

## Using The Pack

To use this Pack, follow these steps:

1. Import the rest collectors and eventbreaker
2. Ensure the route is matching on your collector input id, and the pre-processing pipeline is attached to the collectors.
3. Configure the API key, query conditionals, and additional fields in the collectors.


## Release Notes

### Version 1.00 - 2024-12-02
Initial release


## Contributing to the Pack
To contribute to the Pack, please do the following:

* Email us at dcrooks@ftsc.com or jowen@ftsc.com


## Contact
To contact us please email <dcrooks@ftsc.com>.


## License
This Pack uses the following license: [`<license_name>`](https://link-to-license-example.com).
