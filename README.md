# drupal_patches
Various personal patches to Drupal that *might* be committed to the projects in question.

Patches available:

# [Campaign Monitor] (https://www.drupal.org/project/campaignmonitor)

## [Optional Client
ID](https://github.com/apantwerp/drupal_patches/blob/master/campaignmonitor/optional_client_id.patch)

This patch allows the user to leave the Client ID setting for the
Campaign Monitor module empty. That way a Campaign Monitor account with
multiple clients can be used on the same website to link to lists from
the different clients under its account. 

The default CM module implementations only allows for one specific
Client ID per site.
