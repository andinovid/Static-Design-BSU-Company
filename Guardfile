# A sample Guardfile
# More info at https://github.com/guard/guard#readme

#guard 'coffeescript', :input => 'app/assets/javascripts'

guard 'livereload' do
  #watch(%r{app/views/.+\.(erb|haml|slim)$})
  #watch(%r{app/helpers/.+\.rb})
 	watch(%r{.+\.(css|html|js)$})

  #watch(%r{config/locales/.+\.yml})
  # Rails Assets Pipeline
  watch(%r{(app|vendor)(/assets/\w+/(.+\.(css|js|html|png|jpg))).*}) { |m| "/assets/#{m[3]}" }
end

#guard 'sass', :input => 'sass', :output => 'css'
