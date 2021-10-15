# LWC-Memory-Test-App
App created using lightning web components that was built to display on a Salesforce Community page. 

See my example here: https://adaddario-developer-edition.na163.force.com/portfolio/s/lwc-development

## Deployment
### This app can be deployed using the manifest package.xml

1. Open a Salesforce Org and enable Dev Hub.
2. Open setup and enter "Digital Experience" using the quick find box.
3. Create a community page.
4. Enable the guest user permissions to see/interact with the app.

5. From the command line in the project folder run:

    `$ sfdx force:source:deploy -x manifest/package.xml`

6. Back in your Org open the community page and scroll to **Custom Components** then drag **memoryTest** onto the page.
7. Publish the page.