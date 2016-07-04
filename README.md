# SAP Inside Track Registration app backend

This repository contains the backend for the SITreg app. It is developed on SAP HANA native using XSODATA. For more details check out the information in the [Wiki](https://github.com/sapmentors/SITreg/wiki).

## Setup Guide

You must have developer authorization in your HANA System. To try this project just spin up your own HANA Multitennant Database Container (MDC) on the HANA Cloud Platform Trial (HCP). Open the SAP HANA Web-based Development Workbench and create the package:

    com/sap/sapmentors/sitreg

After you've created the package right click on the gittest package and choose **Syncronize with GitHub**. Provide your GitHub credentials to allow the HANA system to read your GitHub repositories. As you can't specify a GitHub repository URL you have to clone the project so you have it in your repository list. Then coose the cloned repository and GitHub branch **master**. Click **Fetch** to retreive the content. After that step you have to activate the artifacts. Try a right click **activate all**.
 