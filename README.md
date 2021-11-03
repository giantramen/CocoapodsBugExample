# CocoapodsBugExample

Run a pod install with use_frameworks! un-commented, see how Pods/CoreDataPodSample compile sources includes CoreDataPodSample.xcdatamodeld
Then comment out use_frameworks!, and uncomment use_modular_headers!, pod install, and then see how Pods/CoreDataPodSample compile sources DOES NOT include CoreDataPodSample.xcdatamodeld
