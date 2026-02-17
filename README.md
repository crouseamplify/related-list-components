# Related List Components for LWR

A collection of Lightning Web Components for displaying related lists, files, and case articles in Salesforce Lightning Web Runtime (LWR) sites.

## Components

### Lightning Web Components
- **relatedListLWR** - Main related list component for LWR sites
- **relatedFiles** - Display and manage related files
- **caseArticles** - Display case-related knowledge articles
- **relatedListLWRCpe** - Configuration component for the related list

### Apex Controllers
- **RelatedListLWRController** - Backend logic for related list operations
- **RelatedFilesController** - Handles file operations and retrieval
- **CaseArticlesController** - Manages case article queries

### Test Classes
- **RelatedListControllerLWRTest** - Test coverage for RelatedListLWRController
- **RelatedFilesControllerTest** - Test coverage for RelatedFilesController
- **CaseArticlesControllerTest** - Test coverage for CaseArticlesController

## Deployment

Deploy to your Salesforce org using Salesforce CLI:

```bash
sf project deploy start --source-dir force-app
```

## Resources

- [Salesforce Extensions Documentation](https://developer.salesforce.com/tools/vscode/)
- [Salesforce CLI Setup Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_setup.meta/sfdx_setup/sfdx_setup_intro.htm)
- [LWR Sites Documentation](https://developer.salesforce.com/docs/platform/lwr/overview)
