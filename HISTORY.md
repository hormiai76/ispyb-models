# History

## Unreleased / main

## v1.2.5 (26/11/2024)

Update `fyleType` Enum values in the `SSXProcessingResultAttachment` table.


## v1.2.5 (26/11/2024)

Make `dataCollectionId` mandatory in the `SSXProcessingResult` table.
Create a new entry in the `Permission` table to be used by beamine service accounts.

## v1.2.4 (13/11/2024)

Add `nbCrystals` to `SSXProcessingResult` table.

## v1.2.3 (11/11/2024)

Add `LineScan` and `GphNative` to `DataCollectionGroup.experimentType`.


## v1.2.2 (13/09/2024)

Create new tables

-   SSXProcessingResult
-   SSXProcessingResultAttachment


## v1.1.0 (17/01/2023)

Create new tables:

-   SSXDataCollection
-   Component
-   SampleComposition
-   CrystalComposition
-   EventChain
-   EventType
-   Event

Add `SSX-Chip` and `SSX-Jet` to `DataCollectionGroup.experimentType`.

## v1.0.0 (20/07/2022)

-   Regenerate models automatically with recent sqlacodegen (breaking: removes deprecated `backref` option)

## v0.0.3 (18/07/2022)

-   Initial release
-   Absolute basic tests
-   Generate update pr automatically
-   Publish to pypi
