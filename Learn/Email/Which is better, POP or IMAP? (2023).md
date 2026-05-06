---
title: "Which is better, POP or IMAP? (2023)"
source: "https://pomodo.io/tech-archive/imap-vs-pop/"
author:
  - "[[Jonathan Griffin]]"
published: 2023-02-08
created: 2026-05-05
description: "The ultimate showdown between IMAP vs. POP3. We take a look the differences, and most importantly, why you should be using IMAP."
tags:
  - "clippings"
---
If you have set up an email client such as Outlook or Thunderbird, or an email app on your smartphone, you will almost certainly have to choose between POP and IMAP in the settings.

I will explain how POP and IMAP work in this article and their differences. This will enable you to choose the best one. Hint: It’s IMAP.

- IMAP is the acronym for **Internet Message Access Protocol**
- POP is the acronym for **Post Office Protocol**.

Both of these protocols are used for the processing of the transfer of emails between an email server and a mail client (such as Mozilla Thunderbird, Microsoft Outlook, Eudora, or your default smartphone email app).

**POP3** is a protocol that has been around for a very long time. POP1 was first created in1984 and POP2 in early 1985/. [POP3 is the current version created in1988](http://en.wikipedia.org/wiki/Post_Office_Protocol) and remains one of the most popular email protocols.

**IMAP** [was created in 1986](http://en.wikipedia.org/wiki/Internet_Message_Access_Protocol), but at that time, we don’t think they anticipated how well it fits in with the current “cloud-based” trend that has developed over recent years.

## The difference in how IMAP and POP work

The differences between POP and IMAP are evident in their respective workflow processes.

### The POP3 Retrieval Process

![POP Retrieval Process.](https://res.cloudinary.com/thewebmaster/image/upload/c_scale,f_auto,q_auto:best,w_2268/image/POP-retrieval-process.png)
- Your email client is instructed to check mail (either manually or automatically).
- Your email client will connect to the remote server where the emails are stored.
- Your email client will retrieve the mail from the remote server.
- Your emails will be stored locally by your email client.
- Any emails retrieved from the server will be deleted from that server.
- Your email client will disconnect from the remote server.

POP3 will download any messages you have from the mail servers.

If you delete, copy, move or send messages, they will exist only on your local computer. Anyone accessing your email from another location will not know what you have done.

Many POP clients have an option to leave a copy of your messages on the server, but this is not the default behavior and still would not show subsequent changes or sent messages.

### The IMAP Retrieval Process

![IMAP Retrieval Process.](https://res.cloudinary.com/thewebmaster/image/upload/c_scale,f_auto,q_auto:best,w_2268/image/IMAP-retrieval-process.png)
- Connect to the remote server.
- Retrieve changes and content and store it locally.
- Update new changes back to the remote server. E.g., adding sent emails, reading emails, and removing deleted emails.
- Disconnect from the remote server.

Whenever you log into an email client configured with the IMAP protocol, it will mirror any changes you make to the email server.

IMAP won’t delete the email from the server after downloading it. It will keep any replies you make, read status, and record all other actions.

Your emails will sync across multiple devices whenever you log into your email server from your tablet or smartphone.

## What are the advantages of POP?

- Mail is stored locally and can be accessed without an internet connection.
- An Internet connection is only required for sending and receiving email. This means lower bandwidth usage.
- Smaller storage space required (assuming emails are deleted after download). Some hosts will limit mailboxes, for example, 500MB.
- Many POP servers allow you to leave a copy on the server.
- You can group multiple mail accounts into one inbox.
- No Mail is stored on a server, so your data is safer from being hacked.

## What are the disadvantages of POP?

- Any activity related to your emails is not duplicated between computers. Everyday tasks, such as reading, filing, and flagging messages, will need to be undertaken on each machine.
- Messages are only stored in one place. If your computer hard drives fail, all your emails will be lost. There will be no recovery option unless you actively back up your remote server.
- POP servers are incompatible with webmail software.

## What are the advantages of IMAP

- The mail is stored on the remote server so you can access it wherever and on whatever device you wish. You can use different mail programs depending on your device.
- An Internet connection is required to access your emails.
- IMAP is faster, as only necessary information, such as Headers, are downloaded until explicitly requested.
- Mail is automatically backed up if the server is managed correctly.
- Because you don’t download emails to your computer, it saves storage space.
- Many IMAP clients will allow you to store emails locally and will SYNC when online.
- If your computer fails, your emails are safe and can be accessed on a different device.

## What are the disadvantages of IMAP

- Your host can limit message storage. Limits of 200MB or 500MB are not uncommon unless you purchase professional email services.
- All your messages are kept on the server, so hackers can access everything if your server or password is not secure.
- Offline reading depends on your email client. It will need to be explicitly configured.

## Reasons why you MIGHT choose POP

- You want to access your mail from only one single device.
- You like to access your emails when you are offline.
- You like to keep an extensive history of your emails, and your server storage is limited.
- You want your data to be more secure.

## Reasons why you SHOULD choose IMAP

- If you use multiple computers or devices to read email, use IMAP to keep your data in sync.
- If you need to use more than one email program to read your mail, set each application to use IMAP so they remain synced.
- Do you use Webmail occasionally, in addition to an email program? Use IMAP. (Webmail is an IMAP-only email client accessed via a web interface.)
- You have a reliable internet connection.
- You want all your devices to stay in sync, including reading emails, folders, deleted emails, spam, etc.
- You do not have much local storage space.
- You want to safeguard against your computer’s hard drive failing.

Remember, use POP3 **or** IMAP; do not mix the two. Doing so will cause all sorts of problems.

## Where to buy IMAP or POP email hosting

I use IMAP with private hosting for business purposes. It allows maximum flexibility, and companies like Google and Microsoft have excellent business email products that use IMAP.

The benefit of a reputable company for your email is that because mail is stored on a remote server, you need to ensure security is reliable.

You don’t need private email hosting to use IMAP and POP3. Most hosting companies (a few specialized Managed WordPress Hosting companies excluded) allow you to create email accounts with your hosting plan. However, your storage amount may have a per mailbox limit.

If you store a lot of emails, you may want to check before purchasing. Again, all these companies allow you the choice between IMAP and POP.

So, if you want to access your emails anywhere and for them to remain synced, choose IMAP.

## Frequently Asked Questions

### How can I tell if I am using POP or IMAP email protocol?

The most reliable way to check is to log into your email client or app and check whether the Server Account Type shows as IMAP or POP3.

If you do not wish to do that, there are other ways to tell which protocol you are using. If any of the statements are correct, then you are using POP3.

- Create a folder on one of your devices. When you log in to a different device, the folder is missing.
- Read an email on one of your devices. When you log in to a different device, it shows as unread.
- Delete an email on one of your devices. When you log in to a different device, it is still there.

### Are you able to switch between POP and IMAP servers?

Yes, this is possible. This is undertaken by changing a setting in your email client.

If you currently use POP and are changing to IMAP, we recommend setting up a new account in your email client where you now have your POP account. Once you have set up the new account, drag all your emails from your POP account to your IMAP account. This will save all your old emails into your new account and allow you to access them on other computers and mobile devices.