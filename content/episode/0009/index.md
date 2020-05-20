+++
Description = "Reactive Architectures with RSocket & Spring"
aliases = ["/0009"]
author = "paulczar"
hosts = ["bob","paulczar"]
guests = ["spencer"]
Date = "2020-06-02"
PublishDate = "2020-04-01"
episode = "0009"
# 320x180 for image / banner
# once streamed, replace with youtube from below command
# wget -O episode.jpg https://img.youtube.com/vi/<youtube-id>/mqdefault.jpg
episode_image = "episode/0009/episode.jpg"
episode_banner = "episode/0009/episode.jpg"
explicit = "no"
images = ["episode/0009/episode.jpg"]
title = "Reactive Architectures with Spencer Gibbs"
youtube = ""
truncate = ""
twitch = "makejarnotwar"
Draft = true

+++

As more applications are experiencing the benefits of using a reactive programming model, one of the biggest problems they experience is the mismatch between Reactive Stream back pressure and current networking protocols. The RSocket protocol enables Reactive Streams back pressure to be transmitted across a network link connecting reactive flows in multiple applications to directly affect one another in a positive way.

In this talk, we will provide an overview of the key differences and benefits of RSocket-based networking and introduce the RSocket Routing project and the integration with Spring. We will discuss the benefits of this integration, including the impact on speed, scalability, security, and more. We will also discuss use cases, and show how you can leverage this new technology in your applications.