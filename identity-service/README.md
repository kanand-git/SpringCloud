https://seanwasere.com/generate-random-hex/
https://jwt.io/


http://localhost:9000/auth/register
---------------------------------------
{
"name":"pintu",
"email":"np@gmail.com",
"password":"pwd"
}

http://localhost:9000/auth/token
----------------------------------
{
"username":"pintu",
"password":"pwd"
}

Validate token via API Gateway
----------------------------------
http://localhost:9000/auth/validate?token=eyJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJwaW50dSIsImlhdCI6MTY4NzMyNTQxMCwiZXhwIjoxNjg3MzI3MjEwfQ.zTmU_KrEXbdjd6yOWetiYvjkgH6L4QVTW0Oiddtt_aA

Calling Validate token directly will not work need to pass bearer token
-----------------------------------------------------------------------

http://localhost:8765/auth/validate?token=eyJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJwaW50dSIsImlhdCI6MTY5MDg2MzM4MywiZXhwIjoxNjkwODY1MTgzfQ.fP7ZRzxIfFCjMpMhjXkIyoZGkEKdUnFSoZC9Cp4ZtJk

