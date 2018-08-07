# GSOC project Of Wayback Machine Chrome Extension for Internet Archive

This is the project I helped in building along with several contributors for GSOC 18, Internet archive under the mentorship of Abhishek Das (abhidas@archive.org). I am also thankful to Mark Graham (mark@archive.org) for giving me this opportunity.

I worked on the following things, added some new features for the wayback machine chrome extensions. They include :
## The project goals :

## 1.Fixing Bugs :
The first few weeks of my GSOC period ,I spent time to fix the existing bugs of the extension. The code is merged with the original repository.(https://github.com/internetarchive/wayback-machine-chrome)

## 2.Automatic Archiving of URL's :
This feature is regarding auto-archiving the URLs.This happens in 2 modes
### Modes:  
#### Mode1: Displays "S", which indicates that the current URL is being checked and it is not available in the Wayback Machine.
#### Mode2: Then a single click on the extension icon will display a "Check Mark" in the extension icon indicating that the webpage is currently being archived
User can turn on this feature by going to the Settings page(By Clicking on the gear icon on the extension pop-up).By default, it is "off". 
This feature is merged with the original repository.

## 3.Redesigned About page, added Settings, showing URL with status-code when intercepted and added feedback Button "
Some of the time I gave to redesigning of the About page of our extension.I also added "Settings" page where the Users can choose what/how they want to see the extension.I also added a small feedback button ,where it will be easy for the users to give the feedback. Another thing that I worked on is showing URL name and also the status code when intercepted. These parts are also merged with the original repository.

## 4.Context Feature :
This is the main feature that I have worked on during the GSOC period. This feature allows the users to see the different Context of an URL. Users can select how they want to see the Context Screens through the settings page. They can also turn on the auto-update Context feature which allows the Context Screens to update automatically as they visits to different URLs.

Different context that we provide 
* Alexa
* Whois
* Tweets regarding the current URL
* Wayback Machine Overview of the current URL
* Annotations of the Current URL and current Domain
* Tagcloud
* SimilarWeb overview of the current URL

Different way that we provide context
* Showing the Context Screens in tabs
* Showing the Context Screens in windows
* Showing the Context Screens in a single-window

## 5.Borrow Books Feature :
This is the feature that I have worked on the last month. If a user is on a amazon books site, then the user can borrow that book from Archive.org (If we have that book).This feature is also controlled by the user. We provide a small change in icon to "B" indicating we have that book. User can get the link to borrow the books from the extension pop-up window.

### Things left to do/complete
1) Improve the UI
2) Adding more source of context

## License

Copyright Internet Archive, 2017
AGPL-3


## Credits

- Richard Caceres, @rchrd2
- Mark Graham, @markjohngraham
- Benjamin Mandel
- Kumar Yoges
- Anton
- Abhidhas, @abhidas17695
- Rakesh N Chinta, @rakesh-chinta
- Anish Kumar Sarangi, @anishsarangi