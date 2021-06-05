# goaccess-pb

To complile use: `protoc --proto_path=proto --go_out=plugins=grpc:pkg/pb --grpc-gateway_out=logtostderr=true:pkg/pb proto/*.proto`