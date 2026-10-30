Here is your Assignment 1.1 answer ready to submit:

### Assignment 1.1 — How a Website Works

*Explanatory Paragraph:*

When you type a URL like www.google.com and press enter, your Browser (which is the Client) starts the process. First it checks what HTTP means - HyperText Transfer Protocol, which is the set of rules for communication between browser and server, and HTTPS means HyperText Transfer Protocol Secure, which is the secure, encrypted version of HTTP using SSL/TLS. The browser then sends a *Request* to the web Server where the website is hosted. This is called the *Request-Response Cycle* - Client sends a Request, Server processes it, if needed it fetches data from the Database, and then sends back a Response containing HTML, CSS, and JS files. Finally, the browser renders those files on your screen and the website opens. If it is a *Static Website*, the same content is sent to everyone and it doesn't use a database, while a *Dynamic Website* generates different content for each user by fetching data from the database.

*Roles:*

- *Browser:* Shows the website, sends requests.
- *Client:* Your device that asks for information.
- *Server:* Powerful computer that stores the website and sends response.
- *Database:* Stores all data like user logins, posts.

*For Screenshot Task:*
1.  Open any website in Chrome
2.  Press F12 or Right Click > Inspect
3.  Go to *Network* tab
4.  Reload the page (Ctrl+R)
5.  You will see list of requests like `document`, `images`, `css`. Take screenshot of that.

> Take a screenshot like this: It will show Name, Status 200, Type, Time.