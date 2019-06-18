# w.bloggar

A Universal Weblog Editor for Windows

![Logo](https://web.archive.org/web/20090422082706im_/http://wbloggar.com/images/wb-tools.png)

## The Project

Early on the 21st Century, there was a fever, it was called weblogs. Several different blog services started popping up over the Internet, in 2001 Blogger.com was the most popular one. Around that time, Blogger founder, [Evan Williams](https://twitter.com/ev) implemented and shared an API for the service, based on Dave Winer's [XML-RPC protocol](https://en.wikipedia.org/wiki/XML-RPC), that was a seminal work for all modern Web API standards.

As I had recently started my personal blog, I got interested in lerning how to use an API like the one Blogger had, so I created the freeware project Bloggar (with an "a"), that in portuguese sounded exactly as the verb "to blog". Early on, it got some traction over the web and Ev Williams blogged about it, driving a lot of new users to my tool. Just before I release version 2.0, I got an email from Ev asking me to rename the tool as it's pronunciation in english was too close to their trade mark. So I renamed it to w.bloggar as a reference to weblog and Windows (the target platform for the tool).

During the next 6 years I had a lot of fun developing this project, added support to pretty much all blog services in the market (with API), translated to multiple languages, I made a lot of friends all over the world, gave interviews, had w.bloggar cited in several books and magazines, got some donation and even negotiated a possible purchase of the tool by Blogger.com, months before they were accquired by Google. If that deal was made, w.bloggar could have become a Google project.

Around 2007 new browser frameworks like AJAX, started to enable rich editors on web browsers and the interest for my tool started to fade, at the same time my professional life had changed a lot, so I officialy ended the project by that year. Unfortunately because of a miscomunication with the donor of w.bloggar website hosting, I ended up losing the domain and site content. Fortunately [Archive.org has a copy of it](https://web.archive.org/web/20090422082706/http://wbloggar.com/), so you still can download older versions from there.

More recently, in 2013, I was invited to present a panel about w.bloggar history at the Campus Party Recife in Brazil, your can check the [presentation slides (in Portuguese)](https://www.slideshare.net/slideshow/embed_code/key/FZk0LfRlmH3etM).

Now I'm releasing the source code here, as a preservation effort for this project. If you just want the binaries to try it, download the portable version at the [Release page](https://github.com/lvcabral/w.bloggar/releases)

## The Application

The w.bloggar is an application that acts as an interface between the user and one or more blog(s); in other words, it is a Post and Template editor, with several features and resources that the browser based blog editors do not offer.

Because w.bloggar runs over the Windows GUI, it allows the user to edit posts without being connected to the Internet. Posts can be saved locally; and anytime the user wants to publish a new text, one click on the w.bloggar icon in the system tray brings up the editor, and one more click will post it to the weblog.

Another great advantage of w.bloggar is that it is compatible with most of the weblog systems available, allowing an advanced user to have only one interface to several accounts hosted on several different sites, using different publishing systems.

To communicate with the weblog, w.bloggar requires that the blog system have implemented an API (Application Programming Interface.) Currently, w.bloggar is compatible with all tools that implements Blogger API, metaWeblog API, MovableType API and b2 API; all based on the XML-RPC definition.

![UI](https://web.archive.org/web/20100101032924if_/http://wbloggar.com/images/wb4-shot1.png)

## The Features

- Post and Publish on most blogs/cms tools and services
- Edit Posts and Templates
- Save Posts locally for further publishing
- Import Text files
- Add links and images
- Format text font and alignment
- Multiple accounts and blogs
- Post preview
- Colorized HTML code
- HTML tags menu
- Find/Replace option
- Post to many blogs
- Title and Category Fields
- Spell Checking
- File and Image Upload
- Custom Tags Menu
- Toolbar Icons Skin
- Supports Windows XP
- Support to the advanced MovableType options New!
- Add Account Wizard New!
- Support to Multiple Categories New!
- Option to XHTML compliance New!
- Import and Export Settings New!
- Ping to Weblogs.Com, blo.gs, Technorati and ping-o-matic New!
- No Spyware!
- No Nag Screens!

## The ActiveX Dependencies

- **Actbar2.ocx** - DataDynamics ActiveBar v2.0 (commercial component)
- **SizerOne.ocx** - ComponentOne SizerOne v1.0 (commercial component)
- **RichTX32.ocx** - Microsoft RichText Control v6.1 (included with VB6)
- **ActiveCbo.ocx** - [RainDrops Active Combo v1.3](https://github.com/lvcabral/ActivePack) (freeware by Marcelo Lv Cabral)
- **ActiveForm.ocx** - [RainDrops Active Form v1.4](https://github.com/lvcabral/ActivePack) (freeware by Marcelo Lv Cabral)
- **ActiveXMLReg.dll** - XML Based Registry v1.0 (freeware by R. Glenn Scott)
- **DTPicker.ocx** - Date Time Picker Control v1.0 (freeware by Jonas Woltz)
- **SSubTmr6.dll** - [VBAccelerator Subclassing Control v1.1](http://www.vbaccelerator.com/codelib/ssubtmr/ssubtmr.htm) (freeware by Steve McMahon)

All these binaries are included at the foder "Libs" inside the portable package available on the [Release page](https://github.com/lvcabral/w.bloggar/releases) however the two commercial components requires a license to be used on Visual Basic 6 development environment.

## The Author

- My website is [https://lvcabral.com](https://lvcabral.com)
- My twitter is [@lvcabral](https://twitter.com/twitter)
- My podcast is [PODebug Podcast](http://podebug.com)
- Check my other [GitHub repositories](https://github.com/lvcabral)

## The License

Copyright (C) 2011-2018 Marcelo Lv Cabral. All rights reserved.

Licensed under [GPL v2](https://github.com/lvcabral/w.bloggar/blob/master/LICENSE) License.

This repository includes code from project [XML-RPC COM by Jan Sijm](https://sourceforge.net/projects/xmlrpccomobj/)