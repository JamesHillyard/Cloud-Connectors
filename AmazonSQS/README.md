# Amazon SQS

These modules form the basis of the Amazon Simple Queue Service JCA connector. The code is in three modules
* AmazonSQSExample is an EJB jar module that shows a Timer Bean which sends a message periodically and an MDB that receives the message
* AmazonSQSJCAAPI is the bulk of the JCA code and the jar file which must be used as a provided dependency for any code using the JCA module
* AmazonSQSRAR is a maven module that assembles the rar file. The rar file should be deployed to your container.

To use the JCA adapter the AmazonSQSRAR-<version>.rar should be deployed to your application server.

To deploy the JCA adapter on Payara Micro use the following commands.

For more information, please view the full [technical documentation](https://docs.payara.fish/community/docs/Technical%20Documentation/Ecosystem/Connector%20Suites/Cloud%20Connectors/Amazon%20SQS.html).
