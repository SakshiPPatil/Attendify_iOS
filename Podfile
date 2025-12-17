platform :ios, '13.0'

use_frameworks! :linkage => :static

target 'faceIT' do
  pod 'RxSwift',    '~> 3.0'
  pod 'RxCocoa',    '~> 3.0'
  pod 'AsyncSwift', '~> 2.0'
  pod 'PKHUD',      '~> 4.0'
  pod 'SwiftyJSON', '~> 4.0'
  pod 'Charts',     '4.1.0'
  pod 'Toast-Swift','~> 4.0'
end

post_install do |installer|
  installer.pods_project.targets.each do |target|
    target.build_configurations.each do |config|
      config.build_settings['IPHONEOS_DEPLOYMENT_TARGET'] = '13.0'
    end
  end
end

end




