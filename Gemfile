# Ruby 3.2+ compatibility shim for Liquid 4.x
unless Object.method_defined?(:tainted?)
  class Object
    def tainted?; false; end
    def taint; self; end
    def untaint; self; end
  end
end

source 'https://rubygems.org'
gem "github-pages", group: :jekyll_plugins

gem "webrick"
gem "csv"
gem "bigdecimal"
gem "logger"
gem "base64"