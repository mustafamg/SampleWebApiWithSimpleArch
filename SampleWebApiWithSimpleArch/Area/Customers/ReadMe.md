Customer is a sample module. So, each module will have a folder under area. Each module will contain the following:
- Controllers: Web Api gateway to make service available to external world
- Dtos: Data Transfer Object which represent the bussiness to the UI or Outside world
- Services: Use the default repo and extend its functionlity if needed with any more business logic added as well
- Entities: Local representation for the module data (more db related)
- Validations and Business rules specific for that module
- Custom exception for that module
- don't forget to log all exceptions.
