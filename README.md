# goaccess-pb

To complile use: `protoc --proto_path=api/proto --go_out=plugins=grpc:pkg --grpc-gateway_out=logtostderr=true:pkg api/proto/*.proto`