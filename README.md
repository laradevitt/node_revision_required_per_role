# Node revision required per role

This Drupal module allows site administrators to force users to set and log a new revision based on role.

Since "Revision information" doesn't consist of standard fields made available through the *Manage fields* interface, it is excluded by other modules that perform special handling on other fields available on the content entity form. This fills that gap.

IMPORTANT

This module has not been vetted by the community so use at your own risk!

TO CONFIGURE

1. Install module

2. Edit a content type at admin/structure/types/manage/[type]

3. Publishing options > Default options  
   [ x ] Create new revision

4. Publishing options > Revision required  
   Check [ x ] all user roles that must always log a new revision for this type

