# udacity-cloud-developer-project2-image-filter-starter-code
# https://github.com/seremwen/udacity-cloud-developer-project2-image-filter-starter-code

URl to deployed service in Elastic Beanstalk:    http://udacity-cloud-developer-project2-dev.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://api.time.com/wp-content/uploads/2019/03/kitten-report.jpg


branch-defaults:
  main:
  environment: udacity-cloud-develop-project2-dev
    group_suffix: null
deploy:
    artifact: ./www/Archive.zip
global: