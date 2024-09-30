# Azure Open AI Prompt Component

## Description

The **Azure Open AI Prompt** component connects to Azure OpenAI's API (an LLM), processes an inputted natural language prompt, and returns the result as text. This component is useful for integrating Azure's powerful language models into your applications, allowing you to generate text based on a given prompt.

## Inputs

- **Prompt (str):** The natural language prompt to provide to the LLM. This can be manually inputted by the user or dynamically generated by the application.

## Output

- **Output (str):** The response provided by the LLM to the given prompt.

## Input Types

- **Prompt:** TEMPLATE

## Output Type

- **Output:** TEXT

## Configuration Parameters

To use the **Azure Open AI Prompt** component, the following configuration parameters are required:

- **model_name:** The name of the model to be used from Azure OpenAI's API.
- **openai_api_version:** The version of the Azure OpenAI API to be used.
- **deployment_name:** The name of the deployment in Azure where the OpenAI model is hosted.
- **openai_api_key:** The API key for authenticating with Azure OpenAI.
- **azure_endpoint:** The endpoint URL for accessing Azure's OpenAI service.

Ensure that these parameters are correctly configured to successfully connect to the Azure OpenAI service and generate the desired text outputs based on your prompts.

---

Feel free to integrate this component into your applications to leverage the advanced capabilities of Azure's language models for various natural language processing tasks.