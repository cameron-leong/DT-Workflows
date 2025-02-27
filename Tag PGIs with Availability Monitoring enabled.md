The ``Tag PGIs with Availability Monitoring enabled`` Workflow finds each process group which has availability monitoring enabled at the PG level and tags the PG and each PGI with AvailabilityMonitoring:enabled.

Limitations: The page size limit is 500 for the settings objects client. If you have more than 500 PGs with availability monitoring enabled, you will need to add logic to handle the rest of the entries using the nextPageKey.
