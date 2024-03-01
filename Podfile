source 'https://github.com/CocoaPods/Specs.git'
platform :ios, '12.0'

target 'proj-ios' do
  use_frameworks!
  use_modular_headers!

  pod 'PROJ', '~> 9.3.0', :modular_headers => true
  pod 'crs-ios', '~> 1.0.5'

  target 'proj-iosTests' do
    inherit! :search_paths
  end
end
