# SupportDocs: DataSource
This branch is where SupportDocs gets its data! You can add, edit, and delete documents here. For usage instructions, check out the `README`'s [usage](https://github.com/aheze/SupportDocs#using-the-github-repository) section in the main branch.

## Data Source JSON URL
<a href="https://raw.githubusercontent.com/zodttd/GammaSupportDocs/DataSource/_data/supportdocs_datasource.json">https://raw.githubusercontent.com/zodttd/GammaSupportDocs/DataSource/_data/supportdocs_datasource.json</a>

<details markdown="1">
<summary><strong>Show examples</strong></summary>

<hr>

### SwiftUI
```swift
struct SwiftUIExampleView_MinimalCode: View {
    let dataSource = URL(string: "https://raw.githubusercontent.com/zodttd/GammaSupportDocs/DataSource/_data/supportdocs_datasource.json")!
    @State var supportDocsPresented = false
    
    var body: some View {
        Button("Present SupportDocs from SwiftUI!") { supportDocsPresented = true }
        .sheet(isPresented: $supportDocsPresented, content: {
            SupportDocsView(dataSource: dataSource, isPresented: $supportDocsPresented)
        })
    }
}
```

### UIKit
```swift
class UIKitExampleController_MinimalCode: UIViewController {
    /**
    Connect this inside the storyboard.
    
    This is just for demo purposes, so it's not connected yet.
    */
    @IBAction func presentButtonPressed(_ sender: Any) {
        let dataSource = URL(string: "https://raw.githubusercontent.com/zodttd/GammaSupportDocs/DataSource/_data/supportdocs_datasource.json")!
    
        let supportDocsViewController = SupportDocsViewController(dataSource: dataSource)
        self.present(supportDocsViewController, animated: true, completion: nil)
    }
}
```

<hr>

</details>

## Table of Contents
- [404 Page](https://zodttd.github.io/GammaSupportDocs/404) (SupportDocs Integrated File) ([edit](https://github.com/zodttd/GammaSupportDocs/edit/DataSource/404.md))
- [Apple smoothie](https://zodttd.github.io/GammaSupportDocs/Sample-Smoothies/Apple) (smoothies) ([edit](https://github.com/zodttd/GammaSupportDocs/edit/DataSource/Sample-Smoothies/Apple.md))
- [Blueberry smoothie](https://zodttd.github.io/GammaSupportDocs/Sample-Smoothies/Blueberry) (smoothies) ([edit](https://github.com/zodttd/GammaSupportDocs/edit/DataSource/Sample-Smoothies/Blueberry.md))
- [Buy blue boba](https://zodttd.github.io/GammaSupportDocs/Sample-Boba/BuyBlueBoba) (boba) ([edit](https://github.com/zodttd/GammaSupportDocs/edit/DataSource/Sample-Boba/BuyBlueBoba.md))
- [Buy cream boba](https://zodttd.github.io/GammaSupportDocs/Sample-Boba/BuyCreamBoba) (boba) ([edit](https://github.com/zodttd/GammaSupportDocs/edit/DataSource/Sample-Boba/BuyCreamBoba.md))
- [Buy orange boba](https://zodttd.github.io/GammaSupportDocs/Sample-Boba/BuyOrangeBoba) (boba) ([edit](https://github.com/zodttd/GammaSupportDocs/edit/DataSource/Sample-Boba/BuyOrangeBoba.md))
- [How to cook pizza](https://zodttd.github.io/GammaSupportDocs/Sample-FastFood/HowToCookPizza) (fastFood) ([edit](https://github.com/zodttd/GammaSupportDocs/edit/DataSource/Sample-FastFood/HowToCookPizza.md))
- [How to eat burritos](https://zodttd.github.io/GammaSupportDocs/Sample-FastFood/HowToEatBurritos) (fastFood) ([edit](https://github.com/zodttd/GammaSupportDocs/edit/DataSource/Sample-FastFood/HowToEatBurritos.md))
- [How to eat grilled cheese](https://zodttd.github.io/GammaSupportDocs/Sample-FastFood/HowToEatGrilledCheese) (fastFood) ([edit](https://github.com/zodttd/GammaSupportDocs/edit/DataSource/Sample-FastFood/HowToEatGrilledCheese.md))
- [How to eat nachos](https://zodttd.github.io/GammaSupportDocs/Sample-FastFood/HowToEatNachos) (fastFood) ([edit](https://github.com/zodttd/GammaSupportDocs/edit/DataSource/Sample-FastFood/HowToEatNachos.md))
- [How to eat tacos](https://zodttd.github.io/GammaSupportDocs/Sample-FastFood/HowToEatTacos) (fastFood) ([edit](https://github.com/zodttd/GammaSupportDocs/edit/DataSource/Sample-FastFood/HowToEatTacos.md))
- [How to make spaghetti](https://zodttd.github.io/GammaSupportDocs/Sample-FastFood/HowToMakeSpaghetti) (fastFood) ([edit](https://github.com/zodttd/GammaSupportDocs/edit/DataSource/Sample-FastFood/HowToMakeSpaghetti.md))
- [How to prepare ramen](https://zodttd.github.io/GammaSupportDocs/Sample-FastFood/HowToPrepareRamen) (fastFood) ([edit](https://github.com/zodttd/GammaSupportDocs/edit/DataSource/Sample-FastFood/HowToPrepareRamen.md))
- [Peach smoothie](https://zodttd.github.io/GammaSupportDocs/Sample-Smoothies/Peach) (smoothies) ([edit](https://github.com/zodttd/GammaSupportDocs/edit/DataSource/Sample-Smoothies/Peach.md))
- [Plum smoothie](https://zodttd.github.io/GammaSupportDocs/Sample-Smoothies/Plum) (smoothies) ([edit](https://github.com/zodttd/GammaSupportDocs/edit/DataSource/Sample-Smoothies/Plum.md))
- [Red berry smoothie](https://zodttd.github.io/GammaSupportDocs/Sample-Smoothies/RedBerries) (smoothies) ([edit](https://github.com/zodttd/GammaSupportDocs/edit/DataSource/Sample-Smoothies/RedBerries.md))


## Notes
- Your changes make take up to five minutes to deploy. You can track the deployment progress [here](https://github.com/zodttd/GammaSupportDocs/deployments/activity_log?environment=github-pages).
- Do **not** update this file (`README.md`) directly. Your changes will be overriden the next time you push (the GitHub Action will regenerate this file). Instead, update the file in [`_scripts/README.md`](https://github.com/zodttd/GammaSupportDocs/edit/DataSource/_scripts/README.md). 