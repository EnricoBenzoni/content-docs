---
id: integration-description
title: Integration Description File
---

The integration description file is designated to help the XSOAR users to easily configure an instance of the chosen integration.

## Path
The description file should be placed along with all of the integration's files. 

For example, if the Pack name is `HelloWorld` and the integration name is also `HelloWorld`, the description file path is:
```
~/.../content/Packs/HelloWorld/Integrations/HelloWorld/HelloWorld_description.md
```


## Data
The description file should contain details on how to configure an instance of the integration, together with the relevant details needed from the product that are important to perform an easy configuration.
The file's content can include troubleshooting tips and advanced details for different configuration cases.

:::note 
This should not be confused with the integration README file, documented [here](../integrations/integration-docs).
:::

## Example
This is the contents of the `HelloWorld_description.md` file:
```
## Hello World
- This section explains how to configure the instance of HelloWorld in Cortex XSOAR.
- You can use the following API Key: `43ea9b2d-4998-43a6-ae91-aba62a26868c`
```

To display the integration description, click on the question mark button in the integration configuration panel

![](../doc_imgs/integrations/description_question_mark.png)

The content of the description file will be displayed 

![](../doc_imgs/integrations/description.md_example.png)
