# docker ������ postgresql

## ����ȷ�� �Ѿ���postgres����
sudo docker run --name pg_test -e POSTGRES_PASSWORD=123 -e POSTGRES_USER=postgres -d -p 8090:5432 postgres:9.6

## ����postgres
psql -h localhost -p 8090 -d postgres -U postgres --password