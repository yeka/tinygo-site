
---
title: Packages supported by TinyGo
---

The following table shows all Go standard library packages and whether they can be imported by TinyGo. If they can't, you can click the 'no' link to jump to the explanation why the package cannot be compiled.

Note that the fact they can be imported, does not mean that all functions and types in the program can be used. For example, sometimes using some functions or types of the package will still trigger compiler errors.

Package | Importable | Passes tests
--- | --- | --- |
archive/tar |  [<span style="color: red">✗</span> no](#archive-tar)  |  <span style="color: gray">✗</span> no  | 
archive/zip |  [<span style="color: red">✗</span> no](#archive-zip)  |  <span style="color: gray">✗</span> no  | 
bufio |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#bufio)  | 
bytes |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#bytes)  | 
compress/bzip2 |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#compress-bzip2)  | 
compress/flate |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#compress-flate)  | 
compress/gzip |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#compress-gzip)  | 
compress/lzw |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#compress-lzw)  | 
compress/zlib |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#compress-zlib)  | 
container/heap |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#container-heap)  | 
container/list |  <span style="color: green">✔</span> yes  |  <span style="color: green">✔</span> yes  | 
container/ring |  <span style="color: green">✔</span> yes  |  <span style="color: green">✔</span> yes  | 
context |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#context)  | 
crypto |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#crypto)  | 
crypto/aes |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#crypto-aes)  | 
crypto/cipher |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#crypto-cipher)  | 
crypto/des |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#crypto-des)  | 
crypto/dsa |  [<span style="color: red">✗</span> no](#crypto-dsa)  |  <span style="color: gray">✗</span> no  | 
crypto/ecdsa |  [<span style="color: red">✗</span> no](#crypto-ecdsa)  |  <span style="color: gray">✗</span> no  | 
crypto/ed25519 |  [<span style="color: red">✗</span> no](#crypto-ed25519)  |  <span style="color: gray">✗</span> no  | 
crypto/elliptic |  [<span style="color: red">✗</span> no](#crypto-elliptic)  |  <span style="color: gray">✗</span> no  | 
crypto/hmac |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#crypto-hmac)  | 
crypto/md5 |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#crypto-md5)  | 
crypto/rand |  [<span style="color: red">✗</span> no](#crypto-rand)  |  <span style="color: gray">✗</span> no  | 
crypto/rc4 |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#crypto-rc4)  | 
crypto/rsa |  [<span style="color: red">✗</span> no](#crypto-rsa)  |  <span style="color: gray">✗</span> no  | 
crypto/sha1 |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#crypto-sha1)  | 
crypto/sha256 |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#crypto-sha256)  | 
crypto/sha512 |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#crypto-sha512)  | 
crypto/subtle |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#crypto-subtle)  | 
crypto/tls |  [<span style="color: red">✗</span> no](#crypto-tls)  |  <span style="color: gray">✗</span> no  | 
crypto/x509 |  [<span style="color: red">✗</span> no](#crypto-x509)  |  <span style="color: gray">✗</span> no  | 
crypto/x509/pkix |  [<span style="color: red">✗</span> no](#crypto-x509-pkix)  |  <span style="color: gray">✗</span> no  | 
database/sql |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#database-sql)  | 
database/sql/driver |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#database-sql-driver)  | 
debug/dwarf |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#debug-dwarf)  | 
debug/elf |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#debug-elf)  | 
debug/gosym |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#debug-gosym)  | 
debug/macho |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#debug-macho)  | 
debug/pe |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#debug-pe)  | 
debug/plan9obj |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#debug-plan9obj)  | 
encoding |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#encoding)  | 
encoding/ascii85 |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#encoding-ascii85)  | 
encoding/asn1 |  [<span style="color: red">✗</span> no](#encoding-asn1)  |  <span style="color: gray">✗</span> no  | 
encoding/base32 |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#encoding-base32)  | 
encoding/base64 |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#encoding-base64)  | 
encoding/binary |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#encoding-binary)  | 
encoding/csv |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#encoding-csv)  | 
encoding/gob |  [<span style="color: red">✗</span> no](#encoding-gob)  |  <span style="color: gray">✗</span> no  | 
encoding/hex |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#encoding-hex)  | 
encoding/json |  [<span style="color: red">✗</span> no](#encoding-json)  |  <span style="color: gray">✗</span> no  | 
encoding/pem |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#encoding-pem)  | 
encoding/xml |  [<span style="color: red">✗</span> no](#encoding-xml)  |  <span style="color: gray">✗</span> no  | 
errors |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#errors)  | 
expvar |  [<span style="color: red">✗</span> no](#expvar)  |  <span style="color: gray">✗</span> no  | 
flag |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#flag)  | 
fmt |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#fmt)  | 
go/ast |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#go-ast)  | 
go/build |  [<span style="color: red">✗</span> no](#go-build)  |  <span style="color: gray">✗</span> no  | 
go/constant |  [<span style="color: red">✗</span> no](#go-constant)  |  <span style="color: gray">✗</span> no  | 
go/doc |  [<span style="color: red">✗</span> no](#go-doc)  |  <span style="color: gray">✗</span> no  | 
go/format |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#go-format)  | 
go/importer |  [<span style="color: red">✗</span> no](#go-importer)  |  <span style="color: gray">✗</span> no  | 
go/parser |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#go-parser)  | 
go/printer |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#go-printer)  | 
go/scanner |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#go-scanner)  | 
go/token |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#go-token)  | 
go/types |  [<span style="color: red">✗</span> no](#go-types)  |  <span style="color: gray">✗</span> no  | 
hash |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#hash)  | 
hash/adler32 |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#hash-adler32)  | 
hash/crc32 |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#hash-crc32)  | 
hash/crc64 |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#hash-crc64)  | 
hash/fnv |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#hash-fnv)  | 
hash/maphash |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#hash-maphash)  | 
html |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#html)  | 
html/template |  [<span style="color: red">✗</span> no](#html-template)  |  <span style="color: gray">✗</span> no  | 
image |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#image)  | 
image/color |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#image-color)  | 
image/color/palette |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#image-color-palette)  | 
image/draw |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#image-draw)  | 
image/gif |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#image-gif)  | 
image/jpeg |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#image-jpeg)  | 
image/png |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#image-png)  | 
index/suffixarray |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#index-suffixarray)  | 
io |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#io)  | 
io/ioutil |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#io-ioutil)  | 
log |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#log)  | 
log/syslog |  [<span style="color: red">✗</span> no](#log-syslog)  |  <span style="color: gray">✗</span> no  | 
math |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#math)  | 
math/big |  [<span style="color: red">✗</span> no](#math-big)  |  <span style="color: gray">✗</span> no  | 
math/bits |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#math-bits)  | 
math/cmplx |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#math-cmplx)  | 
math/rand |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#math-rand)  | 
mime |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#mime)  | 
mime/multipart |  [<span style="color: red">✗</span> no](#mime-multipart)  |  <span style="color: gray">✗</span> no  | 
mime/quotedprintable |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#mime-quotedprintable)  | 
net |  [<span style="color: red">✗</span> no](#net)  |  <span style="color: gray">✗</span> no  | 
net/http |  [<span style="color: red">✗</span> no](#net-http)  |  <span style="color: gray">✗</span> no  | 
net/http/cgi |  [<span style="color: red">✗</span> no](#net-http-cgi)  |  <span style="color: gray">✗</span> no  | 
net/http/cookiejar |  [<span style="color: red">✗</span> no](#net-http-cookiejar)  |  <span style="color: gray">✗</span> no  | 
net/http/fcgi |  [<span style="color: red">✗</span> no](#net-http-fcgi)  |  <span style="color: gray">✗</span> no  | 
net/http/httptest |  [<span style="color: red">✗</span> no](#net-http-httptest)  |  <span style="color: gray">✗</span> no  | 
net/http/httptrace |  [<span style="color: red">✗</span> no](#net-http-httptrace)  |  <span style="color: gray">✗</span> no  | 
net/http/httputil |  [<span style="color: red">✗</span> no](#net-http-httputil)  |  <span style="color: gray">✗</span> no  | 
net/http/pprof |  [<span style="color: red">✗</span> no](#net-http-pprof)  |  <span style="color: gray">✗</span> no  | 
net/mail |  [<span style="color: red">✗</span> no](#net-mail)  |  <span style="color: gray">✗</span> no  | 
net/rpc |  [<span style="color: red">✗</span> no](#net-rpc)  |  <span style="color: gray">✗</span> no  | 
net/rpc/jsonrpc |  [<span style="color: red">✗</span> no](#net-rpc-jsonrpc)  |  <span style="color: gray">✗</span> no  | 
net/smtp |  [<span style="color: red">✗</span> no](#net-smtp)  |  <span style="color: gray">✗</span> no  | 
net/textproto |  [<span style="color: red">✗</span> no](#net-textproto)  |  <span style="color: gray">✗</span> no  | 
net/url |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#net-url)  | 
os |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#os)  | 
os/exec |  [<span style="color: red">✗</span> no](#os-exec)  |  <span style="color: gray">✗</span> no  | 
os/signal |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#os-signal)  | 
os/user |  [<span style="color: red">✗</span> no](#os-user)  |  <span style="color: gray">✗</span> no  | 
path |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#path)  | 
path/filepath |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#path-filepath)  | 
plugin |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#plugin)  | 
reflect |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#reflect)  | 
regexp |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#regexp)  | 
regexp/syntax |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#regexp-syntax)  | 
sort |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#sort)  | 
strconv |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#strconv)  | 
strings |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#strings)  | 
sync |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#sync)  | 
sync/atomic |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#sync-atomic)  | 
syscall |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#syscall)  | 
syscall/js |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#syscall-js)  | 
testing |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#testing)  | 
testing/iotest |  <span style="color: green">✔</span> yes  |  <span style="color: green">✔</span> yes  | 
testing/quick |  [<span style="color: red">✗</span> no](#testing-quick)  |  <span style="color: gray">✗</span> no  | 
text/scanner |  <span style="color: green">✔</span> yes  |  <span style="color: green">✔</span> yes  | 
text/tabwriter |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#text-tabwriter)  | 
text/template |  [<span style="color: red">✗</span> no](#text-template)  |  <span style="color: gray">✗</span> no  | 
text/template/parse |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#text-template-parse)  | 
time |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#time)  | 
unicode |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#unicode)  | 
unicode/utf16 |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#unicode-utf16)  | 
unicode/utf8 |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#unicode-utf8)  | 
unsafe |  <span style="color: green">✔</span> yes  |  [<span style="color: red">✗</span> no](#unsafe)  | 



## archive/tar



The compiler gave the following error when this package was imported:


    # archive/tar
    /usr/local/go/src/archive/tar/common.go:554:32: os.FileMode(fi.h.Mode).Perm undefined (type os.FileMode has no field or method Perm)
    /usr/local/go/src/archive/tar/common.go:636:15: fi.ModTime undefined (type os.FileInfo has no field or method ModTime)
    /usr/local/go/src/archive/tar/common.go:637:21: fm.Perm undefined (type os.FileMode has no field or method Perm)
    /usr/local/go/src/archive/tar/common.go:640:10: fm.IsRegular undefined (type os.FileMode has no field or method IsRegular)






## archive/zip



The compiler gave the following error when this package was imported:


    # archive/zip
    /usr/local/go/src/archive/zip/struct.go:180:19: fi.ModTime undefined (type os.FileInfo has no field or method ModTime)






## bufio



The compiler gave the following error when running the tests for this package:


    # bufio_test [bufio.test]
    /usr/local/go/src/bufio/bufio_test.go:1259:5: t.Run undefined (type *testing.T has no field or method Run)
    /usr/local/go/src/bufio/bufio_test.go:1689:4: b.ReportAllocs undefined (type *testing.B has no field or method ReportAllocs)
    /usr/local/go/src/bufio/bufio_test.go:1704:4: b.ReportAllocs undefined (type *testing.B has no field or method ReportAllocs)
    /usr/local/go/src/bufio/bufio_test.go:1722:4: b.ReportAllocs undefined (type *testing.B has no field or method ReportAllocs)






## bytes



The compiler gave the following error when running the tests for this package:


    # os/exec [bytes.test]
    /usr/local/go/src/os/exec/exec.go:129:14: Process not declared by package os
    /usr/local/go/src/os/exec/exec.go:133:19: ProcessState not declared by package os
    /usr/local/go/src/os/exec/exec.go:457:6: ProcessState not declared by package os
    /usr/local/go/src/os/exec/exec.go:229:12: Environ not declared by package os
    /usr/local/go/src/os/exec/exec.go:245:23: DevNull not declared by package os
    /usr/local/go/src/os/exec/exec.go:257:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:290:27: DevNull not declared by package os
    /usr/local/go/src/os/exec/exec.go:302:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:417:22: StartProcess not declared by package os
    /usr/local/go/src/os/exec/exec.go:417:57: ProcAttr not declared by package os
    /usr/local/go/src/os/exec/exec.go:579:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:621:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:646:20: Pipe not declared by package os






## compress/bzip2



The compiler gave the following error when running the tests for this package:


    # compress/bzip2 [compress/bzip2.test]
    /usr/local/go/src/compress/bzip2/bzip2_test.go:228:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/compress/bzip2/bzip2_test.go:229:4: b.ReportAllocs undefined (type *testing.B has no field or method ReportAllocs)
    /usr/local/go/src/compress/bzip2/bzip2_test.go:230:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)






## compress/flate



The compiler gave the following error when running the tests for this package:


    can't load test package: package compress/flate (test)
    	imports runtime/debug: cannot find package "runtime/debug" in any of:
    	/home/ayke/.cache/tinygo/goroot-go1.14-fb1405eb1452312019d9a7d9cee4a3d3e4c7fb7c6ad9a2f42abbec348705ea80/src/vendor/runtime/debug (vendor tree)
    	/home/ayke/.cache/tinygo/goroot-go1.14-fb1405eb1452312019d9a7d9cee4a3d3e4c7fb7c6ad9a2f42abbec348705ea80/src/runtime/debug (from $GOROOT)
    	/home/ayke/src/runtime/debug (from $GOPATH)






## compress/gzip



The compiler gave the following error when running the tests for this package:


    # os/exec
    /usr/local/go/src/os/exec/exec.go:129:14: Process not declared by package os
    /usr/local/go/src/os/exec/exec.go:133:19: ProcessState not declared by package os
    /usr/local/go/src/os/exec/exec.go:457:6: ProcessState not declared by package os
    /usr/local/go/src/os/exec/exec.go:229:12: Environ not declared by package os
    /usr/local/go/src/os/exec/exec.go:245:23: DevNull not declared by package os
    /usr/local/go/src/os/exec/exec.go:257:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:290:27: DevNull not declared by package os
    /usr/local/go/src/os/exec/exec.go:302:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:417:22: StartProcess not declared by package os
    /usr/local/go/src/os/exec/exec.go:417:57: ProcAttr not declared by package os
    /usr/local/go/src/os/exec/exec.go:579:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:621:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:646:20: Pipe not declared by package os






## compress/lzw



The compiler gave the following error when running the tests for this package:


    # os/exec
    /usr/local/go/src/os/exec/exec.go:129:14: Process not declared by package os
    /usr/local/go/src/os/exec/exec.go:133:19: ProcessState not declared by package os
    /usr/local/go/src/os/exec/exec.go:457:6: ProcessState not declared by package os
    /usr/local/go/src/os/exec/exec.go:229:12: Environ not declared by package os
    /usr/local/go/src/os/exec/exec.go:245:23: DevNull not declared by package os
    /usr/local/go/src/os/exec/exec.go:257:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:290:27: DevNull not declared by package os
    /usr/local/go/src/os/exec/exec.go:302:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:417:22: StartProcess not declared by package os
    /usr/local/go/src/os/exec/exec.go:417:57: ProcAttr not declared by package os
    /usr/local/go/src/os/exec/exec.go:579:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:621:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:646:20: Pipe not declared by package os






## compress/zlib



The compiler gave the following error when running the tests for this package:


    # os/exec
    /usr/local/go/src/os/exec/exec.go:129:14: Process not declared by package os
    /usr/local/go/src/os/exec/exec.go:133:19: ProcessState not declared by package os
    /usr/local/go/src/os/exec/exec.go:457:6: ProcessState not declared by package os
    /usr/local/go/src/os/exec/exec.go:229:12: Environ not declared by package os
    /usr/local/go/src/os/exec/exec.go:245:23: DevNull not declared by package os
    /usr/local/go/src/os/exec/exec.go:257:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:290:27: DevNull not declared by package os
    /usr/local/go/src/os/exec/exec.go:302:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:417:22: StartProcess not declared by package os
    /usr/local/go/src/os/exec/exec.go:417:57: ProcAttr not declared by package os
    /usr/local/go/src/os/exec/exec.go:579:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:621:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:646:20: Pipe not declared by package os






## container/heap



The compiler gave the following error when running the tests for this package:


    # container/heap [container/heap.test]
    /usr/local/go/src/container/heap/heap_test.go:36:4: t.Helper undefined (type *testing.T has no field or method Helper)










## context



The compiler gave the following error when running the tests for this package:


    # net [context.test]
    ../../../../../usr/include/netdb.h:617:23: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:618:22: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:624:23: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:625:25: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:617:23: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:618:22: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:624:23: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:625:25: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:617:23: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:618:22: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:624:23: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:625:25: unexpected token ILLEGAL






## crypto



The compiler gave the following error when running the tests for this package:


    ld: error: undefined symbol: crypto/cipher.xorBytesSSE2
    >>> referenced by xor_amd64.go:18 (/usr/local/go/src/crypto/cipher/xor_amd64.go:18)
    >>>               /tmp/tinygo188003771/main.o:(crypto/cipher.xorBytes)
    collect2: error: ld returned 1 exit status
    error: failed to link /tmp/tinygo188003771/main: exit status 1






## crypto/aes



The compiler gave the following error when running the tests for this package:


    # crypto/aes [crypto/aes.test]
    /usr/local/go/src/crypto/aes/aes_test.go:354:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/crypto/aes/aes_test.go:355:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)
    /usr/local/go/src/crypto/aes/aes_test.go:368:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/crypto/aes/aes_test.go:369:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)
    /usr/local/go/src/crypto/aes/aes_test.go:379:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)






## crypto/cipher



The compiler gave the following error when running the tests for this package:


    # crypto/cipher_test [crypto/cipher.test]
    /usr/local/go/src/crypto/cipher/benchmark_test.go:14:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/crypto/cipher/benchmark_test.go:22:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)
    /usr/local/go/src/crypto/cipher/benchmark_test.go:29:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/crypto/cipher/benchmark_test.go:38:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)
    /usr/local/go/src/crypto/cipher/benchmark_test.go:45:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/crypto/cipher/benchmark_test.go:55:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)
    /usr/local/go/src/crypto/cipher/benchmark_test.go:85:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/crypto/cipher/benchmark_test.go:92:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)
    /usr/local/go/src/crypto/cipher/benchmark_test.go:131:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/crypto/cipher/benchmark_test.go:144:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/crypto/cipher/gcm_test.go:445:13: Short not declared by package testing
    /usr/local/go/src/crypto/cipher/xor_test.go:18:14: Short not declared by package testing
    /usr/local/go/src/crypto/cipher/xor_test.go:66:5: b.Run undefined (type *testing.B has no field or method Run)
    /usr/local/go/src/crypto/cipher/xor_test.go:69:6: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    [...more lines following...]






## crypto/des



The compiler gave the following error when running the tests for this package:


    # crypto/des [crypto/des.test]
    /usr/local/go/src/crypto/des/des_test.go:1536:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/crypto/des/des_test.go:1537:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)
    /usr/local/go/src/crypto/des/des_test.go:1550:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/crypto/des/des_test.go:1551:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)
    /usr/local/go/src/crypto/des/des_test.go:1564:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/crypto/des/des_test.go:1565:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)
    /usr/local/go/src/crypto/des/des_test.go:1578:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/crypto/des/des_test.go:1579:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)






## crypto/dsa


This package cannot be imported because the following dependencies cannot be compiled:

  * [math/big](#math-big)





## crypto/ecdsa


This package cannot be imported because the following dependencies cannot be compiled:

  * [crypto/elliptic](#crypto-elliptic)
  * [encoding/asn1](#encoding-asn1)
  * [math/big](#math-big)





## crypto/ed25519


This package cannot be imported because the following dependencies cannot be compiled:

  * [crypto/rand](#crypto-rand)





## crypto/elliptic


This package cannot be imported because the following dependencies cannot be compiled:

  * [math/big](#math-big)





## crypto/hmac



The compiler gave the following error when running the tests for this package:


    # crypto/hmac [crypto/hmac.test]
    /usr/local/go/src/crypto/hmac/hmac_test.go:576:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/crypto/hmac/hmac_test.go:589:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)






## crypto/md5



The compiler gave the following error when running the tests for this package:


    # crypto/md5 [crypto/md5.test]
    /usr/local/go/src/crypto/md5/md5_test.go:219:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/crypto/md5/md5_test.go:226:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)






## crypto/rand


This package cannot be imported because the following dependencies cannot be compiled:

  * [math/big](#math-big)





## crypto/rc4



The compiler gave the following error when running the tests for this package:


    # crypto/rc4 [crypto/rc4.test]
    /usr/local/go/src/crypto/rc4/rc4_test.go:145:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)






## crypto/rsa


This package cannot be imported because the following dependencies cannot be compiled:

  * [crypto/rand](#crypto-rand)
  * [math/big](#math-big)





## crypto/sha1



The compiler gave the following error when running the tests for this package:


    # crypto/sha1 [crypto/sha1.test]
    /usr/local/go/src/crypto/sha1/sha1_test.go:217:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)






## crypto/sha256



The compiler gave the following error when running the tests for this package:


    # crypto/sha256 [crypto/sha256.test]
    /usr/local/go/src/crypto/sha256/sha256_test.go:151:5: t.Run undefined (type *testing.T has no field or method Run)
    /usr/local/go/src/crypto/sha256/sha256_test.go:296:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)






## crypto/sha512



The compiler gave the following error when running the tests for this package:


    # crypto/sha512 [crypto/sha512.test]
    /usr/local/go/src/crypto/sha512/sha512_test.go:733:5: t.Run undefined (type *testing.T has no field or method Run)
    /usr/local/go/src/crypto/sha512/sha512_test.go:895:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)






## crypto/subtle



The compiler gave the following error when running the tests for this package:


    # testing/quick
    /usr/local/go/src/testing/quick/quick.go:273:11: fType.NumOut undefined (type reflect.Type has no field or method NumOut)
    /usr/local/go/src/testing/quick/quick.go:276:11: fType.Out undefined (type reflect.Type has no field or method Out)
    /usr/local/go/src/testing/quick/quick.go:280:43: fType.NumIn undefined (type reflect.Type has no field or method NumIn)
    /usr/local/go/src/testing/quick/quick.go:290:12: fVal.Call undefined (type reflect.Value has no field or method Call)
    /usr/local/go/src/testing/quick/quick.go:320:43: xType.NumIn undefined (type reflect.Type has no field or method NumIn)
    /usr/local/go/src/testing/quick/quick.go:330:26: x.Call undefined (type reflect.Value has no field or method Call)
    /usr/local/go/src/testing/quick/quick.go:331:26: y.Call undefined (type reflect.Value has no field or method Call)
    /usr/local/go/src/testing/quick/quick.go:351:25: f.In undefined (type reflect.Type has no field or method In)
    /usr/local/go/src/testing/quick/quick.go:353:95: f.In undefined (type reflect.Type has no field or method In)






## crypto/tls


This package cannot be imported because the following dependencies cannot be compiled:

  * [crypto/ecdsa](#crypto-ecdsa)
  * [crypto/ed25519](#crypto-ed25519)
  * [crypto/elliptic](#crypto-elliptic)
  * [crypto/rand](#crypto-rand)
  * [crypto/rsa](#crypto-rsa)
  * [crypto/x509](#crypto-x509)
  * [encoding/asn1](#encoding-asn1)
  * [math/big](#math-big)
  * [net](#net)





## crypto/x509


This package cannot be imported because the following dependencies cannot be compiled:

  * [crypto/dsa](#crypto-dsa)
  * [crypto/ecdsa](#crypto-ecdsa)
  * [crypto/ed25519](#crypto-ed25519)
  * [crypto/elliptic](#crypto-elliptic)
  * [crypto/rsa](#crypto-rsa)
  * [crypto/x509/pkix](#crypto-x509-pkix)
  * [encoding/asn1](#encoding-asn1)
  * [math/big](#math-big)
  * [net](#net)





## crypto/x509/pkix


This package cannot be imported because the following dependencies cannot be compiled:

  * [encoding/asn1](#encoding-asn1)
  * [math/big](#math-big)





## database/sql



The compiler gave the following error when running the tests for this package:


    # net
    ../../../../../usr/include/netdb.h:617:23: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:618:22: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:624:23: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:625:25: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:617:23: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:618:22: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:624:23: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:625:25: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:617:23: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:618:22: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:624:23: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:625:25: unexpected token ILLEGAL






## database/sql/driver



The compiler gave the following error when running the tests for this package:


    # database/sql/driver [database/sql/driver.test]
    database/sql/driver [database/sql/driver.test]/<init>: interp: unknown GEP
    
    traceback:
    database/sql/driver [database/sql/driver.test]/<init>:
      %57 = getelementptr inbounds { { i8*, i64, i64 } }, { { i8*, i64, i64 } }* %56, i32 0, i32 0, !dbg !2060






## debug/dwarf



The compiler gave the following error when running the tests for this package:


    === RUN   TestSplit






## debug/elf



The compiler gave the following error when running the tests for this package:


    # net
    ../../../../../usr/include/netdb.h:617:23: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:618:22: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:624:23: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:625:25: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:617:23: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:618:22: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:624:23: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:625:25: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:617:23: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:618:22: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:624:23: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:625:25: unexpected token ILLEGAL






## debug/gosym



The compiler gave the following error when running the tests for this package:


    # os/exec
    /usr/local/go/src/os/exec/exec.go:129:14: Process not declared by package os
    /usr/local/go/src/os/exec/exec.go:133:19: ProcessState not declared by package os
    /usr/local/go/src/os/exec/exec.go:457:6: ProcessState not declared by package os
    /usr/local/go/src/os/exec/exec.go:229:12: Environ not declared by package os
    /usr/local/go/src/os/exec/exec.go:245:23: DevNull not declared by package os
    /usr/local/go/src/os/exec/exec.go:257:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:290:27: DevNull not declared by package os
    /usr/local/go/src/os/exec/exec.go:302:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:417:22: StartProcess not declared by package os
    /usr/local/go/src/os/exec/exec.go:417:57: ProcAttr not declared by package os
    /usr/local/go/src/os/exec/exec.go:579:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:621:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:646:20: Pipe not declared by package os






## debug/macho



The compiler gave the following error when running the tests for this package:


    === RUN   TestOpen
    --- FAIL: TestOpen
    	open testdata/gcc-386-darwin-exec.base64: file not found
    
    	open testdata/gcc-amd64-darwin-exec.base64: file not found
    
    	open testdata/gcc-amd64-darwin-exec-debug.base64: file not found
    
    	open testdata/clang-386-darwin-exec-with-rpath.base64: file not found
    
    	open testdata/clang-amd64-darwin-exec-with-rpath.base64: file not found
    
    	open testdata/clang-386-darwin.obj.base64: file not found
    
    	open testdata/clang-amd64-darwin.obj.base64: file not found
    [...more lines following...]






## debug/pe



The compiler gave the following error when running the tests for this package:


    # os/exec
    /usr/local/go/src/os/exec/exec.go:129:14: Process not declared by package os
    /usr/local/go/src/os/exec/exec.go:133:19: ProcessState not declared by package os
    /usr/local/go/src/os/exec/exec.go:457:6: ProcessState not declared by package os
    /usr/local/go/src/os/exec/exec.go:229:12: Environ not declared by package os
    /usr/local/go/src/os/exec/exec.go:245:23: DevNull not declared by package os
    /usr/local/go/src/os/exec/exec.go:257:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:290:27: DevNull not declared by package os
    /usr/local/go/src/os/exec/exec.go:302:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:417:22: StartProcess not declared by package os
    /usr/local/go/src/os/exec/exec.go:417:57: ProcAttr not declared by package os
    /usr/local/go/src/os/exec/exec.go:579:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:621:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:646:20: Pipe not declared by package os






## debug/plan9obj



The compiler gave the following error when running the tests for this package:


    === RUN   TestOpen
    --- FAIL: TestOpen
    	open testdata/386-plan9-exec: file not found
    
    	open testdata/amd64-plan9-exec: file not found
    
    
    === RUN   TestOpenFailure
    --- PASS: TestOpenFailure
    
    exit status 1
    FAIL






## encoding



The compiler gave the following error when running the tests for this package:


    error: function main is undeclared in the main package






## encoding/ascii85



The compiler gave the following error when running the tests for this package:


    # encoding/ascii85 [encoding/ascii85.test]
    /usr/local/go/src/encoding/ascii85/ascii85_test.go:47:4: t.Helper undefined (type *testing.T has no field or method Helper)






## encoding/asn1


This package cannot be imported because the following dependencies cannot be compiled:

  * [math/big](#math-big)





## encoding/base32



The compiler gave the following error when running the tests for this package:


    # encoding/base32 [encoding/base32.test]
    /usr/local/go/src/encoding/base32/base32_test.go:47:4: t.Helper undefined (type *testing.T has no field or method Helper)
    /usr/local/go/src/encoding/base32/base32_test.go:451:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/encoding/base32/base32_test.go:459:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/encoding/base32/base32_test.go:469:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/encoding/base32/base32_test.go:476:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/encoding/base32/base32_test.go:661:5: t.Run undefined (type *testing.T has no field or method Run)






## encoding/base64



The compiler gave the following error when running the tests for this package:


    can't load test package: package encoding/base64 (test)
    	imports runtime/debug: cannot find package "runtime/debug" in any of:
    	/home/ayke/.cache/tinygo/goroot-go1.14-fb1405eb1452312019d9a7d9cee4a3d3e4c7fb7c6ad9a2f42abbec348705ea80/src/vendor/runtime/debug (vendor tree)
    	/home/ayke/.cache/tinygo/goroot-go1.14-fb1405eb1452312019d9a7d9cee4a3d3e4c7fb7c6ad9a2f42abbec348705ea80/src/runtime/debug (from $GOROOT)
    	/home/ayke/src/runtime/debug (from $GOPATH)






## encoding/binary



The compiler gave the following error when running the tests for this package:


    # encoding/binary [encoding/binary.test]
    /usr/local/go/src/encoding/binary/binary_test.go:498:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/encoding/binary/binary_test.go:499:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)
    /usr/local/go/src/encoding/binary/binary_test.go:510:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/encoding/binary/binary_test.go:512:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)
    /usr/local/go/src/encoding/binary/binary_test.go:517:4: b.StopTimer undefined (type *testing.B has no field or method StopTimer)
    /usr/local/go/src/encoding/binary/binary_test.go:524:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/encoding/binary/binary_test.go:525:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)
    /usr/local/go/src/encoding/binary/binary_test.go:535:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/encoding/binary/binary_test.go:536:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)
    /usr/local/go/src/encoding/binary/binary_test.go:548:4: b.StopTimer undefined (type *testing.B has no field or method StopTimer)
    /usr/local/go/src/encoding/binary/binary_test.go:565:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/encoding/binary/binary_test.go:566:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)
    /usr/local/go/src/encoding/binary/binary_test.go:578:4: b.StopTimer undefined (type *testing.B has no field or method StopTimer)
    /usr/local/go/src/encoding/binary/binary_test.go:588:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    [...more lines following...]






## encoding/csv



The compiler gave the following error when running the tests for this package:


    # encoding/csv [encoding/csv.test]
    /usr/local/go/src/encoding/csv/reader_test.go:388:5: t.Run undefined (type *testing.T has no field or method Run)
    /usr/local/go/src/encoding/csv/reader_test.go:443:4: b.ReportAllocs undefined (type *testing.B has no field or method ReportAllocs)






## encoding/gob



The compiler gave the following error when this package was imported:


    # encoding/gob
    /usr/local/go/src/encoding/gob/decode.go:562:21: MakeMapWithSize not declared by package reflect
    /usr/local/go/src/encoding/gob/decode.go:948:22: PtrTo not declared by package reflect
    /usr/local/go/src/encoding/gob/decode.go:1118:30: srt.FieldByName undefined (type reflect.Type has no field or method FieldByName)
    /usr/local/go/src/encoding/gob/encode.go:603:16: PtrTo not declared by package reflect
    /usr/local/go/src/encoding/gob/encode.go:643:70: f.Index undefined (type reflect.StructField has no field or method Index)
    /usr/local/go/src/encoding/gob/type.go:119:12: cannot convert nil (untyped nil value) to reflect.Type
    /usr/local/go/src/encoding/gob/type.go:142:14: PtrTo not declared by package reflect
    /usr/local/go/src/encoding/gob/type.go:867:9: rt.PkgPath undefined (type reflect.Type has no field or method PkgPath)
    /usr/local/go/src/encoding/gob/type.go:870:21: rt.PkgPath undefined (type reflect.Type has no field or method PkgPath)






## encoding/hex



The compiler gave the following error when running the tests for this package:


    # encoding/hex [encoding/hex.test]
    /usr/local/go/src/encoding/hex/hex_test.go:244:5: b.Run undefined (type *testing.B has no field or method Run)
    /usr/local/go/src/encoding/hex/hex_test.go:245:6: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/encoding/hex/hex_test.go:258:5: b.Run undefined (type *testing.B has no field or method Run)
    /usr/local/go/src/encoding/hex/hex_test.go:259:6: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/encoding/hex/hex_test.go:272:5: b.Run undefined (type *testing.B has no field or method Run)
    /usr/local/go/src/encoding/hex/hex_test.go:273:6: b.SetBytes undefined (type *testing.B has no field or method SetBytes)






## encoding/json



The compiler gave the following error when this package was imported:


    # encoding/json
    /usr/local/go/src/encoding/json/decode.go:160:15: cannot convert nil (untyped nil value) to reflect.Type
    /usr/local/go/src/encoding/json/decode.go:235:26: cannot convert nil (untyped nil value) to reflect.Type
    /usr/local/go/src/encoding/json/decode.go:252:30: cannot convert nil (untyped nil value) to reflect.Type
    /usr/local/go/src/encoding/json/decode.go:532:8: v.NumMethod undefined (type reflect.Value has no field or method NumMethod)
    /usr/local/go/src/encoding/json/decode.go:569:7: v.SetLen undefined (type reflect.Value has no field or method SetLen)
    /usr/local/go/src/encoding/json/decode.go:606:6: v.SetLen undefined (type reflect.Value has no field or method SetLen)
    /usr/local/go/src/encoding/json/decode.go:637:40: v.NumMethod undefined (type reflect.Value has no field or method NumMethod)
    /usr/local/go/src/encoding/json/decode.go:658:16: PtrTo not declared by package reflect
    /usr/local/go/src/encoding/json/decode.go:793:17: PtrTo not declared by package reflect
    /usr/local/go/src/encoding/json/decode.go:938:9: v.NumMethod undefined (type reflect.Value has no field or method NumMethod)
    /usr/local/go/src/encoding/json/decode.go:967:6: v.SetBytes undefined (type reflect.Value has no field or method SetBytes)
    /usr/local/go/src/encoding/json/decode.go:974:9: v.NumMethod undefined (type reflect.Value has no field or method NumMethod)
    /usr/local/go/src/encoding/json/decode.go:1007:9: v.NumMethod undefined (type reflect.Value has no field or method NumMethod)
    /usr/local/go/src/encoding/json/decode.go:1031:23: v.OverflowFloat undefined (type reflect.Value has no field or method OverflowFloat)
    [...more lines following...]






## encoding/pem



The compiler gave the following error when running the tests for this package:


    # net
    ../../../../../usr/include/netdb.h:617:23: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:618:22: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:624:23: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:625:25: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:617:23: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:618:22: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:624:23: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:625:25: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:617:23: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:618:22: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:624:23: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:625:25: unexpected token ILLEGAL






## encoding/xml



The compiler gave the following error when this package was imported:


    # encoding/xml
    /usr/local/go/src/encoding/xml/read.go:286:8: val.SetLen undefined (type reflect.Value has no field or method SetLen)
    /usr/local/go/src/encoding/xml/read.go:402:6: v.SetLen undefined (type reflect.Value has no field or method SetLen)
    /usr/local/go/src/encoding/xml/read.go:665:7: dst.SetBytes undefined (type reflect.Value has no field or method SetBytes)
    /usr/local/go/src/encoding/xml/typeinfo.go:114:29: f.Index undefined (type *reflect.StructField has no field or method Index)
    /usr/local/go/src/encoding/xml/typeinfo.go:318:14: typ.FieldByIndex undefined (type reflect.Type has no field or method FieldByIndex)
    /usr/local/go/src/encoding/xml/typeinfo.go:319:14: typ.FieldByIndex undefined (type reflect.Type has no field or method FieldByIndex)






## errors



The compiler gave the following error when running the tests for this package:


    # errors_test [errors.test]
    /usr/local/go/src/errors/wrap_test.go:51:5: t.Run undefined (type *testing.T has no field or method Run)
    /usr/local/go/src/errors/wrap_test.go:156:5: t.Run undefined (type *testing.T has no field or method Run)
    /usr/local/go/src/errors/wrap_test.go:181:5: t.Run undefined (type *testing.T has no field or method Run)






## expvar


This package cannot be imported because the following dependencies cannot be compiled:

  * [encoding/json](#encoding-json)
  * [net/http](#net-http)





## flag



The compiler gave the following error when running the tests for this package:


    # flag_test [flag.test]
    /usr/local/go/src/flag/flag.go:841:48: interp: unsupported instruction
    
    traceback:
    /usr/local/go/src/flag/flag.go:841:48:
      %invoke.func.cast = inttoptr i64 %invoke.func to %runtime._string (i8*, i8*, i8*)*, !dbg !2070
    /usr/local/go/src/flag/flag.go:754:7:
      call void @"(*flag [flag.test].FlagSet).Var"(%"flag [flag.test].FlagSet"* %f, i64 %13, i8* %14, i8* %15, i64 %16, i8* %17, i64 %18, i8* undef, i8* undef), !dbg !2043
    /usr/local/go/src/flag/flag.go:767:13:
      call void @"(*flag [flag.test].FlagSet).StringVar"(%"flag [flag.test].FlagSet"* %f, %runtime._string* %6, i8* %8, i64 %9, i8* %10, i64 %11, i8* %12, i64 %13, i8* undef, i8* undef), !dbg !2043
    /usr/local/go/src/flag/flag.go:774:27:
      %14 = call %runtime._string* @"(*flag [flag.test].FlagSet).String"(%"flag [flag.test].FlagSet"* %6, i8* %8, i64 %9, i8* %10, i64 %11, i8* %12, i64 %13, i8* undef, i8* undef), !dbg !2039
    flag_test [flag.test]/<init>:17:26:
      %0 = call %runtime._string* @"flag [flag.test].String"(i8* getelementptr inbounds ([7 x i8], [7 x i8]* @"flag_test [flag.test].init$string", i32 0, i32 0), i64 7, i8* getelementptr inbounds ([6 x i8], [6 x i8]* @"flag_test [flag.test].init$string.1301", i32 0, i32 0), i64 6, i8* getelementptr inbounds ([27 x i8], [27 x i8]* @"flag_test [flag.test].init$string.1302", i32 0, i32 0), i64 27, i8* undef, i8* undef), !dbg !2029






## fmt



The compiler gave the following error when running the tests for this package:


    # fmt_test [fmt.test]
    /usr/local/go/src/fmt/fmt_test.go:1229:4: b.RunParallel undefined (type *testing.B has no field or method RunParallel)
    /usr/local/go/src/fmt/fmt_test.go:1229:33: PB not declared by package testing
    /usr/local/go/src/fmt/fmt_test.go:1237:4: b.RunParallel undefined (type *testing.B has no field or method RunParallel)
    /usr/local/go/src/fmt/fmt_test.go:1237:33: PB not declared by package testing
    /usr/local/go/src/fmt/fmt_test.go:1245:4: b.RunParallel undefined (type *testing.B has no field or method RunParallel)
    /usr/local/go/src/fmt/fmt_test.go:1245:33: PB not declared by package testing
    /usr/local/go/src/fmt/fmt_test.go:1253:4: b.RunParallel undefined (type *testing.B has no field or method RunParallel)
    /usr/local/go/src/fmt/fmt_test.go:1253:33: PB not declared by package testing
    /usr/local/go/src/fmt/fmt_test.go:1262:4: b.RunParallel undefined (type *testing.B has no field or method RunParallel)
    /usr/local/go/src/fmt/fmt_test.go:1262:33: PB not declared by package testing
    /usr/local/go/src/fmt/fmt_test.go:1270:4: b.RunParallel undefined (type *testing.B has no field or method RunParallel)
    /usr/local/go/src/fmt/fmt_test.go:1270:33: PB not declared by package testing
    /usr/local/go/src/fmt/fmt_test.go:1278:4: b.RunParallel undefined (type *testing.B has no field or method RunParallel)
    /usr/local/go/src/fmt/fmt_test.go:1278:33: PB not declared by package testing
    [...more lines following...]






## go/ast



The compiler gave the following error when running the tests for this package:


    # go/ast [go/ast.test]
    go/ast [go/ast.test]/<init>: unimplemented: bitcast of map
    
    traceback:
    go/ast [go/ast.test]/<init>:
      %pack.ptr = bitcast %runtime.hashmap* %384 to i8*, !dbg !2053






## go/build


This package cannot be imported because the following dependencies cannot be compiled:

  * [go/doc](#go-doc)
  * [os/exec](#os-exec)





## go/constant


This package cannot be imported because the following dependencies cannot be compiled:

  * [math/big](#math-big)





## go/doc


This package cannot be imported because the following dependencies cannot be compiled:

  * [text/template](#text-template)





## go/format



The compiler gave the following error when running the tests for this package:


    # go/format_test [go/format.test]
    /usr/local/go/src/go/format/benchmark_test.go:76:5: b.Run undefined (type *testing.B has no field or method Run)
    /usr/local/go/src/go/format/benchmark_test.go:77:6: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/go/format/benchmark_test.go:78:6: b.ReportAllocs undefined (type *testing.B has no field or method ReportAllocs)
    /usr/local/go/src/go/format/benchmark_test.go:79:6: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)






## go/importer


This package cannot be imported because the following dependencies cannot be compiled:

  * [go/build](#go-build)
  * [go/types](#go-types)





## go/parser



The compiler gave the following error when running the tests for this package:


    # go/parser [go/parser.test]
    /usr/local/go/src/go/parser/performance_test.go:24:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)






## go/printer



The compiler gave the following error when running the tests for this package:


    # go/printer [go/printer.test]
    /usr/local/go/src/go/printer/printer_test.go:206:4: t.Parallel undefined (type *testing.T has no field or method Parallel)
    /usr/local/go/src/go/printer/printer_test.go:211:5: t.Run undefined (type *testing.T has no field or method Run)
    /usr/local/go/src/go/printer/printer_test.go:212:6: t.Parallel undefined (type *testing.T has no field or method Parallel)
    /usr/local/go/src/go/printer/printer_test.go:309:4: t.Parallel undefined (type *testing.T has no field or method Parallel)
    /usr/local/go/src/go/printer/printer_test.go:544:4: t.Parallel undefined (type *testing.T has no field or method Parallel)
    /usr/local/go/src/go/printer/printer_test.go:561:5: t.Run undefined (type *testing.T has no field or method Run)
    /usr/local/go/src/go/printer/printer_test.go:562:6: t.Parallel undefined (type *testing.T has no field or method Parallel)
    /usr/local/go/src/go/printer/printer_test.go:634:4: t.Parallel undefined (type *testing.T has no field or method Parallel)






## go/scanner



The compiler gave the following error when running the tests for this package:


    # go/scanner [go/scanner.test]
    /usr/local/go/src/go/scanner/scanner_test.go:877:4: b.StopTimer undefined (type *testing.B has no field or method StopTimer)
    /usr/local/go/src/go/scanner/scanner_test.go:881:4: b.StartTimer undefined (type *testing.B has no field or method StartTimer)
    /usr/local/go/src/go/scanner/scanner_test.go:894:4: b.StopTimer undefined (type *testing.B has no field or method StopTimer)
    /usr/local/go/src/go/scanner/scanner_test.go:902:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/go/scanner/scanner_test.go:904:4: b.StartTimer undefined (type *testing.B has no field or method StartTimer)






## go/token



The compiler gave the following error when running the tests for this package:


    # encoding/gob
    /usr/local/go/src/encoding/gob/decode.go:562:21: MakeMapWithSize not declared by package reflect
    /usr/local/go/src/encoding/gob/decode.go:948:22: PtrTo not declared by package reflect
    /usr/local/go/src/encoding/gob/decode.go:1118:30: srt.FieldByName undefined (type reflect.Type has no field or method FieldByName)
    /usr/local/go/src/encoding/gob/encode.go:603:16: PtrTo not declared by package reflect
    /usr/local/go/src/encoding/gob/encode.go:643:70: f.Index undefined (type reflect.StructField has no field or method Index)
    /usr/local/go/src/encoding/gob/type.go:119:12: cannot convert nil (untyped nil value) to reflect.Type
    /usr/local/go/src/encoding/gob/type.go:142:14: PtrTo not declared by package reflect
    /usr/local/go/src/encoding/gob/type.go:867:9: rt.PkgPath undefined (type reflect.Type has no field or method PkgPath)
    /usr/local/go/src/encoding/gob/type.go:870:21: rt.PkgPath undefined (type reflect.Type has no field or method PkgPath)






## go/types


This package cannot be imported because the following dependencies cannot be compiled:

  * [go/constant](#go-constant)





## hash



The compiler gave the following error when running the tests for this package:


    # hash_test [hash.test]
    /usr/local/go/src/hash/marshal_test.go:61:5: t.Run undefined (type *testing.T has no field or method Run)






## hash/adler32



The compiler gave the following error when running the tests for this package:


    # hash/adler32 [hash/adler32.test]
    /usr/local/go/src/hash/adler32/adler32_test.go:126:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/hash/adler32/adler32_test.go:134:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)






## hash/crc32



The compiler gave the following error when running the tests for this package:


    # hash/crc32 [hash/crc32.test]
    /usr/local/go/src/hash/crc32/crc32_test.go:113:4: t.Run undefined (type *testing.T has no field or method Run)
    /usr/local/go/src/hash/crc32/crc32_test.go:144:4: t.Run undefined (type *testing.T has no field or method Run)
    /usr/local/go/src/hash/crc32/crc32_test.go:286:4: b.Run undefined (type *testing.B has no field or method Run)
    /usr/local/go/src/hash/crc32/crc32_test.go:287:4: b.Run undefined (type *testing.B has no field or method Run)
    /usr/local/go/src/hash/crc32/crc32_test.go:288:4: b.Run undefined (type *testing.B has no field or method Run)
    /usr/local/go/src/hash/crc32/crc32_test.go:298:6: b.Run undefined (type *testing.B has no field or method Run)
    /usr/local/go/src/hash/crc32/crc32_test.go:300:8: b.Run undefined (type *testing.B has no field or method Run)
    /usr/local/go/src/hash/crc32/crc32_test.go:310:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/hash/crc32/crc32_test.go:323:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)






## hash/crc64



The compiler gave the following error when running the tests for this package:


    # hash/crc64 [hash/crc64.test]
    /usr/local/go/src/hash/crc64/crc64_test.go:77:4: t.Run undefined (type *testing.T has no field or method Run)
    /usr/local/go/src/hash/crc64/crc64_test.go:109:4: t.Run undefined (type *testing.T has no field or method Run)
    /usr/local/go/src/hash/crc64/crc64_test.go:158:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/hash/crc64/crc64_test.go:166:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)
    /usr/local/go/src/hash/crc64/crc64_test.go:175:4: b.Run undefined (type *testing.B has no field or method Run)
    /usr/local/go/src/hash/crc64/crc64_test.go:178:4: b.Run undefined (type *testing.B has no field or method Run)
    /usr/local/go/src/hash/crc64/crc64_test.go:181:4: b.Run undefined (type *testing.B has no field or method Run)
    /usr/local/go/src/hash/crc64/crc64_test.go:184:4: b.Run undefined (type *testing.B has no field or method Run)
    /usr/local/go/src/hash/crc64/crc64_test.go:187:4: b.Run undefined (type *testing.B has no field or method Run)
    /usr/local/go/src/hash/crc64/crc64_test.go:190:4: b.Run undefined (type *testing.B has no field or method Run)






## hash/fnv



The compiler gave the following error when running the tests for this package:


    # hash/fnv [hash/fnv.test]
    /usr/local/go/src/hash/fnv/fnv_test.go:118:5: t.Run undefined (type *testing.T has no field or method Run)
    /usr/local/go/src/hash/fnv/fnv_test.go:242:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/hash/fnv/fnv_test.go:249:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)






## hash/maphash



The compiler gave the following error when running the tests for this package:


    # hash/maphash [hash/maphash.test]
    /usr/local/go/src/hash/maphash/smhasher_test.go:123:16: Short not declared by package testing
    /usr/local/go/src/hash/maphash/smhasher_test.go:137:13: Short not declared by package testing
    /usr/local/go/src/hash/maphash/smhasher_test.go:153:13: Short not declared by package testing
    /usr/local/go/src/hash/maphash/smhasher_test.go:195:13: Short not declared by package testing
    /usr/local/go/src/hash/maphash/smhasher_test.go:224:13: Short not declared by package testing
    /usr/local/go/src/hash/maphash/smhasher_test.go:262:13: Short not declared by package testing
    /usr/local/go/src/hash/maphash/smhasher_test.go:330:13: Short not declared by package testing
    /usr/local/go/src/hash/maphash/smhasher_test.go:402:13: Short not declared by package testing
    /usr/local/go/src/hash/maphash/smhasher_test.go:424:13: Short not declared by package testing






## html



The compiler gave the following error when running the tests for this package:


    SIGABRT: abort
    PC=0x67d661 m=0 sigcode=0
    
    goroutine 0 [idle]:
    runtime.futex(0x9ede48, 0x80, 0x0, 0x0, 0x0, 0x0, 0x7ffe00000000, 0x0, 0x7ffeda1e5a08, 0x623c3f, ...)
    	/usr/local/go/src/runtime/sys_linux_amd64.s:567 +0x21
    runtime.futexsleep(0x9ede48, 0x7ffe00000000, 0xffffffffffffffff)
    	/usr/local/go/src/runtime/os_linux.go:44 +0x46
    runtime.notesleep(0x9ede48)
    	/usr/local/go/src/runtime/lock_futex.go:151 +0x9f
    runtime.stopm()
    	/usr/local/go/src/runtime/proc.go:1828 +0xc0
    runtime.findrunnable(0xc000026800, 0x0)
    	/usr/local/go/src/runtime/proc.go:2360 +0xa0d
    runtime.schedule()
    [...more lines following...]






## html/template


This package cannot be imported because the following dependencies cannot be compiled:

  * [encoding/json](#encoding-json)
  * [text/template](#text-template)





## image



The compiler gave the following error when running the tests for this package:


    # image [image.test]
    /usr/local/go/src/image/image_test.go:124:5: b.Run undefined (type *testing.B has no field or method Run)
    /usr/local/go/src/image/image_test.go:126:6: b.ReportAllocs undefined (type *testing.B has no field or method ReportAllocs)
    /usr/local/go/src/image/image_test.go:127:6: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)
    /usr/local/go/src/image/image_test.go:138:5: b.Run undefined (type *testing.B has no field or method Run)
    /usr/local/go/src/image/image_test.go:140:6: b.ReportAllocs undefined (type *testing.B has no field or method ReportAllocs)
    /usr/local/go/src/image/image_test.go:141:6: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)
    /usr/local/go/src/image/image_test.go:151:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)
    /usr/local/go/src/image/image_test.go:161:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)
    /usr/local/go/src/image/image_test.go:170:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)
    /usr/local/go/src/image/image_test.go:180:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)
    /usr/local/go/src/image/image_test.go:189:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)
    /usr/local/go/src/image/image_test.go:199:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)
    /usr/local/go/src/image/image_test.go:208:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)
    /usr/local/go/src/image/image_test.go:218:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)
    [...more lines following...]






## image/color



The compiler gave the following error when running the tests for this package:


    # testing/quick
    /usr/local/go/src/testing/quick/quick.go:273:11: fType.NumOut undefined (type reflect.Type has no field or method NumOut)
    /usr/local/go/src/testing/quick/quick.go:276:11: fType.Out undefined (type reflect.Type has no field or method Out)
    /usr/local/go/src/testing/quick/quick.go:280:43: fType.NumIn undefined (type reflect.Type has no field or method NumIn)
    /usr/local/go/src/testing/quick/quick.go:290:12: fVal.Call undefined (type reflect.Value has no field or method Call)
    /usr/local/go/src/testing/quick/quick.go:320:43: xType.NumIn undefined (type reflect.Type has no field or method NumIn)
    /usr/local/go/src/testing/quick/quick.go:330:26: x.Call undefined (type reflect.Value has no field or method Call)
    /usr/local/go/src/testing/quick/quick.go:331:26: y.Call undefined (type reflect.Value has no field or method Call)
    /usr/local/go/src/testing/quick/quick.go:351:25: f.In undefined (type reflect.Type has no field or method In)
    /usr/local/go/src/testing/quick/quick.go:353:95: f.In undefined (type reflect.Type has no field or method In)






## image/color/palette



The compiler gave the following error when running the tests for this package:


    error: function main is undeclared in the main package






## image/draw



The compiler gave the following error when running the tests for this package:


    # testing/quick
    /usr/local/go/src/testing/quick/quick.go:273:11: fType.NumOut undefined (type reflect.Type has no field or method NumOut)
    /usr/local/go/src/testing/quick/quick.go:276:11: fType.Out undefined (type reflect.Type has no field or method Out)
    /usr/local/go/src/testing/quick/quick.go:280:43: fType.NumIn undefined (type reflect.Type has no field or method NumIn)
    /usr/local/go/src/testing/quick/quick.go:290:12: fVal.Call undefined (type reflect.Value has no field or method Call)
    /usr/local/go/src/testing/quick/quick.go:320:43: xType.NumIn undefined (type reflect.Type has no field or method NumIn)
    /usr/local/go/src/testing/quick/quick.go:330:26: x.Call undefined (type reflect.Value has no field or method Call)
    /usr/local/go/src/testing/quick/quick.go:331:26: y.Call undefined (type reflect.Value has no field or method Call)
    /usr/local/go/src/testing/quick/quick.go:351:25: f.In undefined (type reflect.Type has no field or method In)
    /usr/local/go/src/testing/quick/quick.go:353:95: f.In undefined (type reflect.Type has no field or method In)






## image/gif



The compiler gave the following error when running the tests for this package:


    can't load test package: package image/gif (test)
    	imports runtime/debug: cannot find package "runtime/debug" in any of:
    	/home/ayke/.cache/tinygo/goroot-go1.14-fb1405eb1452312019d9a7d9cee4a3d3e4c7fb7c6ad9a2f42abbec348705ea80/src/vendor/runtime/debug (vendor tree)
    	/home/ayke/.cache/tinygo/goroot-go1.14-fb1405eb1452312019d9a7d9cee4a3d3e4c7fb7c6ad9a2f42abbec348705ea80/src/runtime/debug (from $GOROOT)
    	/home/ayke/src/runtime/debug (from $GOPATH)






## image/jpeg



The compiler gave the following error when running the tests for this package:


    # image/jpeg [image/jpeg.test]
    /usr/local/go/src/image/jpeg/dct_test.go:16:4: b.StopTimer undefined (type *testing.B has no field or method StopTimer)
    /usr/local/go/src/image/jpeg/dct_test.go:21:4: b.StartTimer undefined (type *testing.B has no field or method StartTimer)
    /usr/local/go/src/image/jpeg/reader_test.go:334:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/image/jpeg/reader_test.go:335:4: b.ReportAllocs undefined (type *testing.B has no field or method ReportAllocs)
    /usr/local/go/src/image/jpeg/reader_test.go:336:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)
    /usr/local/go/src/image/jpeg/writer_test.go:259:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/image/jpeg/writer_test.go:260:4: b.ReportAllocs undefined (type *testing.B has no field or method ReportAllocs)
    /usr/local/go/src/image/jpeg/writer_test.go:261:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)
    /usr/local/go/src/image/jpeg/writer_test.go:281:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/image/jpeg/writer_test.go:282:4: b.ReportAllocs undefined (type *testing.B has no field or method ReportAllocs)
    /usr/local/go/src/image/jpeg/writer_test.go:283:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)






## image/png



The compiler gave the following error when running the tests for this package:


    # image/png [image/png.test]
    /usr/local/go/src/image/png/reader_test.go:333:13: Short not declared by package testing
    /usr/local/go/src/image/png/reader_test.go:690:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/image/png/reader_test.go:691:4: b.ReportAllocs undefined (type *testing.B has no field or method ReportAllocs)
    /usr/local/go/src/image/png/reader_test.go:692:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)
    /usr/local/go/src/image/png/writer_test.go:52:13: Short not declared by package testing
    /usr/local/go/src/image/png/writer_test.go:124:5: t.Run undefined (type *testing.T has no field or method Run)
    /usr/local/go/src/image/png/writer_test.go:233:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/image/png/writer_test.go:234:4: b.ReportAllocs undefined (type *testing.B has no field or method ReportAllocs)
    /usr/local/go/src/image/png/writer_test.go:235:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)
    /usr/local/go/src/image/png/writer_test.go:258:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/image/png/writer_test.go:259:4: b.ReportAllocs undefined (type *testing.B has no field or method ReportAllocs)
    /usr/local/go/src/image/png/writer_test.go:260:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)
    /usr/local/go/src/image/png/writer_test.go:278:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/image/png/writer_test.go:279:4: b.ReportAllocs undefined (type *testing.B has no field or method ReportAllocs)
    [...more lines following...]






## index/suffixarray



The compiler gave the following error when running the tests for this package:


    # index/suffixarray [index/suffixarray.test]
    /usr/local/go/src/index/suffixarray/suffixarray_test.go:344:4: t.Run undefined (type *testing.T has no field or method Run)
    /usr/local/go/src/index/suffixarray/suffixarray_test.go:349:14: Short not declared by package testing
    /usr/local/go/src/index/suffixarray/suffixarray_test.go:359:4: t.Run undefined (type *testing.T has no field or method Run)
    /usr/local/go/src/index/suffixarray/suffixarray_test.go:393:4: t.Run undefined (type *testing.T has no field or method Run)
    /usr/local/go/src/index/suffixarray/suffixarray_test.go:399:25: Short not declared by package testing
    /usr/local/go/src/index/suffixarray/suffixarray_test.go:407:4: t.Run undefined (type *testing.T has no field or method Run)
    /usr/local/go/src/index/suffixarray/suffixarray_test.go:413:24: Short not declared by package testing
    /usr/local/go/src/index/suffixarray/suffixarray_test.go:478:4: b.ReportAllocs undefined (type *testing.B has no field or method ReportAllocs)
    /usr/local/go/src/index/suffixarray/suffixarray_test.go:479:4: b.StopTimer undefined (type *testing.B has no field or method StopTimer)
    /usr/local/go/src/index/suffixarray/suffixarray_test.go:489:4: b.StartTimer undefined (type *testing.B has no field or method StartTimer)
    /usr/local/go/src/index/suffixarray/suffixarray_test.go:490:4: b.SetBytes undefined (type *testing.B has no field or method SetBytes)
    /usr/local/go/src/index/suffixarray/suffixarray_test.go:543:5: b.Run undefined (type *testing.B has no field or method Run)
    /usr/local/go/src/index/suffixarray/suffixarray_test.go:548:15: Short not declared by package testing
    /usr/local/go/src/index/suffixarray/suffixarray_test.go:560:7: b.Run undefined (type *testing.B has no field or method Run)
    [...more lines following...]






## io



The compiler gave the following error when running the tests for this package:


    # io_test [io.test]
    /usr/local/go/src/io/io_test.go:178:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)
    /usr/local/go/src/io/io_test.go:190:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)
    /usr/local/go/src/io/multi_test.go:88:24: AllocsPerRun not declared by package testing
    /usr/local/go/src/io/multi_test.go:155:15: Callers not declared by package runtime
    /usr/local/go/src/io/multi_test.go:159:16: Callers not declared by package runtime
    /usr/local/go/src/io/multi_test.go:229:20: CallersFrames not declared by package runtime
    /usr/local/go/src/io/multi_test.go:241:15: Callers not declared by package runtime
    /usr/local/go/src/io/multi_test.go:245:16: Callers not declared by package runtime
    /usr/local/go/src/io/pipe_test.go:351:4: t.Run undefined (type *testing.T has no field or method Run)
    /usr/local/go/src/io/pipe_test.go:379:4: t.Run undefined (type *testing.T has no field or method Run)






## io/ioutil



The compiler gave the following error when running the tests for this package:


    # io/ioutil [io/ioutil.test]
    /usr/local/go/src/io/ioutil/ioutil_test.go:69:8: Getuid not declared by package os
    /usr/local/go/src/io/ioutil/ioutil_test.go:78:11: RemoveAll not declared by package os
    /usr/local/go/src/io/ioutil/tempfile_test.go:20:11: RemoveAll not declared by package os
    /usr/local/go/src/io/ioutil/tempfile_test.go:82:5: t.Run undefined (type *testing.T has no field or method Run)
    /usr/local/go/src/io/ioutil/tempfile_test.go:94:4: t.Run undefined (type *testing.T has no field or method Run)
    /usr/local/go/src/io/ioutil/tempfile_test.go:107:11: RemoveAll not declared by package os






## log



The compiler gave the following error when running the tests for this package:


    === RUN   TestAll
    --- FAIL: TestAll
    	log output should match "^.*/[A-Za-z0-9_\\-]+\\.go:(60|62): hello 23 world$" is "???:0: hello 23 world"
    	log output should match "^.*/[A-Za-z0-9_\\-]+\\.go:(60|62): hello 23 world$" is "???:0: hello 23 world"
    	log output should match "^[A-Za-z0-9_\\-]+\\.go:(60|62): hello 23 world$" is "???:0: hello 23 world"
    	log output should match "^[A-Za-z0-9_\\-]+\\.go:(60|62): hello 23 world$" is "???:0: hello 23 world"
    	log output should match "^[A-Za-z0-9_\\-]+\\.go:(60|62): hello 23 world$" is "???:0: hello 23 world"
    	log output should match "^[A-Za-z0-9_\\-]+\\.go:(60|62): hello 23 world$" is "???:0: hello 23 world"
    	log output should match "^XXX[0-9][0-9][0-9][0-9]/[0-9][0-9]/[0-9][0-9] [0-9][0-9]:[0-9][0-9]:[0-9][0-9]\\.[0-9][0-9][0-9][0-9][0-9][0-9] .*/[A-Za-z0-9_\\-]+\\.go:(60|62): hello 23 world$" is "XXX1970/01/01 03:20:30.695850 ???:0: hello 23 world"
    	log output should match "^XXX[0-9][0-9][0-9][0-9]/[0-9][0-9]/[0-9][0-9] [0-9][0-9]:[0-9][0-9]:[0-9][0-9]\\.[0-9][0-9][0-9][0-9][0-9][0-9] .*/[A-Za-z0-9_\\-]+\\.go:(60|62): hello 23 world$" is "XXX1970/01/01 03:20:30.696139 ???:0: hello 23 world"
    	log output should match "^XXX[0-9][0-9][0-9][0-9]/[0-9][0-9]/[0-9][0-9] [0-9][0-9]:[0-9][0-9]:[0-9][0-9]\\.[0-9][0-9][0-9][0-9][0-9][0-9] [A-Za-z0-9_\\-]+\\.go:(60|62): hello 23 world$" is "XXX1970/01/01 03:20:30.696400 ???:0: hello 23 world"
    	log output should match "^XXX[0-9][0-9][0-9][0-9]/[0-9][0-9]/[0-9][0-9] [0-9][0-9]:[0-9][0-9]:[0-9][0-9]\\.[0-9][0-9][0-9][0-9][0-9][0-9] [A-Za-z0-9_\\-]+\\.go:(60|62): hello 23 world$" is "XXX1970/01/01 03:20:30.696699 ???:0: hello 23 world"
    	log output should match "^[0-9][0-9][0-9][0-9]/[0-9][0-9]/[0-9][0-9] [0-9][0-9]:[0-9][0-9]:[0-9][0-9]\\.[0-9][0-9][0-9][0-9][0-9][0-9] .*/[A-Za-z0-9_\\-]+\\.go:(60|62): XXXhello 23 world$" is "1970/01/01 03:20:30.697116 ???:0: XXXhello 23 world"
    	log output should match "^[0-9][0-9][0-9][0-9]/[0-9][0-9]/[0-9][0-9] [0-9][0-9]:[0-9][0-9]:[0-9][0-9]\\.[0-9][0-9][0-9][0-9][0-9][0-9] .*/[A-Za-z0-9_\\-]+\\.go:(60|62): XXXhello 23 world$" is "1970/01/01 03:20:30.697438 ???:0: XXXhello 23 world"
    	log output should match "^[0-9][0-9][0-9][0-9]/[0-9][0-9]/[0-9][0-9] [0-9][0-9]:[0-9][0-9]:[0-9][0-9]\\.[0-9][0-9][0-9][0-9][0-9][0-9] [A-Za-z0-9_\\-]+\\.go:(60|62): XXXhello 23 world$" is "1970/01/01 03:20:30.697688 ???:0: XXXhello 23 world"
    [...more lines following...]






## log/syslog


This package cannot be imported because the following dependencies cannot be compiled:

  * [net](#net)





## math



The compiler gave the following error when running the tests for this package:


    ld: error: undefined symbol: math [math.test].Log
    >>> referenced by erfinv.go:99 (/usr/local/go/src/math/erfinv.go:99)
    >>>               /tmp/tinygo635597679/main.o:(math [math.test].Erfinv)
    >>> referenced by jn.go:198 (/usr/local/go/src/math/jn.go:198)
    >>>               /tmp/tinygo635597679/main.o:(math [math.test].Jn)
    >>> referenced by lgamma.go:210 (/usr/local/go/src/math/lgamma.go:210)
    >>>               /tmp/tinygo635597679/main.o:(math [math.test].Lgamma)
    >>> referenced by lgamma.go:224 (/usr/local/go/src/math/lgamma.go:224)
    >>>               /tmp/tinygo635597679/main.o:(math [math.test].Lgamma)
    >>> referenced by lgamma.go:238 (/usr/local/go/src/math/lgamma.go:238)
    >>>               /tmp/tinygo635597679/main.o:(math [math.test].Lgamma)
    >>> referenced by lgamma.go:306 (/usr/local/go/src/math/lgamma.go:306)
    >>>               /tmp/tinygo635597679/main.o:(math [math.test].Lgamma)
    >>> referenced by lgamma.go:0 (/usr/local/go/src/math/lgamma.go:0)
    >>>               /tmp/tinygo635597679/main.o:(math [math.test].Lgamma)
    [...more lines following...]






## math/big



The compiler gave the following error when this package was imported:


    # math/big
    /usr/local/go/src/math/bits.go: interp: branch on a non-constant
    
    traceback:
    /usr/local/go/src/math/bits.go:
      br i1 %1, label %if.then, label %if.done, !dbg !1734
    /usr/local/go/src/math/frexp.go:26:20:
      %7 = call { double, i32 } @math.normalize(double %f, i8* undef, i8* undef), !dbg !1745
    /home/ayke/src/github.com/tinygo-org/tinygo/src/runtime/math.go:129:62:
      %0 = call { double, i32 } @math.frexp(double %x, i8* undef, i8* undef), !dbg !1732
    /usr/local/go/src/math/big/float.go:560:26:
      %44 = call { double, i32 } @math.Frexp(double %x, i8* undef, i8* undef), !dbg !1776
    /usr/local/go/src/math/big/float.go:92:30:
      %5 = call %"math/big.Float"* @"(*math/big.Float).SetFloat64"(%"math/big.Float"* %3, double %x, i8* undef, i8* undef), !dbg !1736
    math/big/<init>:10:18:
    [...more lines following...]






## math/bits



The compiler gave the following error when running the tests for this package:


    === RUN   TestUintSize
    --- PASS: TestUintSize
    
    === RUN   TestLeadingZeros
    --- PASS: TestLeadingZeros
    
    === RUN   TestTrailingZeros
    --- PASS: TestTrailingZeros
    
    === RUN   TestOnesCount
    --- PASS: TestOnesCount
    
    === RUN   TestRotateLeft
    --- PASS: TestRotateLeft
    
    [...more lines following...]






## math/cmplx



The compiler gave the following error when running the tests for this package:


    === RUN   TestAbs
    --- PASS: TestAbs
    
    === RUN   TestAcos
    --- FAIL: TestAcos
    	Acos((NaN+NaNi)) = (NaN+NaNi), want (NaN+NaNi)
    	Acos((2+0i)) not continuous, got (0+1.3169578969248166i) want (0-1.3169578969248164i)
    	Acos((-2+0i)) not continuous, got (3.141592653589793-1.3169578969248164i) want (3.141592653589793+1.3169578969248166i)
    
    === RUN   TestAcosh
    --- FAIL: TestAcosh
    	Acosh((NaN+NaNi)) = (NaN+NaNi), want (NaN+NaNi)
    	Acosh((-2+0i)) not continuous, got (1.3169578969248164+3.141592653589793i) want (1.3169578969248166-3.141592653589793i)
    
    === RUN   TestAsin
    [...more lines following...]






## math/rand



The compiler gave the following error when running the tests for this package:


    # os/exec
    /usr/local/go/src/os/exec/exec.go:129:14: Process not declared by package os
    /usr/local/go/src/os/exec/exec.go:133:19: ProcessState not declared by package os
    /usr/local/go/src/os/exec/exec.go:457:6: ProcessState not declared by package os
    /usr/local/go/src/os/exec/exec.go:229:12: Environ not declared by package os
    /usr/local/go/src/os/exec/exec.go:245:23: DevNull not declared by package os
    /usr/local/go/src/os/exec/exec.go:257:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:290:27: DevNull not declared by package os
    /usr/local/go/src/os/exec/exec.go:302:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:417:22: StartProcess not declared by package os
    /usr/local/go/src/os/exec/exec.go:417:57: ProcAttr not declared by package os
    /usr/local/go/src/os/exec/exec.go:579:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:621:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:646:20: Pipe not declared by package os






## mime



The compiler gave the following error when running the tests for this package:


    # mime [mime.test]
    /usr/local/go/src/mime/type_test.go:143:15: AllocsPerRun not declared by package testing
    /usr/local/go/src/mime/type_test.go:154:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)
    /usr/local/go/src/mime/type_test.go:161:5: b.Run undefined (type *testing.B has no field or method Run)
    /usr/local/go/src/mime/type_test.go:162:6: b.RunParallel undefined (type *testing.B has no field or method RunParallel)
    /usr/local/go/src/mime/type_test.go:162:35: PB not declared by package testing
    /usr/local/go/src/mime/type_test.go:173:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)
    /usr/local/go/src/mime/type_test.go:180:5: b.Run undefined (type *testing.B has no field or method Run)
    /usr/local/go/src/mime/type_test.go:181:6: b.RunParallel undefined (type *testing.B has no field or method RunParallel)
    /usr/local/go/src/mime/type_test.go:181:35: PB not declared by package testing






## mime/multipart


This package cannot be imported because the following dependencies cannot be compiled:

  * [crypto/rand](#crypto-rand)
  * [net/textproto](#net-textproto)





## mime/quotedprintable



The compiler gave the following error when running the tests for this package:


    # os/exec
    /usr/local/go/src/os/exec/exec.go:129:14: Process not declared by package os
    /usr/local/go/src/os/exec/exec.go:133:19: ProcessState not declared by package os
    /usr/local/go/src/os/exec/exec.go:457:6: ProcessState not declared by package os
    /usr/local/go/src/os/exec/exec.go:229:12: Environ not declared by package os
    /usr/local/go/src/os/exec/exec.go:245:23: DevNull not declared by package os
    /usr/local/go/src/os/exec/exec.go:257:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:290:27: DevNull not declared by package os
    /usr/local/go/src/os/exec/exec.go:302:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:417:22: StartProcess not declared by package os
    /usr/local/go/src/os/exec/exec.go:417:57: ProcAttr not declared by package os
    /usr/local/go/src/os/exec/exec.go:579:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:621:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:646:20: Pipe not declared by package os






## net



The compiler gave the following error when this package was imported:


    # net
    /usr/local/go/src/net/parse.go:80:12: st.ModTime undefined (type os.FileInfo has no field or method ModTime)






## net/http


This package cannot be imported because the following dependencies cannot be compiled:

  * [crypto/rand](#crypto-rand)
  * [crypto/tls](#crypto-tls)
  * [mime/multipart](#mime-multipart)
  * [net](#net)
  * [net/http/httptrace](#net-http-httptrace)
  * [net/textproto](#net-textproto)





## net/http/cgi


This package cannot be imported because the following dependencies cannot be compiled:

  * [crypto/tls](#crypto-tls)
  * [net](#net)
  * [net/http](#net-http)
  * [os/exec](#os-exec)





## net/http/cookiejar


This package cannot be imported because the following dependencies cannot be compiled:

  * [net](#net)
  * [net/http](#net-http)





## net/http/fcgi


This package cannot be imported because the following dependencies cannot be compiled:

  * [net](#net)
  * [net/http](#net-http)
  * [net/http/cgi](#net-http-cgi)





## net/http/httptest


This package cannot be imported because the following dependencies cannot be compiled:

  * [crypto/tls](#crypto-tls)
  * [crypto/x509](#crypto-x509)
  * [net](#net)
  * [net/http](#net-http)





## net/http/httptrace


This package cannot be imported because the following dependencies cannot be compiled:

  * [crypto/tls](#crypto-tls)
  * [net](#net)
  * [net/textproto](#net-textproto)





## net/http/httputil


This package cannot be imported because the following dependencies cannot be compiled:

  * [net](#net)
  * [net/http](#net-http)
  * [net/textproto](#net-textproto)





## net/http/pprof


This package cannot be imported because the following dependencies cannot be compiled:

  * [html/template](#html-template)
  * [net/http](#net-http)





## net/mail


This package cannot be imported because the following dependencies cannot be compiled:

  * [net/textproto](#net-textproto)





## net/rpc


This package cannot be imported because the following dependencies cannot be compiled:

  * [encoding/gob](#encoding-gob)
  * [html/template](#html-template)
  * [net](#net)
  * [net/http](#net-http)





## net/rpc/jsonrpc


This package cannot be imported because the following dependencies cannot be compiled:

  * [encoding/json](#encoding-json)
  * [net](#net)
  * [net/rpc](#net-rpc)





## net/smtp


This package cannot be imported because the following dependencies cannot be compiled:

  * [crypto/tls](#crypto-tls)
  * [net](#net)
  * [net/textproto](#net-textproto)





## net/textproto


This package cannot be imported because the following dependencies cannot be compiled:

  * [net](#net)





## net/url



The compiler gave the following error when running the tests for this package:


    # net
    ../../../../../usr/include/netdb.h:617:23: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:618:22: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:624:23: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:625:25: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:617:23: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:618:22: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:624:23: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:625:25: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:617:23: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:618:22: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:624:23: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:625:25: unexpected token ILLEGAL






## os



The compiler gave the following error when running the tests for this package:


    error: function main is undeclared in the main package






## os/exec



The compiler gave the following error when this package was imported:


    # os/exec
    /usr/local/go/src/os/exec/exec.go:129:14: Process not declared by package os
    /usr/local/go/src/os/exec/exec.go:133:19: ProcessState not declared by package os
    /usr/local/go/src/os/exec/exec.go:457:6: ProcessState not declared by package os
    /usr/local/go/src/os/exec/exec.go:229:12: Environ not declared by package os
    /usr/local/go/src/os/exec/exec.go:245:23: DevNull not declared by package os
    /usr/local/go/src/os/exec/exec.go:257:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:290:27: DevNull not declared by package os
    /usr/local/go/src/os/exec/exec.go:302:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:417:22: StartProcess not declared by package os
    /usr/local/go/src/os/exec/exec.go:417:57: ProcAttr not declared by package os
    /usr/local/go/src/os/exec/exec.go:579:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:621:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:646:20: Pipe not declared by package os






## os/signal



The compiler gave the following error when running the tests for this package:


    # os/exec
    /usr/local/go/src/os/exec/exec.go:129:14: Process not declared by package os
    /usr/local/go/src/os/exec/exec.go:133:19: ProcessState not declared by package os
    /usr/local/go/src/os/exec/exec.go:457:6: ProcessState not declared by package os
    /usr/local/go/src/os/exec/exec.go:229:12: Environ not declared by package os
    /usr/local/go/src/os/exec/exec.go:245:23: DevNull not declared by package os
    /usr/local/go/src/os/exec/exec.go:257:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:290:27: DevNull not declared by package os
    /usr/local/go/src/os/exec/exec.go:302:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:417:22: StartProcess not declared by package os
    /usr/local/go/src/os/exec/exec.go:417:57: ProcAttr not declared by package os
    /usr/local/go/src/os/exec/exec.go:579:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:621:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:646:20: Pipe not declared by package os






## os/user



The compiler gave the following error when this package was imported:


    # os/user
    /usr/local/go/src/os/user/lookup.go:15:41: undeclared name: current
    /usr/local/go/src/os/user/lookup.go:36:9: undeclared name: lookupUser
    /usr/local/go/src/os/user/lookup.go:45:9: undeclared name: lookupUserId
    /usr/local/go/src/os/user/lookup.go:51:9: undeclared name: lookupGroup
    /usr/local/go/src/os/user/lookup.go:57:9: undeclared name: lookupGroupId
    /usr/local/go/src/os/user/lookup.go:62:9: undeclared name: listGroups






## path



The compiler gave the following error when running the tests for this package:


    # path [path.test]
    /usr/local/go/src/path/path_test.go:78:13: Short not declared by package testing
    /usr/local/go/src/path/path_test.go:87:21: AllocsPerRun not declared by package testing






## path/filepath



The compiler gave the following error when running the tests for this package:


    # os/exec [path/filepath.test]
    /usr/local/go/src/os/exec/exec.go:129:14: Process not declared by package os
    /usr/local/go/src/os/exec/exec.go:133:19: ProcessState not declared by package os
    /usr/local/go/src/os/exec/exec.go:457:6: ProcessState not declared by package os
    /usr/local/go/src/os/exec/exec.go:229:12: Environ not declared by package os
    /usr/local/go/src/os/exec/exec.go:245:23: DevNull not declared by package os
    /usr/local/go/src/os/exec/exec.go:257:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:290:27: DevNull not declared by package os
    /usr/local/go/src/os/exec/exec.go:302:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:417:22: StartProcess not declared by package os
    /usr/local/go/src/os/exec/exec.go:417:57: ProcAttr not declared by package os
    /usr/local/go/src/os/exec/exec.go:579:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:621:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:646:20: Pipe not declared by package os






## plugin



The compiler gave the following error when running the tests for this package:


    # plugin
    ../../../../../usr/local/go/src/plugin/plugin_dlopen.go:10:6: not implemented: build constraints in #cgo line






## reflect



The compiler gave the following error when running the tests for this package:


    error: function main is undeclared in the main package






## regexp



The compiler gave the following error when running the tests for this package:


    # os/exec
    /usr/local/go/src/os/exec/exec.go:129:14: Process not declared by package os
    /usr/local/go/src/os/exec/exec.go:133:19: ProcessState not declared by package os
    /usr/local/go/src/os/exec/exec.go:457:6: ProcessState not declared by package os
    /usr/local/go/src/os/exec/exec.go:229:12: Environ not declared by package os
    /usr/local/go/src/os/exec/exec.go:245:23: DevNull not declared by package os
    /usr/local/go/src/os/exec/exec.go:257:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:290:27: DevNull not declared by package os
    /usr/local/go/src/os/exec/exec.go:302:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:417:22: StartProcess not declared by package os
    /usr/local/go/src/os/exec/exec.go:417:57: ProcAttr not declared by package os
    /usr/local/go/src/os/exec/exec.go:579:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:621:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:646:20: Pipe not declared by package os






## regexp/syntax



The compiler gave the following error when running the tests for this package:


    # regexp/syntax [regexp/syntax.test]
    /usr/local/go/src/regexp/syntax/parse_test.go:389:7: interp: unsupported instruction
    
    traceback:
    /usr/local/go/src/regexp/syntax/parse_test.go:389:7:
      %12 = inttoptr i64 %11 to i1 (i32, i8*, i8*)*, !dbg !1992
    regexp/syntax [regexp/syntax.test]/<init>:109:24:
      %1647 = call %runtime._string @"regexp/syntax [regexp/syntax.test].mkCharClass"(i8* undef, i64 ptrtoint (%runtime.funcValueWithSignature* @"unicode.IsUpper$withSignature" to i64), i8* undef, i8* undef), !dbg !2423






## sort



The compiler gave the following error when running the tests for this package:


    # os/exec [sort.test]
    /usr/local/go/src/os/exec/exec.go:129:14: Process not declared by package os
    /usr/local/go/src/os/exec/exec.go:133:19: ProcessState not declared by package os
    /usr/local/go/src/os/exec/exec.go:457:6: ProcessState not declared by package os
    /usr/local/go/src/os/exec/exec.go:229:12: Environ not declared by package os
    /usr/local/go/src/os/exec/exec.go:245:23: DevNull not declared by package os
    /usr/local/go/src/os/exec/exec.go:257:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:290:27: DevNull not declared by package os
    /usr/local/go/src/os/exec/exec.go:302:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:417:22: StartProcess not declared by package os
    /usr/local/go/src/os/exec/exec.go:417:57: ProcAttr not declared by package os
    /usr/local/go/src/os/exec/exec.go:579:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:621:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:646:20: Pipe not declared by package os






## strconv



The compiler gave the following error when running the tests for this package:


    # strconv_test [strconv.test]
    /usr/local/go/src/strconv/atof_test.go:458:13: Short not declared by package testing
    /usr/local/go/src/strconv/atof_test.go:583:13: Short not declared by package testing
    /usr/local/go/src/strconv/atof_test.go:671:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)
    /usr/local/go/src/strconv/atoi_test.go:603:4: b.Run undefined (type *testing.B has no field or method Run)
    /usr/local/go/src/strconv/atoi_test.go:606:4: b.Run undefined (type *testing.B has no field or method Run)
    /usr/local/go/src/strconv/atoi_test.go:625:5: b.Run undefined (type *testing.B has no field or method Run)
    /usr/local/go/src/strconv/atoi_test.go:636:4: b.Run undefined (type *testing.B has no field or method Run)
    /usr/local/go/src/strconv/atoi_test.go:639:4: b.Run undefined (type *testing.B has no field or method Run)
    /usr/local/go/src/strconv/atoi_test.go:657:5: b.Run undefined (type *testing.B has no field or method Run)
    /usr/local/go/src/strconv/ftoa_test.go:188:13: Short not declared by package testing
    /usr/local/go/src/strconv/ftoa_test.go:247:5: b.Run undefined (type *testing.B has no field or method Run)
    /usr/local/go/src/strconv/ftoa_test.go:258:5: b.Run undefined (type *testing.B has no field or method Run)
    /usr/local/go/src/strconv/itoa_test.go:205:5: b.Run undefined (type *testing.B has no field or method Run)
    /usr/local/go/src/strconv/itoa_test.go:225:5: b.Run undefined (type *testing.B has no field or method Run)
    [...more lines following...]






## strings



The compiler gave the following error when running the tests for this package:


    # os/exec [strings.test]
    /usr/local/go/src/os/exec/exec.go:129:14: Process not declared by package os
    /usr/local/go/src/os/exec/exec.go:133:19: ProcessState not declared by package os
    /usr/local/go/src/os/exec/exec.go:457:6: ProcessState not declared by package os
    /usr/local/go/src/os/exec/exec.go:229:12: Environ not declared by package os
    /usr/local/go/src/os/exec/exec.go:245:23: DevNull not declared by package os
    /usr/local/go/src/os/exec/exec.go:257:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:290:27: DevNull not declared by package os
    /usr/local/go/src/os/exec/exec.go:302:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:417:22: StartProcess not declared by package os
    /usr/local/go/src/os/exec/exec.go:417:57: ProcAttr not declared by package os
    /usr/local/go/src/os/exec/exec.go:579:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:621:20: Pipe not declared by package os
    /usr/local/go/src/os/exec/exec.go:646:20: Pipe not declared by package os






## sync



The compiler gave the following error when running the tests for this package:


    error: function main is undeclared in the main package






## sync/atomic



The compiler gave the following error when running the tests for this package:


    # sync/atomic_test [sync/atomic.test]
    /usr/local/go/src/sync/atomic/atomic_test.go:879:13: Short not declared by package testing
    /usr/local/go/src/sync/atomic/atomic_test.go:1035:13: Short not declared by package testing
    /usr/local/go/src/sync/atomic/atomic_test.go:1180:13: Short not declared by package testing
    /usr/local/go/src/sync/atomic/atomic_test.go:1203:13: NumCPU not declared by package runtime
    /usr/local/go/src/sync/atomic/atomic_test.go:1204:60: NumCPU not declared by package runtime
    /usr/local/go/src/sync/atomic/atomic_test.go:1208:13: Short not declared by package testing
    /usr/local/go/src/sync/atomic/atomic_test.go:1245:13: NumCPU not declared by package runtime
    /usr/local/go/src/sync/atomic/atomic_test.go:1246:60: NumCPU not declared by package runtime
    /usr/local/go/src/sync/atomic/atomic_test.go:1253:13: Short not declared by package testing
    /usr/local/go/src/sync/atomic/atomic_test.go:1290:13: NumCPU not declared by package runtime
    /usr/local/go/src/sync/atomic/atomic_test.go:1291:60: NumCPU not declared by package runtime
    /usr/local/go/src/sync/atomic/atomic_test.go:1295:13: Short not declared by package testing
    /usr/local/go/src/sync/atomic/atomic_test.go:1336:13: NumCPU not declared by package runtime
    /usr/local/go/src/sync/atomic/atomic_test.go:1337:60: NumCPU not declared by package runtime
    [...more lines following...]






## syscall



The compiler gave the following error when running the tests for this package:


    # net [syscall.test]
    ../../../../../usr/include/netdb.h:617:23: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:618:22: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:624:23: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:625:25: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:617:23: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:618:22: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:624:23: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:625:25: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:617:23: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:618:22: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:624:23: unexpected token ILLEGAL
    ../../../../../usr/include/netdb.h:625:25: unexpected token ILLEGAL






## syscall/js



The compiler gave the following error when running the tests for this package:


    can't load package: package syscall/js: build constraints exclude all Go files in /home/ayke/.cache/tinygo/goroot-go1.14-fb1405eb1452312019d9a7d9cee4a3d3e4c7fb7c6ad9a2f42abbec348705ea80/src/syscall/js






## testing



The compiler gave the following error when running the tests for this package:


    error: function main is undeclared in the main package








## testing/quick



The compiler gave the following error when this package was imported:


    # testing/quick
    /usr/local/go/src/testing/quick/quick.go:273:11: fType.NumOut undefined (type reflect.Type has no field or method NumOut)
    /usr/local/go/src/testing/quick/quick.go:276:11: fType.Out undefined (type reflect.Type has no field or method Out)
    /usr/local/go/src/testing/quick/quick.go:280:43: fType.NumIn undefined (type reflect.Type has no field or method NumIn)
    /usr/local/go/src/testing/quick/quick.go:290:12: fVal.Call undefined (type reflect.Value has no field or method Call)
    /usr/local/go/src/testing/quick/quick.go:320:43: xType.NumIn undefined (type reflect.Type has no field or method NumIn)
    /usr/local/go/src/testing/quick/quick.go:330:26: x.Call undefined (type reflect.Value has no field or method Call)
    /usr/local/go/src/testing/quick/quick.go:331:26: y.Call undefined (type reflect.Value has no field or method Call)
    /usr/local/go/src/testing/quick/quick.go:351:25: f.In undefined (type reflect.Type has no field or method In)
    /usr/local/go/src/testing/quick/quick.go:353:95: f.In undefined (type reflect.Type has no field or method In)








## text/tabwriter



The compiler gave the following error when running the tests for this package:


    # text/tabwriter_test [text/tabwriter.test]
    /usr/local/go/src/text/tabwriter/tabwriter_test.go:663:6: b.Run undefined (type *testing.B has no field or method Run)
    /usr/local/go/src/text/tabwriter/tabwriter_test.go:664:7: b.Run undefined (type *testing.B has no field or method Run)
    /usr/local/go/src/text/tabwriter/tabwriter_test.go:665:8: b.ReportAllocs undefined (type *testing.B has no field or method ReportAllocs)
    /usr/local/go/src/text/tabwriter/tabwriter_test.go:676:7: b.Run undefined (type *testing.B has no field or method Run)
    /usr/local/go/src/text/tabwriter/tabwriter_test.go:677:8: b.ReportAllocs undefined (type *testing.B has no field or method ReportAllocs)
    /usr/local/go/src/text/tabwriter/tabwriter_test.go:696:5: b.Run undefined (type *testing.B has no field or method Run)
    /usr/local/go/src/text/tabwriter/tabwriter_test.go:697:6: b.ReportAllocs undefined (type *testing.B has no field or method ReportAllocs)
    /usr/local/go/src/text/tabwriter/tabwriter_test.go:718:5: b.Run undefined (type *testing.B has no field or method Run)
    /usr/local/go/src/text/tabwriter/tabwriter_test.go:719:6: b.ReportAllocs undefined (type *testing.B has no field or method ReportAllocs)
    /usr/local/go/src/text/tabwriter/tabwriter_test.go:747:4: b.ReportAllocs undefined (type *testing.B has no field or method ReportAllocs)






## text/template



The compiler gave the following error when this package was imported:


    # text/template
    /usr/local/go/src/text/template/exec.go:377:20: val.Recv undefined (type reflect.Value has no field or method Recv)
    /usr/local/go/src/text/template/exec.go:541:25: cannot convert nil (untyped nil value) to reflect.Type
    /usr/local/go/src/text/template/exec.go:603:19: ptr.MethodByName undefined (type reflect.Value has no field or method MethodByName)
    /usr/local/go/src/text/template/exec.go:610:33: receiver.Type().FieldByName undefined (type reflect.Type has no field or method FieldByName)
    /usr/local/go/src/text/template/exec.go:645:21: etyp.FieldByName undefined (type reflect.Type has no field or method FieldByName)
    /usr/local/go/src/text/template/exec.go:678:9: typ.IsVariadic undefined (type reflect.Type has no field or method IsVariadic)
    /usr/local/go/src/text/template/exec.go:679:18: typ.NumIn undefined (type reflect.Type has no field or method NumIn)
    /usr/local/go/src/text/template/exec.go:681:79: typ.NumIn undefined (type reflect.Type has no field or method NumIn)
    /usr/local/go/src/text/template/exec.go:683:25: typ.NumIn undefined (type reflect.Type has no field or method NumIn)
    /usr/local/go/src/text/template/exec.go:684:69: typ.NumIn undefined (type reflect.Type has no field or method NumIn)
    /usr/local/go/src/text/template/exec.go:688:71: typ.NumOut undefined (type reflect.Type has no field or method NumOut)
    /usr/local/go/src/text/template/exec.go:695:32: typ.In undefined (type reflect.Type has no field or method In)
    /usr/local/go/src/text/template/exec.go:698:9: typ.IsVariadic undefined (type reflect.Type has no field or method IsVariadic)
    /usr/local/go/src/text/template/exec.go:699:18: typ.In undefined (type reflect.Type has no field or method In)
    [...more lines following...]






## text/template/parse



The compiler gave the following error when running the tests for this package:


    # text/template/parse [text/template/parse.test]
    /usr/local/go/src/text/template/parse/parse_test.go:489:5: t.Run undefined (type *testing.T has no field or method Run)
    /usr/local/go/src/text/template/parse/parse_test.go:564:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)
    /usr/local/go/src/text/template/parse/parse_test.go:565:4: b.ReportAllocs undefined (type *testing.B has no field or method ReportAllocs)
    /usr/local/go/src/text/template/parse/parse_test.go:597:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)
    /usr/local/go/src/text/template/parse/parse_test.go:598:4: b.ReportAllocs undefined (type *testing.B has no field or method ReportAllocs)






## time



The compiler gave the following error when running the tests for this package:


    # encoding/gob
    /usr/local/go/src/encoding/gob/decode.go:562:21: MakeMapWithSize not declared by package reflect
    /usr/local/go/src/encoding/gob/decode.go:948:22: PtrTo not declared by package reflect
    /usr/local/go/src/encoding/gob/decode.go:1118:30: srt.FieldByName undefined (type reflect.Type has no field or method FieldByName)
    /usr/local/go/src/encoding/gob/encode.go:603:16: PtrTo not declared by package reflect
    /usr/local/go/src/encoding/gob/encode.go:643:70: f.Index undefined (type reflect.StructField has no field or method Index)
    /usr/local/go/src/encoding/gob/type.go:119:12: cannot convert nil (untyped nil value) to reflect.Type
    /usr/local/go/src/encoding/gob/type.go:142:14: PtrTo not declared by package reflect
    /usr/local/go/src/encoding/gob/type.go:867:9: rt.PkgPath undefined (type reflect.Type has no field or method PkgPath)
    /usr/local/go/src/encoding/gob/type.go:870:21: rt.PkgPath undefined (type reflect.Type has no field or method PkgPath)






## unicode



The compiler gave the following error when running the tests for this package:


    # unicode_test [unicode.test]
    /usr/local/go/src/unicode/letter_test.go:487:23: Benchmark not declared by package testing
    /usr/local/go/src/unicode/letter_test.go:488:23: Benchmark not declared by package testing






## unicode/utf16



The compiler gave the following error when running the tests for this package:


    # unicode/utf16_test [unicode/utf16.test]
    /usr/local/go/src/unicode/utf16/utf16_test.go:174:4: b.ResetTimer undefined (type *testing.B has no field or method ResetTimer)






## unicode/utf8



The compiler gave the following error when running the tests for this package:


    === RUN   TestConstants
    --- PASS: TestConstants
    
    === RUN   TestFullRune
    --- PASS: TestFullRune
    
    === RUN   TestEncodeRune
    --- PASS: TestEncodeRune
    
    === RUN   TestDecodeRune
    --- PASS: TestDecodeRune
    
    === RUN   TestDecodeSurrogateRune
    --- PASS: TestDecodeSurrogateRune
    
    [...more lines following...]






## unsafe



The compiler gave the following error when running the tests for this package:


    error: function main is undeclared in the main package





