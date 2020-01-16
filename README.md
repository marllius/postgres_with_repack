# pg_repack
# Postgres with pg_repack installed

postgres:11-alpine with pg_repack 1.4.4 installed

pg_repack version 1.4.4

# Usage example

`docker run --rm -it --env PGPASSWORD='' pg-repack:1.4.4 pg_repack -h $HOSTNAME -U $USER -d $DATABASE -t $TABLE_FOR_REPACKING -k -e`