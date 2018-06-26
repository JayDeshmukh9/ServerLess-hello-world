* npm install -g serverless
* sls / serverless <-- command for execution 
* sls -v <-- Check version 
* cofig env with AWS credentials 
* ---sign up for aws and get key and secret
* ---$ sls config credentials --provider aws --key (key) --secret (SECRET)
* Create a basic boiler plate
* ---$ sls create --template hello-world --path hello-world
* change to hello-world directory 
* --- ls
* -------handler.js (Contains Functions )
* -------serverless.yml (Contains our sLss config for the proj helps you describe your infra as code)
* Deploy 
* ---sls deploy
* -----get endpoint from CTI ===>(https://pm5d8gdwjh.execute-api.us-east-1.amazonaws.com/dev/hello-world)
