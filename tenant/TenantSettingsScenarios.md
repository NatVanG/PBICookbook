# Tenant Settings by Scenario / Use case

## Overview
There are 90 some odd settings in the admin portal for power BI and we have a resource here on this page link that goes to the general recommendations for each one but here we want to discuss describe a number of different scenarios or groups of settings that you should be aware of for different purposes.

I've outlined a number of different topics. Let's have a look at them below.

## Centre of Excellence
These are settings that every leader in a centre of excellence should understand and choose the best options for your tenant. Many of them are simply adding details to your processes for things like creating workspaces, publishing data sets, and data set discovery. There are also, crucially, settings on publishing to web and the use of APIs and service principles in your tenant. It is highly advised for you to understand the different use cases for using service principles and to put in the right processes in place to allow anyone to use the Power BI API. If you're looking for security and governance settings there is a section about that later.

| Settings |
|:------------------------|
[Publish "Get Help" information](https://docs.microsoft.com/en-us/power-bi/guidance/admin-tenant-settings#publish-get-help-information)
[Receive email notifications for service outages or incidents](https://docs.microsoft.com/en-us/power-bi/guidance/admin-tenant-settings#receive-email-notification-service-outages-or-incidents)
[Allow users to try Power BI paid features](https://learn.microsoft.com/en-us/power-bi/admin/service-admin-portal-help-support#allow-users-to-try-power-bi-paid-features)
[Show a custom message before publishing reports](https://learn.microsoft.com/en-us/power-bi/admin/service-admin-portal-help-support#show-a-custom-message-before-publishing-reports)
[Create workspaces](https://docs.microsoft.com/en-us/power-bi/guidance/admin-tenant-settings#create-workspaces)
[Use datasets across workspaces](https://docs.microsoft.com/en-us/power-bi/connect-data/service-datasets-admin-across-workspaces)
[Invite external users to your organization](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#invite-external-users-to-your-organization)
[Invite external users to your organization](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#invite-external-users-to-your-organization)
[Publish to Web](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#publish-to-web)
[Certification](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#certification)
[Featured content](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#certification)
[Make promoted content discoverable](https://docs.microsoft.com/en-us/power-bi/collaborate-share/service-discovery#make-promoted-content-discoverable)
[Make certified content discoverable](https://docs.microsoft.com/en-us/power-bi/collaborate-share/service-discovery#make-certified-content-discoverable)
[Discover content](https://docs.microsoft.com/en-us/power-bi/collaborate-share/service-discovery#discover-content)
[Push apps to end users](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#push-apps-to-end-users)
[Create audit logs for internal activity auditing and compliance](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#create-audit-logs-for-internal-activity-auditing-and-compliance)
[Allow service principals to use Power BI APIs](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#allow-service-principals-to-use-power-bi-apis)
[Allow service principals to create and use profiles](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal-developer#allow-service-principals-to-create-and-use-profiles)
[Allow service principals to use read-only Power BI admin APIs](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal-admin-api-settings#allow-service-principals-to-use-read-only-power-bi-admin-apis )
[Enhance admin APIs responses with detailed metadata](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal-admin-api-settings#enhance-admin-apis-responses-with-detailed-metadata )
[Enhance admin APIs responses with DAX and mashup expressions](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal-admin-api-settings#enhance-admin-apis-responses-with-dax-and-mashup-expressions )
[Create and use dataflows](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal-dataflow#create-and-use-dataflows)
[Allow your Microsoft 365 services to process or store Power BI data which may be outside of your Power BI tenant's geographic area.](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal-share-data-microsoft-365-services#allow-your-microsoft-365-services-to-process-or-store-power-bi-data-which-may-be-outside-of-your-power-bi-tenants-geographic-area )


## Protection, Security, and Governance
The next the next section is about protection security in governance. This group outlined some of the more advanced settings for your tenant which will help protect your content from being shared or used improperly. The main set of settings here are on sensitivity labels which are an external feature to power BI but if your organisation is using them can have certain behaviours configured here.
| Settings |
|:------------------------|
[Allow users to apply sensitivity labels for Power BI content](https://learn.microsoft.com/en-us/power-bi/enterprise/service-security-enable-data-sensitivity-labels#apply-sensitivity-labels-from-data-sources-to-their-data-in-power-bi)
[Apply sensitivity labels from data sources to their data in Power BI](https://learn.microsoft.com/en-us/power-bi/enterprise/service-security-sensitivity-label-inheritance-from-data-sources)
[Automatically apply sensitivity labels to downstream content](https://learn.microsoft.com/en-us/power-bi/enterprise/service-security-sensitivity-label-downstream-inheritance#downstream-inheritance-modes)
[Allow workspace admins to override automatically applied sensitivity labels](https://learn.microsoft.com/en-us/power-bi/enterprise/service-security-sensitivity-label-downstream-inheritance)
[Restrict content with protected labels from being shared via link with everyone in your organization](https://learn.microsoft.com/en-us/power-bi/admin/service-admin-portal-information-protection#restrict-content-with-protected-labels-from-being-shared-via-link-with-everyone-in-your-organization)
[Allow connections to featured tables](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#allow-connections-to-featured-tables)
[Allow shareable links to grant access to everyone in your organization](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal-export-sharing#allow-shareable-links-to-grant-access-to-everyone-in-your-organization)
[Per-user data in usage metrics for content creators](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#per-user-data-in-usage-metrics-for-content-creators-1)
[Allow user data to leave their geography](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal-quick-measure-suggestions-settings#allow-user-data-to-leave-their-geography)

## Guests and B2B
There are many settings which determine how cross tenant behaviour and guests can access your tenant. Not only are you able to turn off access to guest users but you can limit it to security groups and also limit what those guests are allowed to do.
| Settings |
|:------------------------|
[Allow Azure Active Directory guest users to access Power BI](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#allow-azure-active-directory-guest-users-to-access-power-bi)
[Invite external users to your organization](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#invite-external-users-to-your-organization)
[Allow email subscriptions to external users]()
[Allow guest user to work with shared datasets in their own tenants]()
[Allow external data sharing](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal-export-sharing#allow-external-data-sharing)
[External sharing](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal-export-sharing#external-sharing)


## Export Security
To return to the security front there are a number of settings to limit exports in the power by service these include turning off exporting to different file formats printing dashboards and copy and paste of visuals. Since many of these export types may break sensitivity labels or break login requirements it is useful to know that they or configurable in the admin portal.
| Settings |
|:------------------------|
[Copy and paste visuals](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#copy-and-paste-visuals)
[Export to Excel](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#export-to-excel)
[Export to .csv](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#export-to-csv)
[Download reports](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#download-reports)
[Allow live connections](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#allow-live-connections)
[Export reports as PowerPoint presentations or PDF documents](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal-export-sharing#export-reports-as-powerpoint-presentations-or-pdf-documents)
[Export reports as MHTML documents](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#export-reports-as-mhtml-documents)
[Export reports as Word documents](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#export-reports-as-word-documents)
[Export reports as XML documents](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#export-reports-as-xml-documents)
[Export reports as image files](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal-export-sharing#export-reports-as-image-files)
[Print dashboards and reports](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#print-dashboards-and-reports)


## SSO settings
There are four single sign on settings in the tenant Edmond centre: dromio, snowflake, red shift, and Azure ady single sign on for gateways.
| Settings |
|:------------------------|
[Dremio SSO]()
[Snowflake SSO](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal-integration#snowflake-sso )
[Redshift SSO](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal-integration#redshift-sso)
[Azure AD Single Sign-On (SSO) for Gateway](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal-integration#azure-ad-single-sign-on-sso-for-gateway )

## MISC Report Developer settings
The next group of is a miscellaneous bunch of settings that you should be aware of to help super users and common data set developers in your tenant. Two settings here are about DataMarts and Composite Models.
| Settings |
|:------------------------|
[Create Email Subscriptions](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal-export-sharing#email-subscriptions)
[Allow DirectQuery Connections to Power BI Datasets](https://learn.microsoft.com/en-us/power-bi/admin/service-admin-portal-export-sharing#allow-directquery-connections-to-power-bi-datasets)
[Usage metrics for content creators](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#usage-metrics-for-content-creators-1)
[Azure Log Analytics connections for workspace administrators](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal-audit-usage#azure-log-analytics-connections-for-workspace-administrators)
[Web content on dashboard tiles](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#web-content-on-dashboard-tiles)
[Install template apps](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal-template-app#install-template-apps-listed-on-appsource )
[Install template apps not listed in AppSource](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal-template-app#install-template-apps-not-listed-on-appsource )
[Review questions](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal-qa#review-questions)
[Synonym sharing](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal-qa#synonym-sharing)
[Create and use Metrics](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal-goals-settings#create-and-use-goals-preview)
[Receive notifications for top insights (preview)](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal-insights#receive-notifications-for-top-insights-preview)
[Show entry points for insights (preview)](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal-insights#show-entry-points-for-insights-preview)
[Create datamarts (preview_](https://learn.microsoft.com/en-us/power-bi/transform-model/datamarts/datamarts-administration#enabling-datamarts-in-the-admin-portal)
[Allow quick measure suggestions (preview)](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal-quick-measure-suggestions-settings#allow-quick-measure-suggestions-preview)


## Limits to visuals
•	Visual limitations can be added in the tenant as well. You can limit the download of custom visuals from the marketplace, the use of R and Python visuals and the limitation of number of map visuals who's geocoding can often send data out of region.
| Settings |
|:------------------------|
[Use ArcGIS Maps for Power BI](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#use-arcgis-maps-for-power-bi)
[Use global search for Power BI](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal#use-global-search-for-power-bi-preview)
[Use Azure Maps visual](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal-integration#map-and-filled-map-visuals )
[Map and filled map visuals](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal-integration#map-and-filled-map-visuals )
[Allow visuals created using the Power BI SDK](https://docs.microsoft.com/en-us/power-bi/admin/organizational-visuals#allow-visuals-created-using-the-power-bi-sdk)
[Add and use certified visuals only (block uncertified)](https://docs.microsoft.com/en-us/power-bi/admin/organizational-visuals#add-and-use-certified-visuals-only-block-uncertified)
[Allow downloads from custom visuals](https://docs.microsoft.com/en-us/power-bi/admin/organizational-visuals#allow-downloads-from-custom-visuals)
[Interact with and share R and Python visuals](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal-r-python-visuals#interact-with-and-share-r-and-python-visuals )

## Office 365 and Power Platform integration
Finally there are a number of settings that help therapy I and Office 365 connect together.
| Settings |
|:------------------------|
[Enable Microsoft Teams integration in the Power BI service](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal-export-sharing#microsoft-teams-integration-in-the-power-bi-service )
[Install Power BI app for Microsoft Teams automatically](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal-export-sharing#install-the-power-bi-app-for-teams-automatically)
[Enable Power BI add-in for PowerPoint]()
[Integration with SharePoint and Microsoft Lists](https://docs.microsoft.com/en-us/power-bi/admin/service-admin-portal-integration#integration-with-sharepoint-and-microsoft-lists )
[Power Platform Solutions Integration](https://learn.microsoft.com/en-us/power-bi/collaborate-share/service-power-bi-powerapps-integration-about)



## Close
These groups do not cover all the settings of the tenant but they do cover the major areas of which a tenant admin or a leadership leader in power by adoption would need to know.
