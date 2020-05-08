+++
Description = "A Deep Dive Into Creating Production Ready Containers"
aliases = ["/0007"]
author = "paulczar"
hosts = ["bob","tiffany","paulczar"]
guests = ["cora"]
Date = "2020-05-19"
PublishDate = "2020-04-01"
episode = "0007"
# 320x180 for image / banner
# once streamed, replace with youtube from below command
# wget -O episode.jpg https://img.youtube.com/vi/<youtube-id>/mqdefault.jpg
episode_image = "episode/0007/episode.jpg"
episode_banner = "episode/0007/episode.jpg"
explicit = "no"
images = ["episode/0007/episode.jpg"]
title = "Creating Production Ready Containers With Cora Iberkleid"
youtube = ""
truncate = ""
twitch = "makejarnotwar"
Draft = false

+++

As developers, we’ve become adept at packaging our applications, whether on our local machines or in a CI/CD toolchain, relying on mature tools like Maven, Gradle, npm, pip, Composer, and others. But as Kubernetes becomes the runtime platform of choice, packaging our apps is not quite enough. We must now package all of the dependencies as well, including any middleware, runtime, even the OS, into images - the new unit of deployment. What are some of the ways we can tackle this challenge? What are the advantages of one over the other? In this talk we’ll cover a few different approaches for building images: Dockerfile, Jib, and Paketo. By the end of this session, you’ll understand some of the challenges and considerations and be well positioned to start building images easily and maintain them over time.