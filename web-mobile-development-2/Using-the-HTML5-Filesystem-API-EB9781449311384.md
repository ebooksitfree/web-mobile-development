![Cover image for Using the HTML5 Filesystem API](https://imgdetail.ebookreading.net/cover/cover/web_mobile/EB9781449311384.jpg)

[Using the HTML5 Filesystem API](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_1.html "Using the HTML5 Filesystem API")
====================================================================================================================

Author : [Eric Bidelman](https://ebookreading.net/search/author/Eric+Bidelman)

Release Date : 2011/07/01

ISBN : 9781449311384

Topic : [Web & Mobile](https://ebookreading.net/search/category/web-mobile)

Book Description
-----------------

Several client-side storage options are available to web applications, but one area that's been lacking until now is file I/O—the ability to organize binary data into a true hierarchy of folders. That has changed with the advent of HTML5. With this book, you'll learn how to provide your applications with a file system that enables them to create, read, and write files and folders in a sandboxed section of the user's local filesystem.
Author Eric Bidelman, a Senior Developer Programs Engineer on the Google Chrome team, provides several techniques and complete code examples for working with the HTML5 Filesystem API.
Learn common operations for working with files and directoriesBecome familiar with HTML5's storage use cases and security considerationsUnderstand the storage options available, including temporary, persistent, and unlimitedWrite text or append data to an existing user fileImport files into your application by accessing a user's hard driveGet techniques for using a file with filesystem, blob, or data URLsUse the synchronous version of the HTML5 Filesystem API within a Web Worker context              
Table of Contents
-----------------

1. [Preface](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_3.html)
    1. [Conventions Used in This Book](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_3.html#I_sect1_d1e126)
    1. [Using Code Examples](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_3.html#I_sect1_d1e165)
    1. [Safari® Books Online](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_3.html#I_sect1_d1e180)
    1. [How to Contact Us](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_3.html#I_sect1_d1e193)
1. [1. Introduction](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_4.html)
    1. [Use Cases](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_4.html#I_sect11_d1e286)
    1. [Security Considerations](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_4.html#I_sect11_d1e378)
    1. [Browser Support](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_4.html#I_sect11_d1e395)
        1. [A Cautionary Tale](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_4.html#id345258)
1. [2. Storage and Quota](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_5.html)
    1. [Storage Types](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_5.html#I_section2_d1e431)
        1. [Temporary Storage](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_5.html#id345382)
        1. [Persistent Storage](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_5.html#id345343)
        1. [Unlimited Storage](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_5.html#id345407)
    1. [Quota Management API](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_5.html#I_section2_d1e533)
        1. [Requesting More Storage](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_5.html#id342720)
        1. [Checking Current Usage](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_5.html#id342773)
1. [3. Getting Started](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_6.html)
    1. [Opening a Filesystem](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_6.html#requestingafilesyst)
    1. [Handling Errors](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_6.html#I_section3_d1e819)
1. [4. Working with Files](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_7.html)
    1. [The FileEntry](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_7.html#I_section4_d1e852)
    1. [Creating a File](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_7.html#I_section4_d1e991)
    1. [Reading a File by Name](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_7.html#I_section4_d1e1056)
    1. [Writing to a File](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_7.html#filewriter)
        1. [Appending Data to a File](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_7.html#id343371)
    1. [Importing Files](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_7.html#I_section4_d1e1414)
        1. [Using &lt;input type=“file”&gt;](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_7.html#id343487)
        1. [Using HTML5 Drag and Drop](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_7.html#id328108)
        1. [Using XMLHttpRequest](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_7.html#id328156)
        1. [Using Copy and Paste](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_7.html#id328419)
    1. [Removing Files](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_7.html#I_section4_d1e1794)
1. [5. Working with Directories](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_8.html)
    1. [The DirectoryEntry](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_8.html#I_section5_d1e1816)
    1. [Creating Directories](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_8.html#I_section5_d1e1999)
        1. [Subdirectories](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_8.html#id329205)
    1. [Reading the Contents of a Directory](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_8.html#I_section5_d1e2112)
    1. [Removing Directories](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_8.html#I_section5_d1e2170)
        1. [Recursively Removing a Directory](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_8.html#id344083)
1. [6. Copying, Renaming, and Moving   Entries](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_9.html)
    1. [Copying a File or Directory](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_9.html#I_section6_d1e2238)
    1. [Moving a File or Directory](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_9.html#I_section6_d1e2351)
    1. [Renaming a File or Directory](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_9.html#I_section6_d1e2402)
1. [7. Using Files](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_10.html)
    1. [Filesystem URLs](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_10.html#I_section7_d1e2432)
        1. [Summary](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_10.html#id596913)
    1. [Blob URLs](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_10.html#I_section7_d1e2619)
        1. [Summary](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_10.html#id597286)
    1. [Data URLs](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_10.html#I_section7_d1e2811)
        1. [Summary](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_10.html#id597463)
1. [8. The Synchronous API](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_11.html)
    1. [Introduction](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_11.html#I_section8_d1e2921)
    1. [Opening a Filesystem](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_11.html#I_section8_d1e2953)
    1. [Working with Files and Directories](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_11.html#I_section8_d1e2983)
    1. [Handling Errors](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_11.html#I_section8_d1e3029)
    1. [Examples](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_11.html#I_section8_d1e3053)
        1. [Fetching All Entries in the Filesystem](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_11.html#id597788)
        1. [Downloading Files Using XHR2](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_11.html#id597867)
1. [About the Author](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_12.html)
1. [Colophon](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_13.html)
1. [Copyright](https://ebookreading.net/view/book/Using+the+HTML5+Filesystem+API-EB9781449311384_14.html)
