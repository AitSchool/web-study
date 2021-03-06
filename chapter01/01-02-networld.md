
因特网不等同于 web, 因特网范围更大、出现得更早、具有多样性。

想象一下纵横交错的道路是如何将整个世界连接起来的。从小街道到国道再到国际高速公路，你可以驾车到世界上的任何一个地方。值得注意的是，对于整个交通网来说并没有实际意义的中心。

因特网也和交通网类似的，它通过电缆来将世界上的计算机连接起来，并可在各个计算机之间传递数据信息。

最早在 1969 年，美国发明了可以将计算机连接起来的技术。如今，不仅仅是计算机，手提电脑、手机、TV等设备都可以通过因特网连接起来。


### 客户端和服务端

通常，一个连接是发生在 **2** 台计算机之间：

* 一个具有数据信息（服务端）
* 一台则想要另一台计算机中的信息（客户端）

**客户端** 可以是以下多种形式的软件:

* 一个 Web 浏览器 (比如 火狐)
* 一个邮件客户端 (比如 Outlook)
* 一个聊天 app (比如微信)
* 一个视频播放服务应用 (比如优酷)

上面的每一种客户端软件会从服务端(服务器)上检索需要的信息，服务端上会存储网页、邮件、聊天记录、电影等信息。客户端上通常是不会存储这些信息的而是当它需要的时候就到存有信息的服务器上去请求需要的信息。


A **server** can be considered a _dedicated_ computer always connected to the Internet, whose sole purpose is to **deliver** content.

Although any device connected to the Internet can be both a client and a server at the same time, most devices we use are considered **clients**, because we only _retrieve_ data, and don't deliver any.
{: .info}

### IP Address

Like every house has a specific and _unique_ postal address, each computer connected to the Internet is given an **IP address**, in order to be identified on the network.

An IP address usually looks like a combination of 4 numbers: `91.198.174.192`.

### Domains

Although IP addresses are useful for computers to tell each other apart thanks to their uniqueness, they are hard to read and remember for us humans.

That is why **domains** were created in 1985. They _associate_ an IP address like `91.198.174.192` with a string of **text** like `wikipedia.org`. As a result, both are **interchangeable**: you can go to <http://91.198.174.192> or <http://wikipedia.org> and end up on the exact same website.

A domain has **3** parts, that are read from right to left:

* **Top-Level Domain** (or TLD): there are generic ones (`.com`, `.org`, `.net`) and country-specific ones (`.us`, `.nl`, `.fr`).
* **Domain name**: a name like `wikipedia` or `marksheet`, that can include letters, numbers, but no space or dot.
* **Subdomain** (optional). Although this 3rd part is optional, most websites use `www` as the default subdomain.

Think of domains as a way to **name** computers connected to the Internet.

_How do I buy a domain?_{:.question}
You don't actually _buy_ a domain, but actually **rent** it from whoever is managing the TLD you're aiming for.  
Companies who manage Internet domains are called **domain registrars**. The most famous ones are [Namecheap](https://www.namecheap.com/) and [Gandi](https://www.gandi.net/).

### Protocols

The purpose of interconnecting all these computers is for them to **interact** with each other. And like humans talk in different _languages_, computers on the Internet talk using **protocols**.

Each of them serves a different purpose:

<div class="table">
  <table>
    <tr>
      <th>Protocol</th>
      <th>Used for</th>
      <th>Created in</th>
    </tr>
    <tr>
      <td>
        <abbr title="File Transfer Protocol">FTP</abbr>
      </td>
      <td>File transfer</td>
      <td>1971</td>
    </tr>
    <tr>
      <td>
        <abbr title="Simple Mail Transfer Protocol">SMTP</abbr>
      </td>
      <td>Sending Emails</td>
      <td>1971</td>
    </tr>
    <tr>
      <td>
        <abbr title="Internet Message Access Protocol">IMAP</abbr>
      </td>
      <td>Receiving Emails</td>
      <td>1986</td>
    </tr>
    <tr>
      <td>
        <abbr title="Internet Relay Chat">IRC</abbr>
      </td>
      <td>Chat</td>
      <td>1988</td>
    </tr>
    <tr>
      <td>
        <abbr title="HyperText Transfer Protocol">HTTP</abbr>
      </td>
      <td>Browsing HTML documents (Webpages)</td>
      <td>1989</td>
    </tr>
  </table>
</div>

### URL

Now that we've seen how domains and protocols, we can build a **URL**: a **U**niform **R**esource **L**ocator.

For example, the current page's URL is `http://marksheet.io/internet.html`, and can be divided in 3 parts:

* `http://` is the **protocol**
* `marksheet.io` is the **domain**
* `/internet.html` is the **path**

This URL is **unique** and defines

* _where_ to find something across the internet `marksheet.io/internet.html`
* _how_ the computer is supposed to read it `http://`

URLs can be more complex-looking. You can read about the [anatomy of an URL](http://doepud.co.uk/blog/anatomy-of-a-url).
{: .info}

Internet
: A very large **network** of **computers** connected to each other.

Protocol
: A set of rules, like a **language**, in which computers **communicate** with each other.

IP address
: A combination of **numbers** like `91.198.174.192` which acts like a **unique identifier** for a computer connected to the Internet

Domain
: A **text** like `marksheet.io` which acts like a **unique identifier** for a computer connected to the Internet.  
The difference with IP addresses is that domains are easier to read for **humans**.

[^1]: Apart from oceans obviously.

*[SMTP]: Simple Mail Transfer Protocol
