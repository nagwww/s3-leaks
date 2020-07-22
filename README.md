# s3-leaks

## List of AWS S3 Leaks

Feel free to send in a PR if you know of other leaks 

|Date           | Description                         |Notes  |
| ------------- | --------------------------------------------------------------|------------- |
| July2020      |<a href="https://www.theregister.com/2020/07/21/twilio_sdk_code_injection/"> Twilio: Someone broke into our unsecured AWS S3 silo, added 'non-malicious' code to our JavaScript SDK|Attackers tried to update the javascript library hosted on the s3 buckets so this can be picked up by other clients |
|Jan 2020 | <a href="https://www.computerweekly.com/news/252476870/Exposed-AWS-buckets-again-implicated-in-multiple-data-leaks">"Exposed AWS buckets again implicated in multiple data leaks"</a>| Passport scans, tax documents, background checks, job applications, expense claims, contracts, emails and salary details relating to thousands of consultants working in the UK were exposed.|
|June 2020 | <a href="https://cloudsek.com/threatintelligence/7-2-million-records-were-exposed-but-not-from-the-bhim-app/">"7.2 million records were exposed, but not from the BHIM app"| | |
| Oct 2018|<a href="https://www.healthcareitnews.com/news/update-misconfigured-database-breaches-thousands-medcall-advisors-patient-files">Misconfigured database breaches thousands of MedCall Advisors patient files</a>|names, email and postal addresses, phone numbers, dates of birth and Social Security numbers. Other files had recordings of patient evaluations and conversations with doctors, along with medications, allergies and other detailed personal health data.|
| Jun 2019|<a href="https://www.zdnet.com/article/aws-s3-server-leaks-data-from-fortune-100-companies-ford-netflix-td-bank/">AWS S3 server leaks data from Fortune 100 companies: Ford, Netflix, TD Bank</a>|Attunity, an Israeli IT firm that provides data management, warehousing, and replication services for the world's biggest companies, has exposed some of its customers' data after it left three Amazon S3 buckets exposed on the internet without a password.|
| May 2019    | <a href="https://www.upguard.com/breaches/attunity-data-leak"> How a Vendor for Half the Fortune 100 Exposed a Terabyte of Backups</a> ||
| Mar 2018|<a href="https://www.upguard.com/breaches/how-medical-records-and-patient-doctor-recordings-were-exposed">Medical Records and Patient-Doctor Recordings Were Exposed</a>|information for employees of 181 business locations, as well as personally identifiable information (PII) for nearly 3,000 individuals was publicly exposed in an unsecured||
| Mar 2018|<a href="https://thenextweb.com/security/2018/03/14/jewelry-site-accidentally-leaks-personal-details-plaintext-passwords-1-3m-users/">Jewelry site accidentally leaks personal details (and plaintext passwords!) of 1.3M users</a>|addresses, zip-codes, e-mail addresses, and IP addresses. He also claims the database contained plaintext passwords||
| Feb | <a href="https://www.upguard.com/breaches/cloud-leak-octoly">S3 bucket open to world : Octoly</a>|real names, addresses, phone numbers, email addresses|
| Jan 22 | <a href="https://www.scmagazineuk.com/sensitive-medical-records-on-aws-bucket-found-to-be-publicly-accessible/article/738421/"> Sensitive medical records on AWS bucket found to be publicly accessible</a> ||
| Dec 2017 | <a href="http://www.zdnet.com/article/alteryx-s3-leak-leaves-120m-american-households-exposed/">Alteryx leave S3 bucket open for anonymous user : 120m american households exposed|Home addresses, contact information, mortgage status, financial histories|
| Nov 2017|<a href="https://www.upguard.com/breaches/credit-crunch-national-credit-federation">111 GB of internal customer information from National Credit Federation, a Tampa, Florida-based credit repair service</a>|- SSN - Drivers licesne, credit reports |
| Nov 2017|<a href="https://blog.zwillgen.com/2017/09/05/s3-buckets-not-simple/"> Uber, the hack happend couple months back was brought to light in Nov 2017>|personal information of 57 million Uber users and driver's license numbers |
|Nov 2017 | <a href="http://www.zdnet.com/article/nsa-leak-inscom-exposes-red-disk-intelligence-system/">NSA leak exposes Red Disk, the Army's failed intelligence system|100 gigabytes of data from an Army intelligence project, codenamed "Red Disk."|
  | Nov 2017 | <a href="http://deathrattlesports.com/australia-data-leak-nearly-50000-government-and-private-staffers-sensitive-data-publicly-exposed/141646"> Australia data leak: Nearly 50,000 government and private staffers’ sensitive data publicly exposed</a>|S3 bucket left open by a contractor|
| Oct 2017 | <a href="http://www.zdnet.com/article/accenture-left-a-huge-trove-of-client-passwords-on-exposed-servers/"> How A Cloud Leak Exposed Accenture's Business</a>||
| Oct 2017 | <a href="https://mackeepersecurity.com/post/patient-home-monitoring-service-leaks-private-medical-data-online">Patient Home Monitoring Service Leaks Private Medical Data Online</a>| publically accessible Amazon S3 47.5 GB / 316,363 |
|Sep 2017 | <a href="https://www.theregister.co.uk/2017/09/19/viacom_exposure_in_aws3_bucket_blunder/"> Viacom : Open S3 bucket with AWS Keys, passwords, other sensitive info </a>|S3 bucket open to the world|
| Sep 2017      | <a href="https://www.theregister.co.uk/2017/09/04/us_security_clearance_aws_breach/">Leaky S3 bucket sloshes deets of thousands with US security clearance</a>| - Bucket open to the world in the test account|
|Sep 2017       | <a href="http://gizmodo.com/millions-of-time-warner-customer-records-exposed-in-thi-1798701579">Millions of Time Warner Cable Customer Records Exposed in Third-Party Data Leak </a> ||
|August 2017    | <a href="http://www.informationsecuritybuzz.com/expert-comments/indian-creditseva-data-breach/"> Indian Creditseva Data Breach</a> ||
|August 2017    | <a href="https://www.theregister.co.uk/2017/08/22/open_aws_s3_bucket_leaked_hotel_booking_service_data_says_kromtech/"> Open AWS S3 bucket leaked hotel booking service data</a> | |
| July 2017     | <a href="https://www.theregister.co.uk/2017/07/18/dow_jones_index_of_customers_not_prices_leaks_from_aws_repo/"> S3 bucket was set to authenticate all AWS users, not just Dow Jones users</a>||
|July 2017      | <a href="https://www.forbes.com/sites/thomasbrewster/2017/07/06/massive-wwe-leak-exposes-3-million-wrestling-fans-addresses-ethnicities-and-more/#5a0bf96275dd">Massive WWE Leak Exposes 3 Million Wrestling Fans' Addresses, Ethnicities And More</a>
| July 2017     | <a  href="https://thehackernews.com/2017/07/over-14-million-verizon-customers-data.html">Verizon, the major telecommunications provider, has suffered a data security breach with over 14 million US customers' personal details exposed on the Internet</a> | |
|June 2017      | <a href="http://windowsitpro.com/security/faulty-aws-s3-configuration-exposes-personal-data-198m-us-voters">Personal information belonging to more than 198 million registered U.S. voters was exposed </a>
|May 2017      | <a href="http://gizmodo.com/top-defense-contractor-left-sensitive-pentagon-files-on-1795669632">Top Defense Contractor Left Sensitive Pentagon Files on Amazon Server With No Password  </a>||
|May 2017       |<a href="https://www.theregister.co.uk/2017/06/01/us_national_geospatial_intelligence_agency_leak/"> Security company finds unsecured bucket of US military images on AWS</a> ||
| April 2017    | <a href="https://threatpost.com/auto-lender-exposes-loan-data-for-up-to-1-million-applicants/125216/">A California auto loan company left the names, addresses, credit scores and partial Social Security numbers of up to 1 million people exposed </a>         | |
| Feb 2017 | <a href="https://threatpost.com/childrens-voice-messages-leaked-in-cloudpets-database-breach/123956/"> CHILDREN’S VOICE MESSAGES LEAKED IN CLOUDPETS DATABASE BREACH </a> ||
| Jan 2017 | <a href="https://tutorgeeks.blogspot.com/2017/04/aws-s3-bucket-misconfiguration.html"> Paytm S3 bucket misconfiguration allowing PUT operations</a> ||
| March 2013    | <a href="https://www.helpnetsecurity.com/2013/03/27/thousands-of-amazon-s3-buckets-left-open-exposing-private-data/">Thousands of Amazon S3 buckets left open exposing private data</a> |             |



## Elastic Search
|Date           | Description                         |Notes  |
| ------------- | --------------------------------------------------------------|------------- |
| Sep 2017    |<a href="https://threatpost.com/thousands-of-elasticsearch-servers-hijacked-to-host-pos-malware/127965/"> AWS hosted elastic search servers hijacked </a>| |
