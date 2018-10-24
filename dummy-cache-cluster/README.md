To run this example inside Anypoint Studio add next system properties to the VM arguments of the Run configuration:

-Ddefault.ignite.discovery.port=45500 -Ddefault.http.port=8081




These are the entries you must add at each mule instance configuration file in order to run this example.


- Mule instance 1

wrapper.java.additional.17=-Ddefault.http.port=8081

wrapper.java.additional.18=-Ddefault.ignite.discovery.port=45500

- Mule instance 2

wrapper.java.additional.17=-Ddefault.http.port=8082

wrapper.java.additional.18=-Ddefault.ignite.discovery.port=45501
