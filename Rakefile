require 'bundler/setup'
require 'pry'
require 'yaml'
require 'erb'

desc "Sample task"
task :default do
  # load data from yaml file
  users = YAML.load_file('data.yml')

  # load template
  template = File.read('template.erb')

  # get result from them
  result_string = ERB.new(template, nil, '-').result(binding)

  # uncoment below to see how powerful the pry debugger is!!
  #binding.pry

  # output to file
  File.write('result.txt', result_string)
end

