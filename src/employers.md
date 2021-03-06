---
tags: nav
title: Employers
layout: default.liquid
---

<style>
  .grid {
    display: grid;
    grid-template-columns: repeat(12, [col-start] 1fr);
  }

  .employers-hero-img,
  .employers-services,
  .employers-we-ensure,
  .employers-stock-img-1,
  .employers-diversity {
    grid-column: 1 / -1;
  }
</style>
<div class="grid">

  <div class="employers-hero-img" data-aos="fade-up">
    <div class="employers-hero-text">
      <h1 class="text-light-green text-left" style="font-size: 92px; line-height: .75;">EMPLOYERS</h1>
      <p>We are your recruitment team</p>
    </div>
  </div>

  <div class="employers-services" data-aos="fade-up">
    <h1 class="mb-0">OUR SERVICES</h1>
    <p class="text-center"style="font-size: 22px;">Staffing any job can be a time-consuming project</p>
    <p class="text-center" style="font-size:20px;">Advertising, recruiting, sorting through hundreds of applications to select a few candidates for interviews, and selecting the best fit for your company; it takes away time and attention you’d be better off spending on other parts of your business.
      And in the cannabis industry, the process is made even more difficult by the limited number of experienced candidates and the complex regulations and required background checks. By working with our firm, you’ll not only save time and effort, you
      can also rest assured that you will be presented with highly qualified, skilled and motivated candidates. We are dedicated to providing you with the exceptional candidates you need for your company to thrive and grow.</p>
  </div>

  <div class="employers-we-ensure text-center" data-aos="fade-up">
    <h1 class="text-center quick-size-fix">WE ENSURE THAT THE CANDIDATES WE RECOMMEND ARE THE PERFECT MATCH BY TAKING TIME TO UNDERSTAND YOUR COMPANY’S CULTURE AND VALUES</h1>
    <a href="/employer-form" class="text-white text-center" style="font-weight: bold; text-decoration: none;">HOW CAN WE HELP? ></a>
  </div>

  <div class="employers-stock-img-1" data-aos="fade-up">
    <img alt=" " src="img/banner-2.jpg" style="width:100%" />
  </div>

  <div class="employers-diversity" data-aos="fade-up">
    <h1 class="text-left">Why does diversity matter?</h1>
    <p>Diversity is far more than just a moral issue. It’s a business necessity for any company in the 21st century — especially for cannabis businesses, which face opportunities and challenges unlike any other industry. It’s no secret that the medical and
      legal cannabis industries are highly scrutinized. This scrutiny extends to the diversity of the staff of prospective businesses. Several of the most recent states to create a competitive cannabis dispensary application process have requested information
      about the diversity of the applicants.</p>
    <p>
      We will help you find candidates that are aware of and sensitive to the diversity among your customers and stakeholders. With our help, you can build your brand as one of the rare cannabis businesses to connect across communities.
    </p>
    <p>And most importantly, you will find that by bringing together a team with different backgrounds, your workforce will be well equipped to creatively and effectively handle the unpredictable nature of the cannabis business.</p>
  </div>

</div>

{% include partials/for-employers.html %}
{% include partials/testimonials.html %}