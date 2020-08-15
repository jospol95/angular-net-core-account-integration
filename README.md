# angular-net-core-account-integration

Sample project for an Account-integration feature with Angular 9, .NET Core 3.1, OAuth2 and PostgreeSQL.



This app consists in an .NET Core Authentication API.
Users can authenticate using your Auth API, or Google and Facebook APIs (OAuth2). Once registered, we'll provide them the option to link their accounts.

When users register/login the first time the first time, a record is created in the DB. 
Users can't use the same email with another authentication method once they are registered, unless their accounts are linked. 


Once their accounts are integrated/linked, they can choose whatever method authentication they want at the login-page, and the Authentication API should be able to recognize that specific user.
