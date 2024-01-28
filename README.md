# Rotate KrbTGT Account password

This scripts helps you to rotate your AD krbtgt account password. 

The scripts requite english windows server os with english powershell. The scripts with -de in the name are tweaked for german windows server os. 
Normaly you run this scripts interactive. 
The scripts containing automated in the name are intended to be used with a windows scheduled task to automate the krbtgt rotation. We recommend to run these scripts every 30 Days. 

# Disclaimer
do not run the scripts two times without enough time left between each run. This will break your kerberos.


# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
