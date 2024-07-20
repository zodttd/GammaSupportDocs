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
- [Adding Games To Gamma](https://zodttd.github.io/GammaSupportDocs/GettingStarted/AddGames) (gettingstarted, toppriority) ([edit](https://github.com/zodttd/GammaSupportDocs/edit/DataSource/GettingStarted/AddGames.md))
- [An important bug fixed! Version 1.6.2 released](https://zodttd.github.io/GammaSupportDocs/News/Version010602) (news, toppriority) ([edit](https://github.com/zodttd/GammaSupportDocs/edit/DataSource/News/Version010602.md))
- [Big update! Version 1.6.1 released](https://zodttd.github.io/GammaSupportDocs/News/Version010601) (news, toppriority) ([edit](https://github.com/zodttd/GammaSupportDocs/edit/DataSource/News/Version010601.md))
- [Bug Reports & Feature Requests](https://zodttd.github.io/GammaSupportDocs/Contact/BugReport3) (contact) ([edit](https://github.com/zodttd/GammaSupportDocs/edit/DataSource/Contact/BugReport3.md))
- [Cheats are here](https://zodttd.github.io/GammaSupportDocs/News/CheatCodes-2) (news, priority) ([edit](https://github.com/zodttd/GammaSupportDocs/edit/DataSource/News/CheatCodes-2.md))
- [Coming soon!](https://zodttd.github.io/GammaSupportDocs/ControllerSkins/ComingSoon) (controllerskins) ([edit](https://github.com/zodttd/GammaSupportDocs/edit/DataSource/ControllerSkins/ComingSoon.md))
- [Email Us](https://zodttd.github.io/GammaSupportDocs/Contact/Email) (contact) ([edit](https://github.com/zodttd/GammaSupportDocs/edit/DataSource/Contact/Email.md))
- [Game Compatibility](https://zodttd.github.io/GammaSupportDocs/FAQs/Compatibility) (faqs) ([edit](https://github.com/zodttd/GammaSupportDocs/edit/DataSource/FAQs/Compatibility.md))
- [Gamma Support Center has arrived](https://zodttd.github.io/GammaSupportDocs/News/GammaSupportArrived) (news, toppriority) ([edit](https://github.com/zodttd/GammaSupportDocs/edit/DataSource/News/GammaSupportArrived.md))
- [Multi-Disc functionality is here](https://zodttd.github.io/GammaSupportDocs/News/MutiDisc) (news, priority) ([edit](https://github.com/zodttd/GammaSupportDocs/edit/DataSource/News/MutiDisc.md))
- [No more ads with Gamma Pro](https://zodttd.github.io/GammaSupportDocs/News/GammaPro) (news, toppriority) ([edit](https://github.com/zodttd/GammaSupportDocs/edit/DataSource/News/GammaPro.md))
- [Settings](https://zodttd.github.io/GammaSupportDocs/GettingStarted/Settings) (gettingstarted) ([edit](https://github.com/zodttd/GammaSupportDocs/edit/DataSource/GettingStarted/Settings.md))
- [Social Media - Follow us!](https://zodttd.github.io/GammaSupportDocs/Contact/SocialMedia2) (contact) ([edit](https://github.com/zodttd/GammaSupportDocs/edit/DataSource/Contact/SocialMedia2.md))
- [Subscribing as a Gamma Supporter](https://zodttd.github.io/GammaSupportDocs/News/GammaSupporters) (news, priority) ([edit](https://github.com/zodttd/GammaSupportDocs/edit/DataSource/News/GammaSupporters.md))
- [Supported File Types](https://zodttd.github.io/GammaSupportDocs/FAQs/SupportedFileTypes) (faqs) ([edit](https://github.com/zodttd/GammaSupportDocs/edit/DataSource/FAQs/SupportedFileTypes.md))
- [Swap a CD in a multi-disc game](https://zodttd.github.io/GammaSupportDocs/GettingStarted/MultiDisc) (gettingstarted) ([edit](https://github.com/zodttd/GammaSupportDocs/edit/DataSource/GettingStarted/MultiDisc.md))
- [What's New In Version 1.5.4](https://zodttd.github.io/GammaSupportDocs/WhatsNew/v010504tst) (whatsnew, whatsnewv010504, whatsnewv010504tst) ([edit](https://github.com/zodttd/GammaSupportDocs/edit/DataSource/WhatsNew/v010504tst.md))


## Notes
- Your changes make take up to five minutes to deploy. You can track the deployment progress [here](https://github.com/zodttd/GammaSupportDocs/deployments/activity_log?environment=github-pages).
- Do **not** update this file (`README.md`) directly. Your changes will be overriden the next time you push (the GitHub Action will regenerate this file). Instead, update the file in [`_scripts/README.md`](https://github.com/zodttd/GammaSupportDocs/edit/DataSource/_scripts/README.md). 