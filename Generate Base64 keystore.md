### Generate JKS in Base64 format

Input: `android.jks`

Output: `Android.jks.base64.txt`

Command:

`openssl base64 < android.jks | tr -d '\n' | tee Android.jks.base64.txt`
