# Design strategies for archieving high availaibility

# Strategies for achieving high availaibility

* Error prevention
    * Use transactions
    * Input validation

* Error detection
    * Monitoring - Critical metrics neeed to be published and agreggated to be monitored
    * Validate accurancy of results

* Error handling
    * Create machanisms for robust exception handling
        * Retries
        * double server
        * Fail traids to retry
    * Transacion rollback
    * Keep multiple availabiliti zones or instances in different computers


