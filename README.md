# Minimal Reproducible Example for https://github.com/expo/expo/issues/33227
# Steps to Reproduce
1. Start an iOS simulator
2. Run `npx expo run:ios` (This should run fine)
3. `ctrl-c` to stop the dev server
4. Run `npx expo run:ios` again without closing the app in the simulator
