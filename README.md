# AI-RHDH Standard Pipelines

> [!WARNING]
> This repository has been retired and will no longer be maintained. It has been moved to [redhat-developer/rhdh-ai-template-pipelines](https://github.com/redhat-developer/rhdh-ai-template-pipelines).

The Pipelines are in standard [tekton](https://tekton.dev/docs/) format and
they can be found in [./pac/pipelines](./pac/pipelines/), whereas the Tasks are located in [./pac/tasks](./pac/tasks/).

This pipeline repository was forked and customized from the RHTAP [pipeline definition](https://github.com/redhat-appstudio/tssc-sample-pipelines) and plans to act standalone from RHTAP.

## Backstage

Modify the template placeholders to match your Backstage template variables. 

For example, `{{values.rawUrl}}` and `{{ values.image }}` gets updated by the [ai-lab-template repository](https://github.com/redhat-ai-dev/ai-lab-template) script [update-tekton-definition](https://github.com/redhat-ai-dev/ai-lab-template/blob/33bda4738a82d71360ec98e111d16624e3392910/scripts/update-tekton-definition#L22-L23).
