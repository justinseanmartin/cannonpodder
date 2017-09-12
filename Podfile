source 'https://github.com/justinseanmartin/test-specs'
source 'https://github.com/justinseanmartin/test-specs2'
source 'https://github.com/CocoaPods/Specs'

workspace 'CannonPodder.xcworkspace'
project 'proj/App.xcodeproj'

platform :ios, '9.0'

target 'App-ios' do
  pod 'Data/Tests', '~> 1.0' 
  pod 'Data', '~> 1.0' 
end

install! 'cocoapods', :warn_for_multiple_pod_sources => false, :share_schemes_for_development_pods => true, :deterministic_uuids => false

# Disable CocoaPods stats plugin.
ENV['COCOAPODS_DISABLE_STATS'] = 'true'
