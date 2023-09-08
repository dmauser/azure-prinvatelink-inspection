# azure-prinvatelink-inspection
Validation of Private Endpoint Inspection

1.	Hub/Spoke - the location of the Private Endpoint (PE in the same VNET as the Firewall, or different VNETs).
2.	vWAN Secured-vHub with and without RI.
3.	PE Subnet with and without network policies.
4.	SNAT requirement for most PaaS services (accounting also the previous items might change the SNAT requirement).


1) Service Tunnel Public Storage (Workaround PE)
- Validate to VPN GW too.
2) 

2) Spoke over ER keep symentric return path.
On-Prem -> ER GW -> 
Return 0/0 ER -> ERGW -> NVA 0/0.