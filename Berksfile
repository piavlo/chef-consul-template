source "https://api.berkshelf.com"

metadata

cookbook 'consul', github: 'johnbellone/consul-cookbook', tag: 'v0.11.1'


group :test do
  cookbook 'consul-template-spec', path: 'spec/fixtures/cookbooks/consul-template-spec'
end
