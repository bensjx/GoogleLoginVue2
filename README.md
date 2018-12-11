Demo: https://bensjx.github.io/GoogleLoginVue2

## How to use:

1. Go to firebase console, under develop -> authentication -> sign-in methods, enable google login.
2. Under the google login portion, go to Web Client ID. This is your clientID.
3. In index.html, change clientID to your OWN clientID.
4. You have to authorize your webpage to sign in via google. Under the google login portion in step 2, under Authorized Domain, key in the url of your web page you are trying to authorize.

## Note:

You MIGHT not be able to run this in codesandbox as you will receive a 'popup-closed-by user
error'. However if you refresh or use a new browser or clear your cache it might work again.<br>
Solution: Finish your code, commit to github, and run your web page using github hosted pages.
It should work from there.<br>
Also, if you are trying to authorize colab notebooks, click the sign in button and let it auto close, then press ctrl+shift+i (windows) for developer console and look at the console for error message. The link for your colab notebook should be there. It should look like this: "504ykn78cvs-colab.googleusercontent.com".

## Reference:

Type of data you can get from google login (e.g. email, name, id, family name) and might want to display:https://firebase.google.com/docs/reference/js/firebase.User<br>
Code obtained from: https://firebase.google.com/docs/auth/web/google-signin<br>
