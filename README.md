# Integration-Box
New Application
* Bump ruby to v2.7.1
* Bump shopify_app to v17.1.x
* Run `rails g shopify_app:shop_model` to get access_scope column migration
* Update Shop session storage concern to be `ShopSessionStorageWithScopes`
* Configure `reauth_on_access_scope_changes = true` in shopify_app.rb
* Add the `ShopAccessScopesVerification` concern to home_controller
