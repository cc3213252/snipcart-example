## 【ok】Error building site: open /opt/build/repo/content: no such file or directory

forestry中没有创建具体product的数据导致  

## 【ok】Failed to get JSON resource "ENDPOINT_URL": unexpected end of JSON input

教程中forestry创建section时，命名为Products, P是大写，而layout中index.html中的products是小写就会报错
不对，应该是中间有注释导致的  

## 【ok】Mixed Content: The page at 'https://dazzling-booth-e373b0.netlify.app/' was loaded over HTTPS, but requested an insecure stylesheet 'http://example.org/scss/main.min.f8990f1bc90c6d252db0b9fe5514ea7d7c910ae252c6625af671567e8155b376.css'. This request has been blocked; the content must be served over HTTPS.

config.toml中baseURL的缘故

## jquery.min.js:4 GET https://app.snipcart.com/api/sessions 401

https://app.snipcart.com/dashboard/account/credentials