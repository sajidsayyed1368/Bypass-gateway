Bypass Payment gateway on website.
How to hack any Payment Gateway?
Buying free stuff online ain't that the dream of today's generation. I know that cause I am that person who buys everything online, every single thing in my apartment is bought on e-commerce website, trust me everything. We are in a generation where e-commerce has boomed so rapidly that there is no stopping it. Alibaba has set a new record with more than $30.8 billion in sales in just 24 hours, just give that a moment to settle in.
Yet the mechanism behind all these transactions taking place is just bits of information flowing all over giant interconnected web of devices, we call as internet. Anyone who understands the science behind how these transactions take place can figure out a way to shop online forever and that too free of cost.
Let's dig in!
Most of the security personnels reading the article might be thinking it is just a clickbait but I just want you to keep your mind open and follow through as I explain to you the three level of difficulties in which you can hack a payment gateway for a e-commerce brand

1.) The easy way
2.) The tricky way
3.) The next to impossible way
These three points they are the stepping stones to hack and being able to manipulate any payment gateway.
1. The easy way
Now this is the easiest way you can manipulate the amount of the product that you are buying. So this is when the cost / amount of the product is present in the hidden element of the form in the HTML page. So, while we are choosing a item that we are planning to buy the price of the item gets added to the total amount of the product and that price is taken from the hidden field that gets filled into the form and then presented on the grand total.
<input type="hidden" name=" business" value="abc@xyz.com">
‹input type="hidden" name="cmd" value="
_xclick">
<input type="hidden" name=" item_name" value="
Classmate_Notebook">
<input type="hidden" name=" amount" value="550">
<input type="hidden" name=" currency_code" value=" INR">
How to bypass it -
To change the price of the product all you have to do is to change it in the hidden form field where the price is mentioned before adding the product to the cart. In this way the actual price is never added to the cart and you can buy the product literally for free.
2. The tricky way
This is the second way of how to manipulate the amount of the product that you are buying online and change the price to your liking. So, in this process we use a intercept tool like Burp Suite. The price isn't in the hidden field in the form, so we can't change it like the way before and we add the product to the cart.
How to bypass it -
So, once we are at the payment gateway we turn on the intercept and manipulate the cost manually in the packet we just intercepted. After editing the price in the intercepter we then forward the packet and just like that we have ourselves our another free product.
3. The next to impossible way
The people who have been working with payment gateways and online transaction, the steps leading till here might be well known to them and they must have had security in place which might have taken care of the vulnerabilities I just mentioned above. The most well known way to protect from these vulnerabilities is to use a hash.
Hashes are used as a method to check the integrity of the message that has been sent over from the e-commerce website to the
payment gateway. The hash and the other values including the price of the product is then send over for verification and if the hashes before and after the payment gateway matches only then transaction is allowed.
How to bypass it -
This is the method that most of the security vendors consider to be secure, the problem arise when you start to dig a little deeper and begin to focus on one e-commerce website at a time.#cybercommando
The first that you learn as a hacker, is never to give up and find a solubi.
Every security vulnerability that I just exposed and showed above are caused due to the lack of awareness in the developers ere they are unaware of the security risks of their code and how it can cost the company thousands or even million of dollars worth of damage.
If the developers focus more on the security perspective of things and keeping secure coding in mind more than 90% of the errors can be solved straight away and no security risk will arise.
If you enjoyed it please do clap & let's collaborate. Get, Set, Hack!
REGARDS=@sajidsayyed1368@gmail.com
THIS WILL HELP YOU, ITS JUST A SMALL HINT !!
TT BURP SUITE OTP BYPASS IT
Disclaimer: I will be censored about the target on my Practice, so find your own target. WARNING!!! This is Education Purpose Only
Open Mozilla Firefox then configure the proxy like this.
[7:34 pm, 8/10/2024] Sajid Sayyed: Open Burpsuite
Create a Temporary Project, then click next until Burpsuite shows the Dashboard.
After the Dashboard Burpsuite opened, navigate to Proxy Menu then Intercept. Make sure your Intercept is on because if Intercept is off you can't use it.
After you set Intercept is on navigate on Mozilla Firefox then navigate to your website target
Your Intercept text will be changed to orange text, you must forward it until the page on Mozilla Firefox normally opened.
Login into the page that you have to navigate it, after you Login. The page on Mozilla Firefox will not successfully load after you click the Forward button in the Burpsuite.
Click forward until the next page is showing
DON'T MISUSE IT !! JUST ONLY FOR EDUCATIONAL PURPOSE !!
I will not responsible if you are in jail .
BE SAFE
BE LEGAL
BE AWARE