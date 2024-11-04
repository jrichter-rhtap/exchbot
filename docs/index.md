# AI Software Template

This application, exbot, was created from an AI Software Template. These software templates create a new source code repository as well as a new gitops deployment repository.

Included in the source code repository will be the chosen sample source application.

## Sample Source Application

A Large Language Model (LLM)-enabled streamlit chat application. The bot replies with AI generated responses.

## Repositories

The source code for your application can be found in [https://github.com/jrichter-rhtap/exchbot ](https://github.com/jrichter-rhtap/exchbot ).
 
The gitops repository, which contains the kubernetes manifests for the application can be found in 
[https://github.com/jrichter-rhtap/exchbot-gitops ](https://github.com/jrichter-rhtap/exchbot-gitops ). 

## Application namespaces 

The default application will be found in the namespace: **`ai-rhdh-app-development`**. Applications can be deployed into their own unique namespace or multiple software templates can generate numerous applications into the same namespace.