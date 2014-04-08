task :default => [:build]

task :build => [:makecss, :makejs] do
    system("jekyll --no-server")
end

task :dev => [:makecss, :makejs] do
    system("jekyll --server --auto")
end
