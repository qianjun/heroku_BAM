#!/usr/bin/env rake
# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.
require 'rake/dsl_definition'
include Rake::DSL
require File.expand_path('../config/application', __FILE__)

LantanBAM::Application.load_tasks
module ::LantanBAM
  class Application
    include Rake::DSL
  end
end