---
title: Service Support
toc: false
---

# General support

- Australian BioCommons deploy and maintain the platform.

- Service accessibility and availability issues are supported.

- Personal workspaces are not supported by Australian BioCommons at this stage.  

- A live demo of using the service can be arranged during onboarding.

- User guide is available [here](/nextflow-seqera/user-guide/).

# Content/Science Support

Onboarded groups into the service are responsible to develop and maintain their workspaces. In some cases, Australian BioCommons can support the groups to accelerate their utilisation of the service if the following prerequisite list is satisfied.

## Prerequisite list

1. **Access to compute infrastructure**

    The community/organisation should have access to at least one compute infrastructure that will be configured on the Australian Nextflow Seqera Service. There are several supported platforms on Seqera and you can find them [here](https://docs.seqera.io/platform/latest/compute-envs/overview).

2. **Nextflow pipelines**

    The community/organisation should have Nextflow pipelines implemented and tested on the compute environments (from 1). Internally implemented pipelines, those reused from nf-core or any other resources are ok.
    Preferable: Implementation of config profiles that allows conda and docker executions for portability purposes.

3. **Testing datasets**

    For any pipeline, there should be testing datasets available during the deployment on the Australian Nextflow Seqera Service. This should include both small datasets for quick testing and real datasets for production testing.

4. **Nextflow expertise**

    The deployment and configuration of compute environments and pipelines should be led and driven by the community/organisation.  This requires the organisation to have dedicated resources with technical expertise in Nextflow, and infrastructure expertise, including HPC and commercial cloud (depending on the case).

    The dedicated resource with relevant expertise might need to do the following:

    - Implement changes to the pipeline (usually edits to the configuration profiles).
    - Configure, test and debug the pipelines on the community infrastructures.
    - Understand the available computational resources they access.
    - Require admin access to the compute infrastructure.
    - Manage user access to the community/organisation workspace.

    Australian BioCommons will provide all possible support with respect to the available resources.

<br />  

