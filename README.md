# Intellego Grok AI Assistant for IntelliJ IDEA

[![Version](https://img.shields.io/jetbrains/plugin/v/29268-intellego.svg)](https://plugins.jetbrains.com/plugin/29268-intellego)
[![Downloads](https://img.shields.io/jetbrains/plugin/d/29268-intellego.svg)](https://plugins.jetbrains.com/plugin/29268-intellego)

## Welcome to the Intellego – Your Grok AI Assistant

### Required: [xAI account and API credits](https://console.x.ai), typical monthly cost - less than $1

### Freemium: [Premium features](https://plugins.jetbrains.com/plugin/29268-intellego-grok-ai-assistant/prices?noRedirect=true) - price of 1 coffee a month - less than $5

* xAI account and credits: https://console.x.ai
* For details, please refer to [Features](https://plugins.jetbrains.com/plugin/29268-intellego-grok-ai-assistant/features?noRedirect=true) page.
* To purchase license, please visit [Costs](https://plugins.jetbrains.com/plugin/29268-intellego-grok-ai-assistant/prices?noRedirect=true)  page.

### Introduction

Hello, fellow developer!
                    
Intellego brings the power of __Grok by xAI -- first with stateful API__ directly into your favorite JetBrains IDE, so you can 
get smart, fast, and context-aware coding help without ever leaving your editor.
                    
### What you can do right now?
                    
* Chat with Grok anytime using the dedicated tool window
* <img src="https://raw.githubusercontent.com/diligiteiust/publicfiles/refs/heads/main/assets/review_code_icon.svg" width="15" alt="Send to Grok for Review"/>Right-click any code selection → __“Send to Grok for Review”__
* Choose your model: defaults to the super-fast `grok-code-fast`, but you can switch to other Grok models for general questions or bigger reasoning tasks
* <img src="https://raw.githubusercontent.com/diligiteiust/publicfiles/refs/heads/main/assets/temperature.png" height="40" alt="Temperature"/>Adjust the Temperature slider: lower = precise & reliable, higher = more creative suggestions
* Lightning-fast actions on selected code:
  * <img src="https://raw.githubusercontent.com/diligiteiust/publicfiles/refs/heads/main/assets/explain_code_icon.svg" width="15" alt="Explain code"/>__Explain Code__ → _Sends selected code to Grok to receive details explanation_
  * <img src="https://raw.githubusercontent.com/diligiteiust/publicfiles/refs/heads/main/assets/refactor_code_icon.svg" width="15" alt="Refactor and improve"/>__Refactor and improve__ → _Sends selected code to Grok to receive refactored and improved code._
  * <img src="https://raw.githubusercontent.com/diligiteiust/publicfiles/refs/heads/main/assets/debug_code_icon.svg" width="15" alt="Debug"/>__Debug / Find Bugs__ → _Sends selected code to Grok to help with debuting_
  * Copy to clipboard last Grok's response in markdown
* <img src="https://raw.githubusercontent.com/diligiteiust/publicfiles/refs/heads/main/assets/auto_copy.png" height="40" alt="Auto copy selected text"/>Switch __ON/OFF__ automated copying selected code to Grok's Assistant
* <img src="https://raw.githubusercontent.com/diligiteiust/publicfiles/refs/heads/main/assets/stateful_calls.png" height="40" alt="Stateful calls"/>Switch __ON/OFF__ stateful API calls. Stateful API makes Grok remember previous queries and context which improves
  subsequent answers without a need to repeat all the details from previous calls. However, it may increase overall
  costs of Grok API usage.

### Quick setup (takes 30 seconds)

1. Go to __Settings → Tools → Grok Assistant__
2. Paste your Grok API key (get one for free at __https://console.x.ai → API Keys → Create API Key__)
3. Click __Test Connection__ – you’re ready to go!

That’s it! Start selecting code and let Grok do the heavy lifting for explanations, refactoring ideas, 
bug hunting, and more.

> Note for Android Studio!
> > To use the plugin in Android Studio you need JCEF Runtime. It takes 10 seconds to switch over to JCEF Runtime. 
> > Please follow [these instructions](https://joachimschuster.de/posts/android-studio-markdown-struggle-never-ends/).
> 
> In short:
> 1. Open menu Help > Find Action… (⇧ Shift + ⌘ Cmd + A) and search for “Choose Boot Java Runtime for the IDE…”
> 2. In the dialog open the drop down Select runtime with JCEF
> 3. Confirm with OK.
> 4. After download and install you have to apply the changes with Restart now

### Feedback & Support

We’re just getting started and would love to hear from you!

Project home & issues: https://diligiteiustitiam.world/Intellego

Questions? Ideas? Found a bug? Open an issue – we usually reply within a day.

Happy coding, and enjoy having Grok as your new pair programmer! 🤓❤️

_— The Intellego team_

<!-- Plugin description end -->

## Installation

- Using the IDE built-in plugin system:

  <kbd>Settings/Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>Marketplace</kbd> > <kbd>Search for "intellego"</kbd> >
  <kbd>Install</kbd>

- Using JetBrains Marketplace:

  Go to [JetBrains Marketplace](https://plugins.jetbrains.com/plugin/MARKETPLACE_ID) and install it by clicking the <kbd>Install to ...</kbd> button in case your IDE is running.

  You can also download the [latest release](https://plugins.jetbrains.com/plugin/MARKETPLACE_ID/versions) from JetBrains Marketplace and install it manually using
  <kbd>Settings/Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>⚙️</kbd> > <kbd>Install plugin from disk...</kbd>

- Manually:

  Download the [latest release](https://github.com/arthef/intellego/releases/latest) and install it manually using
  <kbd>Settings/Preferences</kbd> > <kbd>Plugins</kbd> > <kbd>⚙️</kbd> > <kbd>Install plugin from disk...</kbd>

