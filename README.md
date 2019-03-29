
Cipher: AES/256/CBC/PKCS5Padding with random generated salt


### Usage

```go
import "github.com/johnjjung/go-aes256"

// encryption
aes256.Encrypt("TEXT", "PASSWORD")

// decryption
aes256.Decrypt("ENCRYPTED", "PASSWORD")
```

