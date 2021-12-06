
## Documentation


## How to run


## Installation

Install flutter as per the flutter official documentation for your machine


https://docs.flutter.dev/get-started/install


for the mac os  follow the steps

1. Download the following installation bundle to get the latest stable release of the Flutter SDK:

https://storage.googleapis.com/flutter_infra_release/releases/stable/macos/flutter_macos_2.5.3-stable.zip


2. Extract the file in the desired location, for example:


```bash
 cd ~/development
 unzip ~/Downloads/flutter_macos_2.5.3-stable.zip
```

3. Add the flutter tool to your path:
    

 ```bash
 export PATH="$PATH:`pwd`/flutter/bin"
```

4. Run flutter doctor
Run the following command to see if there are any dependencies you need to install to complete the setup (for verbose output, add the -v flag):
 
 
 ```bash
flutter doctor
```
This command checks your environment and displays a report to the terminal window. The Dart SDK is bundled with Flutter; it is not necessary to install Dart separately. Check the output carefully for other software you might need to install or further tasks to perform (shown in bold text).

For example:

 ```bash
[-] Android toolchain - develop for Android devices
    • Android SDK at /Users/obiwan/Library/Android/sdk
    ✗ Android SDK is missing command line tools; download from https://goo.gl/XxQghQ
    • Try re-installing or updating your Android SDK,
      visit https://docs.flutter.dev/setup/#android-setup for detailed instructions.
```


The following sections describe how to perform these tasks and finish the setup process.

Once you have installed any missing dependencies, run the flutter doctor command again to verify that you’ve set everything up correctly.


If you did not use the archive, Flutter will download necessary development binaries as they are needed (if you used the archive, they are included in the download). You may wish to pre-download these development binaries (for example, you may wish to do this when setting up hermetic build environments, or if you only have intermittent network availability). To do so, run the following command:

 ```bash
 flutter precache
```


## Run Application

For running the flutter application in development mode, you should need any of the flutter Developent IDE like 

Android Studio or VS Code 


Clone this repo or use the project zip file and navigate to the project location.  run

 ```bash
  flutter packages get
```

Run this application in your desired virtual or physical devices

 ```bash
  flutter run 
```

## Screenshots


![Simulator Screen Shot - iPhone 13 - 2021-12-06 at 22 10 28](https://user-images.githubusercontent.com/24736242/144907382-14a35c10-3e4d-4ee0-9ab5-4aeb64b60679.png)
![Simulator Screen Shot - iPhone 13 - 2021-12-06 at 22 10 29](https://user-images.githubusercontent.com/24736242/144907455-cda69e38-ac82-48cc-9d41-5b32fdbe804a.png)




## Tech Stack

**Client:** Flutter, Dart




## Support

For support, email muhsin.3009@gmail.com


## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/muhsinzyne/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/muhsinzyne)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/muhsinzyne)




## License

[MIT](https://choosealicense.com/licenses/mit/)

