Before using Legenda, you first need to make certain that your server and WordPress meets the theme’s requirements, including  WordPress version 3.9+. Most problems, such as white screen after theme installation, out of memory errors, fails when import demo content, etc., are usually related to server settings and excessively low PHP configuration limits. You can change them by yourself, or contact your hosting provider and request the limits be increased to the following minimums:  

\- PHP version - 5.6 or higher;

\- Memory_limit is no less than 96M;

\- Upload_max_filesize should be no less than 40M;

\- max_execution_time: no less than 180;

\- PHP Max Input Vars - no less than 1000;

\- file_get_contents() function should be enabled in the server configuration.