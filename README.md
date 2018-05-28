# ObservatoryMonitor
Observatory Monitor is an Arduino based device that monitors several safety related aspects of a small astrophotography observatory.

It monitors safety relays from environmental and observatory equipment to provide a consolidated safety relay.  It also makes the status of the individual relays available to a supervisor over a USB connection.

Inputs would be provided by devices like Lunatico Astronomia CloudWatcher/Solo, Hydreon RG11 rain sensor, or my MountMonitor project.

The ObservatoryMonitor provides a single relay output that indicates that the observatory is safe to open when all sensors indicate safe.

The USB data stream also indicates the safety status of individual inputs, and the Parked and Meridian Limit status from the MountMonitor.
