---
layout: post
title:  "Recap of Presentation at RUG:B August Meeting on Engines and Spree 2.0"
author: pickledolives 
date:   2013-08-02 12:54:20
categories: rails engines spree2 presentation
---

On thursday evening on the 1. of August I had the chance to give a talk on Rails Engines and Spree Commerce 2.0 @ RUG:B. Since it is a Ruby group and not everyone is even working with Rails, I did not want to dig to deep into details or code. Instead I gave a brief overview on what Rails Engines are and what they are good for and how kickass Spree is and tried to create some curiosity amongst the audience and advertise for our river-spree group.

I'll tryto sum up my presentation here in a few sentences to explain the [slides you find here]({{ site.root }}/pdf/engines_spree_2_0.pdf) a bit.

\[1..4] Spree Commerce is a Rails Engine and Rails Engines are made for fitting a certain business case to a max. Spree's business case is Ecommerce and there is no better Rails solution out there and no better Open Source solution in general, imho. That's because you'll usually need to customize shops which requires you to understand the code and that's best with Ruby, because Ruby is the most expressive programming language out there and Rails just makes far better sense than any other web dev framework I've seen so far.

\[5..7] Spree has an excellent documentation to get started and some demo instances as well. It brings in the power of a bunch of battle hardened Gems like ActiverMerchant for payments, Devise for authentication, Paperclip for file uploads and many more. To get started Rails, Bundler and imagemagick need to be installed on your system. 

\[7..12] Hitting a few generator commands as on page 7 will instantly bring up your demo shop. You can try, you can test, you can play. You're up and running immediately and don't forget to check out the backend with the default sample login. Once you got familiar it is time to start customizing. First step of course is to check for extensions, themes and considering integration of a CMS. Every line you do not write yourself is a line you do not need to maintain. 'Manual' customization can be done using Deface, which is basically inserting html snippets before / behind certain Spree view elements which are all marked by data-hooks. You may use Decorators on Controllers and Models and last bust not least overwriting is always an option.

\[13..14] Spree by default comes with a Jirafe reporting and analysis dashboard, just what Yoav Aner presented to us before in 'measure anything'. The API is very nicely put up and gives detailed feedback, just try it out.

\[16..21] In Spree 2.0 backend and frontend are now extracted from core into own modulues, which enables you to write own frontends in Angular oder Ember for example. There is a big deal about split shipments recently, but I personally have no experience with that, selling digital goods myself. As far as I got it you can better manage multiple warehouses alias stock locations and pick shipment methods and split packages by several conditions. The API has been extended and you are now able to define custom RABL templates for API responses. Furthermore there has been serious internationalization improvements, especially enabling you to translate product descriptions and taxonomies directly in your backend.

So, I hope you got the motivation now to dive into Spree Commerce and if you are Berlin based or Germany based or for whatever reason feel like joining us, you'll find all our contact data below. I consider the presentation to be a success, since nobody complained and we actually found a fourth member in the audience. Yay!

Enjoy, Oliver
