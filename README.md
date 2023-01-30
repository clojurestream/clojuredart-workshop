# ClojureDart Workshop

ClojureDart is a Clojure dialect for writing cross-platform native desktop and mobile apps. It allows Clojure devs to reach new client platforms thanks to Flutter. (Flutter is a performant cross-platform GUI library by Google.) By the end of the workshop you will know ClojureDart, Flutter ecosystem and be autonomous to write apps.

## System Requirements

- [Flutter][flutter] latest
- [clojure-cli-tools][clojure-cli-tools] v1.10.3.814 or greater

To verify things are set up properly, you can run this:
```
flutter doctor
=> 
...
[✓] Flutter (Channel stable, <version>, on <os>, locale en-US)
...
```

```
clj -Sdescribe
=>
{:version "1.11.1.1208"
 :config-files ["<paths>"]
 :config-user "/Users/<user>/.clojure/deps.edn"
 :config-project "deps.edn"
 :install-dir "<path>"
 :config-dir "/Users/<user>/.clojure"
 :cache-dir ".cpcache"
 :force false
 :repro false
 :main-aliases ""
 :repl-aliases ""}
```

## Setup

- Install XCode
- Install Android Studio
- Clone the repo and follow the instructions in [00-setup](exercises/00-setup/README.md)

```
git clone https://github.com/clojurestream/clojuredart-workshop

cd clojuredart-workshop/exercies/00-setup
```

## Workshop Feedback

At the end of the workshop, please [provide short feedback][feedback-form].


[flutter]: https://flutter.dev/docs/get-started/install
[clojure-cli-tools]: https://clojure.org/guides/install_clojure
[feedback-form]: https://forms.gle/iZ8YMfftWdu3MsSPA
[android-studio]: https://developer.android.com/studio
