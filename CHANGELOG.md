### 0.0.20 (January 21st, 2021)

- rename `notification.proto` to `notification_req.proto` as this is being 
required for the notification resource.
- add `notification_channel.proto` and `notification.proto`

### 0.0.19 (January 19th, 2021)

- added `sendActivationEmail` to resend registration emails

### 0.0.18 (January 19th, 2021)

- changed the input field to `identifier` to support both user-name and email for all operations from `id`.

### 0.0.17 (December 4th, 2020)

- moved last_login from user proto to token proto

### 0.0.16 (November 22nd, 2020)

- added role_associations and HR scopes to subject

### 0.0.15 (November 18th, 2020)

- removed duplicate field from graph proto

### 0.0.14 (November 18th, 2020)

- updated graph proto to rename vertex fields
- updated user proto to remove populateRoleAssocCache rpc, updated token proto to remove findByUid and findByuserCode, added token_type to Tokens and moved HRScopeReq and Response from user proto to auth proto
- added interactive flag for tokens
- up token type and expires in fields to match oidc keys

### 0.0.13 (October 30th, 2020)

- removed ApiKey from oneof authorization for requests and restructured subject

### 0.0.12 (October 14th, 2020)

- updated ostorage proto to include data (google.protobuf.any) in options
- update rule and policy proto with field evaluation_cacheable

### 0.0.11 (October 3rd, 2020)

- restructuring of user proto

### 0.0.10 (October 2nd, 2020)

- restructuring of protos (auth, tokens, attributes)
- added token and authenticaion_log proto
- updated user proto to include last_login and last_access

### 0.0.9 (September 9th, 2020)

- updated all protos to include subject in request
- updated user proto to include subject, tokens and HR scope request

### 0.0.8 (June 18th, 2020)

- added copy operation for ostorage-srv

### 0.0.7 (June 16th, 2020)

- added subject_id for job protos

### 0.0.6 (June 10th, 2020)

- added sendInvitation rpc for user proto
- updates for fulfillment proto

### 0.0.5 (April 16th, 2020)

- added tags option to ostorage proto

### 0.0.4 (April 1st, 2020)

- added download option to ostorage proto

### 0.0.3 (March 24th, 2020)

- updated ostorage protos to include encoding and content options
- updates for payment proto

### 0.0.2 (February 10th, 2020)

Updated user proto to include auth_context and roles proto to include `assignable_by_roles` field

### 0.0.1 (January 29th, 2020)

Initial share.
