```bash
mvn jasypt:encrypt-value '-Djasypt.encryptor.algorithm="PBEWITHHMACSHA512ANDAES_256"' '-Djasypt.encryptor.password="the password"' '-Djasypt.plugin.value="theValueYouWantToEncrypt"'

java -cp E:\repo\org\jasypt\jasypt\1.9.3\jasypt-1.9.3.jar org.jasypt.intf.cli.JasyptPBEStringEncryptionCLI password="ADUMDFUOV7834*" algorithm=PBEWithMD5AndDES input=root
```
