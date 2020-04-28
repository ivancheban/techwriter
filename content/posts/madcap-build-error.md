---
title: MadCap Build Failed Error
date: 2019-06-23T21:00:00.000+00:00
thumb_img_path: "/images/madcap.png"
content_img_path: "/images/madcap.png"
excerpt: 'The error 10086: The process cannot access the file because it is being
  used by another process in MadCap Flare.'
layout: post
subtitle: ''
canonical_url: ''

---
In MadCap Flare, the 10086 **The process cannot access the file because it is being used by another process** error will prevent you from building your target (PDF) in MadCap.

[![](https://1.bp.blogspot.com/-19zXH-cOyFM/XRC6oWmgAvI/AAAAAAAAVzM/vkQ_aYK426824-Sbp9rhc0MO6kiPpSnTQCLcBGAs/s640/2019-06-24_14-33-23.jpg =640x136)](https://1.bp.blogspot.com/-19zXH-cOyFM/XRC6oWmgAvI/AAAAAAAAVzM/vkQ_aYK426824-Sbp9rhc0MO6kiPpSnTQCLcBGAs/s1600/2019-06-24_14-33-23.jpg)

Such error in my case arises when your MadCap project is bound to Git. You need to commit and push all your changes before building the target.

Another workaround is:

1. Open Windows Task Manager.
2. Select AdobeCollabSync.exe process.
3. Select **End task**.

[![](https://1.bp.blogspot.com/-PxZ9dJ3sgjU/XTBfrXaAKiI/AAAAAAAAV7g/1sqzzBqzqHoXvpA5cS8JQDbss6I2-PNRwCLcBGAs/s640/2019-07-18_14-42-48.png =640x550)](https://1.bp.blogspot.com/-PxZ9dJ3sgjU/XTBfrXaAKiI/AAAAAAAAV7g/1sqzzBqzqHoXvpA5cS8JQDbss6I2-PNRwCLcBGAs/s1600/2019-07-18_14-42-48.png)

One more workaround is to use [Foxit Reader](https://www.foxitsoftware.com/downloads/) instead of Adobe Acrobat Reader.