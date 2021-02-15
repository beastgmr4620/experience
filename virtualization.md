- To run virtual machines (wsl2, hyperv, docker, etc...) on HyperV, you must expose virtualization extension to guest machine(s).
Set-VMProcessor -VMName <VMName> -ExposeVitualizationExtensions $true
