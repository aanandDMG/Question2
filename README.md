# goals101Nginx--Question2

Requirement 

Kubernetes 

-------------------------------------------------------------------------------------------------------------------
Details
-------------------------------------------------------------------------------------------------------------------

1 Kindly run kubectl apply -f nginx.yaml for the nginx deploymnet, this one have 3 replicas set defined.

2 Kindly run kubeclt apply -f service.yaml once the deploymnet from nginx.yaml has been done for the LoadBalancing and publci access. Change the IPaddress from 
externalIPs section, it should be any public IPaddress having port 80 opened.

3 Once all above steps are done kindly verify endpoints from, kubectl describe services <service-name-listed-in-service.yaml>



**Note : ExternalIPS is for the bare metals, on cloud they take care of the public ip part.
