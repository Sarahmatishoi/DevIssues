<h3>1. Duplication on the recent activites</h3>

<p>Implimented filters on the backend to make sure duplicated fields are not returned</p>

<h3>2. Tokens</h3>

<h3>3. Smile id intergration</h3>

<p> This is to help us to confirm the true identity of the real time service providers that uses our app </p>

<h3> Tasks on smile id</h3>

<h3>1. Mobile side </h3>

<p> i. Added Mavern Central Repo to project level build.gradle  </p>

<p> ii. Added the Smile Identity Class Path in the project level build.gradle</p>

<p>iii. Applied the Smile ID Plugin in the module level build.gradle </p>

<p>iv. Added the Smile ID SDK as a dependency</p>

<p>v. Allowed the required permission and added Smile UI Activities to the application manifest</p>

<h3>2. Server side </h3>

<p> i. Generated a unique signature and timestamp for every job to be runned</p>

<p> ii. Created the callback endpoint that will allow us to make a job request and receive all results without polling.</p>

<p> Created a way of getting the user selfie profile and the national id for the service providers</p>

<h3>4. Mixpanel</h3>

<p> This is to help analyze the behaviour of the users and how they interact with ziada app in their daily basis while using the it</p>

<h3>5. Mpesa intergration</h3>

<p> This is to allow easy transaction between the service providers that uses ziada app and ziada company</p>

<h3>6. Push notifications</h3>

<p>These notifications are designed to grab attention of ziada users, convey reminders, any new updates on the app, and promotions available </p>

<h3>7. Show blinking on pending requests</h3>

<p> This is to help alert the service providers on the new request and also work as notification to notify the service provider to respond on the request placed by the client on time </p>