# IOS8AdvancedMobileAccess
Advanced Mobile Access gives your mobile application key security and monitoring functionality. You can configure client authentication and identity providers. You can also add monitoring function to your app that enables both client logging and usage statistics. 

    Create a mobile application, download the SDK and set up your development environment. For more information, see Getting started.
    Configure security.
    Configure app monitoring.

Client-side development
IBM® MobileFirst provides the following security capabilities on the client side:

    Register your client app, so that your client is recognized and authentication requests are handled.
    Issue standard requests to resources using IMFResourceRequest methods.
    Intercept requests sent to protected resources and adds the authorization header to outbound requests using IMFURLProtocol.

Authentication mechanisms

By default, no authentication is required when registering apps with IBM MobileFirst server. If you wish to add authenticate to your app, IBM MobileFirst server provides three mechanisms as identity providers: Facebook, Google, and custom. If you choose none of these options, the default authentication is applied and the app user is treated as 'anonymous'. The 'anonymous' option lets you register your app and work, without configuring any additional authentication mechanism.

    For more on the default ('anonymous') mechanism, see Registering your Advanced Mobile Access client app.
    For instructions on using Facebook and Google as identity providers, see Facebook or Google.
    For guidelines on integrating your own custom authentication mechanism with IBM MobileFirst server, see Using a custom identity provider.

Support for Apple Touch ID

Access tokens that are issued by IBM MobileFirst server can be secured on a device using the Apple Touch ID API. Learn more...
Server-side integration
You can protect and enable authorized access to your Node.js apps by integrating with two npm modules that are implemented in IBM MobileFirst:

    The passport-imf-token-validation module provides validation strategies for protecting your node apps.
    The imf-oauth-user-sdk module lets you get authorization from the IBM MobileFirst server for node apps.


