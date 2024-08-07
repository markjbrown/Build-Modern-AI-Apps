# Build & Modernize AI Applications

This page is intended as a home page for all of the Microsoft Official Build & Modernize AI Applications reference solutions and content.

## Solutions

The Solution Accelerators and Hackathons below are designed to demonstrate how to build AI-enabled applications and services in Azure. These production-ready solutions can be forked or cloned to help build prototypes for your organizations, helping you get started and reduce time to market. Each of the solution accelerator solutions below are also accompanied by a 1-2 day hackathon that provide a series of challenges for users to learn the concepts, technical skills and Azure Services used to build these types of applications.

### Build Your Own Copilot (Official Solution Accelerator)

[Navigate to Build Your Own Copilot](https://github.com/Azure/BuildYourOwnCopilot)

This is an in-depth production-quality solution accelerator with an advanced implemention. The scenario centers around a retail "Intelligent Agent" that allows users to ask questions (RAG Pattern) on vectorized product, customer and sales order data stored in Azure Cosmos DB.

This solution demonstrates many concepts developers will encounter when building Generative-AI applications including:

- Generating and storing vectors in real-time on transactional data.
- Performing vector searches on data in a database.
- Generating completions from a large language model.
- Managing conversational context and chat history.
- Token management for large langage models.
- Managing data models for defining what data gets vectorized for search.
- How to use Semantic Kernel SDK connectors, plug-ins, agents and planners.

[Build Your Own Copilot Hackathon](https://github.com/Azure/Build-Modern-AI-Apps-Hackathon)

![alt](architecture.png)


### Real-Time Payment and Transaction Processing

[Navigate to Real-Time Transaction Payment Processing](https://github.com/Azure/Real-time-Payment-Transaction-Processing-at-Scale)

The scenario centers around a payments and transactions solution. Members having accounts, each account with corresponding balances, overdraft limits and credit/debit transactions. Transaction data is replicated across multiple geographic regions for both reads and writes, while maintaining consistency. Updates are made efficiently with the patch operation. Business rules govern if a transaction is allowed. An AI powered co-pilot enables agents to analyze transactions using natural language.

[Real Time Transactions Hackathon Content](https://github.com/Azure/Real-Time-Transactions-Hackathon)

### Medical Claims Processing

[Navigate to Medical Claims Processing](https://github.com/Azure/Medical-Claims-Transaction-Processing-at-scale)

The scenario centers around a medical claims management solution. Members having coverage and making claims, providers who deliver services to the member and payers who provide the insurance coverage that pays providers for services to the members. Claims submitted are submitted in a stream and loaded into the backing database for review and approval. Business rules govern the automated or human approval of claims. An AI powered co-pilot empowers agents with recommendations on how to process the claim.

[Claims Processing Hackathon Content](https://github.com/Azure/Medical-Claims-Processing-Hackathon)

## Workshops

### Intelligent App Workshop for Microsoft Copilot Stack

The [Intelligent App Workshop for Microsoft Copilot Stack](https://copilotwksp.com/) is inspired by Github Copilot's impact on developer productivity. This experiential workshop is designed to demonstrate how you can infuse similar intelligence and product experience into traditional software systems. Using [Microsoft's Copilot stack](https://learn.microsoft.com/semantic-kernel/overview/#semantic-kernel-is-at-the-center-of-the-copilot-stack) and practical [use cases](https://copilotwksp.com/wksp/05-use-cases/#use-cases), this workshop will guide you in envisioning and creating intelligent systems that integrate foundation models throughout all stages of application development - from design and user experience to deployment.

By leveraging design thinking, [Project Miyagi](https://github.com/Azure-Samples/miyagi) which provides the underlying samples for this workshop, and art-of-the-possible examples (with samples and skills from [Semantic Kernel (SK)](https://github.com/microsoft/semantic-kernel), Project Miyagi, and [Reddog](https://github.com/Azure/reddog-solutions)), this workshop offers a comprehensive, hands-on exploration of how foundation models can augment your applications with intelligence to create hyper-personalized product experiences and improve productivity. We will also have an Architecture Design Session (ADS) to unlock and operationalize the full potential of AI-infused applications for your organization.

![alt](wip-azure.png)

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
