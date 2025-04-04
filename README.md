# iOS 101: Lab - Week 7 - Flix Detail (TableView + Navigation)

## 🎯 Goals

By the end of this lab I was able to...

- Handle table view cell selection  
- Implement push navigation  
- Pass data to another view controller using segues  
- Use `prepare(for:sender:)` to pass data  
- Display detailed information in a secondary view  
- Customize and polish a detail screen UI  

## 🚀 Features

### ✅ Required Features

- Tap on a movie cell to navigate to a detail screen  
- Add a new view controller for the detail screen in storyboard  
- Use a segue with the "Show" style to navigate between view controllers  
- Create and link a `DetailViewController` class to the detail screen  
- Add UI elements (poster, backdrop, title, overview, vote average, release date)  
- Pass movie data to the detail view using the `prepare(for:sender:)` method  
- Configure the detail UI using passed movie data and `Nuke` to load images  
- Enable large titles for the feed view and small titles for the detail view  
- Deselect table cell on return to feed view  

## 📚 Resources I Used

- [UITableView - Passing Data](https://guides.codepath.com/ios/Using-UITableView#3-passing-data-from-table-view-cells)  
- [UINavigationController - Apple Docs](https://developer.apple.com/documentation/uikit/uinavigationcontroller)  
- [Push Navigation - CodePath Guide](https://guides.codepath.com/ios/Understanding-Navigation-in-iOS#push-navigation)  
- [TMDB API - Get Popular Movies](https://developers.themoviedb.org/3/movies/get-popular-movies)  
- [Swift Codable with Custom Dates](https://useyourloaf.com/blog/swift-codable-with-custom-dates/)  
- [Date Formatter Reference](https://nsdateformatter.com/)  
- [Nuke - GitHub](https://github.com/kean/Nuke)  

## 🛠 Notes

- The project builds on the previous movie feed lab  
- UI polish included adjusting image view content modes, font styles, and navigation titles  
- The `movie` property in `DetailViewController` uses `!` because it’s guaranteed to be set before the detail screen loads  
- I only edited the parts of the code marked for customization  
- This lab helped reinforce how to create multi-screen apps using storyboards, segues, and view controller communication in Swift  

