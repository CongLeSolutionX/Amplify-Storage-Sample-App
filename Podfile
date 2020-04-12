# Uncomment the next line to define a global platform for your project
platform :ios, '13.0'

AWS_SDK_VERSION = "2.12.0"

target 'AmplifyStorageSampleApp' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for AmplifyStorageSampleApp
  pod 'AWSAppSync'
  pod 'Amplify'
  pod 'AmplifyPlugins'
  pod 'AWSPluginsCore'
  pod 'AWSPredictionsPlugin'
  pod 'CoreMLPredictionsPlugin'
  pod 'AWSS3', "~> #{AWS_SDK_VERSION}"
  pod "AWSMobileClient", "~> #{AWS_SDK_VERSION}"
  pod 'AWSAuthUI', "~> #{AWS_SDK_VERSION}"
  pod 'AWSUserPoolsSignIn', "~> #{AWS_SDK_VERSION}"
  target 'AmplifyStorageSampleAppTests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'AmplifyStorageSampleAppUITests' do
    inherit! :search_paths
    # Pods for testing
  end

end
