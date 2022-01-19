platform :ios, '13.0'

post_install do |installer|
 installer.pods_project.targets.each do |target|
  target.build_configurations.each do |config|
   config.build_settings['IPHONEOS_DEPLOYMENT_TARGET'] = '13.0'
  end
 end
end

target 'Flash-Chat' do
  use_frameworks!

  # Pods for Flash-Chat
  
  pod 'CLTypingLabel', '~> 0.4.0'
  pod 'Firebase/Auth'
  pod 'Firebase/Firestore'

end
