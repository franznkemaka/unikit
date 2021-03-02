# ♾️ Unikit

### Universal React Native + Web Kit

Unikit is a library that offers React Native + Web native libraries. No .web.\* or .native.\* files anymore. It wraps React Native libs and adds web support when needed.

## 💡 Why Unikit

There is already Expo Unimodules that supports Android, iOS, Web ... packages why unikit? The idea behind is to transport vanilla React Native libraries on the web in single libraries.

Unikit aims to have an easy setup, mock the original React Native library when possible to avoid learning curves and maintenance.

## ⁉ How it works

When you install a unikit-library let's say `@unikit/firebase-analytics`. It installs `@react-native-firebase/analytics` for React Native Android and iOS. On the web it installs and configures `Firebase JS SDK`.

You just have to configure `@unikit/firebase-analytics` once and it works everywhere!

## ℹ️ Usage

The usage of each package can be found in their respective README files.

## 🗺 Project Layout

- [`packages`](/packages) All the source for react-native supported libraries. You can add and modify libraries there.

## ❤️ Contributing

Under the Projects tab, you can find and suggest new libraries!

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## ⚖️ License

This project is licensed under the [MIT license](LICENSE)

© 2021 Franz Nkemaka
