# -*- coding: utf-8 -*-
$:.unshift("/Library/RubyMotion/lib")
require 'motion/project'

Motion::Project::App.setup do |app|
  # Use `rake config' to see complete project settings.
  app.name = 'Tesseract'

  app.vendor_project('vendor/tesseract', :static,
    :products => %w{lib/liblept.a lib/libtesseract_all.a})
end
