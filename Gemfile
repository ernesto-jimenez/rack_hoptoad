source :gemcutter

group :runtime do
  gem 'rack'
  gem 'toadhopper', :git => 'git://github.com/ernesto-jimenez/toadhopper.git'
end

group :test do
  gem 'rake'
  gem 'rspec'#,      :require => 'spec'
  if RUBY_VERSION =~ /^1\.9/
    gem 'ruby-debug19'
  else
    gem 'ruby-debug'
  end
  gem 'rcov'
  gem 'bundler'
end
