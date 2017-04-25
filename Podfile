source 'https://github.com/CocoaPods/Specs.git'
platform :ios, '9.0'
use_frameworks!

def shared_pods
	pod 'Alamofire'
	pod 'ObjectMapper'
	pod 'AlamofireObjectMapper'
	pod 'SwiftyJSON'
	pod 'Starscream'
	pod 'KeychainAccess'
	pod 'CocoaLumberjack/Swift', '~> 3.0.0'
end

target 'SparkSDK' do
	shared_pods
end

target 'SparkSDKTests' do
	shared_pods
end
