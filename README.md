## create app image
```docker image build -t book_app . ```

## run composer
```docker-compose up -d```

running on port localhost:8080

some basic info on 
http://localhost:8080/api-docs/swagger-ui/index.html

except for login/register other needs Authorization header set to Bearer Token

In Register ROLE should be passed ADMIN/CUSTOMER