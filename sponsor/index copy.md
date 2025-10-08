---
title: Why Sponsor OWASP BeNeLux Days 2025?
layout: sponsor
---

OWASP chapter Meetings & Events are the heartbeat of the application and
product security community, aimed to spread knowledge and learn from each
other.

The local Chapters of OWASP in The Netherlands and Belgium come together
every year to host a physical event called **“OWASP BeNeLux Days”** which this
year is happening in the heart of the City of Mechlen in Begium. It brings
together a wide range of security technologists, from executives to individual
contributors across SMBs and major corporations.These are important
influencers and decision makers who drive the buying decisions for investments
in security.

This event presents sponsors with a unique opportunity to elevate their brand
visibility among a select group of influential individuals through our competitive
sponsorship packages.

We would be proud to work alongside and partner with vendors and
organizations who believe in our mission to educate, inspire, and spread
security awareness. Your support for our event will not only align and recognize
your **brand** with key influencers, our community but also resonate with
thousands of **potential customers**.
By sponsoring our event, your message will be strategically tailored to engage
with specific personas within our community who are active contributors and
participants. This targeted approach ensures that your brand receives
maximum exposure and recognition among our audience, ultimately driving
demand and boosting brand awareness.

Our sponsorship packages are designed to provide sponsors with maximum
exposure and engagement, allowing them to showcase their brand in a
compelling and impactful way.

OWASP globally has established strategic relationships with many major media
groups worldwide and in BeNeLux, focused on IT security—print publications,
newsletters, portals, consultants, associations, and user groups. Your
message—and leadership positioning—reaches thousands of prospects before
you even arrive at OWASP events.

Please know that due to the high-profile nature of our non-profit organization,
limited sponsorship opportunities are available and sell rapidly - so we urge you
to act quickly!

We would love to welcome you and your organization and hope to see you at
the event.

All proceeds from sponsorship support the mission of the OWASP Foundation
(represented in Europe by OWASP Europe VZW, non-profit under Belgian Law).
Supporting these events drives the funding for research grants, tools and documents, local
chapters, and more*

# About the BeNeLux Event

OWASP BeNeLux 2025 will take place on **Tuesday, 2 December, and Wednesday, 3
December, 2025**, at **Lamot, Mechelen, Belgium**. This two-day event brings together
security professionals from Belgium, the Netherlands, and beyond to share
knowledge, learn from industry experts, and discuss emerging trends in application
security.

The event features:
- The Conference on 2nd of December featuring international and local speakers
covering key OWASP topics and broader challenges of Security.
- Hands-On training sessions on 3rd of December delivered by experienced
practitioners on security topics.

Our chapters regularly organize meetings with expert talks and panel discussions,
typically gathering around **80 attendees** and reaching over **1,500 security
practitioners** across Belgium and the Netherlands.

OWASP BeNeLux has a strong tradition of fostering community and knowledge-
sharing. Previous editions, held at venues such as the University of Leuven, CORDA
Campus in Hasselt, RAI Amsterdam, Jaarbeurs Utrecht, and the University of
Luxembourg, have brought together over an average of 280 attendees from across the
region. In 2025, we aim to welcome more than 250 participants, continuing to build
connections and share insights with the security community.

**Location** : Lamot Conference Center, Mechelen, Belgium
**Date:** December 2-3, 2025

# Sponsorship packages
- This is for the conference on **2nd of December 2025**.
- We provide three sponsorship tiers: Platinum, Gold and Silver.
- Additionally, there are opportunities to sponsor specific items like social events
as well (details here).

# Sponsorship package details:


<div class="price-table-container">
{% assign sp = site.data.sponsorpackages %}
{% assign spPlatinum = sp.levels | where:"name", "Platinum" | first %}
{% assign spGold = sp.levels | where:"name", "Gold" | first %}
{% assign spSilver = sp.levels | where:"name", "Silver" | first %}
  <table class="price-table">
    <thead>
      <tr>
        <th>Feature</th>
        <th>{{ spPlatinum.name }}</th>
        <th>{{ spGold.name }}</th>
        <th>{{ spSilver.name }}</th>
      </tr>
    </thead>
    <tbody>
      {% for feature in sp.features %}
      {% assign ftPlatinum = spPlatinum.features | where:"name", feature.name | first %}
      {% assign ftGold = spGold.features | where:"name", feature.name | first %}
      {% assign ftSilver = spSilver.features | where:"name", feature.name | first %}
      <tr>
        <td>{{ feature.text }}</td>
        <td>{% include sponsorfeature.part feature = ftPlatinum %}</td>
        <td>{% include sponsorfeature.part feature = ftGold %}</td>
        <td>{% include sponsorfeature.part feature = ftSilver %}</td>
      </tr>
      {% endfor %}
    </tbody>
  </table>
</div>

<div class="notes">
  <p>(*) The speaking slot will be clearly marked as a sponsor speaking slot at the start/end of normal talks.</p>
  <p>(**)Social sponsorship at the OWASP Benelux conference entails hosting
the evening event near or in the conference venue, providing attendees
with dinner and drinks. As a social sponsor, you'll have the opportunity to
engage with conference participants in a relaxed setting, fostering
networking and camaraderie among industry professionals. Please
contact us for more options and details around Social Event Sponsorship.</p>
  <p>(***) With a opt-out after first year (without loosing the 10% discount)</p>
  <p>(***) Order of choice is based on order of commitment and paid sponsorships.</p>
</div>

<div class="contact-us-small">
  <h3>Contact us:</h3>
  <ul>
    <li>
      <strong>Priyam Awasthy</strong>
      -
      <a href="mailto:priyam.awasthy@owasp.org">priyam.awasthy@owasp.org</a>
    </li>
    <li>
      <strong>Amit Sharma</strong>
      -
      <a href="mailto:amit.sharma@owasp.org">amit.sharma@owasp.org</a>
    </li>
    <li>
      <strong>Stella Dineva</strong>
      -
      <a href="mailto:stella.dineva@owasp.org">stella.dineva@owasp.org</a>
    </li>
  </ul>
  <a class="btn db" href="{{ site.baseurl }}/assets/files/OWASP_Sponsorship_Brochure_Benelux_2025.pdf" download>Download our sponsor brochure</a>  
</div>



