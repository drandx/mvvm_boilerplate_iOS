source 'https://github.com/CocoaPods/Specs.git'
xcodeproj 'mvvm_boilerplate_iOS.xcodeproj'

def import_pods
    pod 'Moya'
    pod 'Moya/RxSwift'
    pod 'Moya/ReactiveCocoa'
    pod 'ObjectMapper', '~> 1.0'
    pod 'ReactiveCocoa' 
end

target :mvvm_boilerplate_iOS do
    xcodeproj 'mvvm_boilerplate_iOS.xcodeproj'
    platform :ios, '8.0'
    use_frameworks!
    import_pods
end