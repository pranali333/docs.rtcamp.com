---
title: Migration from BuddyPress-Media 2.x to rtMedia 3.x
---

Follow this guideline for migrating smoothly from BuddyPress-Media 2.x to rtMedia 3.x.

**Caution: Ensure that your WordPress database has been backed up before starting the migration.**



	
  1. rtMedia needs two database tables i.e. `wp_rt_rtm_media` and `wp_rt_rtm_media_meta`. If it fails to create them, migration will NOT work.

	
  2. rtMedia migration is designed to run forever if the browser tab is kept open. For this site itself migration took hours. To speed up migration, please deactivate other plugins.

	
  3. Apart from speed issues, other plugins can also interfere in the migration process.

	
  4. If you have a live site, create a test site with live data to test migration script first.

	
  5. Make sure test site has exactly the same server environment, permission and configuration. Otherwise, what works on test site may fail on live site.


[![migration](https://rtcamp.com/wp-content/uploads/2013/10/migration_thumb.png)](https://rtcamp.com/wp-content/uploads/2013/10/migration.png)
