# Uncomment the next line to define a global platform for your project
platform :ios, '8.0'

use_frameworks!

def instantsearch_core
    pod 'InstantSearch-Core-Swift', '~> 2.0.0'
end

target 'InstantSearch' do
  instantsearch_core
  pod 'SwiftLint'
  
  target 'InstantSearchTests' do
      inherit! :search_paths
  end
  
end

target 'Example' do
    workspace 'InstantSearch.xcworkspace'
    project 'Example/Example.xcodeproj'
    instantsearch_core
end
