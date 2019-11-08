# HelloAzure
Contains an example project outlining the process of building a CI/CD pipeline with azure, and deploying a function.

The project contains a single .NET Core Solution.
* `HelloAzure`

The solution has two projects
* `HelloAzure.BusinessLogic`
    * Contains contrived business logic to simulate referencing a shared library in a .NET Core Azure Function
* `HelloAzure.Function`
    * Contains a single Azure Function that can be called via HTTP and will return a greeting for a specified name.
    
There is a wiki available [here](https://github.com/jsmithdenverdev/HelloAzure/wiki) that provides a deep dive into setting up a similar project. The wiki also covers testing a function locally, deploying it to Azure, and automating the deployment process using a CI/CD pipeline.
