require_relative '../node_modules/react-native/scripts/react_native_pods'
require_relative '../node_modules/@react-native-community/cli-platform-ios/native_modules'

platform :ios, '10.0'

target 'AwesomeModal' do
  config = use_native_modules!

  use_react_native!(:path => config["reactNativePath"])

  pod 'react-native-safe-area', :path => '../node_modules/react-native-safe-area'
end


