**Before you start:** rename this file to `html12c_Protocols_lastname.md`, using your own last name. Watch videos 7–11 and use **Part 3** of `html12_ColorsSeoProtocols_StudyGuide.md` (in this folder) to answer. Put the file in an `html12` folder in your `htmlCssJavaScript` repo. Commit and push when you're done.

**Name:**

---

# Task 12c — Internet Protocols

Type your answers on the blank line under each **Answer:**, or fill in the tables. Explain in your own words where a question asks why.

## 1. Which protocol?

**a.** For each situation, write the protocol that does the job: **HTTP, HTTPS, FTP, SFTP, DNS, TCP, or IP**.

| Situation | Protocol |
|---|---|
| You type `example.com` and your computer needs its IP address | DNS |
| You upload your website's files to a web host | FTP |
| You log in to your bank's website | HTTPS |
| A server sends a plain web page to your browser | HTTP |
| Packet 7 of a file never arrived, so it gets sent again | TCP |
| Each packet needs an address so it reaches the right computer | IP |
| You upload files to a server and want the transfer encrypted | SFTP |

**b.** In your own words, what is a protocol? Give an example from everyday life of two people following the same "rules" so they understand each other.

**Answer:**



## 2. IP addresses and DNS

**c.** Which of these are valid IPv4 addresses? Write **Valid** or **Not valid**, and give the reason for any that are not.

| Address | Valid? | Reason |
|---|---|---|
| `192.168.0.1` | Valid |  |
| `10.0.300.5` | Not valid | 300 is to big, max number is 255 |
| `172.16.4` | Not valid | it only has 3 numbers |
| `8.8.8.8` | Valid |  |

**d.** DNS is called the internet's "phone book." Explain why that comparison makes sense.

**Answer:**

    It has the phone number (IP adress) for each name (URL).

## 3. Packets

**e.** A photo is sent across the internet. It is split into 20 packets, and they take different paths. Packet 12 arrives last and packet 5 never arrives at all. Explain what happens, and which protocol handles it.

**Answer:**


## 4. HTTP and HTTPS

**f.** Write the status code for each situation.

| Situation | Status code |
|---|---|
| The page loaded fine | 200 |
| You typed a page name that does not exist | 404 |
| Something broke on the server | 500 |

**g.** A website has a login form but uses `http://` instead of `https://`. What is the risk? What would the browser show?

**Answer:**

Anyone could read your password, the browser should show "Not secure'

**h.** What do SSL and TLS have to do with HTTPS? Which one is newer?

**Answer:**

    SSL and TLS are the certificates that make sure a website is what is says it is.

    The newer one is TLS

## 5. FTP

**i.** What is FTP used for in web design? Why is SFTP a better choice than plain FTP?

**Answer:**


## 6. The parts of a URL

**j.** Break each URL into its parts.

`https://www.medinapets.com/dogs/grooming.html`

| Part | Answer |
|---|---|
| Protocol | |
| Subdomain | |
| Domain name | |
| Top-level domain (TLD) | |
| Path | |
| File name | |

`http://library.example.edu/books/index.html`

| Part | Answer |
|---|---|
| Protocol | |
| Subdomain | |
| Domain name | |
| Top-level domain (TLD) | |
| Path | |
| File name | |

**k.** Is the second URL secure? How can you tell?

**Answer:**


## 7. Putting it together

**l.** These steps happen when you type a URL and press Enter, but they are out of order. Number them 1–5.

| Order | Step |
|---|---|
| | The browser puts the packets back together and draws the page |
| | DNS finds the server's IP address |
| | The browser sends an HTTPS request for the page |
| | TCP/IP opens a connection to the server |
| | The server sends back the HTML, CSS, and images in packets |

**m.** FTP is not one of those steps. When does FTP get used instead?

**Answer:**


## Closing 12c — Vocabulary

| Term | Your definition |
|---|---|
| Protocol | |
| IP address | |
| DNS | |
| Packet | |
| HTTPS | |
| URL | |
