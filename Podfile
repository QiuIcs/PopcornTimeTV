use_frameworks!

source 'https://github.com/CocoaPods/Specs'
source 'https://github.com/PopcornTimeTV/Specs'

def pods
    pod 'PopcornTorrent', '~> 1.1.13'
    pod 'XCDYouTubeKit', '~> 2.5.6'
    pod 'Alamofire', '~> 4.5.1'
    pod 'AlamofireImage', '~> 3.3.0'
    pod 'SwiftyTimer', '~> 2.0.0'
    pod 'FloatRatingView', '~> 2.0.1'
    pod 'Reachability', '~> 3.1.1'
    pod 'MarqueeLabel/Swift', '~> 3.1.0'
    pod 'ObjectMapper', '~> 3.0.0'
end

target 'PopcornTimeiOS' do
    platform :ios, '11.1'
    pods
    pod 'AlamofireNetworkActivityIndicator', '~> 2.2.0'
    pod 'google-cast-sdk', '~> 3.5.6'
    pod 'OBSlider', '~> 1.1.1'
    pod '1PasswordExtension', '~> 1.8.4'
    pod 'MobileVLCKit-unstable', '~> 3.0.0a43'
end

target 'PopcornTimetvOS' do
    platform :tvos, '11.1'
    pods
    pod 'TvOSMoreButton', '1.0.2'
    pod 'TVVLCKit-unstable', '~> 3.0.0a43'
    pod 'MBCircularProgressBar', '~> 0.3.5-1'
end

target 'TopShelf' do
    platform :tvos, '11.1'
    pod 'ObjectMapper', '~> 3.0.0'
end

def kitPods
    pod 'Alamofire', '~> 4.5.1'
    pod 'ObjectMapper', '~> 3.0.0'
    pod 'AlamofireXMLRPC', '~> 2.2.0'
    pod 'SwiftyJSON', '~> 4.0.0-alpha.1'
    pod 'Locksmith', '~> 4.0.0'
end

target 'PopcornKit tvOS' do
    platform :tvos, '11.1'
    kitPods
end

target 'PopcornKit iOS' do
    platform :ios, '11.1'
    kitPods
    pod 'google-cast-sdk', '~> 3.5.6'
end
