Deploying an application to Elastic Beanstalk was pretty tricky for me at first. It's pretty simple but somehow I messed it up so many times. Here is a guide to get you started so you don't make the same mistakes I did. 

## First things first

1. clone or download this repo [https://github.com/ikey2244/apollo-server-elastic-beanstalk.git](https://github.com/ikey2244/apollo-server-elastic-beanstalk.git)
2. navigate to wherever you downloaded it
3. click on the apollo-server-elastic-beanstalk folder
4. highlight everything, right click and create a zip called application.zip
5. we will be using this zip later so just hang on to it for now

![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/d1u3ler75cnz90g4haqx.gif)

## Getting Started with Elastic Beanstalk

Sign into your AWS console [https://aws.amazon.com/](https://aws.amazon.com/). Or go to [https://portal.aws.amazon.com/billing/signup#/start](https://portal.aws.amazon.com/billing/signup#/start) if you haven't made an account

**dislaimer: AWS makes you put in a credit card in order to make an account. It's free but you have to monitor your usage. It's very easy to wrack up charges.*

Once you've signed in or created your account you will be greeted with this page. Go ahead and search for Elastic Beanstalk. Click the "Elastic Beanstalk" from the suggestions list

![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/ri8idymlymo3mumfyc94.png)

Click the blue "Get Started" button

![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/y81g6zwqvzee0pkiouir.png)

This is where we will configure our Elastic Beanstalk environment and application.

![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/x1gv9raed1hg664yynwa.png)

Go ahead and do the following:
1. **Application name**: apollo-server
2. **Platform**: Node.js
3. **Upload your code: click "upload" button**
a window will pop up that looks like this:

![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/xkyf090n95o2n1b4yyhn.png)

4. Choose the zip file called application.zip that we created earlier
5. Click "Upload" button
6. Finally click the "Create Application" button

After following those steps you should see something like this:

![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/r0vc5o2vdacwmquorpmt.png)

Now we wait...

## Finishing up

If followed each step correctly you should see something like this. Success!

![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/2qvf99uyow026n5mjvym.png)

Click on the URL that was generated at the top and see your new application in all of its glory!

![Alt Text](https://thepracticaldev.s3.amazonaws.com/i/hmysdb2bascoll13k72i.png)

This is a pretty simple setup. Stay tuned for a more complicated example. :)
