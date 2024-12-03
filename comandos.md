vagrant provision

user: admin
password: admin

b59ac4eb4c59222503f70d1d2f135ff314fe716b

sonar-scanner \
  -Dsonar.projectKey=redis-app \
  -Dsonar.sources=. \
  -Dsonar.host.url=http://localhost:9000 \
  -Dsonar.login=b59ac4eb4c59222503f70d1d2f135ff314fe716b
