## How To fix Hacked Website and Malware Removal
# Steps:
1. Back-up the wordpress file.
2. Check the ht-access file.
   Note: If you are unable to open the ht-access, then change the file permissions
3. If the ht-access files is corrupt, download a new ht-access file and input it into the file manager.
   Note: If you change it and it still gives the old ht-access still appears with the infections, that means a 
   cron job runs that allows the ht-access generates itself after been removed.
4. What we need to to add a malware scanner plugin. And if from the wp-admin page, we are unable to access the plugins icon, then 
   we need to download the plugin as a file locally and upload it to the plugin folder in the wp-content folder.
   Note: The malware scanner to download is "Wordfence" from google or the official wordpress site.
5. While doing the upload of the plugins and extract it... You can also check each files and names of files to see if there are any names that are off or
   scripts that contains gibbereish.
6. On the wp-admin page, we gto to plugins and then we scroll down to Wordfence and activate it. We click on dashboard and finally click on Scan. 
   Then we click on start new scan.
7. After runnin the scan, we find if wefix it by clicking repair files. If we do not have access to repair files, then we need to findout whoser account did the            infection come from. We do this by clicking on tools. Then we look for the suspected user and remove.
8. Go to the file manager and remove everything except wp-content and archive.
9. Then go to the file manager, Rename wp-content and delete all the files execpt the archive file, wp-pcontent, wp-config and our newly uploaded wordpress file.
10. Extract the wordpress file, go into it and select all files excpt the wp-content and move them to the file manager.
11. Thyen we rename the wp-content in the file manager to iyts original name.
12. then clean up by removing files like the archive.

Visit https://www.youtube.com/watch?v=vI1RFTcN4AU&t=148s to learn more.
