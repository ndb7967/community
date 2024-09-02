이후에 README.md 파일을 생성하여 다음과 같이 작성합니다.
기본적으로 README는 프로젝트를 동작시키기 위한 적절한 방법을 알려주도록 작성합니다.
그래서 설명 문서를 작성하듯이 README 파일을 작성해야 합니다.

#### Prepare the Source Codes

<pre>
git clone https://github.com/ndb7967/community
</pre>

#### Prepare the Configuration File

* Prepare the <code>config.json</code> file.
<pre>
{
    "db_string": {MongoDB Database String},
    "jwt_key": {JWT Secret Key}
}
</pre>

#### Install and Start the Server Application

<pre>
cd backend
yarn install
nodemon index.js
</pre>

#### Install and Start the Client Application

<pre>
cd frontend
yarn install
yarn start
</pre>

#### Usage

* Connect the website <code>http://localhost:3000/</code>.
