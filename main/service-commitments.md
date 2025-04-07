---
title: The Australian Nextflow Seqera Service commitments
toc: true
---

# Definitions
Throughout this document, the following terms shall be defined as written below.

## Business Day

Monday to Friday, excluding any Australian Eastern Standard Time (AEST) public holidays.

## Business hours 
9 am - 5 pm Australian Eastern Standard Time (AEST)

## Australian BioCommons Service Contact

<seqera@biocommons.org.au>

## Operational Partners

1. Pawsey Supercomputing Research Centre (Pawsey, Western Australia).
2. Seqera (Spain).
3. National Computational Infrastructure (NCI, Australian Capital Territory)
4. Amazon Web Services (AWS) is the service host

## The Australian Nextflow Seqera Service

This represents the Nextflow Seqera Platform deployed by Australian BioCommons on AWS.

## The Australian Nextflow Seqera ecosystem

The Australian Nextflow Seqera ecosystem consists of three main components:
1. The Australian Nextflow Seqera Service: The web platform deployed on AWS.
2. Authentication: Mailserver at Pawsey.
3. Backend compute infrastructure: This is the compute backend where workflows will be submitted to and launched from the Service platforms. This includes the infrastructure provided by the Operational Partners such as GADI at NCI and Setonix at Pawsey, on-premises infrastructure provided by the users of the service and commercial cloud services such as AWS and Azure. 


# Support

## Best effort operations

We realise that the workflows you configure and run within the Australian Nextflow Seqera Service are important to you.  For that reason, we commit to making best endeavours to keep the service as reliable and responsive as possible, and to keep your data intact.

The Australian Nextflow Seqera Service is designed and engineered in best endeavours, however without warranty, to support reproducible science. 

During our business hours, we aim to triage tickets and support requests within one business day. Resolution of tickets, requests, outages and issues will take longer outside normal business hours, on weekends, and on public holidays.

## Content/Science Support

The users of the Australian Nextflow Seqera Service are responsible for developing their workspaces and maintaining them. This includes managing workspace memberships, management of compute environments, credentials, and workflows, as well as running and monitoring workflow execution. In some cases, when capacity is available, Australian BioCommons will support users that fulfil specific criteria as described at [Service Support](https://australianbiocommons.github.io/tower/main/support).


# Availability
The Nextflow Seqera ecosystem is expected to be available 24/7 apart from any planned maintenance periods of the Australian Nextflow Seqera Service and the compute backend infrastructures. However, interruption can happen and we aim to make sure that the service availability is at least 99% (95% outside normal business hours). 

For a specific user, the availability will impacted by two factors:
1. The availability of the Australian Nextflow Seqera Service.
2. The availability of any backend compute infrastructure they are utilising. For example, for a user using Pawsey HPC as a backend, the availability of NCI is not factored into the availability calculation.

## Availability of the Australian Nextflow Seqera Service

<table style="border-collapse: collapse; border: medium none; border-spacing: 0px;" width="80%">
	<tr>
		<td style="border-color: rgb(0, 0, 0); border-style: solid; border-width: 1px; padding-right: 3pt; padding-left: 3pt;" rowspan="2" width = "20%">
			<br>
		</td>
		<td style="border-color: rgb(0, 0, 0); border-style: solid; border-width: 1px; text-align: center; padding-right: 3pt; padding-left: 3pt;" colspan="2" width = "25%">
			<b>Availability</b>
		</td>
		<td style="border-color: rgb(0, 0, 0); border-style: solid; border-width: 1px; text-align: center; padding-right: 3pt; padding-left: 3pt;" rowspan="2" width = "35%">
			<b>Comments</b>
		</td>
		<td style="border-color: rgb(0, 0, 0); border-style: solid; border-width: 1px; text-align: center; padding-right: 3pt; padding-left: 3pt;" rowspan="2" width = "20%">
			<b>Contact</b>
		</td>
	</tr>
	<tr>
		<td style="border-color: rgb(0, 0, 0); border-style: solid; border-width: 1px; text-align: center; padding-right: 3pt; padding-left: 3pt;">
			<i>Business Hours</i>
		</td>
		<td style="border-color: rgb(0, 0, 0); border-style: solid; border-width: 1px; text-align: center; padding-right: 3pt; padding-left: 3pt;">
			<i>Other times</i>
		</td>
	</tr>
	<tr>
		<td style="border-color: rgb(0, 0, 0); border-style: solid; border-width: 1px; text-align: center; padding-right: 3pt; padding-left: 3pt;">
			Nextflow Seqera available<wbr>
		</td>
		<td style="border-color: rgb(0, 0, 0); border-style: solid; border-width: 1px; text-align: center; padding-right: 3pt; padding-left: 3pt;"> 99%
		</td>
		<td style="border-color: rgb(0, 0, 0); border-style: solid; border-width: 1px; text-align: center; padding-right: 3pt; padding-left: 3pt;"> 95%
		</td>
		<td style="border-color: rgb(0, 0, 0); border-style: solid; border-width: 1px; padding-right: 3pt; padding-left: 3pt;">
        This is only for the web portal independent of the backend compute infrastructure availability. 
		</td>
		<td style="border-color: rgb(0, 0, 0); border-style: solid; border-width: 1px; padding-right: 3pt; padding-left: 3pt;">
        seqera@biocommons.org.au
        </td>
	</tr>
</table>

## Availability of the Australian Nextflow Seqera ecosystem
This relies on both the availability of the Australian Nextflow Seqera Service as well as the backend compute environments. 

<table style="border-collapse: collapse; border: medium none; border-spacing: 0px;" width="80%">
	<tr>
		<td style="border-color: rgb(0, 0, 0); border-style: solid; border-width: 1px; padding-right: 3pt; padding-left: 3pt;" rowspan="2" width = "20%">
			<br>
		</td>
		<td style="border-color: rgb(0, 0, 0); border-style: solid; border-width: 1px; text-align: center; padding-right: 3pt; padding-left: 3pt;" colspan="2" width = "25%">
			<b>Availability</b>
		</td>
		<td style="border-color: rgb(0, 0, 0); border-style: solid; border-width: 1px; text-align: center; padding-right: 3pt; padding-left: 3pt;" rowspan="2" width = "35%">
			<b>Comments</b>
		</td>
		<td style="border-color: rgb(0, 0, 0); border-style: solid; border-width: 1px; text-align: center; padding-right: 3pt; padding-left: 3pt;" rowspan="2" width = "20%">
			<b>Contact</b>
		</td>
	</tr>
	<tr>
		<td style="border-color: rgb(0, 0, 0); border-style: solid; border-width: 1px; text-align: center; padding-right: 3pt; padding-left: 3pt;">
			<i>Business Hours</i>
		</td>
		<td style="border-color: rgb(0, 0, 0); border-style: solid; border-width: 1px; text-align: center; padding-right: 3pt; padding-left: 3pt;">
			<i>Other times</i>
		</td>
	</tr>
	<tr>
		<td style="border-color: rgb(0, 0, 0); border-style: solid; border-width: 1px; text-align: center; padding-right: 3pt; padding-left: 3pt;">
			The service available at Pawsey<wbr>
		</td>
		<td style="border-color: rgb(0, 0, 0); border-style: solid; border-width: 1px; text-align: center; padding-right: 3pt; padding-left: 3pt;"> 99%
		</td>
		<td style="border-color: rgb(0, 0, 0); border-style: solid; border-width: 1px; text-align: center; padding-right: 3pt; padding-left: 3pt;"> 95%
		</td>
		<td style="border-color: rgb(0, 0, 0); border-style: solid; border-width: 1px; padding-right: 3pt; padding-left: 3pt;">
        <a href="https://status.pawsey.org.au/"> Setonix Status</a> 
		</td>
		<td style="border-color: rgb(0, 0, 0); border-style: solid; border-width: 1px; padding-right: 3pt; padding-left: 3pt;">
        <a href="mailto:help@pawsey.org.au">Helpdesk: help@pawsey.org.au</a>
        </td>
	</tr>
    <tr>
		<td style="border-color: rgb(0, 0, 0); border-style: solid; border-width: 1px; text-align: center; padding-right: 3pt; padding-left: 3pt;">
			The service available at NCI<wbr>
		</td>
		<td style="border-color: rgb(0, 0, 0); border-style: solid; border-width: 1px; text-align: center; padding-right: 3pt; padding-left: 3pt;"> 99%
		</td>
		<td style="border-color: rgb(0, 0, 0); border-style: solid; border-width: 1px; text-align: center; padding-right: 3pt; padding-left: 3pt;"> 95%
		</td>
		<td style="border-color: rgb(0, 0, 0); border-style: solid; border-width: 1px; padding-right: 3pt; padding-left: 3pt;">
        <a href="https://nci.org.au/our-systems/status"> GADI Status</a>
		</td>
		<td style="border-color: rgb(0, 0, 0); border-style: solid; border-width: 1px; padding-right: 3pt; padding-left: 3pt;">
        <a href="mailto:help@nci.org.au">Helpdesk: help@nci.org.au</a>
        </td>
	</tr>
    <tr>
		<td style="border-color: rgb(0, 0, 0); border-style: solid; border-width: 1px; text-align: center; padding-right: 3pt; padding-left: 3pt;">
			The service available on AWS<wbr>
		</td>
		<td style="border-color: rgb(0, 0, 0); border-style: solid; border-width: 1px; text-align: center; padding-right: 3pt; padding-left: 3pt;"> 99%
		</td>
		<td style="border-color: rgb(0, 0, 0); border-style: solid; border-width: 1px; text-align: center; padding-right: 3pt; padding-left: 3pt;"> 95%
		</td>
		<td style="border-color: rgb(0, 0, 0); border-style: solid; border-width: 1px; padding-right: 3pt; padding-left: 3pt;">
        </td>
		<td style="border-color: rgb(0, 0, 0); border-style: solid; border-width: 1px; padding-right: 3pt; padding-left: 3pt;">
        </td>
	</tr>
    <tr>
		<td style="border-color: rgb(0, 0, 0); border-style: solid; border-width: 1px; text-align: center; padding-right: 3pt; padding-left: 3pt;">
			Other compute backend<wbr>
		</td>
		<td style="border-color: rgb(0, 0, 0); border-style: solid; border-width: 1px; text-align: center; padding-right: 3pt; padding-left: 3pt;"> 99%
		</td>
		<td style="border-color: rgb(0, 0, 0); border-style: solid; border-width: 1px; text-align: center; padding-right: 3pt; padding-left: 3pt;"> 95%
		</td>
		<td style="border-color: rgb(0, 0, 0); border-style: solid; border-width: 1px; padding-right: 3pt; padding-left: 3pt;">
        If you are using your own compute infrastructure, you will be affected by the availability of Nextflow Seqera Platform and your own compute backend only. 
		</td>
		<td style="border-color: rgb(0, 0, 0); border-style: solid; border-width: 1px; padding-right: 3pt; padding-left: 3pt;">
        </td>
	</tr>
</table>

#  Lifetime of the Australian Nextflow Seqera Service

Service funding is confirmed until May 2026. Australian BioCommons aims to continue to support the service in the future - user demand and interest in the service will assist in justifying continued funding.
In the unlikely event of service closure, registered account holders will be notified one year in advance.

# Maintenance

## Australian Nextflow Seqera Service maintenance

The maintenance and administration of the Australian Nextflow Seqera Service is a balance between service uptime and the health of the service. From time to time, the service may become unavailable during planned or unscheduled maintenance events. In addition, as the service is deployed on AWS, it may be affected by the availability of AWS services. 

### Planned maintenance

Planned maintenance will occur to upgrade the service, expand its capacity and fix non-urgent issues. During these planned maintenance periods, the service may not be available.
Notification of planned service unavailability will be made via a notice on the Australian Nextflow Seqera Service and via email to registered account holders. The period of notice varies depending on the length of the planned service unavailability:

| Planned Downtime | Advanced Notice period|
| ---------------- | ------------------|
| < 10 minutes | Without notice |
| 1 hour  | 1 day |
| 1 day | 1 week |
| 1 week | 1 month|



### Unscheduled maintenance

On occasion, the Australian Nextflow Seqera Service may need to perform urgent maintenance (e.g. for urgent security patching) resulting in service downtime outside of scheduled and planned maintenance windows. In this case, we will make every effort to give users as much advance notice as possible to limit disruption.

## Nextflow Seqera ecosystem maintenance 

In addition to the Australian Nextflow Seqera Service maintenance described above, there will be planned and unplanned maintenance from the other components of the Nextflow Seqera ecosystem such as the compute backed on GADI and Setonix.

Updates on the status of these backends are available at:

- <a href="https://status.pawsey.org.au/"> Setonix Status</a>
- <a href="https://nci.org.au/our-systems/status"> GADI Status</a>
