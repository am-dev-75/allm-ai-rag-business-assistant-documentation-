# allm-ai-rag-business-assistant-documentation-

Documentation about AnythingLLM-based Assistant conceived to deal with business knowledge base.

# Testbed

For setting up the testbeds, basically the same approach described [here](https://github.com/am-dev-75/cc-ai-rag-business-assistant-documentation) was followed. In this case, however, I didn't use [web-scraper-crawler-00 ](https://github.com/am-dev-75/web-scraper-crawler-00) for populating the vector database. Instead, I used the built-in function known as "Bulk Link Scraper".
Other relevant differences are noted explicitly if any.

# Knowledge base: [https://wiki.dave.eu](https://wiki.dave.eu)

## AnythingLLM version v1.8.4

DAVE Bot's anwer (golden answer): The maximum power consumption of the AURA SOM is up to 2W. Let us know how to contact you!


| Testbed setup<br /># | Workspace (1) | Language model<br />(2) | Embedder              | Vector count | Benchmark<br />"What is the maximum power consumption of AURA SoM?"<br /><br />(Only the first answer is tabulated. For more details, pleasee see the following sections.) |
| ---------------------- | --------------- | ------------------------- | ----------------------- | -------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1                    | wiki.dave.eu  | Llama3.2:3b              | Multilingual-E5-small |              |                                                                                                                                                                            |
|                      |               |                         |                       |              |                                                                                                                                                                            |

(1)

AnythingLLM allows to create separate workspaces, each one with its own settings.

(2)

Temperature set to 0. The other settings are left at their default values.
