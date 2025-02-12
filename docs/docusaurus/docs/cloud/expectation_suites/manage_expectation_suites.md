---
sidebar_label: 'Manage Expectation Suites'
title: 'Manage Expectation Suites'
description: Create and manage Expectation Suites in GX Cloud.
---

Expectation Suites contain multiple Expectations for a single Data Asset. Like Expectations, they can help you better understand your data and help you improve data quality. A default Expectation Suite is created when you create a Data Asset. 

To learn more about Expectation Suites, see [Expectation Suites](/reference/learn/terms/expectation_suite.md).

## Prerequisites

- The GX Agent is running. See [Try GX Cloud](../try_gx_cloud.md) or [Connect GX Cloud](../connect/connect_lp.md).

- You have a [Data Asset](/cloud/data_assets/manage_data_assets.md#create-a-data-asset).

## Automatically create an Expectation Suite that tests for missing data

Automatically create an Expectation Suite that you can use to determine if your Data Asset contains missing data (null values). Creating Expectation Suites automatically saves you writing and then running the same code for each column in your Data Asset.

1. In GX Cloud, click **Data Assets** and select a Data Asset in the **Data Assets** list.

2. Click the **Expectations** tab.

3. Click **Create New Suite** in the **Expectation Suites** pane.

4. Click **Automatic (Experimental)**.

5. Click **Missingness** and then enter a name for the Expectation Suite in the **Suite name** field.

6. Click **Generate Expectations**. 

    It might take several minutes to create the Expectation Suite. When the process is complete, a new Expectation Suite appears in the **Expectation Suites** pane.

7. Optional. Run a Validation on the Expectation Suite. See [Run a Validation](/cloud/validations/manage_validations.md#run-a-validation).

## Create an empty Expectation Suite

If you have specific business requirements, or you want to examine specific data, you can create an empty Expectation Suite and then add Expectations individually.

1. In GX Cloud, click **Data Assets** and select a Data Asset in the **Data Assets** list.

2. Click the **Expectations** tab.

3. Click **Create New Suite** in the **Expectation Suites** pane.

4. Click **Manual**.

5. Enter a name for the Expectation Suite in the **Suite name** field.

6. Click **Generate Expectations**. 

7. Add Expectations to the Expectation Suite. See [Create an Expectation](/cloud/expectations/manage_expectations.md#create-an-expectation).

8. Optional. Run a Validation on the Expectation Suite. See [Run a Validation](/cloud/validations/manage_validations.md#run-a-validation).

## Edit an Expectation Suite name

1. In GX Cloud, click **Expectation Suites**.

2. Click **Edit** for the Expectation Suite you want to edit.

3. Edit the Expectation Suite name and then click **Save**.

4. Update the Expectation Suite name in all code that included the previous Expectation Suite name.

## Delete an Expectation Suite

1. In GX Cloud, delete all Checkpoints associated with the Expectation Suite. See [Delete a Checkpoint](/cloud/checkpoints/manage_checkpoints.md#delete-a-checkpoint). 

2. Click **Expectation Suites**.

3. Click **Delete** for the Expectation Suite you want to delete.

4. Click **Delete**.

## Related documentation

- [Manage Expectations](../expectations/manage_expectations.md)

- [Manage Validations](../validations/manage_validations.md)