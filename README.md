protoc --go_out=. todo.proto

cat mydb.pb| protoc --decode_raw

hexdump mydb.pb
hexdump -c mydb.pb
