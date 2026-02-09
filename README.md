# Cyber Security

## Information
- Kanokwan Chaichana (MAIL)
- 6602041630012
- s6602041630012@email.kmutnb.ac.th

## Environment
```sh
cp env.simple.env
```

## Running a services
## Database
```sh
docker compose -f db.yaml up # monitoring
docker compose -f db.yaml up -d # background
```

## Database
```sh
docker compose -f admin.yaml up # monitoring
docker compose -f admin.yaml up -d # background
```