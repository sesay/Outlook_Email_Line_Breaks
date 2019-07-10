# Outlook_Email_Line_Breaks

This styling removes unwanted line breaks and spaces on Outlook 2013 and 2016 , a life saver

[**Reference Link:**] (https://www.contactmonkey.com/blog/outlook-rendering-issues)

```<style>   html,   body {     margin: 0 auto !important;     padding: 0 !important;     height: 100% !important;     width: 100% !important;   }    /* Stop Outlook resizing small text. */   * {     -ms-text-size-adjust: 100%;   }    /* Stop Outlook from adding extra spacing to tables. */   table,   td {     mso-table-lspace: 0pt !important;     mso-table-rspace: 0pt !important;   }    /* Use a better rendering method when resizing images in Outlook IE. */   img {     -ms-interpolation-mode: bicubic;   }    /* Prevent Windows 10 Mail from underlining links. Styles for underlined links should be inline. */   a {     text-decoration: none;   } </style>```
