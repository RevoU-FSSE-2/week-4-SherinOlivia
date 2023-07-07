
# Week 4 Assignment Overview

For this week's assignment, the main focus are :

1. Familiarity with Git and Github
- Creating branches
- Committing changes
- Pull request
- Pull request review and merge code
2. Custom Domain and DNS Configuration
- Purchasing custom domain from domestic registrar "Niagahoster"
- Connecting and Managing custom domain with "Cloudfare"
- Deploying site through "Netlify" and connecting custom domain with Netlify's subdomain
3. Technical Writing
- Proficiency in 'Technical Writing' to create clear and concise documentation.

## Website Development Overview
<p align="center">
<a href="https://roozonev2.netlify.app/">roozonev2.netlify.app</a>
|
<a href="https://roozone.site/">roozone.site</a>
|
<a href="https://www.roozone.site/">www.roozone.site</a>
</p>

In regard to the first focus point of the assignment, I used internal terminal of VSCode to create the branches and committing changes, and Github to make pull requests and merging the codes. For this simple personal website, I created 3 branches and 6 pull requests. 

- Creating a new  branch and switching to the new branch:
<img src="https://raw.githubusercontent.com/RevoU-FSSE-2/week-4-SherinOlivia/main/assets/documentation/Creating%20and%20Switching%20to%20Git%20Branch.webp" alt="creating branches through VSCode internal terminal">

- Committing changes and pushing to the new branch:
<img src="https://raw.githubusercontent.com/RevoU-FSSE-2/week-4-SherinOlivia/main/assets/documentation/Git%20Push%20to%20Git%20Branch.webp" alt="committing changes and pushing to the new branch through VSCode internal terminal">

- Pull Request
<img src="https://raw.githubusercontent.com/RevoU-FSSE-2/week-4-SherinOlivia/main/assets/documentation/Pull%20Request%20Review.webp" alt="Making pull request to merge codes from branch to main">

- Pull Request Review & Merge code
<img src="https://raw.githubusercontent.com/RevoU-FSSE-2/week-4-SherinOlivia/main/assets/documentation/Pull%20Request.webp" alt="Pull Request review">

- Succesfull Pull Request
<img src="https://raw.githubusercontent.com/RevoU-FSSE-2/week-4-SherinOlivia/main/assets/documentation/Successful%20Pull%20Request.webp" alt="an example of a succesful pull request">

<strong>Simple Website features:</strong>
- functional navigation bar 
- Responsive layout
- Custom font
- Actual data for :
    - Resume (Education & Experience Information)
    - Portfolio (Results from Hobbies and RevoU's Past Assignments)
    - Contact Information
- Semantic tags for Accessibility
- Javascript filter (used tutorial to learn this)

<strong>Future updates may include (tried topics):</strong>
- Gallery Carousel
- Animation & Transition
- Grid layout
- Hamburger button with side bar
- Image filters
- Dark & light mode


## Pagespeed Analysis Result

<img src="https://raw.githubusercontent.com/RevoU-FSSE-2/week-4-SherinOlivia/main/assets/documentation/Pagespeedanalysis.webp" alt="Pagespeed Analysis Result">

## Purchasing Custom Domain

To purchase a custom domain, we either need a :

- internationally accepted credit card for international domain registrar

or

- m-banking / qris / e-wallet / physical-visit to any partner convenience store for domestic domain registrar.

In this particular tutorial, we are opting for domestic domain registrar, 'Niagahoster'.

1. First, go to <a href="https://www.niagahoster.co.id/"> www.niagahoster.co.id</a>
2. Sign up or login through Facebook or Google account.
<img src="https://raw.githubusercontent.com/RevoU-FSSE-2/week-4-SherinOlivia/main/assets/documentation/niagahosterloginorsignup.webp" alt="sign up or login through Facebook or Google account" />

3. Check the availability of any domain name of your liking.
<img src="https://raw.githubusercontent.com/RevoU-FSSE-2/week-4-SherinOlivia/main/assets/documentation/checkdomainname.webp" alt="domain name checking process" />

4. Purchase the custom domain and pay using your preferred payment method.
<img src="https://raw.githubusercontent.com/RevoU-FSSE-2/week-4-SherinOlivia/main/assets/documentation/niagahosterpaymentmethod.webp" alt="purchasing custom domain" />

5. Wait for the transaction to finish

## Pre-Web Deployment and DNS Configuration

For the deployment process, we will be using Netlify to host our website and Cloudfare to manage the domain because of the SSL/TLS protection provided for free by Cloudfare.

Before we deploy the website through Netlify, we will have to configure some settings in Cloudfare. 

To do that,

1. First, we go to <a href="https://www.cloudflare.com/"> www.cloudfare.com</a>
2. Sign up with your email and verify the account through your email
<img src="https://raw.githubusercontent.com/RevoU-FSSE-2/week-4-SherinOlivia/main/assets/documentation/loginorsignupcloudfare.webp" alt="Cloudfare Sign Up menu" />

3. On the home page, click 'Add a Site' and enter your 'Custom Domain
<img src="https://raw.githubusercontent.com/RevoU-FSSE-2/week-4-SherinOlivia/main/assets/documentation/cloudfareaddsite.webp" alt="add a site on home page of Cloudfare" />

4. Click 'Add Site' to confirm
<img src="https://raw.githubusercontent.com/RevoU-FSSE-2/week-4-SherinOlivia/main/assets/documentation/addsiteconfirmationcloudfare.webp" alt="add site confirmation" />

5. From the subscription plans shown, choose Free Plan option
<img src="https://raw.githubusercontent.com/RevoU-FSSE-2/week-4-SherinOlivia/main/assets/documentation/cloudfarefreeplan.webp" alt="free plan from Cloudfare" />

6. Copy the Nameserver shown (We will use them to change the Nameserver in Niagahoster)
<img src="https://raw.githubusercontent.com/RevoU-FSSE-2/week-4-SherinOlivia/main/assets/documentation/cloudfarenameserver.webp" alt="Cloudfare's nameservers" />

7. Go to <a href="https://client.niagahoster.co.id/">www.client.niagahoster.co.id</a> and click on your Custom Domain

8. On the Nameserver setting (or in 'Overview Domain'), click change nameserver and paste both nameservers from Cloudfare.
<img src="https://raw.githubusercontent.com/RevoU-FSSE-2/week-4-SherinOlivia/main/assets/documentation/verifyemailandchangenameserver.webp" alt="change Niagahoster Nameserver with Cloudfare's" />

9. Wait for Cloudfare to verify this process, you will get an email from Cloudfare when your custom domain is successfully activated on Cloudfare's free plan.
<img src="https://raw.githubusercontent.com/RevoU-FSSE-2/week-4-SherinOlivia/main/assets/documentation/cloudfareemail.webp" alt="Custom domain active notification by email from Cloudfare" />

## Web Deployment

Now that our custom domain is active, we can go ahead and deploy our website through Netlify.

1. Go to <a href="https://app.netlify.com/">app.netlify.com</a>.
2. Sign up using your preferred account or email, but in this tutorial, We will be using 'Sign Up with Github' method.
3. Fill out the short survey and set your team's name
4. Click 'Add new site' and choose 'Import an existing project'
<img src="https://raw.githubusercontent.com/RevoU-FSSE-2/week-4-SherinOlivia/main/assets/documentation/netlifyimportproject.webp" alt="add new site on Netlify" />

5. Choose 'Deploy with Github', on your first time, you will be directed to login to your Github account to authorize the connection
<img src="https://raw.githubusercontent.com/RevoU-FSSE-2/week-4-SherinOlivia/main/assets/documentation/deploywithgithub.webp" alt="Deploy with Github" />

6. Look for the repository of your website. 
<img src="https://raw.githubusercontent.com/RevoU-FSSE-2/week-4-SherinOlivia/main/assets/documentation/chooserepotodeploy.webp" alt="choosing repository to deploy" />

7. Scroll down and click on 'Deploy (repository name)'
<img src="https://raw.githubusercontent.com/RevoU-FSSE-2/week-4-SherinOlivia/main/assets/documentation/deploysite.webp" alt="deploy repository confirmation" />

8. Wait for your website to get deployed (Usually almost instantly)
9. When your website is successfully deployed, you will get a randomly named website with 'netlify.app' subdomain. 
<img src="https://raw.githubusercontent.com/RevoU-FSSE-2/week-4-SherinOlivia/main/assets/documentation/netlifyrandomnamesite.webp" alt="netlify's randomly-named site" />
10. Click 'Site configuration' -> 'Change site name' to change the website's name.
<img src="https://raw.githubusercontent.com/RevoU-FSSE-2/week-4-SherinOlivia/main/assets/documentation/changesitenamenetlify.webp" alt="changing site name" />


<p>We're 75% there! Now we need to configure the setting so our custom domain will link to our deployed website.<p>

11. Now, click on 'Domain settings' -> 'Add a domain'. 
<img src="https://raw.githubusercontent.com/RevoU-FSSE-2/week-4-SherinOlivia/main/assets/documentation/addcustomdomainnetlify.webp" alt="domain setting in netlify to add custom domain"/>
12. Insert your custom domain and click on 'verify'
<img src="https://raw.githubusercontent.com/RevoU-FSSE-2/week-4-SherinOlivia/main/assets/documentation/addcustomdomain_2_.webp" alt="insert custom domain to domain setting"/>
<img src="https://raw.githubusercontent.com/RevoU-FSSE-2/week-4-SherinOlivia/main/assets/documentation/addcustomdomain_3_.webp" alt="adding custom domain to netlify" />
13. Next, go back to Cloudfare and click on your custom domain.

14. Click on 'DNS' setting on the left side-bar or under Quick Action on the right side.
<img src="https://raw.githubusercontent.com/RevoU-FSSE-2/week-4-SherinOlivia/main/assets/documentation/wheretofinddnssetting.webp" alt="Where to find DNS Setting" />
15. Click on 'Add record', and insert these:
- Type: CNAME, Name: www, Content: (your custom domain i.e roozone.site)
- Type: CNAME, Name: (your custom domain i.e roozone.site), Content: (your netlify website link i.e roozonev2.netlify.app)
<img src="https://raw.githubusercontent.com/RevoU-FSSE-2/week-4-SherinOlivia/main/assets/documentation/dnsrecordmanagement.webp" alt="DNS Record management" />

<p align="center"><strong>Now We are done! Happy Testing!</strong><p>

<img src="https://raw.githubusercontent.com/RevoU-FSSE-2/week-4-SherinOlivia/main/assets/documentation/successfulcustomdomain.webp" alt="succesfully configured custom domain to netlify site" />

### Contact Me:

<img src="https://raw.githubusercontent.com/RevoU-FSSE-2/week-4-SherinOlivia/ec070b5a2e4e0ad121706596ada521e0e856af7b/assets/icons/email.svg" alt="gmail"/> SOChronicle@gmail.com (personal)

<img src="https://raw.githubusercontent.com/RevoU-FSSE-2/week-4-SherinOlivia/ec070b5a2e4e0ad121706596ada521e0e856af7b/assets/icons/email.svg" alt="gmail"/> SOlivia198@gmail.com (work)

<a href="https://discord.com/users/shxdxr#7539" target="_blank"><img src="https://raw.githubusercontent.com/RevoU-FSSE-2/week-4-SherinOlivia/ec070b5a2e4e0ad121706596ada521e0e856af7b/assets/icons/discord.svg" class="discordLogo" alt="discord"/></a>&ensp;<a href="https://instagram.com/shxdxr?igshid=MzRlODBiNWFlZA==" target="_blank"><img src="https://raw.githubusercontent.com/RevoU-FSSE-2/week-4-SherinOlivia/ec070b5a2e4e0ad121706596ada521e0e856af7b/assets/icons/instagram.svg" class="instagramLogo" alt="instagram"/></a>&ensp;<a href="https://www.linkedin.com/in/sherin-olivia-07311127a/" target="_blank"><img src="https://raw.githubusercontent.com/RevoU-FSSE-2/week-4-SherinOlivia/ec070b5a2e4e0ad121706596ada521e0e856af7b/assets/icons/linkedin.svg" class="linkedLogo" alt="linkedin"/></a>
