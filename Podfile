# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'
platform :ios, '8.0'
target 'react_native' do
    rn_path = '../node_modules/react-native'
    pod 'yoga', path: "#{rn_path}/ReactCommon/yoga/yoga.podspec"
    pod 'React', path: rn_path, subspecs: [
        'Core',
        'RCTActionSheet',
        'RCTAnimation',
        'RCTGeolocation',
        'RCTImage',
        'RCTLinkingIOS',
        'RCTNetwork',
        'RCTSettings',
        'RCTText',
        'RCTVibration',
        'RCTWebSocket',
        'DevSupport',
        #'BatchedBridge'
    ]
end
   
   
