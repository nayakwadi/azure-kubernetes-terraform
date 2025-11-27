# Currency Exchange Micro Service - H2

This is a simple Java project which provides Currency Conversion Service using H2 for local storage and maven as build tool.
Install java, maven on your local machine
Open a command propmt, go to the project path folder where there is pom.xml file exists
execute below commands, one by one:
1. mvn clean
2. mvn build
3. mvn compile
4. mvn test
5. mvn install
6. mvn pacakge (this will display the path where .jar file is generated)
7. run command java -jar <path for .jar file from above step>
8. Open broweser and go to http://localhost:8000/currency-exchange/from/USD/to/INR

## Resources

- http://localhost:8000/currency-exchange/from/USD/to/INR

```json
{
  "id": 10001,
  "from": "USD",
  "to": "INR",
  "conversionMultiple": 65.00,
  "environmentInfo": "NA"
}
```



## Containerization

### Troubleshooting


### Creating Container


### Running Container

#### Basic

