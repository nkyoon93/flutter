# flutter

flutter setting in ubuntu

1.getting flutter SDK
'''
git clone -b stable https://github.com/flutter/flutter.git
'''

2.setting path of flutter SDK
'''
export PATH=$PATH:`pwd`/flutter/bin
'''

3.flutter upgrade
'''
sudo apt-get install curl
flutter upgrade
flutter doctor
'''

4.Install dependencies
'''
sudo apt install lib32stdc++6 
'''

5.android studio install
'''
sudo add-apt-repository ppa:maarten-fonville/android-studio
sudo apt update
sudo apt-get update
sudo apt-get install android-studio
'''

6.agree lisence
'''
cd $HOME/flutter/bin
./flutter doctor --android-licenses
'''

DONE!
