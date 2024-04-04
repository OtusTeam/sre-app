# otus-app
# Start
PORT=80 ADMIN_USER=user ADMIN_PASS=spassword go run main.go

# Access admin panel
curl -i -u user:password  http://url/admin

# Access app
curl -i  http://url/

# Access healthcheck
curl -i http://url/healthz

