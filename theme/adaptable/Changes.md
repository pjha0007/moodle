Change Log in version 39.1.6 (2020073113)
=========================================
1. Change the following mod icons to Font Awesome 6.2.1 free ones:
     Assign - fa-solid fa-file-pen
     Assignment - fa-solid fa-file-signature
     Book - fa-solid fa-book-open
     Chat - fa-regular fa-comments
     Choice - fa-solid fa-arrows-split-up-and-left
     Data - fa-solid fa-database
     Feedback - fa-regular fa-comment-dots
     File - fa-regular fa-file
     Folder - fa-regular fa-folder
     Forum - fa-solid fa-people-group
     Glossary - fa-solid fa-box-archive
     IMScp - fa-solid fa-boxes-stacked
     Label - fa-solid fa-tag
     Lesson - fa-solid fa-chalkboard-user
     LTI - fa-solid fa-puzzle-piece
     Page - fa-solid fa-sheet-plastic
     Quiz - fa-solid fa-person-circle-question
     Resource - fa-regular fa-file
     SCORM - fa-solid fa-box
     Survey - fa-solid fa-square-poll-horizontal
     URL - fa-solid fa-link
     Wiki - fa-solid fa-circle-nodes
     Workshop - fa-solid fa-people-arrows
  Converted to PNG with Inkscape.

Change Log in version 39.1.5 (2020073112)
=========================================
1. Re-fix 'Title moved to top by search', ref: https://moodle.org/mod/forum/discuss.php?d=425729#p1718073.
2. Fix 'block configuration actions menu does not contrast enough', ref: https://moodle.org/mod/forum/discuss.php?d=427627.
3. Fix 'My Courses dropdown not showing all enrolled courses' - #258.
4. Fix "My courses dropdown can show hidden courses when user does not have capability when 'mysitessortoverride' setting is not
   set to 'Use list from my overview'", related to #258.
5. Fix 'One Topic font color change not getting applied' - #264.
6. Add 'OneTopic active tab colour' - #269.
7. Fixed semantic versioning 2.0.0 (https://semver.org/) for the release value, whereby the 'major' number is the Moodle core branch
   number.  The 'version' property still needs to follow the Moodle way in order for the plugin to operate within the core API.

Change Log in version 3.9.1.4 (2020073111)
==========================================
1. Fix 'Drag-and-drop onto image question type - preview not visible' - Ref: https://moodle.org/mod/forum/discuss.php?d=426557.
2. Remove redundant CSS selector - #33.
3. Fix 'Grader report preferences layout broken', ref: https://moodle.org/mod/forum/discuss.php?d=425016&parent=1715752.
4. Remove redundant navbar toggler and tidy the CSS.
5. Further CSS tidy and refactor some to SCSS.
6. Settings in the CSS can now be pre-processed before passed to the SCSS compiler.  Thus enabling further transition to SCSS of the CSS.
   This will reduce the amount of source 'CSS' and help to spot duplication and mistakes.
7. Added extra information in the settings tabs about maturity of the release.
8. Fix 'Userdata cache not used' - #247.
9. Fix 'setting colours (courses)' - Ref: https://moodle.org/mod/forum/discuss.php?d=426492.
10. Fix empty setting value of 'pageheaderheight' causes SCSS compilation issue - Ref: https://moodle.org/mod/forum/discuss.php?d=426553.
11. Change SCSS comments from CSS to SCSS ones so that they are not in the 'all' file sent to the browser and hence it will be smaller.
12. Fix dialog text colour, i.e. adding a new question to a quiz.
13. Fix 'Title moved to top by search', ref: https://moodle.org/mod/forum/discuss.php?d=425729#p1718073.

Change Log in version 3.9.1.3 (2020073110)
==========================================
1. Fix 'Expandable search in header two not working well' - #234.
2. Fix 'Assignment Grouping' - #233.
3. Fix 'This course section list overflows page' - #236.
4. Fix 'Navbar link icon spacing wrong' - #235.
5. Fix 'Missing theme cache reset' - Ref: https://moodle.org/mod/forum/discuss.php?d=420530.
6. Added upgrade script to change settings with '0px' to '0' for upgrades that don't have "No such thing as '0px'" change.
   Thus, when they do, the setting will be changed correctly instead of getting a default and effectively changing the
   value of the setting.
7. README.md to Readme.md - #240.
8. Fix 'Mobile view does not show bulleted list' - #238.
9. Fix 'Site administration in 'dock' on mobile view' - #237.
10. Improve menu accessible titles and vertically centred header title.
11. Fix 'Breadcrumb trail' - #242.
12. Enhancement 'Implement Global Search capability' - #241.
13. Fix 'Inactive tabs are displaced' - #244.
14. Fix 'Styling self-registration message card on login page' - #183.
15. Fix 'Site title not showing when 'responsiveheader' and 'responsivecoursetitle' settings are set to 'Extra small - Extra large'.'.
    Ref: https://moodle.org/mod/forum/discuss.php?d=424098.
16. Fix 'Divider in custom menus' - Ref: https://moodle.org/mod/forum/discuss.php?d=424547.
17. Fix 'Notifications menu colour problem' - #248.
18. Fix 'Message drawer height' - Header height fluctuates so go with a simple solution as there is a close icon.
19. Fix 'Sitename overlays loginbox on mobile devices' - Ref: https://moodle.org/mod/forum/discuss.php?d=424098#p1708632.

Change Log in version 3.9.1.2 (2020073109)
==========================================
1. Fix 'borderradius cannot be set to zero' - Ref: https://moodle.org/mod/forum/discuss.php?d=419461#p1692161.
2. Small login page CSS syntax error.

Change Log in version 3.9.1.1 (2020073108)
==========================================
1. Small header fixes.
2. Fix 'Issue with Adaptable Theme Header' - #227.
3. Fix "No vertical gap with side post blocks when 'blockside' setting is 'Left side'" - Ref: https://moodle.org/mod/forum/discuss.php?d=419201#p1689468.
4. Fix 'File picker .nav-item's have header changes' - Ref: https://moodle.org/mod/forum/discuss.php?d=419201#p1689468.
5. Fix 'put_properties in Toolbox does not process all of the file settings' - #221.
6. Add information page in the settings with readme and settings lang tidy.
7. Add 'thirdpartylibs.xml' information.
8. Tidy the language strings.
9. Organise the settings tabs.
10. Tidy and optimise adaptable.css.
11. Add Support.md file.
12. Fix 'Json error when getting course info in combined list on frontpage' - #229.
13. Fix 'menuoverrideprofilefield topmenusettings error' - #228.

Change Log in version 3.9.1.0 (2020073107)
==========================================
1. Fix 'Quiz due date has no background colour'.
2. Possible fix for header title underlaps search box - https://moodle.org/mod/forum/discuss.php?d=417124#p1685280.
3. Refactor renderers so that don't have to worry about calls to undefined methods when upgrading or in maintenance.
4. Fix 'Coventry tiles do not show teachers' - ref: https://moodle.org/mod/forum/discuss.php?d=418430.
5. Added 'editcognocourseupdate' setting so that when 'off' the cog / gear icon will not show in courses for users 
   without the 'moodle/course:update' capability.
6. Port of fix 'Undefined property: stdClass::$groupmember in moodle/course/format/topcoll/classes/activity.php on line 650' from Collapsed Topics.
7. Removed 'editverticalpadding' setting as contradictory to the ability to centre the button text accurately.
8. No such thing as '0px'.
9. Corrected style spelling of 'edittingbutton' to 'editingbutton'.
10. Fix '0 attempted' - ref: https://moodle.org/mod/forum/discuss.php?d=418918.
11. Remove FireFox CSS that breaks the activity / resource editing page.

Change Log in version 3.0.5 (2020073106)
========================================
1. Fix 'Menu bar height loss' - #222.
2. Fix 'Activity meta information not showing when student first accesses page' - https://moodle.org/mod/forum/discuss.php?d=417731.
3. Fix 'Footer shown on popup layout' - https://moodle.org/mod/forum/discuss.php?d=417793.
4. Fix 'User profile image is cropped' - https://moodle.org/mod/forum/discuss.php?d=417776.
5. Fix 'Textured page background image does not extend down when the page height changes' - #223.
6. Grid format has changed method name of 'section_header_onsectionpage_topic0notattop' to 'section_header_onsectionpage'.
7. Fix 'Redirection loop' - #224.

Change Log in version 3.0.4 (2020073105)
========================================
1. Fix 'Header issues with logo and background image'.
2. Fix 'Custom menu items not shown even when "disablecustommenu" is false'.
3. Fix 'Header style two does not show logo when there is no site title'.
4. Fix 'Undefined property: stdClass::$tickertext1 when running behat tests' - #159.

Change Log in version 3.0.3 (2020073104)
========================================
1. Fix 'Cope when there is no first or full name' when showing a user profile.
2. Fix 'Frontpage tiles do not show course contacts' - #184.
3. Due date label doesn't honor overridden dates for mod_assign - #186,
   thanks to https://github.com/golenkovm for the original patch in Collapsed Topics.
4. Fix 'adaptable_setting_confightmleditor does not set setting as empty when there is no content' - #187.
5. Fix 'Sub sub menus and below show all at once' - #188.
6. Fix the ability for Behat to run without '$CFG->forced_plugin_settings' being set - dashboard.php issue only - #159.
7. Fix 'admin_setting_configselect defaults should use the index and not the value' - #189.
8. Fix 'regression - background colour on dashboard' - #190.
9. Add 'Book printing to PDF' - #173.
10. Fix 'Dashboard dropdown hover makes text unreadable' - #194.
11. Add 'Not submitted confusing when student can no longer submit' - #195.
12. Fix 'buttondropshadow does not use lang strings' - #152.
13. Port of Collapsed Topics accessible colours for the activity meta - https://github.com/gjb2048/moodle-format_topcoll/issues/88.
14. Tabbed settings and fixed use of $PAGE which gives invalid variable values when Adaptable is not the set theme.
15. Fix 'PHPUnit install fails' - #197.
16. Fix 'Install fails on Moodle 3.9' - #198 - thanks to https://gitlab.com/kiklopgs for the patch in https://gitlab.com/jezhops/moodle-theme_adaptable/-/merge_requests/34.
17. Fix 'Gradebook: Edit link not working' - #201.
18. Fix 'edit_button in renderers.php is not used' - #202.
19. Fix 'Redundant CSS' - #96.
20. Fix 'theme_adaptable_get_html_for_settings() is not used!' - #27.
21. Fix '$hasmiddle is not used!' - #26.
22. Fix '$hasfootnote is not used!' - #203.
23. Fix '$responsivealerts = $PAGE->theme->settings->responsivealerts; not used!' - #204.
24. Fix 'Improve Activity Completion Icons' - #8.
25. Fix 'User menu available when using "Full screen pop-up with some Javascript scurity" in Quiz' - #210.
26. Fix 'Adding Activity with Safari in Moodle 3.9' - #211.
27. Fix 'Second level links do not work when using 3 levels of sub-menu in custom menus' - #117.
28. Fix 'Course formatting in Safari and Moodle 3.9' - #212.
29. Fix ''About me' tab should be the default for the user profile page' - #206.
30. Add version information to settings pages.
31. Fix 'Calendar links on the page'.
32. Fix 'Navigation tweaks'.
33. Fix 'User details not visible on profile page' - #119.
34. Tabs update in line with MDL-69301.
35. Fix block header icons.
36. Fix block hide / show icon size.
37. Fix 'Wrong display of date user profile fields' - #214.
38. Fix property display can cause markup to be interpreted.
39. Allow Import / Export settings to work by separating from tabbed settings.
40. Fix 'Impossible to enter a course with Coventry tiles' - #156.
41. Remove setting to control activities in chooser - M3.9+ only - #135.
42. Fix 'stickynavbar' JS error on login page.
43. Fix 'Login page cookies popup not working' - #217.
44. Fix 'Onetopic: background color in tabs' - #215.
45. Fix 'Theme does not respect the before_footer callback' - #216.
46. Fix 'No multilang support in headers and footer' - #132.
47. Fix 'Drag&Drop Image question behaviour problem' - #220.
48. Fix 'Duplicate code in get_logo_title()' - #208.
49. Fix 'responsivealerts used?' - #205.
50. Fix 'fonttitlecolorcourse setting not used' - #154.
51. Fix 'enablealertcoursepages setting used?' - #151.

Change Log in version 3.0.2 (2020073103)
========================================
1. Fix 'Error in function quiz_num_submissions_ungraded' - #176.
2. Fix 'course_participant_count inaccurate' - #179.
3. Fix 'Lesson status inaccurate' - #180.

Change Log in version 3.0.1 (2020073102)
========================================
1. Fix 'Too few arguments to function theme_adaptable_core_renderer::render_mycourses(),
   0 passed in [dirroot]/lib/outputrenderers.php on line 497 and exactly 1 expected' - #172.
2. Fix navbar is not showing on the frontpage.
3. Fix 'Book module has two icons' - #174.
4. Fix 'Course in category' - https://moodle.org/mod/forum/discuss.php?d=408081#p1656297.
5. Fix 'Ungraded assign' - https://moodle.org/mod/forum/discuss.php?d=410681.
6. Fix btn-secondary text colour when link.
7. Fix 'Filter not applied' - https://moodle.org/mod/forum/discuss.php?d=408081#p1657138.
8. Fix 'Support for Embedded Questions filter' - #177.

Change Log in version 3.0.0 (2020073101)
========================================
Release candidate for Moodle 3.9.

1. Fix licence from GPLv2 to GPLv3 as is incorrect - Moodle plugins must be GPLv3.
2. Fix message drawer closure.
3. Fix 'Regression - Frontpage marketing blocks don't display on desktop' - #139.
4. Moodle 3.9 New Activity Chooser styling needs work - #131.
5. Fix 'Blocks - My Home recently accessed course' - #9.
6. Fix rubic icons -> https://moodle.org/mod/forum/discuss.php?d=408081#p1646693.
7. Fix 'Searchbox conflict with Advanced Forum (hsuforum)' - #133.
8. Fix 'Bullet list display in Collapsed Topics course format' - #81.
9. Fix 'Block settings are left justified' - #82.
10. Improve 'Improve Onetopic course format tab rendering' - #115.
11. Fix 'Missing action menu (like editing button / cog button) on content bank page' - #140.
12. Fix 'Button/link 'Turn editing on' missing on Moodle 3.9' - #129.
13. Fix '.btn declaired after .hidden' - #130.
14. Fix message drawer hover.
15. Improve position of #82.
16. Make 'side-post' have no padding on the right so that the page is symmetrical.
17. Fix 'H5P iframe element too small in content bank page' - #146.
18. Fix 'Navbar Custom Menu does not fit' - #128.
19. Fix 'Editing cog colour not consistent' - #149.
20. Fix 'Whitespace Below Header in Course Pages' - #38.
21. Fix 'Use of "$setting->set_updatedcallback('theme_reset_all_caches');" not needed on some settings' - #25.
22. Fix 'lib.php preg_match logic flaw' - #150.
23. Fix 'wrong rtl css' - #142.
24. Fix 'Impossible to enter a course with Coventry tiles' - #156.
25. Update to version 3 https://moodlehq.github.io/moodle-plugin-ci/UPGRADE-3.0.html - #158.
26. Assignment with restricting grouping shows all users or groups - #161.
27. Fix 'Regression? / Inconsistent cog positioning in content bank' - #166.
28. Fix 'Quiz attempt: no breadcrumbs' - #123.
29. Fix '$fontname can never be 'custom'' - #104.
30. Implement 'Update google fonts list ' - #42 - thanks to 'Sal Zaydon' - https://gitlab.com/szaydon for the list.
31. Fix no such font-family as 'default' - #42.
32. Fix 'Topic header text now black' - #167.

Change Log in version 2.2.2 (2019112601)
========================================

Main fixes & Enhancements done in this release.

- Fix mobile responsive settings in "layout responsive" settings page
- Fix ability to set general box color in forums
- Fix issues with login page when no header in use
- Fix issue of footer riding up on short pages with little content
- Fix close icon for activity chooser in Moodle 3.8
- Fix combo list on mobile, now collapses into single column

What's new?

- Layout responsive settings page
- Setting to control color of forum "general box" background where forum description is displayed


HTML/CSS sample code for block areas
------------------------------------
Here you will find some code samples to help you to customize the Info Box and the Marketing Blocks.

You can insert any HTML tag to customize the front page blocks. Use a 'div' tag as a main container and add the height to keep the
same value in all the blocks.

The Font Awesome icons set is available in
http://fortawesome.github.io/Font-Awesome/icons/.

You can insert any of them following the examples
http://fortawesome.github.io/Font-Awesome/examples/


Front Page Slider Styles
------------------------
Add images with at least 1900px x 400px.
If you want to reduce or increase the height, Adaptable will resize the image automatically.
There are two possible slider styles each with different markup required:


Original BCU Slider Markup:
````
<div class="span9">
  <h4>Information</h4>
    Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore
    et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip
    ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
  </div>

  <div class="span3">
  <a href="#" class="submit">2016/17 Courses <i class="fa-chevron-right fa"></i></a>
</div>
````


Coventry Style Slider Markup
````
<div class="span6 col-sm-6">
<h3>Hand-crafted</h3> <h4>pixels and code for the Moodle community</h4>
<a href="#" class="submit">Check out our custom theme pricing!</a>
</div>
````

Frontpage Marketing Block HTML structure Coventry
````
<div><img src="http://somewebsite.com/2.jpg" class="marketimage"></div>
<h4><a href="#">International Courses</a></h4>
<p>Some text below the link....</p>
````

Front page Info Box and Marketing Blocks
----------------------------------------

There are two Info blocks in the front page located above and below the Marketing Blocks. These are just for compatibility with the
old BCU.

It is recommended to use the new marketing blocks builder that allows you to create your own layout and add much more blocks.

There are 8 rows where you can add up to 4 blocks in each with a total of 32 block of different size. See pix/layout.png for
more information.

You can enter any HTML code to the block, include FA icons, images, videos and apply in-line styles.

Some samples:


Block with solid background, FA icon and some text:
````
<div style="text-align:center; background: #e6e6e6; height: 350px; padding: 7px;">
    <i class="fa fa-paint-brush fa-5x" style="color: #3A454b;"></i>
    <h3>Title </h3>
    <div style="text-align:center;">Add your text here.</div>
</div>
````

Block with border and transparent background:
````
<div style="text-align:center; height: 350px; padding: 7px; border: 1px solid #3A454b;">
    <i class="fa fa-list fa-5x" style="color: #3A454b;"></i>
    <h3>Heading</h3>
    <div style="text-align:center; padding: 5px; color: #3A454b;">Add your text here.</div>
</div>
````

Block with an image:
````
<div style="height: 350px;">
    <img src="http://yoursite/yourimage.jpg" style="vertical-align:text-bottom; margin: 0 .5em;" height="auto" width="100%">
    <p style="margin-top: 5px; color: #333333; text-align: center;"><strong>Add your text here</strong></p>
</div>
````

Block with a video:
````
<div style="background: #606060; height: 350px">
    <center>
    <iframe src="https://www.youtube.com/embed/wop3FMhoLGs" allowfullscreen="" frameborder="0" height="315" width="560"></iframe>
    </center>
</div>
````

Block using multi-lang filter:
````
<div style="width: 100%; height: 240px; background-color: #cccccc;">
<h1 style="text-align: center; line-height: 120px;">
      <span class="multilang" lang="en">text in english</span>
      <span class="multilang" lang="es">texto en espaÃƒÂ±ol</span>
      <span class="multilang" lang="fr">texte en franÃƒÂ§ais</span>
      <span class="multilang" lang="ca">text en catalÃƒ </span>
</div>
````

Footer Blocks
-------------
You can apply the same HTML/CSS in the footer blocks.

Some samples:

Contact information
````
<i class="fa fa-building"></i>  High St. 100<br>
<span style="margin-left: 20px;">123456 City</span><br><br>
<i class="fa fa-phone"></i> +12 (3)456 78 90<br>
<i class="fa fa-envelope"></i> info@mail.com<br>
<i class="fa fa-globe"></i> www.example.com
````

List with Chevron
````
<ul class="block-list">
    <li><a href="http://moodle.org/"><span class="fa fa-chevron-right"></span><span>Accessibility</span></a></li>
    <li><a href="http://moodle.org/"><span class="fa fa-chevron-right"></span><span>Moodle Help</span></a></li>
    <li><a href="http://moodle.org/"><span class="fa fa-chevron-right"></span><span>Moodle Feedback</span></a></li>
    <li><a href="http://moodle.org/"><span class="fa fa-chevron-right"></span><span>IT Help</span></a></li>
    <li><a href="http://moodle.org/"><span class="fa fa-chevron-right"></span><span>IT Feedback</span></a></li>
</ul>
````

Copyright text
--------------
A sample of copyright text using FA icon
````
Made with <i class="fa fa-heart" style="color: #ff0000;"></i> in Europe
````

News Ticker
-----------
From version 1.3 the news ticker do not need to create an unordered list. Just add paragraphs using 'p' tags:
````
<p>Configure all the theme colors</p>
<p>Use any Google Font for the content, headings and site title</p>
<p>Display a logo or a configurable title site</p>
<p>Configurable Slideshow</p>
<p>Display up to 12 marketing blocks in the front page</p>
````

Messages / Notifications
------------------------
Moodle 3.2 includes a new system to display messages and notifications in the screen.

The new system displays a hard coded black icons that are difficult to see when using dark background color in the top header.
In that case, you can use an alternate icons pack using white color.

Login the server by FTP or SFTP and open /theme/adaptable/pix_core/i and
delete notifications.png and rename notifications-white.png to notifications.png

Then open /theme/adaptable/pix_core/t and delete message.png and
rename message-white.png to message.png

From moodle 3.6 the messages and notifications has been changed to the called "Messages Drawer".


Activities icons
------------------------
From version 1.4, Adaptable includes its own icons pack that replace the default moodle icons.
If you don't want to use the icons just remove adaptable/pix_plugins and adaptable/pix_core/f
You can enable this icons from the administration.