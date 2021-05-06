Here used Owner lib for different mobile platforms, devices, platforms:

Run tests on "browserstack server" for iOS devices: gradle clean -Denv=bs_ios bs_ios_tests

Run tests on "browserstack server" for Android devices: gradle clean -Denv=bs_android bs_android_tests 

Run tests on "phone emulator" for Android devices: gradle clean -Denv=emu_android emu_android_tests

Run tests on "live phone" for Android devices: gradle clean -Denv=phone_android emu_android_tests

Run tests on "selenoid" for Android devices: gradle clean -Denv=selenoid emu_android_tests


