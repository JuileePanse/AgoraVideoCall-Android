# Open Video Call for Android Using Agora.io

The Open Video Call for Android Sample App is an open-source demo that will help you get video chat integrated directly into your Android applications using the Agora Video SDK.

# Obtain an App ID

To build and run the sample application, get an App ID:
1. Create a developer account at [agora.io](https://dashboard.agora.io/signin/). Once you finish the signup process, you will be redirected to the Dashboard.
2. Navigate in the Dashboard tree on the left to **Projects** > **Project List**.
3. Save the **App ID** from the Dashboard for later use.
4. Generate a temp **Access Token** (valid for 24 hours) from dashboard page with given channel name, save for later use.

5. Update "app/src/main/res/values/strings_config.xml" with your App ID and Token.
```
<string name="private_app_id"><#YOUR APP ID#></string>
<!-- Please leave it if not enable App Certificate -->
<!-- You can generate a temporary token at https://dashboard.agora.io/projects -->
<string name="agora_access_token"><#YOUR TOKEN#></string>
```

### Run the Application

Open project with Android Studio, connect your Android device, build and run.
      
Or use `Gradle` to build and run.
