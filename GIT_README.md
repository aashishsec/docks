# GITHUB Dorks for Bug Bounty

A list of GitHub Dorks for Bug Bounty, Web Application Security, and Pentesting.

---

### GitHub Dorks for Finding Files

> filename:manifest.xml "example.com"

> filename:travis.yml  "example.com"

> filename:vim_settings.xml "example.com"

> filename:database "example.com"

> filename:prod.exs NOT prod.secret.exs "example.com"

> filename:prod.secret.exs "example.com"

> filename:.npmrc _auth "example.com"

> filename:.dockercfg auth "example.com"

> filename:WebServers.xml "example.com"

> filename:.bash_history  "example.com"

> filename:sftp-config.json "example.com"

> filename:sftp.json path:.vscode  "example.com"

> filename:secrets.yml password  "example.com"

> filename:.esmtprc password  "example.com"

> filename:passwd path:etc "example.com"

> filename:dbeaver-data-sources.xml  "example.com"

> path:sites databases password  "example.com"

> filename:config.php dbpasswd  "example.com"

> filename:prod.secret.exs  "example.com"

> filename:configuration.php JConfig password "example.com"

> filename:.sh_history  "example.com"

> shodan_api_key language:python "example.com"

> filename:shadow path:etc "example.com"

> JEKYLL_GITHUB_TOKEN "example.com"

> filename:proftpdpasswd "example.com"

> filename:.pgpass "example.com"

> filename:idea14.key "example.com"

> filename:hub oauth_token "example.com"

> HEROKU_API_KEY language:json "example.com"

> HEROKU_API_KEY language:shell "example.com"

> SF_USERNAME salesforce "example.com"

> filename:.bash_profile aws "example.com"

> extension:json api.forecast.io "example.com"

> filename:.env MAIL_HOST=smtp.gmail.com "example.com"

> filename:wp-config.php "example.com"

> extension:sql mysql dump "example.com"

> filename:credentials aws_access_key_id "example.com"

> filename:id_rsa or filename:id_dsa "example.com"

### GitHub Dorks for Finding Languages

> language:python username  "example.com"

> language:php username  "example.com"

> language:sql username "example.com"

> language:html password "example.com"

> language:perl password "example.com"

> language:shell username "example.com"

> language:java api "example.com"

> HOMEBREW_GITHUB_API_TOKEN language:shell "example.com"

### GiHub Dorks for Finding API Keys, Tokens and Passwords

> api_key  "example.com"

> “api keys” "example.com"

> authorization_bearer: "example.com"

> oauth "example.com"

> auth "example.com"

> authentication "example.com"

> client_secret "example.com"

> api_token: "example.com"

> “api token” "example.com"

> client_id "example.com"

> password "example.com"

> user_password "example.com"

> user_pass "example.com"

> passcode "example.com"

> client_secret "example.com"

> secret "example.com"

> password hash "example.com"

> OTP "example.com"

> user auth "example.com"

### GitHub Dorks for Finding Usernames


> user:name (user:admin) 

> org:name (org:google type:users)

> in:login (<username> in:login)

> in:name (<username> in:name)

> fullname:firstname lastname (fullname:<name> <surname>)

> in:email (data in:email)

### GitHub Dorks for Finding Information using Dates

> created:<2012–04–05 "example.com"

> created:>=2011–06–12 "example.com"

> created:2016–02–07 location:iceland  "example.com"

> created:2011–04–06..2013–01–14 <user> in:username "example.com"

### GitHub Dorks for Finding Information using Extension


> extension:pem private "example.com"

> extension:ppk private "example.com"

> extension:sql mysql dump "example.com"

> extension:sql mysql dump password "example.com"

> extension:json api.forecast.io "example.com"

> extension:json mongolab.com "example.com"

> extension:yaml mongolab.com "example.com"

> [WFClient] Password= extension:ica "example.com"

> extension:avastlic “support.avast.com” "example.com"

> extension:json googleusercontent client_secret "example.com"
