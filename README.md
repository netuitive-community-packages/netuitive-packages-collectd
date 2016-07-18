#netuitive.packages.collectd 1.1.0

**Default Plugins**
The following are the Collectd plugins that we assume Netuitive customers will use by default.

 - **CPU** - collects the amount of time spent by the CPU in various states, most notably executing user code, executing system code, waiting for IO-operations and being idle
 - **DF** - collects file system usage information (how much space on a mounted partition is used and how much is available)
 - **Disk** - collects performance statistics of hard-disks and, where supported, partitions
 - **Interface** - collects network information about traffic (octets per second), packets per second, and errors
 - **Load** - collects system load to give rough overview of machine utilization
 - **Memory** - collects physical memory utilization
 - **Processes** - collects the number of processes, grouped by their state (e. g. running, sleeping, zombies, etc.)
 - **Uptime** - keeps track of the system uptime

Additional plugins may be enabled; policies and configurations for those plugins will be packaged separately as they become available.

For detailed information on this package, please refer to the [online documentation](https://help.app.netuitive.com/Content/Misc/Datasources/new_collectd_datasource.htm).

##Release History

###Version 1.1.0

* Removed utilization tag from individual disk metrics.

###Version 1.0.0

* Initial production release of the package for monitoring OS metrics from Collectd.