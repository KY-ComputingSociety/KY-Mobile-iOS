# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'kymaryam' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!
  pod 'Firebase/Analytics'
  pod 'Firebase/Auth'
  pod 'FirebaseFirestore'
  pod 'Firebase/Storage'

  # Pods for kymaryam

end

post_install do |installer|
  installer.pods_project.build_configurations.each do |config|
    config.build_settings["EXCLUDED_ARCHS[sdk=iphonesimulator*]"] = "arm64"
  end
end
    
