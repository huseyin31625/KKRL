You must write these commands firstly:
bcdedit /set {current} testsigning on
shutdown /r /t 0
devcon install kkrl.inf root\kkrl
shutdown /r /t 0
