---
title: Field-based stitching
description: Understand the prerequisites and limitations of stitching data using field-based stitching.
---

# Field-based stitching

Cross-device Analytics provides two distinct methods to stitch data together. This method relies on an Analytics variable, such as a [prop](/help/implement/vars/page-vars/prop.md) or [eVar](/help/implement/vars/page-vars/evar.md), to contain a person identifier. It uses that variable as a base to link devices together.

## Prerequisites specific to field-based stitching

If you intend to implement Cross-Device Analytics using field-based stitching, the following are required. Work with teams within your organization and your Adobe Account Manager to ensure that you meet all of the following.

>[!IMPORTANT]
>
>Failure to meet all prerequisites can result in the inability to enable Cross-Device Analytics or poor results when stitching data.

* All prerequisites listed on the [overview page](overview.md).
* Your implementation must set a prop or eVar that uniquely identifies an indivual whenever possible, such as when a user logs in or opens an email. This requirement applies to all platforms, including mobile apps if used. Communicate the desired identifying variable to your Account Manager when provisioned for Field-based stitching.

## Limitations specific to field-based stitching

* Field-based stitching works best on report suites that have a high user identification rate. If your report suite has a low identification or login rate, consider using the [Co-op graph](device-graph.md).

## Next steps

Once your organization meets all requirements met and understands the limitations, you can start [Setting up Cross-Device Analytics](setup.md).