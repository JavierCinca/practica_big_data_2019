FROM mongo:latest

COPY origin_dest_distances.jsonl /
CMD mongoimport --host mongo:27017 -d agile_data_science -c origin_dest_distance --file /origin_dest_distances.jsonl
