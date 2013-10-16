ABAP-TO-GOOGLE
==============

Access and update Google data (with Authentication) using ABAP

By Chris Twirbutt
ctwirbutt@comcast.net

Purpose:
To demonstrate how to:

1) Authenticate with Google using a Refresh Token to Obtain an Access Token, and then

2) Create an ABAP function module that uses Access Tokens to do CRUD (Create, Read, Update, Delete) with Google (sql to Fusion Tables).

PreRequisites:

1) Set up a Google Account for your organization,

      1.1 Create a Fusion Table under this account
  
2) Enable your API access on Google's API Console

3) Use OAuth2.0 Google Playground to obtain a Refresh token


The following is a GREAT Video produced by my colleague Forrest Horner on the overall process including setting up the 3 PreRequisite Steps above:
http://youtu.be/uDgTxiR00cY


Please see my NUGG (SAPLink Nugget) file for the source code of both Function Modules.

For those who do not know how to open SAPLink Nugget files here is a good link for information, download, etc.. :
http://wiki.scn.sap.com/wiki/display/ABAP/SAPlink


