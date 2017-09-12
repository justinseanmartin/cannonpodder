# Uncomment the first cocoapods reference fixes the issue.
# NOTE: Make sure to delete the `Podfile.lock` on switching between the two.
#
# The proper behavior is for Core to bring version '1.0.1', which exists in both of the following:
#   - https://github.com/justinseanmartin/test-specs
#   - https://github.com/justinseanmartin/test-specs2

source 'https://rubygems.org' do
  # vvvvvvv Works properly vvvvvvv

  # CocoaPods 1.3.1 - uses molinillo 0.5.7
  # Brings Core pod version 1.0.1

  # gem 'cocoapods', '1.3.1'

  # vvvvvvv Broken vvvvvvv

  # CocoaPods latest master (soon to be 1.4.0.beta.1) - uses molinillo 0.6.x
  # Brings Core pod version 1.0.0

  gem 'cocoapods', github: 'cocoapods/cocoapods', ref: '087e894f22c367bdba2cda860a5963a76ad60c7a'
  gem 'cocoapods-core', github: 'cocoapods/core', ref: '77f5b2081bf347db73e5978737633e1943dc5f29'
end
