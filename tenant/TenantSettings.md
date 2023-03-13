## Main Settings

### Help and support
| Settings | Description | Recomended Value |
|:------------------------:|:-----------------------:|:-----------:|
| [Publish "Get Help" information](https://docs.microsoft.com/en-us/power-bi/guidance/admin-tenant-settings#publish-get-help-information) | Custom URLs which can replace the built-in URLs on the help menu | Set relevant values | 
| [Receive email notifications for service outages or incidents](https://docs.microsoft.com/en-us/power-bi/guidance/admin-tenant-settings#receive-email-notification-service-outages-or-incidents) | Specifies which group which is informed via e-mail when an incident is occurring which impacts reliability | Add mail-enabled group for Power BI Support | 
| [Allow users to try Power BI paid features](https://learn.microsoft.com/en-us/power-bi/admin/service-admin-portal-help-support#allow-users-to-try-power-bi-paid-features) | This setting increases your control over how users get license upgrades. In scenarios where you have blocked self-service purchase, this setting lets users use more features free for 60 days | Enable |
| [Show a custom message before publishing reports](https://learn.microsoft.com/en-us/power-bi/admin/service-admin-portal-help-support#show-a-custom-message-before-publishing-reports) | Allows the admin to provide a custom message that appears before a user publishes a report from Power BI Desktop | Recomended Value |

### Workspaces
| Settings | Description | Recomended Value |
|:------------------------:|:-----------------------:|:-----------:|
| [Create workspaces](https://docs.microsoft.com/en-us/power-bi/guidance/admin-tenant-settings#create-workspaces) | Specifies which Power BI Pro users in the organization are permitted to create new workspaces. | Enable only as needed, supported by a resposive workspace creation request process | 
| [Use datasets across workspaces](https://docs.microsoft.com/en-us/power-bi/connect-data/service-datasets-admin-across-workspaces) | Permits report designers to create reports in one workspace that connect to datasets in a different workspace, assuming the requisite permissions have been granted fot the dataset | Enable for all users | 

### Information Protection
| Settings | Description | Recomended Value |
|:------------------------:|:-----------------------:|:-----------:|
|[Allow users to apply sensitivity labels for Power BI content](https://learn.microsoft.com/en-us/power-bi/enterprise/service-security-enable-data-sensitivity-labels#apply-sensitivity-labels-from-data-sources-to-their-data-in-power-bi)|Specifies which users in the organization are permitted to apply sensitivity labels to content published in the Power BI service | Allow for all content authors. Keep in mind that Sensitivity labels have other associated costs and can complicate report source control. [Label limits in Power BI](https://learn.microsoft.com/en-us/power-bi/enterprise/service-security-sensitivity-label-overview#considerations-and-limitations)|
|[Apply sensitivity labels from data sources to their data in Power BI](https://learn.microsoft.com/en-us/power-bi/enterprise/service-security-sensitivity-label-inheritance-from-data-sources)|Allows labels in a data source to be tagged to Power BI Artifacts|Enable if using labels in your organisation|
|[Automatically apply sensitivity labels to downstream content](https://learn.microsoft.com/en-us/power-bi/enterprise/service-security-sensitivity-label-downstream-inheritance#downstream-inheritance-modes)|Enables the automatic passing of labels to downstream content. i.e. from dataset to a new report.|Enable if using labels in your organisation to assist content owners to in managing labels|
|[Allow workspace admins to override automatically applied sensitivity labels](https://learn.microsoft.com/en-us/power-bi/enterprise/service-security-sensitivity-label-change-enforcement)|Allows for automatic labelling to be effective but overridable by workspace admins|Enable if using labels in your organisation to assist with auto-labelling accuracy and adoption.|
|[Restrict content with protected labels from being shared via link with everyone in your organization](https://learn.microsoft.com/en-us/power-bi/admin/service-admin-portal-information-protection#restrict-content-with-protected-labels-from-being-shared-via-link-with-everyone-in-your-organization) |Helps limit mass sharing of protected content. For example, your organization may have a "Highly Confidential" label that includes encryption and applies a "Highly Confidential" watermark to content with this label. Therefore, when this tenant setting is enabled and a report has a sensitivity label with protection settings, then users can't create sharing links for People in your organization:|Enable if using labels in your organisation|


### Export and Sharing
| Settings | Description | Recomended Value |
|:------------------------:|:-----------------------:|:-----------:|
| [Allow Azure Active Directory guest users to access Power BI](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#allow-azure-active-directory-guest-users-to-access-power-bi) | Enabling this setting allows Azure Active Directory Business-to-Business (Azure AD B2B) guest users to access Power BI | This setting should be aligned with the organization’s security policy | 
| [Invite external users to your organization](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#invite-external-users-to-your-organization) | The Invite external users to your organization setting helps organizations choose whether new external users can be invited to the organization through Power BI sharing and permissions experiences | This setting should be aligned with the organization’s security policy |
| [Allow external guest users to edit and manage content in the organization](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#allow-external-guest-users-to-edit-and-manage-content-in-the-organization) | Azure AD B2B guest users can edit and manage content in the organization | This setting should be aligned with the organization’s security policy |
| [Show Azure Active Directory guests in lists of suggested people](https://learn.microsoft.com/en-us/power-bi/admin/service-admin-portal-export-sharing#show-azure-active-directory-guests-in-lists-of-suggested-people) | Azure AD B2B guest users can bee seen in permissions dropdowns and search | This setting should be aligned with the organization’s security policy |
| [Publish to Web](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#publish-to-web) | As a Power BI admin, the Publish to web setting gives you options that let users create embed codes to publish reports to the web. This functionality makes the report and its data available to anyone on the web | Only enable for users who have a legitimate need to publish data publicly |
| [Copy and paste visuals](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#copy-and-paste-visuals) | Users in the organization can copy visuals from a tile or report visual and paste them as static images into external applications |  Should usually be enabled for all users without any limitations for maximum productivity. Disable to handle specific confidentiality scenarios |
| [Export to Excel](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#export-to-excel) | Users in the organization can export the data from a visualization to an Excel file | Should usually be enabled for all users without any limitations for maximum productivity | 
| [Export to .csv](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#export-to-csv) | Users in the organization can export data from a tile, visualization, or paginated report to a .csv file | Should usually be enabled for all users without any limitations for maximum productivity | 
| [Export reports as PowerPoint or PDF documents](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#export-reports-as-powerpoint-presentations-or-pdf-documents) | Users in the organization can export reports as PowerPoint files or PDF documents | Should usually be enabled for all users without any limitations for maximum productivity | 
| [Export reports as MHTML documents](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#export-reports-as-mhtml-documents) | Users in the organization can export Paginated reports as MHTML documents | Should usually be enabled for all users without any limitations for maximum productivity |
| [Export reports as Word documents](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#export-reports-as-word-documents) | Users in the organization can export Paginated reports as Word documents | Should usually be enabled for all users without any limitations for maximum productivity |
| [Export reports as XML documents](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#export-reports-as-xml-documents) | Users in the organization can export Paginated reports as XML documents | Should usually be enabled for all users without any limitations for maximum productivity |
| [Export reports as image files (preview)](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#export-reports-as-image-files-preview) | Users in the organization can use the export report to file API to export reports as image files | Should usually be enabled for all users without any limitations for maximum productivity |
| [Print dashboards and reports](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#print-dashboards-and-reports) | Users are able to print reports and dashboards in the Power BI service | Should usually be enabled for all users without any limitations for maximum productivity |
| [Download reports](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#download-reports) | Users in the organization can download .pbix files and paginated reports | N/A | 
| [Allow live connections](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#allow-live-connections) | Users in the organization can use Power BI service Live Connect. This includes Analyze in Excel | Should usually be enabled for all users without any limitations for maximum productivity.  | 
| [Certification](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#certification) | Allow users in this org to certify datasets, dataflows, reports, and apps | The ability to certify content should be restricted to a small group of subject matter experts | 
| [Featured content](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#certification) | Allow some or all report authors in your organization to feature their content on the Featured section of Power BI Home | Start with a small set of promoters first. Allowing the entire organization to feature content on Home may make it difficult to keep track of all the promoted content | 
| [Allow connections to featured tables](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#allow-connections-to-featured-tables) | This setting lets Power BI admins control who in the organization can use [featured tables](https://docs.microsoft.com/en-us/power-bi/collaborate-share/service-excel-featured-tables) in the Excel Data Types Gallery | Should usually be enabled for maximum productivity |
| [Email Subscriptions](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#email-subscriptions) | Users in the organization can create email subscriptions | Should usually be enabled for maximum productivity |
| [Share to Teams](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#share-to-teams) | This setting allows organizations to hide the Share to Teams buttons in the Power BI service | Should usually be enabled for maximum productivity |

### Apps
| Settings | Description | Recomended Value |
|:------------------------:|:-----------------------:|:-----------:|
| [Publish apps to the entire organization](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#publish-content-packs-and-apps-to-the-entire-organization) | Permits publishing of apps to the entire organization, rather than specific groups | Restrict to BI teams |
| [Create template apps](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#create-template-apps-and-organizational-content-packs) | Permits the creation of [template apps](https://docs.microsoft.com/en-us/power-bi/connect-data/service-template-apps-create) | Restrict to BI teams |
| [Push apps to end users](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#push-apps-to-end-users) | Allows the ability to automatically install a published app on the users’ Apps menu | Restrict to BI teams |

### Integration
| Settings | Description | Recomended Value |
|:------------------------:|:-----------------------:|:-----------:|
| [Allow XMLA endpoints and Analyze in Excel with on-premises datasets](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#allow-xmla-endpoints-and-analyze-in-excel-with-on-premises-datasets) | Users in the organization can use Excel to view and interact with on-premises Power BI datasets | Should be enabled for Analysis Services on prem, if used |
| [Use ArcGIS Maps for Power BI](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#use-arcgis-maps-for-power-bi) | Users in the organization can use the ArcGIS Maps for Power BI visualization provided by Esri | Should be disabled if the organization does not use Esri services for mapping |
| [Use global search for Power BI](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#use-global-search-for-power-bi-preview) | Users in the organization can use external search features that rely on Azure Search | Typically, there are no concerns with this being enabled. Content would be very difficult to locate without the search functionality |
| [R visuals settings](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#r-visuals-settings) | Users in the organization can interact with and share visuals created with R scripts | Since R visuals can potentially represent data privacy or data leakage concerns, depending on the individual developer, this should be used with a measure of caution |

### Audit and usage
| Settings | Description | Recomended Value |
|:------------------------:|:-----------------------:|:-----------:|
| [Create audit logs for internal activity auditing and compliance](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#create-audit-logs-for-internal-activity-auditing-and-compliance) | Permits actions taken in Power BI to be captured in the audit logs in Office 365 | Should be enabled |
| [Usage metrics for content creators](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#usage-metrics-for-content-creators-1) | Permits individuals to view the usage metrics related to the dashboards and reports they published | Should be enabled so that content creators are able to understand the effectiveness of the solutions they create |
| [Per-user data in usage metrics for content creators](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#per-user-data-in-usage-metrics-for-content-creators-1) | Usage metrics for content creators will expose display names and email addresses of users who are accessing content | Typically enabled. Hiding names and e-mail addresses from certain content authors would usually be an exception; the ability to contact users directly about how they use the content can be very valuable to improving the content |

### Dashboard
| Settings | Description | Recomended Value |
|:------------------------:|:-----------------------:|:-----------:|
| [Data classification for dashboards](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#data-classification-for-dashboards) | Users in the organization can tag dashboards with classifications that indicate dashboard security levels | Sensitivity labels in conjunction with Microsoft Information Protection should be used instead of data classifications |
| [Web content on dashboard tiles](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#web-content-on-dashboard-tiles) | Users in the organization can add and view web content tiles on Power BI dashboards |  Typically enabled, though if the organization has a more restrictive security policy this could be restricted |

### Developer
| Settings | Description | Recomended Value |
|:------------------------:|:-----------------------:|:-----------:|
| [Embed content in apps](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#embed-content-in-apps) | Users in the organization can embed Power BI dashboards and reports in Software as a Service (SaaS) applications |  Should be enabled only for specific groups, such as custom developers, as appropriate |
| [Allow service principals to use Power BI APIs](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#allow-service-principals-to-use-power-bi-apis) | Web apps registered in Azure Active Directory (Azure AD) will use an assigned service principal to access Power BI APIs without a signed in user | Should be enabled for a tightly controlled list of service principals |

### Template app
| Settings | Description | Recomended Value |
|:------------------------:|:-----------------------:|:-----------:|
| [Publish Template Apps](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#publish-template-apps) | Users in the organization can create template apps workspaces |  Typically disabled by most organizations, as this is usually only applicable to software vendors who publish template apps to AppSource |
| [Install template apps listed on AppSource](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#install-template-apps-listed-on-appsource) | Specifies who may use template apps which are found in AppSource, such as Salesforce or Google Analytics | Should be enabled to encourage maximum user productivity and user satisfaction |
| [Install template apps not listed on AppSource](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#install-template-apps-not-listed-on-appsource) | Control which users in the organization can download and install template apps not listed on AppSource | Should be disabled |

## Resources
For details of this deployment pattern, please see Page 184 of the [Power BI deployment whitepaper](https://aka.ms/PBIEnterpriseDeploymentWP).

