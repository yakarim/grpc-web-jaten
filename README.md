export GOPRIVATE="golang.org,github.com/fasthttp-contrib/render,go.etcd.io/bbolt,github.com/google/uuid,golang.org/x/crypto,github.com/tj/go-dropbox,github.com/asdine/storm,github.com/kr/pretty,github.com/stretchr/testify,github.com,google.golang.org,gopkg.in,github.com/dgrijalva/jwt-go,github.com/fasthttp/session,github.com/gosimple/slug,github.com/nfnt/resize,github.com/k3a/html2text,github.com/shiyanhui/hero,github.com/geekypanda/httpcache,github.com/yakarim/storm/v3export,go.uber.org,cloud.google.com,honnef.co/*"


 protoc -I. --grpc-gateway_out=logtostderr=true:. echopb/service.proto