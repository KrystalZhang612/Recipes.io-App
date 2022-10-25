# Recipes.io App
An App that allows users to store recipes, browse them, organize them by categories and view the details of a certain recipe. The user can also add a new recipe to our collection. The App contains a basic tab bar, data model, grid layout, and AsyncImage. Besides a tab user interface that switches between the main screens of the App, the home screen also presents a list of recipes in the form of cards with images stored remotely. Each card can be redirected to a specific recipe outlining its details. The recipes can also be accessed from the categories where the recipes are filtered by type of meal. All that was for browsing purposes. The App was built from Scratch.
## Recipes.io App Overview:
<p align = "center">
   <img src ="https://github.com/KrystalZhang612/Recipes.io-App/blob/main/Recipe.io%20App%20overview-1.png" width = "403.44" height = "873.1034"/>&nbsp; 
   <img src = "https://github.com/KrystalZhang612/Recipes.io-App/blob/main/Recipe.io%20App%20overview-2.png" width = "403.44" height = "873.1034"/>
   <img src = "https://github.com/KrystalZhang612/Recipes.io-App/blob/main/Recipe.io%20App%20overview-3.png" width = "403.44" height = "873.1034"/>&nbsp; 
   <img src ="https://github.com/KrystalZhang612/Recipes.io-App/blob/main/Recipe.io%20App%20overview-4.png" width = "403.44" height = "873.1034"/>
   <img src = "https://github.com/KrystalZhang612/Recipes.io-App/blob/main/Recipe.io%20App%20overview-5.png" width = "403.44" height = "873.1034"/>&nbsp;
   <img src = "https://github.com/KrystalZhang612/Recipes.io-App/blob/main/Recipe.io%20App%20overview-6.png" width = "403.44" height = "873.1034"/>
</p> 


# Build
[Method to Run & Test the Project Locally](https://github.com/KrystalZhang612/Recipes.io-App/blob/main/README.md#method-to-run--test-the-project-locally)<br/>
[Prerequisites & Setups](https://github.com/KrystalZhang612/Recipes.io-App/blob/main/README.md#prerequisites--setups)<br/> 
[Debugging&Troubleshooting]()<br/> 
[Synchronous Developing Notes](https://github.com/KrystalZhang612/Recipes.io-App/blob/main/README.md#synchronous-developing-notes)<br/> 
[Testing Result]()
# Contribution
[Author]()
# Functionalities/Demo
- Allowing users to store their favorite recipes from various online resources like Pinterest. 
- Allowing users to organize their saved recipes by different categories and view details.
- Allowing users to create new recipes and add all details and descriptions.
# Compatibility
`iPhone 13+`, `Any iOS Version < iOS 16`
# Method to Run & Test the Project Locally
Download the entire project to local directory <br/> 
Xcode must be `13.4` and higher versions with all Xcode dependencies updated. <br/>
`NOTE`Not fully compatiable with iOS 16. Fully compatiable with any versions lower than iOS 16 devices. <br/> 
Compatible with MacOS Monterey `12.0` or higher versions <br/> 
Run the project, choose Simulator iPhone 13 or iPhone 13ProMax for best compatiability.
# 🛠️ Developing Languages, Tools, and Techniques Needed
[SwiftUI](https://developer.apple.com/xcode/swiftui/)<br/> 
[Xcode 14.0.1 iPhone 13 Simulator iOS 15](https://developer.apple.com/documentation/xcode-release-notes/xcode-14_0_1-release-notes)<br/>
[Scratch](https://en.wikipedia.org/wiki/Scratch_(programming_language))<br/> 
[SF Symbols](https://developer.apple.com/sf-symbols/)<br/> 
[Swift](https://developer.apple.com/swift/)<br/> 
[Forks over Knives Recipes](https://www.forksoverknives.com)<br/> 
[PostImage(JPG/PNG Direct Link Generator)](https://postimages.org)<br/>
<div>
   <img src ="https://github.com/KrystalZhang612/RepliFlix/blob/main/swift%20ui%20symbol%20logo.png" title="SwiftUI" alt ="SwiftUI" width="60" height ="60"/>&nbsp; 
   <img src ="https://github.com/devicons/devicon/blob/master/icons/xcode/xcode-plain.svg" title ="Xcode" alt ="Xcode" width="60" height ="60"/>&nbsp; 
   <img src ="https://github.com/KrystalZhang612/RepliFlix/blob/main/sf%20symbol%20logo.png" title = "SF Symbol" alt ="SF Symbol" width = "60" height="60"/>&nbsp; 
   <img src ="https://github.com/devicons/devicon/blob/master/icons/swift/swift-original.svg" title ="Swift" alt ="Swift" width="60" height="60"/>&nbsp;
   <img src ="https://github.com/KrystalZhang612/Recipes.io-App/blob/main/postimage%20logo.png" title="PostImage" alt="PostImage" width="286" height="60"/>&nbsp; 
   <img src ="https://github.com/KrystalZhang612/Recipes.io-App/blob/main/forks%20over%20knives%20logo.png" title ="Forks over Knives" alt ="Forks over Knives" width = "358" height = "60"/>&nbsp;     
</div>

# Prerequisites & Setups
Create a new Xcode project.<br/> 
Rearrange all files into different folders properly.<br/>
Set up Automatic Preview for SwiftUI files: `Adjust Editor Options -> Enable Canvas on-side.`
# Synchronous Developing Notes
Start by create several View files under `Main` and define their navigation view titles:<br/>
In [HomeView.swift](https://github.com/KrystalZhang612/Recipes.io-App/blob/main/Recipes.io%20App/Views/Main/HomeVIew.swift):
```Swift 
struct HomeView: View {
    var body: some View {
        NavigationView {
            Text("My Recipes")
                .navigationTitle("My Recipes")
}}}
In CategoriesView.swift:
 struct CategoriesView: View {
    var body: some View {
        NavigationView {
            Text("Categories")
.navigationTitle("Categories") In NewRecipeView.swift:
 struct NewRecipeView: View {
    var body: some View {
```

































