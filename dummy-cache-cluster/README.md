# Dummy cache cluster

This example is used at the [Setup a Development Environment](https://docs.hawkore.com/private/tutorials/en/latest/apache-Ignite-connector-mule3/setup-development-environment/)
tutorial.

*Setup a development environment, in less than 15 minutes, where you can evaluate how two mule instances, correctly configured, work in cluster using the Apache Ignite connector operations.*

## Run the demo

Follow this [tutorial](https://docs.hawkore.com/private/tutorials/en/latest/apache-Ignite-connector-mule3/setup-development-environment/)
or watch this [video](https://www.youtube.com/watch?v=asrxhljogdQ).


## Notes

To run this example inside Anypoint Studio add next system properties to the VM arguments of the Run configuration:

-Ddefault.ignite.discovery.port=45500 -Ddefault.http.port=8081


These are the entries you must add at each mule instance configuration file in order to run this example.


- Mule instance 1

wrapper.java.additional.17=-Ddefault.http.port=8081

wrapper.java.additional.18=-Ddefault.ignite.discovery.port=45500

- Mule instance 2

wrapper.java.additional.17=-Ddefault.http.port=8082

wrapper.java.additional.18=-Ddefault.ignite.discovery.port=45501

# Other resources

Sign up at [www.hawkore.com](https://www.hawkore.com) to access full documentation.

- [Product documentation](https://docs.hawkore.com/private/apache-ignite-connector-mule3/)
- [Tutorials](https://docs.hawkore.com/private/tutorials/)
