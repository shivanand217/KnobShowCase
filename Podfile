# Uncomment the next line to define a global platform for your project
platform :ios, '12.0'

target 'KnobShowcase' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  pod 'KnobControl', :git => "https://github.com/shivanand217/KnobControl", :tag => '1.0.0'

  # Pods for KnobShowcase

  post_install do |installer|
    installer.pods_project.build_configurations.each do |config|
        config.build_settings.delete('CODE_SIGNING_ALLOWED')
        config.build_settings.delete('CODE_SIGNING_REQUIRED')
    end
  end
end
