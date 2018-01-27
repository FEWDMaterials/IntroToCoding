Guts of an HTTP Request
---

**Learning objective**: Understand how HTTP, or the HyperText Transfer Protocol, works.

---

#### Question 
What happens when you type in [http://www.google.com](http://www.google.com) into your URL bar?

#### As it turns out, a whole lot.

1. Chrome has no idea what [http://www.google.com](http://www.google.com) actually means, so first, it looks up the **IP Address** for Google.
2. **DNS**, or **Domain Name System**, is a phone book containing IP Addresses for all the websites that exist on the internet.
3. Chrome then sends an **HTTP Request** to the IP address associated with Google. An HTTP Request is essentially a text message asking Google for data.
4. Google's **server** will issues a server **Response** back to your browser. This response is parsed by Chrome (ie: should Chrome display this response data? download it? etc)
5. **???**
6. Profit.

#### Ok great, why do we care?

There are a few key insights to take away here.

First and foremost, the main communication mechanism for the internet &mdash; you know, that thing that rules our lives &mdash; is **text**. Literally just **letters and words and numbers and characters**.

The other main point to take away here is this: the text that is transferred is written in a highly specific manner. It follows a very strict set of rules that can be parsed and understood by the server and the browser. In other words, this text follows a **specific set of grammatical rules**.

This set of grammar is what determines a **language**. In other words, the text being passed back and forth is a specific language (**HTML**, as it turns out). The browser and server understand this language. If **we** were to learn it as well, we would be able to command the browser to do whatever we want (ie: we would be able to create webpage layouts).

