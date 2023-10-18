# SupaLogin Chrome Extension
![image](https://github.com/OrangeDev2/SupaLogin-Chrome-Extension/assets/47803678/4762b2d1-53b6-4d98-90c3-8d4c42c6b72b)

## Unpacking Your Extension
1. Fork this repository.
2. Go to `chrome://extensions/`.
3. Click "Load Unpacked" and select your repo directory.
4. The extension should show up.
   
![image](https://github.com/OrangeDev2/SupaLogin-Chrome-Extension/assets/47803678/ac4bbbf4-698c-46df-8e73-6ca5d4b63632)

## Retrieving Your Google Credentials
1. Go to [Google Cloud Console](https://console.cloud.google.com/) and create a project.
2. Search for "APIs & Services" > "Credentials".
3. You must create your Consent Screen before creating Credentials for your Supabase Project.
4. Under "External", fill in App Information (App Name, Dev Email, Support Email should be sufficient) and select Scopes (3).

![image](https://github.com/OrangeDev2/SupaLogin-Chrome-Extension/assets/47803678/1bd278bd-6116-4873-a5eb-db3c0839ca6a)

5. Now you can create Credentials > OAuth Client ID
6. Select "Application Type" > "Web Application" to generate your Client ID and Client Secret.
    
![image](https://github.com/OrangeDev2/SupaLogin-Chrome-Extension/assets/47803678/8a35750b-e460-443f-b510-c753bea13ce8)

## Create a Supabase Project and Set Up Auth Flow
1. Go to [Supabase](https://supabase.com/) and create your project.
2. Hover and click the "Authentication" tab > "Providers" tab. Click on "Google Provider".
   
![image](https://github.com/OrangeDev2/SupaLogin-Chrome-Extension/assets/47803678/baf2aaba-f06e-4e73-93d5-7579fd12c379)

3. Fill in Client ID and Client Secret from your Google Cloud Console.
4. Save!

<!--
## Editing Chrome Extension (Manifest.json, supaLogin.js)
1. In `Manifest.json`, fill in the Authorized Client ID from your Supabase Project (where you filled it in) or Google Cloud Console.
   
![image](https://github.com/OrangeDev2/SupaLogin-Chrome-Extension/assets/47803678/050c852a-6256-4f61-8be4-ae60613a152d)

2. In `supaLogin.js`, fill in the Supabase URL and Anon Key from your Supabase Settings > API.
-->

![image](https://github.com/OrangeDev2/SupaLogin-Chrome-Extension/assets/47803678/b67c5ae6-eaa0-45d9-b96e-62835c61753e)

## Updating the Extension and Testing Supabase Social Login
1. Click the refresh logo to update your extension with the filled information.
   
![image](https://github.com/OrangeDev2/SupaLogin-Chrome-Extension/assets/47803678/ca180aaf-076d-415d-9725-c3c6665a47a2)

2. Click the "Login with Supabase" button.
   
![image](https://github.com/OrangeDev2/SupaLogin-Chrome-Extension/assets/47803678/ac4bbbf4-698c-46df-8e73-6ca5d4b63632)


Links: 
- [Supabase](https://supabase.com/)
- [Supabase Chrome Extension Documentation](https://supabase.com/docs/guides/auth/social-login/auth-google?platform=chrome-extensions)
- [Google Cloud Console](https://console.cloud.google.com/)
