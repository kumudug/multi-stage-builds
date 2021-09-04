* Start
   - `docker-compose up -d --build`
* Stop
   - `docker-compose down -v`

* Build prod version of frontend

   - `docker build -f frontend/Dockerfile.prod -t kumudug/ecs-frontend ./frontend`
   - `docker push kumudug/ecs-frontend`