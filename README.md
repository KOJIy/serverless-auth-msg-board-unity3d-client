# serverless-auth-msg-board-unity3d-client


---

<div align=center>Work In Progress!</div>

---

### Description
Unity 3D example code for connecting to a credentials authenticated AWS Api Gateway endpoint.
The example uses Facebook as an AWS Cognito Federated Identity Provider and how to use Signature V4 to sign the request. To demonstrate this an abstract simple message board was implemented (See [serverless-auth-msg-board](https://github.com/guywald/serverless-auth-msg-board) project)

The signature process is based on [Examples of Signature Calculations Using C# (AWS Signature Version 4)](http://docs.aws.amazon.com/AmazonS3/latest/API/sig-v4-examples-using-sdks.html#sig-v4-examples-using-sdk-dotnet) docs but was changed to fit Unity 3D.

<b>Important Note:</b> Server backend must be set first, please see [serverless-auth-msg-board](https://github.com/guywald/serverless-auth-msg-board) project for more details.

##### Additional libraries and assets needed:

 * [AWS Mobile SDK for Unity](http://docs.aws.amazon.com/mobile/sdkforunity/developerguide/) - Install the Cognito Identity  Package
 * [Facebook SDK for Unity](https://developers.facebook.com/docs/unity/)
 * [Text Mesh Pro](https://www.assetstore.unity3d.com/en/#!/content/84126) (Free) - For displaying a log

Work In Progress:

Currently only the POST method of creating a message works. The REST of the examples (pun intended) will be available soon.

