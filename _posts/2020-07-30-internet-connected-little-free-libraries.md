---
guid: http://randomodbuild.tk/?p=60
layout: post
author: brooks
permalink: /2020/07/internet-connected-little-free-libraries/
date: 2020-07-30T23:34:01-05:00
enclosure:
  - >
    https://randomodbuild.tk/wp-content/uploads/2020/07/LittleFreeLibraryNews-1.mp4

    9208557

    video/mp4
title: Internet Connected Little Free Libraries™
id: 60
image: /wp-content/uploads/2020/07/Screen-Shot-2020-07-30-at-5.50.07-PM.png
categories:
  - Uncategorized
---
At the school I used to attend, a community service project was required to graduate. You could do it as a group or alone, so of course I was in a group with 2 of my friends. I originally wanted to do something related to 3D printing. I had purchased a budget 3D printer in 2017, the Tronxy X1. My idea was to go to my elementary school, get a 3D printer, and have a little class teaching kids how to use and maintain a 3D printer. It probably would have benefited the community (a requirement for the project), but there were too many variables. It would be hard to do as a group, because my friends lived 30 minutes away, and having classes about 3D printers would be a pain to coordinate. Plus, we needed money. And while 3D printers have gone down significantly in price and we could&#8217;ve just bought a few Ender 3&#8217;s, it would&#8217;ve been a hassle to rally parents into funding 3D printers that their student may not even use. So it could&#8217;ve worked, but would have been a huge pain to coordinate. Plus, Jake (one of the 2 friends) came up with a much better idea; to make a little free library. So we quickly decided to do away with the original plan.

Jake&#8217;s new idea was simple: Build a little free library, place it in a neighborhood, and be done. Pretty simple to do. Nathan agreed to this plan, and so did I, but (being myself) I wanted to complicate things just a little. I have been interested in IoT devices for the longest time, and I thought it would be really cool to have a camera inside the LFL (that&#8217;s what I&#8217;m going to call the &#8220;book box) so you could check online which books are in stock before you go. At first I was thinking super complicated&#8211;I wanted to have a raspberry pi inside with a camera and a LoRa Hat and somehow broadcast that image to another pi acting as a gateway to decode the packet into an image file and then upload that to a website blah blah blah. But we wanted to keep costs low and reliability high, and keep it simple. So I will get back to this part of the story.

We had all agreed on building a LFL and I had filled them in on the plan to add a camera. We knew that we could build a LFL, but the camera part was tricky. We didn&#8217;t want any issues with the camera system to prevent the main point from failing&#8211;to have a usable LFL. So we decided to be constantly brainstorming about the camera system while we planned out the main library. This was the most difficult part. While it was all pre-quarantine, we still lived very far apart, so most of the brainstorming had to happen remotely. We each checked our local neighborhoods for any LFLs so we could measure them and form our own plans. Luckily for me, there was one within a quarter mile of my house. My parents were hounding me to get this started, and when my mom was walking she found the LFL previously mentioned. She even had a brief talk with the nice lady who made the library, and said that her son may be over taking some photos soon. So a few days later I biked over and brought my measuring tape and phone to take a few photos and measurements.

![Front view of little free library](/assets/img/observelflfront.png)



![roof view of reference library](/assets/img/roofreferencelfl.jpeg)



![other side of roof of reference library](/assets/img/othersideroofreferenceLfl.jpeg)



![](/assets/img/measreflfl.jpeg)



![](/assets/img/measheightreflfl.jpeg)



![](/assets/img/measwidreflfl.jpeg)



![](/assets/img/measroofreflfl.jpeg)



![](/assets/img/indoorreflfl.jpeg)



![](/assets/img/booksreflfl.jpeg)



![](/assets/img/inheightreflfl.jpeg)



![](/assets/img/lowwidthreflfl.jpeg)



![](/assets/img/mountreflfl.jpeg)

<figure class="wp-block-gallery columns-3 is-cropped">

<ul class="blocks-gallery-grid">
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/4C8EDA8D-BCA3-45B4-9AC7-CCA1458BFC31_1_105_c.jpeg" alt="" data-id="63" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/4C8EDA8D-BCA3-45B4-9AC7-CCA1458BFC31_1_105_c.jpeg" data-link="https://randomodbuild.tk/?attachment_id=63#main" class="wp-image-63" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/4C8EDA8D-BCA3-45B4-9AC7-CCA1458BFC31_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/4C8EDA8D-BCA3-45B4-9AC7-CCA1458BFC31_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/1B5E9729-A693-4801-804D-67AC03B0ED60_1_105_c.jpeg" alt="" data-id="64" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/1B5E9729-A693-4801-804D-67AC03B0ED60_1_105_c.jpeg" data-link="https://randomodbuild.tk/?attachment_id=64#main" class="wp-image-64" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/1B5E9729-A693-4801-804D-67AC03B0ED60_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/1B5E9729-A693-4801-804D-67AC03B0ED60_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/9F16B04A-F0BA-4E32-9125-A338BFAC1F0B_1_105_c.jpeg" alt="" data-id="65" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/9F16B04A-F0BA-4E32-9125-A338BFAC1F0B_1_105_c.jpeg" data-link="https://randomodbuild.tk/?attachment_id=65#main" class="wp-image-65" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/9F16B04A-F0BA-4E32-9125-A338BFAC1F0B_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/9F16B04A-F0BA-4E32-9125-A338BFAC1F0B_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/0242AAE9-E4C5-4399-A3F0-A08F2B26AD75_1_105_c.jpeg" alt="" data-id="66" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/0242AAE9-E4C5-4399-A3F0-A08F2B26AD75_1_105_c.jpeg" data-link="https://randomodbuild.tk/?attachment_id=66#main" class="wp-image-66" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/0242AAE9-E4C5-4399-A3F0-A08F2B26AD75_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/0242AAE9-E4C5-4399-A3F0-A08F2B26AD75_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/A4826AE2-BC8A-4C9F-90C2-B52B2F0E4DE5_1_105_c.jpeg" alt="" data-id="67" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/A4826AE2-BC8A-4C9F-90C2-B52B2F0E4DE5_1_105_c.jpeg" data-link="https://randomodbuild.tk/?attachment_id=67#main" class="wp-image-67" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/A4826AE2-BC8A-4C9F-90C2-B52B2F0E4DE5_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/A4826AE2-BC8A-4C9F-90C2-B52B2F0E4DE5_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/C8971C37-8882-41AB-9D1F-05C2C27AC8FF_1_105_c.jpeg" alt="" data-id="68" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/C8971C37-8882-41AB-9D1F-05C2C27AC8FF_1_105_c.jpeg" data-link="https://randomodbuild.tk/?attachment_id=68#main" class="wp-image-68" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/C8971C37-8882-41AB-9D1F-05C2C27AC8FF_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/C8971C37-8882-41AB-9D1F-05C2C27AC8FF_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/EE7EF7EF-FD7A-4AF0-BF15-CB9FEF2758C1_1_105_c.jpeg" alt="" data-id="69" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/EE7EF7EF-FD7A-4AF0-BF15-CB9FEF2758C1_1_105_c.jpeg" data-link="https://randomodbuild.tk/?attachment_id=69#main" class="wp-image-69" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/EE7EF7EF-FD7A-4AF0-BF15-CB9FEF2758C1_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/EE7EF7EF-FD7A-4AF0-BF15-CB9FEF2758C1_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/76C83DD7-D4F3-4CD0-8F87-B89127249E67_1_105_c.jpeg" alt="" data-id="70" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/76C83DD7-D4F3-4CD0-8F87-B89127249E67_1_105_c.jpeg" data-link="https://randomodbuild.tk/?attachment_id=70#main" class="wp-image-70" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/76C83DD7-D4F3-4CD0-8F87-B89127249E67_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/76C83DD7-D4F3-4CD0-8F87-B89127249E67_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/C704CD17-4E71-4FBE-9B81-1AE22D6C4228_1_105_c.jpeg" alt="" data-id="71" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/C704CD17-4E71-4FBE-9B81-1AE22D6C4228_1_105_c.jpeg" data-link="https://randomodbuild.tk/?attachment_id=71#main" class="wp-image-71" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/C704CD17-4E71-4FBE-9B81-1AE22D6C4228_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/C704CD17-4E71-4FBE-9B81-1AE22D6C4228_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/D43926DC-D35E-4448-980D-298F05473B3C_1_105_c.jpeg" alt="" data-id="72" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/D43926DC-D35E-4448-980D-298F05473B3C_1_105_c.jpeg" data-link="https://randomodbuild.tk/?attachment_id=72#main" class="wp-image-72" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/D43926DC-D35E-4448-980D-298F05473B3C_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/D43926DC-D35E-4448-980D-298F05473B3C_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/4F94A2D6-8406-4033-AE08-140416223B0A_1_105_c.jpeg" alt="" data-id="73" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/4F94A2D6-8406-4033-AE08-140416223B0A_1_105_c.jpeg" data-link="https://randomodbuild.tk/?attachment_id=73#main" class="wp-image-73" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/4F94A2D6-8406-4033-AE08-140416223B0A_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/4F94A2D6-8406-4033-AE08-140416223B0A_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/45BAC310-D060-42F2-926B-0C434DEF4262_1_105_c.jpeg" alt="" data-id="74" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/45BAC310-D060-42F2-926B-0C434DEF4262_1_105_c.jpeg" data-link="https://randomodbuild.tk/?attachment_id=74#main" class="wp-image-74" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/45BAC310-D060-42F2-926B-0C434DEF4262_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/45BAC310-D060-42F2-926B-0C434DEF4262_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
</ul><figcaption class="blocks-gallery-caption">The Library I took measurements from.</figcaption></figure> 

The nice lady who made the library was there, and I filled her in on our plan. She thought it was really cool, and even offered me some spare shingles that she used for the roof! Awesome! A few days later we had come up with the final dimensions for the library.<figure class="wp-block-gallery columns-3 is-cropped">

<ul class="blocks-gallery-grid">
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/9A449FD4-9B5F-4FF3-A091-250C87DFC149_1_105_c.jpeg" alt="" data-id="75" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/9A449FD4-9B5F-4FF3-A091-250C87DFC149_1_105_c.jpeg" data-link="https://randomodbuild.tk/?attachment_id=75#main" class="wp-image-75" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/9A449FD4-9B5F-4FF3-A091-250C87DFC149_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/9A449FD4-9B5F-4FF3-A091-250C87DFC149_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/BC02F9E1-70E7-4FF4-8D80-2851DE064272_1_105_c.jpeg" alt="" data-id="76" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/BC02F9E1-70E7-4FF4-8D80-2851DE064272_1_105_c.jpeg" data-link="https://randomodbuild.tk/?attachment_id=76#main" class="wp-image-76" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/BC02F9E1-70E7-4FF4-8D80-2851DE064272_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/BC02F9E1-70E7-4FF4-8D80-2851DE064272_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/376FFC11-D6CD-4F60-BA24-8599257BB9C1_1_105_c.jpeg" alt="" data-id="77" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/376FFC11-D6CD-4F60-BA24-8599257BB9C1_1_105_c.jpeg" data-link="https://randomodbuild.tk/?attachment_id=77#main" class="wp-image-77" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/376FFC11-D6CD-4F60-BA24-8599257BB9C1_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/376FFC11-D6CD-4F60-BA24-8599257BB9C1_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
</ul><figcaption class="blocks-gallery-caption">Some rough plans for our library.</figcaption></figure> 

This is what we originally came up with. We had some design requirements. It had to allow for a camera system. At this point in the project we knew we were doing a camera system, even if it turned out to be stolen or whoever knows what. In the notepad you can sort of see where the opening for the books would be. The roof would be flat and sloped to account for the solar panel on top. The whole front wouldn&#8217;t just be a door; there had to be space on the top of the opening to house a camera, and on the side to house the power supply. With this design, we always *could* add the camera, but it wouldn&#8217;t be too restrictive if we didn&#8217;t. We could simply take the internal divider (what separated the main book compartment from the power supply compartment) out to get even more book space if need be. As I said earlier, coming up with the design was the hardest part of the construction because we wanted it to be compatible with the camera system and we wanted it to be not too huge but also not too small.

Once we had come up with the rough design. I started drawing up the actual design and the shopping list.<figure class="wp-block-gallery columns-3 is-cropped">

<ul class="blocks-gallery-grid">
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="780" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/IMG_1664-copy-780x1024.jpg" alt="" data-id="82" data-link="http://randomodbuild.tk/?attachment_id=82#main" class="wp-image-82" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/IMG_1664-copy-780x1024.jpg 780w, https://www.randomodbuild.com/wp-content/uploads/2020/07/IMG_1664-copy-228x300.jpg 228w, https://www.randomodbuild.com/wp-content/uploads/2020/07/IMG_1664-copy-768x1009.jpg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/IMG_1664-copy-1169x1536.jpg 1169w, https://www.randomodbuild.com/wp-content/uploads/2020/07/IMG_1664-copy-1559x2048.jpg 1559w, https://www.randomodbuild.com/wp-content/uploads/2020/07/IMG_1664-copy-scaled.jpg 1949w" sizes="(max-width: 780px) 100vw, 780px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="751" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/IMG_1660-1-751x1024.jpg" alt="" data-id="81" data-link="http://randomodbuild.tk/?attachment_id=81#main" class="wp-image-81" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/IMG_1660-1-751x1024.jpg 751w, https://www.randomodbuild.com/wp-content/uploads/2020/07/IMG_1660-1-220x300.jpg 220w, https://www.randomodbuild.com/wp-content/uploads/2020/07/IMG_1660-1-768x1047.jpg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/IMG_1660-1-1126x1536.jpg 1126w, https://www.randomodbuild.com/wp-content/uploads/2020/07/IMG_1660-1-1502x2048.jpg 1502w, https://www.randomodbuild.com/wp-content/uploads/2020/07/IMG_1660-1-scaled.jpg 1877w" sizes="(max-width: 751px) 100vw, 751px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="733" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/IMG_1661-733x1024.jpg" alt="" data-id="79" data-link="http://randomodbuild.tk/?attachment_id=79#main" class="wp-image-79" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/IMG_1661-733x1024.jpg 733w, https://www.randomodbuild.com/wp-content/uploads/2020/07/IMG_1661-215x300.jpg 215w, https://www.randomodbuild.com/wp-content/uploads/2020/07/IMG_1661-768x1073.jpg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/IMG_1661-1100x1536.jpg 1100w, https://www.randomodbuild.com/wp-content/uploads/2020/07/IMG_1661-1466x2048.jpg 1466w, https://www.randomodbuild.com/wp-content/uploads/2020/07/IMG_1661-scaled.jpg 1833w" sizes="(max-width: 733px) 100vw, 733px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="884" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/IMG_1665-884x1024.jpg" alt="" data-id="80" data-link="http://randomodbuild.tk/?attachment_id=80#main" class="wp-image-80" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/IMG_1665-884x1024.jpg 884w, https://www.randomodbuild.com/wp-content/uploads/2020/07/IMG_1665-259x300.jpg 259w, https://www.randomodbuild.com/wp-content/uploads/2020/07/IMG_1665-768x890.jpg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/IMG_1665-1326x1536.jpg 1326w, https://www.randomodbuild.com/wp-content/uploads/2020/07/IMG_1665-1767x2048.jpg 1767w" sizes="(max-width: 884px) 100vw, 884px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="749" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/IMG_1663-copy-749x1024.jpg" alt="" data-id="83" data-link="https://randomodbuild.tk/?attachment_id=83#main" class="wp-image-83" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/IMG_1663-copy-749x1024.jpg 749w, https://www.randomodbuild.com/wp-content/uploads/2020/07/IMG_1663-copy-220x300.jpg 220w, https://www.randomodbuild.com/wp-content/uploads/2020/07/IMG_1663-copy-768x1049.jpg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/IMG_1663-copy-1124x1536.jpg 1124w, https://www.randomodbuild.com/wp-content/uploads/2020/07/IMG_1663-copy-1499x2048.jpg 1499w, https://www.randomodbuild.com/wp-content/uploads/2020/07/IMG_1663-copy-scaled.jpg 1874w" sizes="(max-width: 749px) 100vw, 749px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="742" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/IMG_1662-copy-742x1024.jpg" alt="" data-id="84" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/IMG_1662-copy-scaled.jpg" data-link="https://randomodbuild.tk/?attachment_id=84#main" class="wp-image-84" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/IMG_1662-copy-742x1024.jpg 742w, https://www.randomodbuild.com/wp-content/uploads/2020/07/IMG_1662-copy-217x300.jpg 217w, https://www.randomodbuild.com/wp-content/uploads/2020/07/IMG_1662-copy-768x1060.jpg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/IMG_1662-copy-1113x1536.jpg 1113w, https://www.randomodbuild.com/wp-content/uploads/2020/07/IMG_1662-copy-1484x2048.jpg 1484w, https://www.randomodbuild.com/wp-content/uploads/2020/07/IMG_1662-copy-scaled.jpg 1855w" sizes="(max-width: 742px) 100vw, 742px" /></figure>
  </li>
</ul><figcaption class="blocks-gallery-caption">Drawn up plans for our LFL</figcaption></figure> 

The next day we went to Lowes to get all the wood, paint, brackets, etc. Anything that was in the shopping list. Then, we started building. Jake and Nathan came over.<figure class="wp-block-gallery columns-3 is-cropped">

<ul class="blocks-gallery-grid">
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="1024" height="767" src="https://randomodbuild.tk/wp-content/uploads/2020/07/photo_2020-07-30-16.49.10-1024x767.jpeg" alt="" data-id="85" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/photo_2020-07-30-16.49.10.jpeg" data-link="https://randomodbuild.tk/?attachment_id=85#main" class="wp-image-85" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/photo_2020-07-30-16.49.10-1024x767.jpeg 1024w, https://www.randomodbuild.com/wp-content/uploads/2020/07/photo_2020-07-30-16.49.10-300x225.jpeg 300w, https://www.randomodbuild.com/wp-content/uploads/2020/07/photo_2020-07-30-16.49.10-768x575.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/photo_2020-07-30-16.49.10.jpeg 1276w" sizes="(max-width: 1024px) 100vw, 1024px" /><figcaption class="blocks-gallery-item__caption">Makeshift Sawhorses</figcaption></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="767" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/photo_2020-07-30-16.49.13-767x1024.jpeg" alt="" data-id="87" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/photo_2020-07-30-16.49.13.jpeg" data-link="https://randomodbuild.tk/?attachment_id=87#main" class="wp-image-87" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/photo_2020-07-30-16.49.13-767x1024.jpeg 767w, https://www.randomodbuild.com/wp-content/uploads/2020/07/photo_2020-07-30-16.49.13-225x300.jpeg 225w, https://www.randomodbuild.com/wp-content/uploads/2020/07/photo_2020-07-30-16.49.13-768x1025.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/photo_2020-07-30-16.49.13.jpeg 956w" sizes="(max-width: 767px) 100vw, 767px" /><figcaption class="blocks-gallery-item__caption">Not enough protection</figcaption></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="1024" height="767" src="https://randomodbuild.tk/wp-content/uploads/2020/07/photo_2020-07-30-16.49.21-1024x767.jpeg" alt="" data-id="88" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/photo_2020-07-30-16.49.21.jpeg" data-link="https://randomodbuild.tk/?attachment_id=88#main" class="wp-image-88" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/photo_2020-07-30-16.49.21-1024x767.jpeg 1024w, https://www.randomodbuild.com/wp-content/uploads/2020/07/photo_2020-07-30-16.49.21-300x225.jpeg 300w, https://www.randomodbuild.com/wp-content/uploads/2020/07/photo_2020-07-30-16.49.21-768x575.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/photo_2020-07-30-16.49.21.jpeg 1276w" sizes="(max-width: 1024px) 100vw, 1024px" /><figcaption class="blocks-gallery-item__caption">Stick to the plan!!</figcaption></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="1024" height="767" src="https://randomodbuild.tk/wp-content/uploads/2020/07/photo_2020-07-30-16.49.36-1024x767.jpeg" alt="" data-id="89" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/photo_2020-07-30-16.49.36.jpeg" data-link="https://randomodbuild.tk/?attachment_id=89#main" class="wp-image-89" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/photo_2020-07-30-16.49.36-1024x767.jpeg 1024w, https://www.randomodbuild.com/wp-content/uploads/2020/07/photo_2020-07-30-16.49.36-300x225.jpeg 300w, https://www.randomodbuild.com/wp-content/uploads/2020/07/photo_2020-07-30-16.49.36-768x575.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/photo_2020-07-30-16.49.36.jpeg 1276w" sizes="(max-width: 1024px) 100vw, 1024px" /><figcaption class="blocks-gallery-item__caption">Buds sanding</figcaption></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="1024" height="767" src="https://randomodbuild.tk/wp-content/uploads/2020/07/photo_2020-07-30-16.49.38-1024x767.jpeg" alt="" data-id="90" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/photo_2020-07-30-16.49.38.jpeg" data-link="https://randomodbuild.tk/?attachment_id=90#main" class="wp-image-90" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/photo_2020-07-30-16.49.38-1024x767.jpeg 1024w, https://www.randomodbuild.com/wp-content/uploads/2020/07/photo_2020-07-30-16.49.38-300x225.jpeg 300w, https://www.randomodbuild.com/wp-content/uploads/2020/07/photo_2020-07-30-16.49.38-768x575.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/photo_2020-07-30-16.49.38.jpeg 1276w" sizes="(max-width: 1024px) 100vw, 1024px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="1024" height="576" src="https://randomodbuild.tk/wp-content/uploads/2020/07/photo_2020-07-30-16.49.48-1024x576.jpeg" alt="" data-id="91" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/photo_2020-07-30-16.49.48.jpeg" data-link="https://randomodbuild.tk/?attachment_id=91#main" class="wp-image-91" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/photo_2020-07-30-16.49.48-1024x576.jpeg 1024w, https://www.randomodbuild.com/wp-content/uploads/2020/07/photo_2020-07-30-16.49.48-300x169.jpeg 300w, https://www.randomodbuild.com/wp-content/uploads/2020/07/photo_2020-07-30-16.49.48-768x432.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/photo_2020-07-30-16.49.48.jpeg 1280w" sizes="(max-width: 1024px) 100vw, 1024px" /><figcaption class="blocks-gallery-item__caption">Made a mess&#8230; seems familiar</figcaption></figure>
  </li>
</ul></figure> 

While we thought we were being productive, we only got the wood cut out and started sanding it, not much else. Then, we had winter break. After a vacation, I started work again. While it is not Nathan and Jake&#8217;s fault for living far away from the site of assembly, I did 99% of all assembly from then on. But they contributed more in other areas of the project, so I&#8217;d say it evened out.<figure class="wp-block-gallery columns-3 is-cropped">

<ul class="blocks-gallery-grid">
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/3F7C9E36-3ABE-4627-8CE0-B674EF73CC54_1_105_c.jpeg" alt="" data-id="92" data-link="https://randomodbuild.tk/?attachment_id=92#main" class="wp-image-92" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/3F7C9E36-3ABE-4627-8CE0-B674EF73CC54_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/3F7C9E36-3ABE-4627-8CE0-B674EF73CC54_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/EB0F2655-337D-4981-A072-9BECD1C26059_1_105_c.jpeg" alt="" data-id="93" data-link="https://randomodbuild.tk/?attachment_id=93#main" class="wp-image-93" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/EB0F2655-337D-4981-A072-9BECD1C26059_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/EB0F2655-337D-4981-A072-9BECD1C26059_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/EBEFF808-3C88-4851-A79C-F18101945F8A_1_105_c.jpeg" alt="" data-id="94" data-link="https://randomodbuild.tk/?attachment_id=94#main" class="wp-image-94" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/EBEFF808-3C88-4851-A79C-F18101945F8A_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/EBEFF808-3C88-4851-A79C-F18101945F8A_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/BCF35F2D-3D3A-494F-95D5-A0F24CB7FA06_1_105_c.jpeg" alt="" data-id="95" data-link="https://randomodbuild.tk/?attachment_id=95#main" class="wp-image-95" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/BCF35F2D-3D3A-494F-95D5-A0F24CB7FA06_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/BCF35F2D-3D3A-494F-95D5-A0F24CB7FA06_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/CC922E83-6ECD-48D9-845C-3D1E42FF1420_1_105_c.jpeg" alt="" data-id="96" data-link="https://randomodbuild.tk/?attachment_id=96#main" class="wp-image-96" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/CC922E83-6ECD-48D9-845C-3D1E42FF1420_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/CC922E83-6ECD-48D9-845C-3D1E42FF1420_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/EB0B1BD5-73DA-4EBC-A546-EBCC5D1192A1_1_105_c.jpeg" alt="" data-id="97" data-link="https://randomodbuild.tk/?attachment_id=97#main" class="wp-image-97" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/EB0B1BD5-73DA-4EBC-A546-EBCC5D1192A1_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/EB0B1BD5-73DA-4EBC-A546-EBCC5D1192A1_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/71AFAC5E-290C-426D-8A4C-ABFF4A0366EA_1_105_c.jpeg" alt="" data-id="98" data-link="https://randomodbuild.tk/?attachment_id=98#main" class="wp-image-98" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/71AFAC5E-290C-426D-8A4C-ABFF4A0366EA_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/71AFAC5E-290C-426D-8A4C-ABFF4A0366EA_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/99A9CAA6-F01E-4E03-B5F4-39017D5C9F9D_1_105_c.jpeg" alt="" data-id="99" data-link="https://randomodbuild.tk/?attachment_id=99#main" class="wp-image-99" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/99A9CAA6-F01E-4E03-B5F4-39017D5C9F9D_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/99A9CAA6-F01E-4E03-B5F4-39017D5C9F9D_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/7A7F3D2C-C89A-4925-B6D5-5922C944441C_1_105_c.jpeg" alt="" data-id="100" data-link="https://randomodbuild.tk/?attachment_id=100#main" class="wp-image-100" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/7A7F3D2C-C89A-4925-B6D5-5922C944441C_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/7A7F3D2C-C89A-4925-B6D5-5922C944441C_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/BBC52AE9-7B10-4340-920F-FA90BF82C8A2_1_105_c.jpeg" alt="" data-id="101" data-link="https://randomodbuild.tk/?attachment_id=101#main" class="wp-image-101" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/BBC52AE9-7B10-4340-920F-FA90BF82C8A2_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/BBC52AE9-7B10-4340-920F-FA90BF82C8A2_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/3A98E642-7038-4B49-B354-8D263702773F_1_105_c.jpeg" alt="" data-id="102" data-link="https://randomodbuild.tk/?attachment_id=102#main" class="wp-image-102" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/3A98E642-7038-4B49-B354-8D263702773F_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/3A98E642-7038-4B49-B354-8D263702773F_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/DE70E0F1-BB26-460F-92DE-1D4AA3875360_1_105_c.jpeg" alt="" data-id="103" data-link="https://randomodbuild.tk/?attachment_id=103#main" class="wp-image-103" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/DE70E0F1-BB26-460F-92DE-1D4AA3875360_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/DE70E0F1-BB26-460F-92DE-1D4AA3875360_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/BE04C53E-DA69-4847-B706-A2CA712DF09B_1_105_c.jpeg" alt="" data-id="104" data-link="https://randomodbuild.tk/?attachment_id=104#main" class="wp-image-104" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/BE04C53E-DA69-4847-B706-A2CA712DF09B_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/BE04C53E-DA69-4847-B706-A2CA712DF09B_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/D839980D-51E4-4D60-B8DA-4615CF00E509_1_105_c.jpeg" alt="" data-id="105" data-link="https://randomodbuild.tk/?attachment_id=105#main" class="wp-image-105" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/D839980D-51E4-4D60-B8DA-4615CF00E509_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/D839980D-51E4-4D60-B8DA-4615CF00E509_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/04595655-B1E8-4C2F-86DB-7EE42A31C2E3_1_105_c.jpeg" alt="" data-id="106" data-link="https://randomodbuild.tk/?attachment_id=106#main" class="wp-image-106" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/04595655-B1E8-4C2F-86DB-7EE42A31C2E3_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/04595655-B1E8-4C2F-86DB-7EE42A31C2E3_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/9139A1F5-1905-4947-A7BC-ECB37096F183_1_105_c.jpeg" alt="" data-id="107" data-link="https://randomodbuild.tk/?attachment_id=107#main" class="wp-image-107" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/9139A1F5-1905-4947-A7BC-ECB37096F183_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/9139A1F5-1905-4947-A7BC-ECB37096F183_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/18D26106-FA27-4224-B145-28BF7C926B56_1_105_c.jpeg" alt="" data-id="123" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/18D26106-FA27-4224-B145-28BF7C926B56_1_105_c.jpeg" data-link="https://randomodbuild.tk/?attachment_id=123#main" class="wp-image-123" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/18D26106-FA27-4224-B145-28BF7C926B56_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/18D26106-FA27-4224-B145-28BF7C926B56_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
</ul></figure> 

First, I finished sanding the individual pieces and applied a few coats to each. I painted the individual pieces instead of after the assembly because we wanted them to be more waterproof, and because we were using brackets instead of wood glue.<figure class="wp-block-gallery columns-3 is-cropped">

<ul class="blocks-gallery-grid">
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/AA95E90E-CBFA-4B70-A8C4-194836C9B5C5_1_105_c.jpeg" alt="" data-id="108" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/AA95E90E-CBFA-4B70-A8C4-194836C9B5C5_1_105_c.jpeg" data-link="https://randomodbuild.tk/?attachment_id=108#main" class="wp-image-108" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/AA95E90E-CBFA-4B70-A8C4-194836C9B5C5_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/AA95E90E-CBFA-4B70-A8C4-194836C9B5C5_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/BBF74780-696D-4612-96D3-B39DFB3DECD0_1_105_c.jpeg" alt="" data-id="109" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/BBF74780-696D-4612-96D3-B39DFB3DECD0_1_105_c.jpeg" data-link="https://randomodbuild.tk/?attachment_id=109#main" class="wp-image-109" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/BBF74780-696D-4612-96D3-B39DFB3DECD0_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/BBF74780-696D-4612-96D3-B39DFB3DECD0_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/A3DCA92A-9424-4786-B0DA-23A760B4DA49_1_105_c.jpeg" alt="" data-id="110" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/A3DCA92A-9424-4786-B0DA-23A760B4DA49_1_105_c.jpeg" data-link="https://randomodbuild.tk/?attachment_id=110#main" class="wp-image-110" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/A3DCA92A-9424-4786-B0DA-23A760B4DA49_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/A3DCA92A-9424-4786-B0DA-23A760B4DA49_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/B9E1897A-CFFD-4E6B-86CF-CB48A4B4542C_1_105_c.jpeg" alt="" data-id="111" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/B9E1897A-CFFD-4E6B-86CF-CB48A4B4542C_1_105_c.jpeg" data-link="https://randomodbuild.tk/?attachment_id=111#main" class="wp-image-111" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/B9E1897A-CFFD-4E6B-86CF-CB48A4B4542C_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/B9E1897A-CFFD-4E6B-86CF-CB48A4B4542C_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/12118518-53A3-4F39-BA23-DD27AB795FC6_1_105_c.jpeg" alt="" data-id="112" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/12118518-53A3-4F39-BA23-DD27AB795FC6_1_105_c.jpeg" data-link="https://randomodbuild.tk/?attachment_id=112#main" class="wp-image-112" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/12118518-53A3-4F39-BA23-DD27AB795FC6_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/12118518-53A3-4F39-BA23-DD27AB795FC6_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
</ul></figure> 

Then, I started assembling it. I also spray painted the brackets black before installing them.

After finding some old white paint to give the door some contrast from the rest of the LFL, it was done.<figure class="wp-block-image size-large">

<img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/ED8DB553-B948-4121-B6DB-86211A09F700_1_105_c.jpeg" alt="" class="wp-image-113" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/ED8DB553-B948-4121-B6DB-86211A09F700_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/ED8DB553-B948-4121-B6DB-86211A09F700_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /> </figure> 

What you see in the photo is the library. The roof was completed using shingles from the nice lady mentioned above, and from aluminum roof patch on the edges for waterproofing and a nice look. The door is constructed from standard 1&#215;2 and brackets. Also a typical cabinet/drawer knob. The window is a piece of Acrylic (sometimes called Plexiglass). I scored it over and over with a utility knife, then clamped it at the joint of 2 pieces of wood, and broken off. It is secured to the frame with screws and washers, with pieces of old bike inner tube as an inner seal and silicone caulking for the external seal. So boom. Done. The LFL was done.

Except for the camera system! I told you I would get back to this. So at this point in the project, we were mostly done with the library and decided to pull the trigger and setup the camera system. So I went to amazon and ordered a Lead Acid battery, a 20watt solar panel, and a cheap solar charge controller. The total cost of this was under $60 shipped. But how were we going to do the camera system? I had been brainstorming this and decided on a solution. Instead of overcomplicating things and trying to use a raspberry pi, I decided to use something that already has everything we need. A smartphone! I used my dad&#8217;s old HTC One X+. This thing was terribly slow and wasn&#8217;t being used at all, so perfect for this project. The battery life on it is terrible, but it is being plugged in to the solar charge controller all day, right? Plus, I rooted it a while back and it ran much smoother after I removed all the crap bloatware from it. A phone is great, because it has: a camera, easy to use script apps, and, connection to the internet where there is no WiFi. I used the app &#8220;Automate&#8221; and created a script where whenever the phone felt vibration (whenever somebody opens/closes the LFL door), it would wait 10 minutes, then delete the photo called &#8220;latest.jpg&#8221; in a directory. Then it would take a photo with the flash and with a filename of &#8220;latest.jpg&#8221;. There are also some delays and conditions in there, making it only take photos in the daytime and with a maximum of like 3 photos per day. So we have it take a photo. Now we need it to get the photo to a website. Pretty simple. I got a freedompop sim card and spent $16 all in configuring the plan so it wouldn&#8217;t &#8220;add credit to my account when I am 100mb away from my limit&#8221; or the other BS that they try to pull. But I can&#8217;t complain. With this, the phone has 200mb of data allowance FREE per month, plenty to upload the sub 1MB image files. The only downside is every now and then I get a $0.01 charge to my account for &#8220;account maintenance&#8221;. The only piece left in the puzzle for the camera system is uploading the image. I downloaded and configured an app called &#8220;DriveSync&#8221; to be constantly searching the directory where Automate saves the images and uploading them to a folder in my google drive. From there, the library website, <a rel="noreferrer noopener" href="https://littlecataloglfl.tk" target="_blank">https://littlecataloglfl.tk</a> uses a plugin called google drive gallery, which searches a specific folder in my google drive (the same one that DriveSync is syncing to) and displays any images found. The result: a website with an up to date version of what books are currently in stock in the LFL.<figure class="wp-block-image size-large">

<img loading="lazy" width="1024" height="471" src="https://randomodbuild.tk/wp-content/uploads/2020/07/Screen-Shot-2020-07-30-at-5.33.26-PM-1024x471.png" alt="" class="wp-image-114" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/Screen-Shot-2020-07-30-at-5.33.26-PM-1024x471.png 1024w, https://www.randomodbuild.com/wp-content/uploads/2020/07/Screen-Shot-2020-07-30-at-5.33.26-PM-300x138.png 300w, https://www.randomodbuild.com/wp-content/uploads/2020/07/Screen-Shot-2020-07-30-at-5.33.26-PM-768x353.png 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/Screen-Shot-2020-07-30-at-5.33.26-PM.png 1280w" sizes="(max-width: 1024px) 100vw, 1024px" /> </figure> 

It works pretty well! Here are some photos of the library with the electronics inside.<figure class="wp-block-gallery columns-3 is-cropped">

<ul class="blocks-gallery-grid">
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/4C54CD0C-975A-4461-8517-4F78E19300EC_1_105_c.jpeg" alt="" data-id="115" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/4C54CD0C-975A-4461-8517-4F78E19300EC_1_105_c.jpeg" data-link="https://randomodbuild.tk/?attachment_id=115#main" class="wp-image-115" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/4C54CD0C-975A-4461-8517-4F78E19300EC_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/4C54CD0C-975A-4461-8517-4F78E19300EC_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/5FB4CBD1-A151-4D27-9528-FA38DE79B3C0_1_105_c.jpeg" alt="" data-id="116" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/5FB4CBD1-A151-4D27-9528-FA38DE79B3C0_1_105_c.jpeg" data-link="https://randomodbuild.tk/?attachment_id=116#main" class="wp-image-116" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/5FB4CBD1-A151-4D27-9528-FA38DE79B3C0_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/5FB4CBD1-A151-4D27-9528-FA38DE79B3C0_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/95FB6004-8620-4187-835E-E3D7E32E6AF7_1_105_c.jpeg" alt="" data-id="117" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/95FB6004-8620-4187-835E-E3D7E32E6AF7_1_105_c.jpeg" data-link="https://randomodbuild.tk/?attachment_id=117#main" class="wp-image-117" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/95FB6004-8620-4187-835E-E3D7E32E6AF7_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/95FB6004-8620-4187-835E-E3D7E32E6AF7_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/ED499848-DF06-4ABE-AA4B-5C941D6E86BD_1_105_c.jpeg" alt="" data-id="118" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/ED499848-DF06-4ABE-AA4B-5C941D6E86BD_1_105_c.jpeg" data-link="https://randomodbuild.tk/?attachment_id=118#main" class="wp-image-118" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/ED499848-DF06-4ABE-AA4B-5C941D6E86BD_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/ED499848-DF06-4ABE-AA4B-5C941D6E86BD_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/F8E410D5-3CA1-4544-B0D1-DC6800B5BE6C_1_105_c.jpeg" alt="" data-id="119" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/F8E410D5-3CA1-4544-B0D1-DC6800B5BE6C_1_105_c.jpeg" data-link="https://randomodbuild.tk/?attachment_id=119#main" class="wp-image-119" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/F8E410D5-3CA1-4544-B0D1-DC6800B5BE6C_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/F8E410D5-3CA1-4544-B0D1-DC6800B5BE6C_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/85F4B1D5-DD0B-45B6-B645-5E1FE6CEFB00_1_105_c.jpeg" alt="" data-id="120" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/85F4B1D5-DD0B-45B6-B645-5E1FE6CEFB00_1_105_c.jpeg" data-link="https://randomodbuild.tk/?attachment_id=120#main" class="wp-image-120" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/85F4B1D5-DD0B-45B6-B645-5E1FE6CEFB00_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/85F4B1D5-DD0B-45B6-B645-5E1FE6CEFB00_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/F36F2EEC-2CA0-488D-A814-344B23935960_1_105_c.jpeg" alt="" data-id="121" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/F36F2EEC-2CA0-488D-A814-344B23935960_1_105_c.jpeg" data-link="https://randomodbuild.tk/?attachment_id=121#main" class="wp-image-121" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/F36F2EEC-2CA0-488D-A814-344B23935960_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/F36F2EEC-2CA0-488D-A814-344B23935960_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
</ul></figure> 

Also, the fundraiser! We started a GoFundMe to pay back the supplies used to build this library. Using the money we raised, were able to pay back my dad for the materials we bought, and we have some extra for future maintenance and improvements to the Library (because things do happen). <figure class="wp-block-image size-large">

<img loading="lazy" width="1024" height="497" src="https://randomodbuild.tk/wp-content/uploads/2020/07/Screen-Shot-2020-07-30-at-5.50.07-PM-1024x497.png" alt="" class="wp-image-122" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/Screen-Shot-2020-07-30-at-5.50.07-PM-1024x497.png 1024w, https://www.randomodbuild.com/wp-content/uploads/2020/07/Screen-Shot-2020-07-30-at-5.50.07-PM-300x146.png 300w, https://www.randomodbuild.com/wp-content/uploads/2020/07/Screen-Shot-2020-07-30-at-5.50.07-PM-768x373.png 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/Screen-Shot-2020-07-30-at-5.50.07-PM.png 1272w" sizes="(max-width: 1024px) 100vw, 1024px" /> </figure> 

The last part of the project was to plant it somewhere. But even now, the library still isn&#8217;t planted. This whole Covid-19 mess happened, and we wanted to put the LFL on a piece of city land. We wanted this library to get some good use, somewhere public but not too public, and we found the spot. It is a really nice place, but you know how this process can be. I am still in contact with somebody in the city, and I can promise that this library will be planted and used, and serve its purpose. It may not be at the same spot, it may be. But it will be put out there. This is us at the spot with the library:<figure class="wp-block-gallery columns-3 is-cropped">

<ul class="blocks-gallery-grid">
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/7BCD29F0-B7F8-4030-A78B-890657D4275B_1_105_c-2.jpeg" alt="" data-id="142" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/7BCD29F0-B7F8-4030-A78B-890657D4275B_1_105_c-2.jpeg" data-link="https://randomodbuild.tk/?attachment_id=142#main" class="wp-image-142" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/7BCD29F0-B7F8-4030-A78B-890657D4275B_1_105_c-2.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/7BCD29F0-B7F8-4030-A78B-890657D4275B_1_105_c-2-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/0610AF97-0D42-40D1-B83C-6E86FE5EA442_1_105_c-2.jpeg" alt="" data-id="143" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/0610AF97-0D42-40D1-B83C-6E86FE5EA442_1_105_c-2.jpeg" data-link="https://randomodbuild.tk/?attachment_id=143#main" class="wp-image-143" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/0610AF97-0D42-40D1-B83C-6E86FE5EA442_1_105_c-2.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/0610AF97-0D42-40D1-B83C-6E86FE5EA442_1_105_c-2-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/0C809EA9-E85E-4F6A-A9B5-67D964564DE0_1_105_c-2.jpeg" alt="" data-id="144" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/0C809EA9-E85E-4F6A-A9B5-67D964564DE0_1_105_c-2.jpeg" data-link="https://randomodbuild.tk/?attachment_id=144#main" class="wp-image-144" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/0C809EA9-E85E-4F6A-A9B5-67D964564DE0_1_105_c-2.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/0C809EA9-E85E-4F6A-A9B5-67D964564DE0_1_105_c-2-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/2E99346A-CE84-46B5-82FA-AE03B8DE4B2F_1_105_c-2.jpeg" alt="" data-id="145" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/2E99346A-CE84-46B5-82FA-AE03B8DE4B2F_1_105_c-2.jpeg" data-link="https://randomodbuild.tk/?attachment_id=145#main" class="wp-image-145" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/2E99346A-CE84-46B5-82FA-AE03B8DE4B2F_1_105_c-2.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/2E99346A-CE84-46B5-82FA-AE03B8DE4B2F_1_105_c-2-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="1024" height="768" src="https://randomodbuild.tk/wp-content/uploads/2020/07/5E3A5A12-9166-4F92-8C3E-C9C86B1BF325_1_105_c-2.jpeg" alt="" data-id="147" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/5E3A5A12-9166-4F92-8C3E-C9C86B1BF325_1_105_c-2.jpeg" data-link="https://randomodbuild.tk/?attachment_id=147#main" class="wp-image-147" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/5E3A5A12-9166-4F92-8C3E-C9C86B1BF325_1_105_c-2.jpeg 1024w, https://www.randomodbuild.com/wp-content/uploads/2020/07/5E3A5A12-9166-4F92-8C3E-C9C86B1BF325_1_105_c-2-300x225.jpeg 300w, https://www.randomodbuild.com/wp-content/uploads/2020/07/5E3A5A12-9166-4F92-8C3E-C9C86B1BF325_1_105_c-2-768x576.jpeg 768w" sizes="(max-width: 1024px) 100vw, 1024px" /></figure>
  </li>
</ul></figure> 

I remember in the beginning of the year, my teacher said our goal for the project should be to make the news. I remember thinking that this was a high but achievable goal. Cut to after the library was built. We were looking for a home for the library, so I made a post on Nextdoor.<figure class="wp-block-image size-large">

<img loading="lazy" width="583" height="621" src="https://randomodbuild.tk/wp-content/uploads/2020/11/littlefreelibrarynextdoor.png" alt="" class="wp-image-184" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/11/littlefreelibrarynextdoor.png 583w, https://www.randomodbuild.com/wp-content/uploads/2020/11/littlefreelibrarynextdoor-282x300.png 282w" sizes="(max-width: 583px) 100vw, 583px" /> </figure> 

The next morning, I got a PM from somebody at SpectrumLocalNews, and later that day, we were interviewed! Even though it was only a recorded video and for a local news channel, we still made the news.<figure class="wp-block-gallery columns-3 is-cropped">

<ul class="blocks-gallery-grid">
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/B8DDEF43-F043-4C65-A8FE-D0CA6800072B_1_105_c.jpeg" alt="" data-id="126" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/B8DDEF43-F043-4C65-A8FE-D0CA6800072B_1_105_c.jpeg" data-link="https://randomodbuild.tk/?attachment_id=126#main" class="wp-image-126" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/B8DDEF43-F043-4C65-A8FE-D0CA6800072B_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/B8DDEF43-F043-4C65-A8FE-D0CA6800072B_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="768" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/CCEBD433-AF08-49E6-A9BD-8FEBBE26F96E_1_105_c.jpeg" alt="" data-id="127" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/CCEBD433-AF08-49E6-A9BD-8FEBBE26F96E_1_105_c.jpeg" data-link="https://randomodbuild.tk/?attachment_id=127#main" class="wp-image-127" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/CCEBD433-AF08-49E6-A9BD-8FEBBE26F96E_1_105_c.jpeg 768w, https://www.randomodbuild.com/wp-content/uploads/2020/07/CCEBD433-AF08-49E6-A9BD-8FEBBE26F96E_1_105_c-225x300.jpeg 225w" sizes="(max-width: 768px) 100vw, 768px" /></figure>
  </li>
  <li class="blocks-gallery-item">
    <figure><img loading="lazy" width="576" height="1024" src="https://randomodbuild.tk/wp-content/uploads/2020/07/C0BD4DA7-117E-49BE-A836-ABB4165BAF31_1_105_c-576x1024.jpeg" alt="" data-id="128" data-full-url="https://randomodbuild.tk/wp-content/uploads/2020/07/C0BD4DA7-117E-49BE-A836-ABB4165BAF31_1_105_c.jpeg" data-link="https://randomodbuild.tk/?attachment_id=128#main" class="wp-image-128" srcset="https://www.randomodbuild.com/wp-content/uploads/2020/07/C0BD4DA7-117E-49BE-A836-ABB4165BAF31_1_105_c-576x1024.jpeg 576w, https://www.randomodbuild.com/wp-content/uploads/2020/07/C0BD4DA7-117E-49BE-A836-ABB4165BAF31_1_105_c-169x300.jpeg 169w, https://www.randomodbuild.com/wp-content/uploads/2020/07/C0BD4DA7-117E-49BE-A836-ABB4165BAF31_1_105_c.jpeg 665w" sizes="(max-width: 576px) 100vw, 576px" /></figure>
  </li>
</ul></figure> 

Here is the video in all of its glory 🙂<figure class="wp-block-video"><video src="https://randomodbuild.tk/wp-content/uploads/2020/07/LittleFreeLibraryNews-1.mp4"></video></figure> 

So why am I posting this just now to the website? I hope that eventually this idea will catch on. Sure, there are shortcomings. Cameras will be stolen, some don&#8217;t see the point of it, but I hope others do. Someday I hope to expand this idea, possibly making more libraries, or maybe using OCR and setting up a real catalogue. The beauty of this current system is that it doesn&#8217;t hinder anybody&#8217;s use of the library. You don&#8217;t have to scan any QR codes, you don&#8217;t have to log which books are in every time you use it, everything is automated. Sometimes the simplest solutions work the best, and I&#8217;d say the current solution is pretty simple. Maybe eventually the Little Free Library™ website will have a catalogue of books using this technique, which would be super cool. First, we have to get the library planted, before we even talk about future plans though(although I would definitely not mind helping others if they wanted to do something similar to this) but after.

Alrighty! If you made it this far pat yourself on the back! If you just skipped ahead than I would recommend you at least check out the photos, some are interesting. Here is the link to the website where you can see the books: <https://littlecataloglfl.tl>\
And here is the link to the news article/video:\
<https://spectrumlocalnews.com/nc/charlotte/news/2020/01/25/eighth-graders-build-little-free-library-with-solar-powered-camera>  

If you have any other questions or comments, feel free to use the comments section below!