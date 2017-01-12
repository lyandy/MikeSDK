platform :ios, '8.0'
workspace 'MikeSDKDemo.xcworkspace'

abstract_target 'MikeKitDemo' do
    pod 'SDWebImage', '3.8.2'
    pod 'Toast', '~> 3.0'
    pod 'SVProgressHUD', '~> 2.0.3'
    pod 'M80AttributedLabel', '~> 1.5.0'
    pod 'TZImagePickerController', '~> 1.7.7'
    pod 'AFNetworking'

    target 'MikeSDKDemo' do
        project 'MikeSDKDemo.xcodeproj'
        pod 'FMDB', '~> 2.5'
        pod 'Reachability', '~> 3.1.1'
        pod 'CocoaLumberjack', '~> 2.0.0-rc2'
        pod 'SSZipArchive', '~> 1.2'
    end
    
    target 'Interface' do
        project '../Interface/Interface.xcodeproj'
    end
end
