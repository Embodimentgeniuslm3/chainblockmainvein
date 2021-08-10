# [OneDrive](index.md)
# [REST APIs](rest-api/index.md)
## [Getting started](rest-api/getting-started/index.md)
### [App registration](rest-api/getting-started/app-registration.md)
### [Authentication](rest-api/getting-started/authentication.md)
#### [Microsoft Graph](rest-api/getting-started/graph-oauth.md)
#### [Azure Active Directory](rest-api/getting-started/aad-oauth.md)
#### [Microsoft Account](rest-api/getting-started/msa-oauth.md)
### [Release notes](rest-api/getting-started/release-notes.md)
## [Concepts](rest-api/concepts/index.md)
### [Addressing items](rest-api/concepts/addressing-driveitems.md)
### [App folder](rest-api/concepts/special-folders-appfolder.md)
### [Custom metadata](rest-api/concepts/custom-metadata-facets.md)
### [Error responses](rest-api/concepts/errors.md)
### [Filter](rest-api/concepts/filtering-results.md)
### [Long running actions](rest-api/concepts/long-running-actions.md)
### [OneDrive endpoint](rest-api/concepts/direct-endpoint-differences.md)
### [Query string parameters](rest-api/concepts/optional-query-parameters.md)
### [Uploading files](rest-api/concepts/upload.md)
### [Using sharing links](rest-api/concepts/using-sharing-links.md)
### [Working with CORS](rest-api/concepts/working-with-cors.md)
## [Drives](rest-api/resources/drive.md)
### [Get drive](rest-api/api/drive_get.md)
### [Get special folder](rest-api/api/drive_get_specialfolder.md)
### [List drives](rest-api/api/drive_list.md)
### [List shared files](rest-api/api/drive_sharedwithme.md)
### [Recent files](rest-api/api/drive_recent.md)
## [DriveItems](rest-api/resources/driveitem.md)
### [Check In](rest-api/api/driveitem_checkin.md)
### [Check Out](rest-api/api/driveitem_checkout.md)
### [Copy](rest-api/api/driveitem_copy.md)
### [Create folder](rest-api/api/driveitem_post_children.md)
### [Delete](rest-api/api/driveitem_delete.md)
### [Download](rest-api/api/driveitem_get_content.md)
### [Download formats](rest-api/api/driveitem_get_content_format.md)
### [Get item](rest-api/api/driveitem_get.md)
### [List children](rest-api/api/driveitem_list_children.md)
### [Move](rest-api/api/driveitem_move.md)
### [Search](rest-api/api/driveitem_search.md)
### [Sync changes](rest-api/api/driveitem_delta.md)
### [Thumbnails](rest-api/api/driveitem_list_thumbnails.md)
### [Update](rest-api/api/driveitem_update.md)
### [Upload](rest-api/api/driveitem_put_content.md)
### [Upload large files](rest-api/api/driveitem_createuploadsession.md)
### [List versions](rest-api/api/driveitem_list_versions.md)
### [Get version](rest-api/api/driveitemversion_get.md)
### [Restore version](rest-api/api/driveitemversion_restore.md)
## [Permissions](rest-api/resources/permission.md)
### [Add permissions](rest-api/api/driveitem_invite.md)
### [Create sharing link](rest-api/api/driveitem_createlink.md)
### [List permissions](rest-api/api/driveitem_list_permissions.md)
### [Remove permissions](rest-api/api/permission_delete.md)
### [Update permission](rest-api/api/permission_update.md)
### [Get shared item](rest-api/api/shares_get.md)
## [Activities](rest-api/resources/itemActivity.md)
### [List activities](rest-api/api/activities_list.md)
## [Sites](rest-api/resources/site.md)
### [Get by ID](rest-api/api/site_get.md)
### [Get by path](rest-api/api/site_getbypath.md)
### [Get lists](rest-api/api/list_list.md)
### [List subsites](rest-api/api/site_list_subsites.md)
### [Search](rest-api/api/site_search.md)
## [Lists](rest-api/resources/list.md)
### [Get](rest-api/api/list_get.md)
### [Create](rest-api/api/list_create.md)
### [Get listItems](rest-api/api/listitem_list.md)
## [ListItems](rest-api/resources/listitem.md)
### [Create](rest-api/api/listitem_create.md)
### [Delete](rest-api/api/listitem_delete.md)
### [Get](rest-api/api/listitem_get.md)
### [Update](rest-api/api/listitem_update.md)
### [List versions](rest-api/api/listitem_list_versions.md)
### [Get version](rest-api/api/listitemversion_get.md)
### [Restore version](rest-api/api/listitemversion_restore.md)
## [Webhooks](rest-api/concepts/using-webhooks.md)
### [Create](rest-api/api/subscription_post_subscriptions.md)
### [Delete](rest-api/api/subscription_delete.md)
### [Update](rest-api/api/subscription_update.md)
### [Validation](rest-api/concepts/webhook-receiver-validation-request.md)
## [Resources](rest-api/resources/index.md)
### [AsyncJobStatus](rest-api/resources/asyncJobStatus.md)
### [Audio](rest-api/resources/audio.md)
### [BaseItem](rest-api/resources/baseItem.md)
### [BaseItemVersion](rest-api/resources/baseitemversion.md)
### [BooleanColumn](rest-api/resources/booleancolumn.md)
### [CalculatedColumn](rest-api/resources/calculatedcolumn.md)
### [ChoiceColumn](rest-api/resources/choicecolumn.md)
### [ColumnDefinition](rest-api/resources/columndefinition.md)
### [ColumnLink](rest-api/resources/columnlink.md)
### [CommentAction](rest-api/resources/commentaction.md)
### [ContentType](rest-api/resources/contenttype.md)
### [ContentTypeInfo](rest-api/resources/contenttypeinfo.md)
### [ContentTypeOrder](rest-api/resources/contenttypeorder.md)
### [CreateAction](rest-api/resources/createaction.md)
### [CurrencyColumn](rest-api/resources/currencycolumn.md)
### [DateTimeColumn](rest-api/resources/datetimecolumn.md)
### [DefaultColumnValue](rest-api/resources/defaultcolumnvalue.md)
### [DeleteAction](rest-api/resources/deleteaction.md)
### [Deleted](rest-api/resources/deleted.md)
### [DriveItemVersion](rest-api/resources/driveitemversion.md)
### [DriveRecipient](rest-api/resources/driverecipient.md)
### [EditAction](rest-api/resources/editaction.md)
### [Error](rest-api/resources/error.md)
### [FieldValueSet](rest-api/resources/fieldvalueset.md)
### [File](rest-api/resources/file.md)
### [FileSystemInfo](rest-api/resources/filesysteminfo.md)
### [Folder](rest-api/resources/folder.md)
### [FolderView](rest-api/resources/folderview.md)
### [GeoCoordinates](rest-api/resources/geocoordinates.md)
### [Hashes](rest-api/resources/hashes.md)
### [Identity](rest-api/resources/identity.md)
### [IdentitySet](rest-api/resources/identitySet.md)
### [Image](rest-api/resources/image.md)
### [ItemActionSet](rest-api/resources/itemactionset.md)
### [ItemActivityTimeSet](rest-api/resources/itemactivitytimeset.md)
### [ItemReference](rest-api/resources/itemReference.md)
### [ListInfo](rest-api/resources/listinfo.md)
### [ListItemVersion](rest-api/resources/listitemversion.md)
### [LookupColumn](rest-api/resources/lookupcolumn.md)
### [MentionAction](rest-api/resources/mentionaction.md)
### [MoveAction](rest-api/resources/moveaction.md)
### [NumberColumn](rest-api/resources/numbercolumn.md)
### [Package](rest-api/resources/package.md)
### [Photo](rest-api/resources/photo.md)
### [PublicationFacet](rest-api/resources/publicationfacet.md)
### [Quota](rest-api/resources/quota.md)
### [RemoteItem](rest-api/resources/remoteitem.md)
### [RenameAction](rest-api/resources/renameaction.md)
### [RestoreAction](rest-api/resources/restoreaction.md)
### [Root](rest-api/resources/root.md)
### [SearchResult](rest-api/resources/searchresult.md)
### [ShareAction](rest-api/resources/shareaction.md)
### [Shared](rest-api/resources/shared.md)
### [SharedDriveItem](rest-api/resources/shareddriveitem.md)
### [SharepointIds](rest-api/resources/sharepointIds.md)
### [SharingInvitation](rest-api/resources/sharinginvitation.md)
### [SharingLink](rest-api/resources/sharinglink.md)
### [SiteCollection](rest-api/resources/siteCollection.md)
### [SpecialFolder](rest-api/resources/specialfolder.md)
### [Subscription](rest-api/resources/subscription.md)
### [SystemFacet](rest-api/resources/systemfacet.md)
### [TextColumn](rest-api/resources/textcolumn.md)
### [Thumbnail](rest-api/resources/thumbnail.md)
### [ThumbnailSet](rest-api/resources/thumbnailSet.md)
### [UploadSession](rest-api/resources/uploadSession.md)
### [VersionAction](rest-api/resources/versionaction.md)
### [Video](rest-api/resources/video.md)
### [Webhook notification](rest-api/resources/webhooknotification.md)

# File handlers
## [Overview](file-handlers/index.md)
## [Defining actions](file-handlers/define-actions.md)
## [Registering](file-handlers/register-manually.md)
## [Localization](file-handlers/localization.md)

# [File pickers](controls/file-pickers/index.md)
## [Android](controls/file-pickers/android/index.md)
## [JavaScript](controls/file-pickers/js-v72/index.md)
### [Open a file](controls/file-pickers/js-v72/open-file.md)
### [Save a file](controls/file-pickers/js-v72/save-file.md)