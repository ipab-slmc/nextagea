# Edinburgh Nextage Resources

This repo contains URDFs, launch files and common resources for the Nextage platform. See the IPAB Wiki for more details: https://github.com/ipab-slmc/wiki/wiki/Nextage

## Gazebo

Work is currently ongoing to configure the Nextage in Gazebo. The current status of this work is:
* Nextage is correctly configured, with relatively good trajectory PID gains and no joint disturbances, for a FIXED base - where the base is suspended above the world plane
* For a non-fixed base, the Nextage drops to the world plane and then slowly rotates on its axis (possibly due to vibration in the model). Further configuration is required.
