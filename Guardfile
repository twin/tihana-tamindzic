guard 'nanoc' do
  watch('nanoc.yaml') # Change this to config.yaml if you use the old config file name
  watch('Rules')
  watch(%r{^(content|layouts|lib)/.*$})
end

guard 'livereload' do
  watch(%r{output/.+\.(html|css|js)$})
end
