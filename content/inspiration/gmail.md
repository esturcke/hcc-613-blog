+++
title = "Details, Details, Details"
description = "The hard work of simplifying Gmail."
date = "2016-03-09"
publishdate = "2016-03-09"
+++

{{% fig "gmail.jpg" %}}**Figure 1** A blank New Message badger in Gmail, waiting to be written in.{{% /fig %}}

Google's [bar.foo](https://bar.foo) hosts short engineering essays about work
they have done. I found an entry on [the compose window in
Gmail](https://bar.foo/gmail.html) a nice contrast to the Hoekman reading from
last week. This emphasis here was also how simplifying improve UX, but this was
certainly not accomplished by doing 20% of the work. The team went through
painstaking iterations, observed individual users as well as collected
usage statistics over a large set of users. They worried about cross browser
compatibility and single pixel jumps when editing the "To:" addresses. Simplifying
here means tucking many of the features away, while still maintaining feature
parity as noted:

> Most people think of Gmail compose as this simple textbox that you type in,
> click send, and it's all good. But in reality, there are many features in our
> compose window, and you don't necessarily realize just how many there are
> until you examine the code. For instance, in Gmail you can label drafts
> inside of a composition, you can insert emoji, you can do all kinds of
> formatting, you can print drafts, you can insert photos and docs, etc. There
> are also a lot of labs that integrate with compose, like canned responses.
> Not only did we have to replicate all of those things in the new compose
> experience, we also had to find ways to integrate them into the new UI, which
> involved so many design challenges. It was pretty awesome to be able to see
> all of the inner workings of these features that are really unique, and then
> to find ways to reproduce them in the badger.
