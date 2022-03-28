<details>
<summary>5 factors to consider in building scalability applications</summary>
App scalability is one of the most important features to consider when building scalable applications.
It's what will make or break the applications. It's something that should be planned from the very start.
There are a number of things that we need to take into account before deciding if the application can be scale, including what we expect the future throughput or how heavy load might be.

</details>

<details>
<summary>Tokenomics</summary>

Tokenomics has become a popular term in a last few years to describe the math and incentives governing crypto assets. It includes everything about the mechanics of how they work, as well as all psychological or behavioral forces that could affect its value long term. 

Projects with well-designed tokenomics are much more likely to succeed in the long term because they have done a good job of incentives buying and holing their token. 
But projects with poor tokenomics are deemed to failure, as people rapidly sell the tokens at the first sign of trouble.
If you are considering whether to buy a crypto asset or not, Understanding the tokenomics is the one of the most useful first steps you can take to make a good decision.

As someone who has been writing about the Defi for nearly a year now and who designed the tokenomics for a popular crypto videogame, here is what I look at when I am evaluating the tokenomics of a new project.

## It all comes down to Supply and Demand

As in normal economics, the two forces we are most interested in are Supply and Demand. Understanding of how those are baked into the crypto assets will give us a good sense of how desirable a given token or cryptocurrency should be.

1. Supply: Emissions, Inflation, and Distribution.
 
Let's start on supply side first since it's a little easier to understand. The main thing you are trying to figure out is 
"Based on the Supply only, Can I expect the token to hold or increase its value or will that value be inflated away?"

On the Supply side, a token will increase in value if fewer of those tokens exist - we call that deflation. A token will increase in value if more of them exist, it's inflation.
When you are evaluating the Supply side, you don't have to worry about things like whether the token has any utility, it will generate income for its holders.
You are just thinking about the Supply and how it will change over time.

The questions you want to ask are

1). How many of these tokens exist right now?
2). How many will ever exist?
3). How quickly new one being released?

Bitcoin was created with simple supply curve that is emitted over 140 years.

![bitcoin supply curve](https://d24ovhgu8s7341.cloudfront.net/uploads/editor/posts/1963/optimized_5H9DU1E_sz1cDKAY2hK8ZyTAlQ4LLpMHSeNIpgfNASuu2K6VF_wya-y7ASnTRE2KHEA3BxjruMYXvjndzEpr1xLpfhHjhDjyqu_U1DnC6uho5Llrf9pawpX5UdvxzqWiPt5ROxmr.png)

There will only ever be 21,000,000 bitcoin. They are released at a rate that gets cut in a half every four years or so. Roughly, 19,000,000 bitcoin already exist, so there are only 2,000,000 to be released over the next 120 years.

That means 90% of the Supply is already in circulation, and here will only be 10.5% more bitcoin for 100 years from now. so you shouldn't expect any serious inflationary pressure bringing down the value of the coin. 

2. Demand: ROI, Memes, and Game Theory

1) Return on Investment 
2) Memes
3) Game Theory 

4. Tokenomics in Practice: Evaluating a Project


</details>


<details>
<summary>Webhook</summary>

 A webhook in web development is a method of augmenting or alternating the behavior of a web page or web app, with callbacks. These callbacks may be maintained, modified, managed by third party users and developers who may not necessarily be affiliated with the originating website or application.

</details>

<details>
 <summary>DNS Record Types</summary>

 If you are new to DNS management, you were probably a little overwhelmed when you saw dozens of different record types. In this article, I am going to teach you the differences between the four main record types. You will learn how you can use these different records to improve your domain's performance. Before continuing, we recommend that you already have a basic understanding of what the DNS is and How it works. 

 ## 1. A Record

 A records are most commonly used record type. If you have ever set up a website, you most likely configured an A record. A records are the basic form of DNS record types and all most other record types we will discuss are based off A record functionality. When you set up an A record, you will specify a FQDN, which stands for Fully Qualified Domain Name to be pointed to an IPv4 address. When you are creating a website, the IP address will usually be given to you by your DNS registrar when you purchased a domain name for your website.
 A record also have the ability to be pointed to the root of a domain. For example if your website is at www.example.com, the root of the domain name would be example.com which is represented by @ symbol in the record type when you are configuring a record. You can learn how to set up A record [hear](http://help.constellix.com/a-records/)

 ## 2. AAAA Record (quad A)

 This is where things start to get a bit complicated. AAAA record is similar to A record in that they point a domain name to an IP address. The catch is, the IP address is not the typical IPv4 address. Instead, AAAA records point to IPv6 address which is a new ip address type. Not to long ago, we realized the world would eventually be out of IPv4 addresses, so IPv6 addresses were developed. These longer addresses allow an astronomical number of unique addresses and won't be in short supply for a very long time. Since we developed a new address type, we also had to create a new record type to support it - hence the addition of the AAAA records. 
 You can learn how to set up AAAA record [here](http://help.constellix.com/aaaa-records/)

 ## 3. CNAME Records (CNAME vs Alias)

 CNAME records, also known as Alias, point a hostname to the other hostname or FQDN. These records are typically used to point multiple hosts to a single location, without having to specifically assign an A record to each hostname. For example, if you moved your blog from news.example.com to blogs.example.com, you would use a CNAME record. CNAME record can also be used to point a hostname to the another domain or external hostname. To resolve a CNAME record, the name server must behave in a slightly different way than it would do with a normal query of another record type. When a name server looks up a name and finds it is a CNAME, then it will replace it with canonical name and looks up new name. In a sense a CNAME looksup performs two queries to reach the final resolution.
There are a few limitations you should consider before configuring a CNAME record.
 First, you should only use a CNAME record if there are no other record type for that hostname. Second, CNAME record can't be used for a root record.
 You can learn how to set up CNAME record [here](http://help.constellix.com/aaaa-records/)

 ## 4. ANAME Record
 You may have noticed that some records we have already covered have a few limitations. We needed a record that could point a host name to another hostname or FQDN but could also represent root record, essentially a CNAME record for the root of a domain. RFC requirements does not allow this, so instead we developed our very own ANAME records. These records allow you to point the root of your domain to a hostname or FQDN. This functionality has also allowed ANAME record to work seamlessly with CDNs (Content Delivery Networks) because they allow for multiple dynamically updated IP addresses to be authoritative for a domain in many locations. ANAME records allow you to do so much more with your DNS configurations.

</details>
