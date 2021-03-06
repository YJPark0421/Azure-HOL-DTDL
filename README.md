# Azure Digital Twin HOL(Hands On Lab) 

## 1️⃣ Overview
   
### ◽ Development Environment
page_type | languages | products
:------:|:------:|:------:
`Dev`|`C#` `DTDL`|`Azure` `Azure Digital Twin` `Azure Function` `Event Grid` `IoT hub`
---

### ◽ Architecture
<p align="left"> <img src="https://user-images.githubusercontent.com/88306533/128794979-4865d0aa-ac02-4e7d-ae46-03857d6301a2.png" width="90%" height="90%"></img></p>

---

### ◽ Objective
   - [x] Create an instance of Azure Digital Twins by using the Azure portal.
   - [x] Create digital models for the production line of a chocolate factory.
   - [x] Validate the digital models by using the validator sample.
   - [x] Create a graph of the models by using the Azure Digital Twins explorer sample.
   - [x] Query the graph by using SQL-like queries.
---

### ◽ Scenario of HOL : A chocolate manufacturing company(Contoso Chocolate) 
**The following image shows the production line:**
<p align="left"> <img src="https://user-images.githubusercontent.com/88306533/128786638-a10562e3-748b-40a0-8b21-81e51c80451d.png" width="50%" height="50%"></img></p>

> **① Roasting**
> <br>
> The roasting process cooks fermented cocoa beans. The temperature and time of cooking depends on the type of beans, but typically the roasting (sometimes called fanning in the chocolate trade) might take 35 minutes at 250 to 300 degrees Fahrenheit. Roasting aids the removal of unwanted stuff, such as acetic acid, and the formation of the sweet taste of cocoa.
> <br> 
> **② Grinding**
> <br> 
> The grinding process takes the cocoa nibs that result from the roasting and crushes them to pieces, typically between steel plates, to create a liquid cocoa butter.
> <br> 
> **③ Molding**
> <br> 
> The molding process cools the cocoa butter in molds, giving the desired shape: chocolate bars, egg shells, and figures. The following image shows roasted cocoa nibs:  
---  
<br>

## 2️⃣ PreRequirement
### ◽ Setup a development environment (Windows 10)
> - [Install **`.NET Core 3.1`**](https://dotnet.microsoft.com/download)
> - [Install **`Visual Studio Code`**](https://code.visualstudio.com/)
> - [Install VS Code **`C# Extension`**](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp)
> - [Install VS Code **`Azure Function Extension`**](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azurefunctions)
> - [Install **`Git`**](https://git-scm.com/downloads)
> - [Install **`Node.js`**](https://nodejs.org/ko/download/)
> - [Install **`Azure CLI 2.0`**](https://docs.microsoft.com/ko-kr/cli/azure/install-azure-cli)
---
<br>

## 3️⃣ Methodology
### ◽ A Step-By-Step Guide to Azure Digital Twin Test**
> - [Guide 1 Build an Azure Digital Twins graph for a chocolate factory production line (90m)](https://docs.microsoft.com/ko-kr/learn/modules/build-azure-digital-twins-graph-for-chocolate-factory/)
> - [HOL 1 Azure Digital Twin HOL(180m)](https://github.com/ilseokoh/iot-hol/tree/master/ADT)
---
<br>

## 4️⃣ Reference

> **ADT Related Github Page**
> - [Digital Twins Definition Language (DTDL)](https://github.com/Azure/opendigitaltwins-dtdl/blob/master/DTDL/v2/dtdlv2.md)
> - [Azure Digital Twin Demo with Azure Data explorer](https://github.com/ilseokoh/adt-adx-demo)
---
> **Ontology building for Industries**
> - [RealEstateCore, a smart building ontology for digital twins, is now available](https://techcommunity.microsoft.com/t5/internet-of-things/realestatecore-a-smart-building-ontology-for-digital-twins-is/ba-p/1914794)
> - [Smart Cities Ontology for Digital Twins](https://techcommunity.microsoft.com/t5/internet-of-things/smart-cities-ontology-for-digital-twins/ba-p/2166585)
---
> **Domestic Customer Use Case**
> - [Doosan Manufacturing Azure Digital Twins](https://customers.microsoft.com/en-us/story/848311-doosan-manufacturing-azure-digital-twins)
---
> **Deep Dive Yotube Content**
> - [Deep Dive: Azure Digital Twins for smart buildings: A look into WillowTwin solution](https://www.youtube.com/watch?v=Kbv1a_74FC0)
> - [RealEstateCore, a smart building ontology for digital twins](https://www.youtube.com/watch?v=mN0pAvC2pAo&list=RDCMUCL7wy-iy_V76xxPnrIzGOZQ&index=3)
> - [Deep Dive: Azure Digital Twins Updated Capabilities](https://channel9.msdn.com/Shows/Internet-of-Things-Show/Deep-Dive-Azure-Digital-Twins-Updated-Capabilities)
> - [Deep Dive: Integrating 3D Models and IoT data with iTwin and Azure Digital Twins](https://channel9.msdn.com/Shows/Internet-of-Things-Show/Deep-Dive-Integrating-3D-Models-and-IoT-data-with-iTwin-and-Azure-Digital-Twins?term=Bentley&lang-en=true)
