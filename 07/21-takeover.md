# Google Associate Cloud Engineer Takeover - July 21st, 2020
Recently, I was reading the [Official Google Cloud Certified Associate Cloud Engineer Study Guide](https://www.amazon.com/Google-Cloud-Certified-Associate-Engineer/dp/1119564417/) by Dan Sullivan. 

Throughout the book, the author provides examples of how a cloud engineer might configure Google services such as Google Cloud Storage or App Engine. These examples often include "theoretical" example domain names that, when viewed in e-book form, are clickable hyperlinks.

(!img/book-takeover1.png)

While scrolling through the book on my phone, I clicked one of these links, and found that it sent me to a 404 page.

(!img/book-takeover2.png)

In the above example, a hypothetical PDF file is referenced that is stored in a Google Cloud Storage bucket called ace-certification-prep. Since Cloud Storage buckets are globally named, and this particular Cloud Storage bucket was not yet registered, any Google Cloud user could take over the hyperlink listed in the book. In short, the Official study guide for the GCP ACE certification could be abused to serve malware. 

(!img/book-takeover3.png)

Later, three more examples were identified. The book referred to three hypothetical appspot.com URLs. These are determined by the GCP project name, which is also global. These projects were also not yet registered, so I took them over.

https://current-time-zone.appspot.com

https://time-zone-ui.appspot.com

https://time-zone-calculate.appspot.com

