# Uncomment the next line to define a global platform for your project
platform :ios, '9.0'
use_frameworks!

# 共通インストール
def install_pods

  pod 'Fabric'
  pod 'Crashlytics'

end

target 'DistributeTest Dev' do
  install_pods
end

target 'DistributeTest Staging' do
  install_pods
end

target 'DistributeTest Release' do
  install_pods
end


target 'DistributeTestTests' do
  inherit! :search_paths
end

target 'DistributeTestUITests' do
  inherit! :search_paths
end