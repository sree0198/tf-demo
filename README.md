# Terraform-IaC
**Objective:** 
Participants are given an incomplete JSON configuration file (Terraform or ARM configuration). They must fill in the blanks to create a valid configuration that provisions the required infrastructure. The configuration file is available in the GitHub repo.



**Scenario:** 
"You’re tasked with creating a cloud infrastructure for a new project. Your team has started configuring it using Infrastructure as Code, but some key elements are missing. Fill in the blanks to complete the configuration, allowing you to provision resources quickly with code, not clicks!"

**Instructions:**
1. Virtual machine should be launched in East-US region.
2. Image should be Ubuntu server.
3. Private IP range should be 10.0.2.0/26
4. Define a suitable VM size in `azurerm_linux_virtual_machine`
5. VM disk type should be 'Standard_SSD'.
