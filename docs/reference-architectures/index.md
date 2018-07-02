---
title: Azure Reference Architectures
description: Reference architectures, blueprints, and prescriptive implementation guidance for common workloads on Azure.
layout: LandingPage
ms.topic: landing-page
---

# Azure Reference Architectures

Our reference architectures are arranged by scenario, with related architectures grouped together. Each architecture includes recommended practices, along with considerations for scalability, availability, manageability, and security. Most also include a deployable solution.


## Big data solutions

<ul  class="panelContent cardsF">
<!-- SQL Data Warehouse -->
<li style="display: flex; flex-direction: column;">
    <a href="./data/enterprise-bi-sqldw.md" style="display: flex; flex-direction: column; flex: 1 0 auto;">
        <div class="cardSize" style="flex: 1 0 auto; display: flex;">
            <div class="cardPadding" style="display: flex;">
                <div class="card">
                    <div class="cardImageOuter">
                        <div class="cardImage">
                            <img src="./data/images/data-guide.svg" />
                        </div>
                    </div>
                    <div class="cardText">
                        <h3>Enterprise BI with SQL Data Warehouse</h3>
                        <p>Implements an ELT pipeline that moves data from an on-premises database into SQL Data Warehouse.</p>
                    </div>
                </div>
            </div>
        </div>
    </a>
</li>
<li style="display: flex; flex-direction: column;">
    <a href="./data/enterprise-bi-adf.md" style="display: flex; flex-direction: column; flex: 1 0 auto;">
        <div class="cardSize" style="flex: 1 0 auto; display: flex;">
            <div class="cardPadding" style="display: flex;">
                <div class="card">
                    <div class="cardImageOuter">
                        <div class="cardImage">
                            <img src="./data/images/data-guide.svg" />
                        </div>
                    </div>
                    <div class="cardText">
                        <h3>Automated enterprise BI with SQL Data Warehouse and Azure Data Factory</h3>
                        <p>Automates an ELT pipeline by using Azure Data Factory.</p>
                    </div>
                </div>
            </div>
        </div>
    </a>
</li>
</ul>

## VM workloads

<ul  class="panelContent cardsF">
<li style="display: flex; flex-direction: column;">
    <a href="./n-tier/n-tier-sql-server.md" style="display: flex; flex-direction: column; flex: 1 0 auto;">
        <div class="cardSize" style="flex: 1 0 auto; display: flex;">
            <div class="cardPadding" style="display: flex;">
                <div class="card">
                    <div class="cardImageOuter">
                        <div class="cardImage">
                            <img src="./n-tier/images/Windows.svg" height="140px" />
                        </div>
                    </div>
                    <div class="cardText">
                        <h3>N-tier application with SQL Server</h3>
                        <p>Virtual machines and a virtual network configured for an N-tier application using SQL Server on Windows.</p>
                    </div>
                </div>
            </div>
        </div>
    </a>
</li>

<!-- Multi-region Windows -->
<li style="display: flex; flex-direction: column;">
    <a href="./n-tier/multi-region-sql-server.md" style="display: flex; flex-direction: column; flex: 1 0 auto;">
        <div class="cardSize" style="flex: 1 0 auto; display: flex;">
            <div class="cardPadding" style="display: flex;">
                <div class="card">
                    <div class="cardImageOuter">
                        <div class="cardImage">
                            <img src="./n-tier/images/Windows.svg" height="140px" />
                        </div>
                    </div>
                    <div class="cardText">
                        <h3>Multi-region N-tier application with SQL Server</h3>
                        <p>N-tier application in two regions for high availability, using SQL Server Always On Availability Groups.</p>
                    </div>
                </div>
            </div>
        </div>
    </a>
</li>

<!-- N-tier Linux -->
<li style="display: flex; flex-direction: column;">
    <a href="./n-tier/n-tier-cassandra.md" style="display: flex; flex-direction: column; flex: 1 0 auto;">
        <div class="cardSize" style="flex: 1 0 auto; display: flex;">
            <div class="cardPadding" style="display: flex;">
                <div class="card">
                    <div class="cardImageOuter">
                        <div class="cardImage">
                            <img src="./n-tier/images/LinuxPenguin.svg" height="140px" />
                        </div>
                    </div>
                    <div class="cardText">
                        <h3>N-tier application with Cassandra</h3>
                        <p>Virtual machines and a virtual network configured for an N-tier application using Apache Cassandra on Linux.</p>
                    </div>
                </div>
            </div>
        </div>
    </a>
</li>

<!-- Jenkins -->
<li style="display: flex; flex-direction: column;">
    <a href="./jenkins/index.md" style="display: flex; flex-direction: column; flex: 1 0 auto;">
        <div class="cardSize" style="flex: 1 0 auto; display: flex;">
            <div class="cardPadding" style="display: flex;">
                <div class="card">
                    <div class="cardImageOuter">
                        <div class="cardImage">
                            <img src="./jenkins/images/logo.svg" height="140px" />
                        </div>
                    </div>
                    <div class="cardText">
                        <h3>Jenkins build server</h3>
                        <p>Scalable, enterprise-grade Jenkins server on Azure.</p>
                    </div>
                </div>
            </div>
        </div>
    </a>
</li>
<!-- SharePoint -->
<li style="display: flex; flex-direction: column;">
    <a href="./sharepoint/index.md" style="display: flex; flex-direction: column; flex: 1 0 auto;">
        <div class="cardSize" style="flex: 1 0 auto; display: flex;">
            <div class="cardPadding" style="display: flex;">
                <div class="card">
                    <div class="cardImageOuter">
                        <div class="cardImage">
                            <img src="./sharepoint/images/sharepoint.svg" height="140px" />
                        </div>
                    </div>
                    <div class="cardText">
                        <h3>SharePoint Server 2016 farm</h3>
                        <p>Highly available SharePoint Server 2016 farm on Azure with SQL Server Always On Availability Groups.</p>
                    </div>
                </div>
            </div>
        </div>
    </a>
</li>

<!-- SAP -->
<li style="display: flex; flex-direction: column;">
    <a href="./sap/sap-netweaver.md" style="display: flex; flex-direction: column; flex: 1 0 auto;">
        <div class="cardSize" style="flex: 1 0 auto; display: flex;">
            <div class="cardPadding" style="display: flex;">
                <div class="card">
                    <div class="cardImageOuter">
                        <div class="cardImage">
                            <img src="./sap/images/sap.svg" height="140px" />
                        </div>
                    </div>
                    <div class="cardText">
                        <h3>SAP NetWeaver for AnyDB</h3>
                        <p>SAP NetWeaver on Windows, in a high availability environment that supports disaster recovery.</p>
                    </div>
                </div>
            </div>
        </div>
    </a>
</li>
<li style="display: flex; flex-direction: column;">
    <a href="./sap/sap-s4hana.md" style="display: flex; flex-direction: column; flex: 1 0 auto;">
        <div class="cardSize" style="flex: 1 0 auto; display: flex;">
            <div class="cardPadding" style="display: flex;">
                <div class="card">
                    <div class="cardImageOuter">
                        <div class="cardImage">
                            <img src="./sap/images/sap.svg" height="140px" />
                        </div>
                    </div>
                    <div class="cardText">
                        <h3>SAP S/4HANA</h3>
                        <p>SAP S/4HANA on Linux, in a high availability environment that supports disaster recovery.</p>
                    </div>
                </div>
            </div>
        </div>
    </a>
</li>
<li style="display: flex; flex-direction: column;">
    <a href="./sap/hana-large-instances.md" style="display: flex; flex-direction: column; flex: 1 0 auto;">
        <div class="cardSize" style="flex: 1 0 auto; display: flex;">
            <div class="cardPadding" style="display: flex;">
                <div class="card">
                    <div class="cardImageOuter">
                        <div class="cardImage">
                            <img src="./sap/images/sap.svg" height="140px" />
                        </div>
                    </div>
                    <div class="cardText">
                        <h3>SAP HANA on Azure Large Instances</h3>
                        <p>HANA Large Instances are deployed on physical servers in Azure regions.</p>
                    </div>
                </div>
            </div>
        </div>
    </a>
</li>


</ul>


## Virtual network design




## Web applications


<!-- 
<section class="series">
    <ul class="panelContent">


<li style="display: flex; flex-direction: column;">
    <a href="./n-tier/index.md" style="display: flex; flex-direction: column; flex: 1 0 auto;">
        <div class="cardSize" style="flex: 1 0 auto; display: flex;">
            <div class="cardPadding" style="display: flex;">
                <div class="card">
                    <div class="cardImageOuter">
                        <div class="cardImage">
                            <img src="./n-tier/images/n-tier-sql-server.svg" />
                        </div>
                    </div>
                    <div class="cardText">
                        <h3>N-tier application</h3>
                        <p>Deploy an N-tier application to Azure, for Windows or Linux.</p>
                        <p>Configurations are shown for SQL Server and Apache Cassandra. For high availability, deploy an active-passive configuration in two regions.</p>
                    </div>
                </div>
            </div>
        </div>
    </a>
</li>

<li style="display: flex; flex-direction: column;">
    <a href="./hybrid-networking/index.md" style="display: flex; flex-direction: column; flex: 1 0 auto;">
        <div class="cardSize" style="flex: 1 0 auto; display: flex;">
            <div class="cardPadding" style="display: flex;">
                <div class="card">
                    <div class="cardImageOuter">
                        <div class="cardImage">
                            <img src="./hybrid-networking/images/vpn.svg" height="140px" />
                        </div>
                    </div>
                    <div class="cardText">
                        <h3>Hybrid network</h3>
                        <p>This series shows options for creating a network connection between an on-premises network and Azure.</p>
                        <p>Configurations include site-to-site VPN or Azure ExpressRoute for a private, dedicated connection.</p>
                    </div>
                </div>
            </div>
        </div>
    </a>
</li>
<li style="display: flex; flex-direction: column;">
    <a href="./dmz/index.md" style="display: flex; flex-direction: column; flex: 1 0 auto;">
        <div class="cardSize" style="flex: 1 0 auto; display: flex;">
            <div class="cardPadding" style="display: flex;">
                <div class="card">
                    <div class="cardImageOuter">
                        <div class="cardImage">
                            <img src="./dmz/images/secure-vnet-dmz.svg" height="140px" />
                        </div>
                    </div>
                    <div class="cardText">
                        <h3>Network DMZ</h3>
                        <p>This series shows how to create a network DMZ to protect the boundary between an Azure virtual network and an on-premises network or the Internet.</p>
                    </div>
                </div>
            </div>
        </div>
    </a>
</li>
<li style="display: flex; flex-direction: column;">
    <a href="./identity/index.md" style="display: flex; flex-direction: column; flex: 1 0 auto;">
        <div class="cardSize" style="flex: 1 0 auto; display: flex;">
            <div class="cardPadding" style="display: flex;">
                <div class="card">
                    <div class="cardImageOuter">
                        <div class="cardImage">
                            <img src="./identity/images/adds-extend-domain.svg" height="140px" />
                        </div>
                    </div>
                    <div class="cardText">
                        <h3>Identity management</h3>
                        <p>This series show options for integrating your on-premises Active Directory (AD) environment with an Azure network.</p>
                    </div>
                </div>
            </div>
        </div>
    </a>
</li>
<li style="display: flex; flex-direction: column;">
    <a href="./app-service-web-app/index.md" style="display: flex; flex-direction: column; flex: 1 0 auto;">
        <div class="cardSize" style="flex: 1 0 auto; display: flex;">
            <div class="cardPadding" style="display: flex;">
                <div class="card">
                    <div class="cardImageOuter">
                        <div class="cardImage">
                            <img src="./app-service-web-app/images/scalable-web-app.svg" height="140px" />
                        </div>
                    </div>
                    <div class="cardText">
                        <h3>App Service web application</h3>
                        <p>This series shows best practices for web applications that use Azure App Service.</p>
                    </div>
                </div>
            </div>
        </div>
    </a>
</li>
    </ul>
</section>

<ul class="panelContent cardsI">
<li style="display: flex; flex-direction: column;">
    <a href="./sap/index.md" style="display: flex; flex-direction: column; flex: 1 0 auto;">
        <div class="cardSize" style="flex: 1 0 auto; display: flex;">
            <div class="cardPadding" style="display: flex;">
                <div class="card">
                    <div class="cardImageOuter">
                        <div class="cardImage">
                            <img src="./sap/images/sap.svg" height="140px" />
                        </div>
                    </div>
                    <div class="cardText">
                        <h3>Run SAP on Azure</h3>
                        <p>Deploy and run SAP in a high availability environment on Azure.</p>
                    </div>
                </div>
            </div>
        </div>
    </a>
</li>
</ul>
-->