[Home](Home.md)

##public static string GetDomainFromUserAccount(string userAccount)
This function parses the domain out of an user-account.  

parameter: a user account has following format: DOMAIN\UserName.  
returns: the domain of an user account.

e.g.  
var domainName = AdSearch.GetDomainFromUserAccount(@"PPWDEV\jjanssenss");  
Console.WriteLine(domainName);  
=> PPWDEV

##public static string GetAccountNameFromUserAccount(string userAccount)
This function parses the UserName out of an user account.  

parameter: a user account with the following format: DOMAIN\UserName.  
returns: the user name for the given account.  

e.g.  
var userName = AdSearch.GetAccountNameFromUserAccount(@"PPWDEV\jjanssenss");  
Console.WriteLine(userName);    
=> jjanssens


##public IEnumerable<string> AvailableProperties(string userAccount)
List all available properties of an SAM Account.  

parameter: a user account with the following format: DOMAIN\UserName.  
returns: a list with all available properties on the given account.

##public ResultPropertyValueCollection GetProperty(string userAccount, string propertyName)
Gets the value for a specified property name of a SAM account. 
 
parameters:  
- userAccount: a user account with the following format: DOMAIN\UserName.  
- propertyName: a valid property name.   
returns: the value for the given property belonging to the given userAccount.

##public bool UserExists(string userAccount)
Checks whether a given user exists.  

parameter: a user account with the following format: DOMAIN\UserName.  
returns: a boolean indication whether the given userAccount exists.

##public string FindName(string userAccount)
Gets the display name property of a SAM-account. 
   
parameter: a user account with the following format: DOMAIN\UserName.  
returns: the display name for the given userAccount.

##public string FindEmail(string userAccount)
Gets the email address of a SAM-account. 
 
parameter: a user account with the following format: DOMAIN\UserName.  
returns:the email address for the given userAccount.

