# Mass-Tagging-Azure
<#
This Az CLI script is update tags for all resources within a specified resource group, 
including the resource group itself. The primary purpose of the script is to ensure consistency 
of these tags across all resources within a resource group and identify resource owners. 
It achieves this by adding new tags, updating existing ones with new values, and ensuring 
that all resources, including the resource group itself, are uniformly tagged. 

Modify the script to scope at the Subscription and RG, double check you scoping. Measure twice cut once, and paste the script in Az CLI. 
#>
