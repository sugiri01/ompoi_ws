# OMPOI Website Content Replacements Guide

**Complete HTML Content Replacement Instructions**

This document provides exact text replacements for converting the Gettree template to OMPOI (Online Marketplace of India) website.

---

## 📋 Table of Contents

1. [Global Replacements (All Files)](#global-replacements)
2. [index.html (Home Page)](#indexhtml-home-page)
3. [about.html (About Page)](#abouthtml-about-page)
4. [services.html (Services Page)](#serviceshtml-services-page)
5. [service-details.html (Service Details)](#service-detailshtml-service-details)
6. [case-study.html (Case Studies)](#case-studyhtml-case-studies)
7. [case-details.html (Case Details)](#case-detailshtml-case-details)
8. [blog.html (Blog Listing)](#bloghtml-blog-listing)
9. [blog-detail.html (Blog Post)](#blog-detailhtml-blog-post)
10. [faq.html (FAQ Page)](#faqhtml-faq-page)
11. [team.html (Team Page)](#teamhtml-team-page)
12. [contact.html (Contact Page)](#contacthtml-contact-page)

---

## Global Replacements (All Files)

Apply these replacements across **ALL** HTML files:

### Title & Meta Tags

```html
<!-- FIND -->
<title>Gettree - Garden & Landscaping</title>

<!-- REPLACE WITH -->
<title>OMPOI - Online Marketplace of India | Agricultural Commodities Trading Platform</title>
```

```html
<!-- FIND -->
<meta name="author" content="themesflat.com">

<!-- REPLACE WITH -->
<meta name="author" content="OMPOI">
```

```html
<!-- ADD after <meta name="author"> -->
<meta name="description" content="India's most transparent digital marketplace for agricultural commodities. Connect with verified suppliers, access real-time pricing intelligence, and streamline procurement.">
```

### Logo & Brand

```html
<!-- FIND -->
<img src="https://themesflat.co/html/gettree/icon/logo-dark.png" alt="images">

<!-- REPLACE WITH -->
<img src="icon/Ompoi-logo-final-dark.png" alt="OMPOI - Online Marketplace of India">
```

```html
<!-- FIND (light logo) -->
<img src="https://themesflat.co/html/gettree/icon/logo.png" alt="images">

<!-- REPLACE WITH -->
<img src="icon/Ompoi-logo-final-light.png" alt="OMPOI">
```

### Top Bar Contact Information

```html
<!-- FIND -->
<span class="top-location">2072 Pinnickinick Street, WA 98370</span>

<!-- REPLACE WITH -->
<span class="top-location">Chennai, Tamil Nadu, India · Mumbai · Bangalore</span>
```

```html
<!-- FIND -->
<span class="top-mail"><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="...">[email&#160;protected]</a></span>

<!-- REPLACE WITH -->
<span class="top-mail"><a href="mailto:info@ompoi.com">info@ompoi.com</a></span>
```

```html
<!-- FIND -->
<span class="top-phone">1-800-643-4500</span>

<!-- REPLACE WITH -->
<span class="top-phone">+91-XXXXXXXXXX</span>
```

### Footer Content

```html
<!-- FIND (Footer About Text) -->
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum et ligula purus. Nulla facilisi. Integer accumsan...</p>

<!-- REPLACE WITH -->
<p>OMPOI (Online Marketplace of India) is a comprehensive digital platform connecting buyers, sellers, agents, and logistics providers in the agricultural commodities sector. We bring transparency, efficiency, and intelligence to traditional supply chains.</p>
```

```html
<!-- FIND (Footer Copyright) -->
<p class="copyright">Copyright 2021, Gettree. Design by ThemesFlat. All Rights Reserved.</p>

<!-- REPLACE WITH -->
<p class="copyright">© 2025 OMPOI - Online Marketplace of India. All rights reserved.</p>
```

```html
<!-- FIND (Footer Address) -->
<li>2072 Pinnickinick Street, WA 98370</li>

<!-- REPLACE WITH -->
<li>Headquarters: Chennai, Tamil Nadu, India</li>
```

```html
<!-- FIND (Footer Email) -->
<li><a href="mailto:themesflat@gmail.com">themesflat@gmail.com</a></li>

<!-- REPLACE WITH -->
<li><a href="mailto:info@ompoi.com">info@ompoi.com</a></li>
<li><a href="mailto:support@ompoi.com">support@ompoi.com</a></li>
```

```html
<!-- FIND (Footer Phone) -->
<li>+800-123-4567</li>

<!-- REPLACE WITH -->
<li>+91-XXXXXXXXXX</li>
```

---

## index.html (Home Page)

### Hero Section

```html
<!-- FIND (Main Heading) -->
<h2 class="mainn-heading">Garden & Landscaping<br> Services</h2>

<!-- REPLACE WITH -->
<h2 class="mainn-heading">India's Most Transparent<br> Digital Marketplace</h2>
```

```html
<!-- FIND (Hero Subheading) -->
<p class="sub-heading">We Are Professional & Experienced</p>

<!-- REPLACE WITH -->
<p class="sub-heading">For Agricultural Commodities Trading</p>
```

```html
<!-- FIND (Hero Description) -->
<p class="description">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum et ligula purus...</p>

<!-- REPLACE WITH -->
<p class="description">Connect with 300+ verified suppliers, access real-time pricing intelligence, and streamline your entire procurement workflow from request to delivery.</p>
```

```html
<!-- FIND (Hero CTA Button) -->
<a href="#" class="flat-button">Get Started</a>

<!-- REPLACE WITH -->
<a href="/signup" class="flat-button">Get Started</a>
```

```html
<!-- FIND (Hero Secondary CTA) -->
<a href="#" class="flat-button style-2">Learn More</a>

<!-- REPLACE WITH -->
<a href="/demo" class="flat-button style-2">Request a Demo</a>
```

### Why Choose Us Section

```html
<!-- FIND (Section Title) -->
<h2 class="title-section">Why Choose Us</h2>
<p class="sub-title-section">Professional Landscaping Services</p>

<!-- REPLACE WITH -->
<h2 class="title-section">Why Choose OMPOI</h2>
<p class="sub-title-section">Transparent, Intelligent, and Efficient Trading Platform</p>
```

#### Feature Box 1

```html
<!-- FIND -->
<h3 class="title-feature-box">Landscaping Design</h3>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>

<!-- REPLACE WITH -->
<h3 class="title-feature-box">Verified Supplier Network</h3>
<p>Access 300+ KYC-verified suppliers across India. Every vendor undergoes rigorous quality checks and compliance verification to ensure reliability and trust.</p>
```

#### Feature Box 2

```html
<!-- FIND -->
<h3 class="title-feature-box">Garden Care</h3>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>

<!-- REPLACE WITH -->
<h3 class="title-feature-box">Transparent Pricing</h3>
<p>Get real-time market quotes and competitive bids. Our platform provides complete pricing visibility, helping you make informed procurement decisions.</p>
```

#### Feature Box 3

```html
<!-- FIND -->
<h3 class="title-feature-box">Tree Plantation</h3>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>

<!-- REPLACE WITH -->
<h3 class="title-feature-box">Integrated Logistics</h3>
<p>Seamless coordination from warehouse to destination. Track shipments in real-time with structured delivery updates and dispatch management.</p>
```

#### Feature Box 4

```html
<!-- FIND -->
<h3 class="title-feature-box">Lawn Maintenance</h3>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>

<!-- REPLACE WITH -->
<h3 class="title-feature-box">AI-Powered Intelligence</h3>
<p>Leverage machine learning for demand forecasting, pricing trends, and procurement analytics. Make data-driven decisions with confidence.</p>
```

### About/Introduction Section

```html
<!-- FIND (About Section Title) -->
<h2 class="title-section">About Gettree</h2>
<p class="sub-title-section">We Are Professional Landscapers</p>

<!-- REPLACE WITH -->
<h2 class="title-section">About OMPOI</h2>
<p class="sub-title-section">Transforming India's Agricultural Supply Chains</p>
```

```html
<!-- FIND (About Description) -->
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum et ligula purus. Nulla facilisi. Integer accumsan semper odio, vel vulputate tellus interdum sed...</p>

<!-- REPLACE WITH -->
<p>OMPOI (Online Marketplace of India) revolutionizes how agricultural commodities are bought and sold across India. We unite buyers, sellers, agents, and logistics providers on one transparent, intelligent platform powered by AI-driven analytics and real-time tracking.</p>
```

```html
<!-- FIND (Additional About Text) -->
<p>Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris...</p>

<!-- REPLACE WITH -->
<p>From small-scale farmers to large exporters, OMPOI provides tools and insights that level the playing field, enabling better business outcomes through verified suppliers, transparent pricing, and data-driven intelligence.</p>
```

### How It Works / Process Section

```html
<!-- FIND (Section Title) -->
<h2 class="title-section">How It Works</h2>

<!-- REPLACE WITH -->
<h2 class="title-section">How OMPOI Works</h2>
```

#### Step 1

```html
<!-- FIND -->
<h3 class="title-step">Consulation</h3>
<p>Lorem ipsum dolor sit amet consectetur adipiscing elit...</p>

<!-- REPLACE WITH -->
<h3 class="title-step">Post Your Requirement</h3>
<p>Share product specifications, quantity, delivery location, and timeline through our intuitive interface</p>
```

#### Step 2

```html
<!-- FIND -->
<h3 class="title-step">Design Concept</h3>
<p>Lorem ipsum dolor sit amet consectetur adipiscing elit...</p>

<!-- REPLACE WITH -->
<h3 class="title-step">Receive Competitive Bids</h3>
<p>Get quotes from multiple verified suppliers within 24 hours, complete with pricing breakdowns</p>
```

#### Step 3

```html
<!-- FIND -->
<h3 class="title-step">Installation</h3>
<p>Lorem ipsum dolor sit amet consectetur adipiscing elit...</p>

<!-- REPLACE WITH -->
<h3 class="title-step">Choose & Confirm</h3>
<p>Compare offers side-by-side, negotiate terms if needed, and confirm your order securely</p>
```

#### Step 4

```html
<!-- FIND -->
<h3 class="title-step">Maintenance</h3>
<p>Lorem ipsum dolor sit amet consectetur adipiscing elit...</p>

<!-- REPLACE WITH -->
<h3 class="title-step">Track Your Delivery</h3>
<p>Monitor shipment status from dispatch to doorstep with real-time GPS tracking and automated notifications</p>
```

### Statistics/Counter Section

```html
<!-- FIND (Counter 1) -->
<h3 class="number-counter">1250</h3>
<p class="title-counter">Happy Clients</p>

<!-- REPLACE WITH -->
<h3 class="number-counter">300+</h3>
<p class="title-counter">Verified Suppliers</p>
```

```html
<!-- FIND (Counter 2) -->
<h3 class="number-counter">2500</h3>
<p class="title-counter">Projects Done</p>

<!-- REPLACE WITH -->
<h3 class="number-counter">2000+</h3>
<p class="title-counter">Successful Shipments</p>
```

```html
<!-- FIND (Counter 3) -->
<h3 class="number-counter">780</h3>
<p class="title-counter">Awards Won</p>

<!-- REPLACE WITH -->
<h3 class="number-counter">4.8/5</h3>
<p class="title-counter">Customer Satisfaction</p>
```

```html
<!-- FIND (Counter 4) -->
<h3 class="number-counter">95</h3>
<p class="title-counter">Experienced Staff</p>

<!-- REPLACE WITH -->
<h3 class="number-counter">&lt;24h</h3>
<p class="title-counter">Average Quote Time</p>
```

### Services Section (on Home Page)

```html
<!-- FIND (Services Section Title) -->
<h2 class="title-section">Our Services</h2>
<p class="sub-title-section">Professional Landscaping Services</p>

<!-- REPLACE WITH -->
<h2 class="title-section">Our Services</h2>
<p class="sub-title-section">Comprehensive Solutions for Modern Commodity Trading</p>
```

#### Service 1

```html
<!-- FIND -->
<h3 class="title-service-box">Garden Landscaping</h3>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>

<!-- REPLACE WITH -->
<h3 class="title-service-box">Sourcing & Vendor Verification</h3>
<p>Connect with 300+ KYC-verified suppliers. Rigorous quality and compliance checks ensure reliability.</p>
```

#### Service 2

```html
<!-- FIND -->
<h3 class="title-service-box">Lawn Care</h3>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>

<!-- REPLACE WITH -->
<h3 class="title-service-box">Pricing Intelligence & Forecasting</h3>
<p>Real-time market data, pricing trends, and AI-powered forecasts for informed decisions.</p>
```

#### Service 3

```html
<!-- FIND -->
<h3 class="title-service-box">Tree Plantation</h3>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>

<!-- REPLACE WITH -->
<h3 class="title-service-box">Logistics & Fulfillment</h3>
<p>End-to-end logistics with real-time tracking, dispatch management, and delivery confirmation.</p>
```

#### Service 4

```html
<!-- FIND -->
<h3 class="title-service-box">Hedge Trimming</h3>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>

<!-- REPLACE WITH -->
<h3 class="title-service-box">Quality & Traceability</h3>
<p>End-to-end traceability systems and quality monitoring for compliance and assurance.</p>
```

#### Service 5

```html
<!-- FIND -->
<h3 class="title-service-box">Garden Maintenance</h3>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>

<!-- REPLACE WITH -->
<h3 class="title-service-box">Contracts & Payments</h3>
<p>Secure digital contracts, automated invoicing, and flexible payment terms with escrow.</p>
```

#### Service 6

```html
<!-- FIND -->
<h3 class="title-service-box">Irrigation System</h3>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>

<!-- REPLACE WITH -->
<h3 class="title-service-box">Analytics Dashboards</h3>
<p>Business intelligence tools with custom dashboards, metrics, and actionable insights.</p>
```

### Testimonials Section

```html
<!-- FIND (Testimonial Section Title) -->
<h2 class="title-section">What Our Clients Say</h2>

<!-- REPLACE WITH -->
<h2 class="title-section">What Our Clients Say</h2>
```

#### Testimonial 1

```html
<!-- FIND -->
<p class="text-testimonial">"Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum et ligula purus..."</p>
<h3 class="name-testimonial">John Doe</h3>
<p class="position-testimonial">Garden Owner</p>

<!-- REPLACE WITH -->
<p class="text-testimonial">"OMPOI transformed our procurement process. We now get quotes from verified suppliers in hours, not days. The transparency in pricing has saved us over 12% in costs."</p>
<h3 class="name-testimonial">Rajesh Kumar</h3>
<p class="position-testimonial">Managing Director, AgriSource Solutions</p>
```

#### Testimonial 2

```html
<!-- FIND -->
<p class="text-testimonial">"Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum et ligula purus..."</p>
<h3 class="name-testimonial">Jane Smith</h3>
<p class="position-testimonial">Homeowner</p>

<!-- REPLACE WITH -->
<p class="text-testimonial">"The logistics tracking and AI insights are game-changers. We can now forecast demand accurately and optimize our inventory. Highly recommend OMPOI."</p>
<h3 class="name-testimonial">Priya Menon</h3>
<p class="position-testimonial">Procurement Head, Southern Commodities Ltd.</p>
```

#### Testimonial 3

```html
<!-- FIND -->
<p class="text-testimonial">"Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum et ligula purus..."</p>
<h3 class="name-testimonial">Robert Johnson</h3>
<p class="position-testimonial">Business Owner</p>

<!-- REPLACE WITH -->
<p class="text-testimonial">"As a supplier, OMPOI has opened up new markets for us. The structured enquiry system and timely payments have significantly improved our business operations."</p>
<h3 class="name-testimonial">Mohammed Yusuf</h3>
<p class="position-testimonial">Founder, Kerala Cashew Exporters</p>
```

### Call to Action Section

```html
<!-- FIND -->
<h2>Ready to Transform Your Garden?</h2>
<p>Get in touch with us today for a free consultation</p>
<a href="#" class="flat-button">Contact Us</a>

<!-- REPLACE WITH -->
<h2>Ready to Transform Your Procurement?</h2>
<p>Join 300+ suppliers and buyers trading smarter with OMPOI</p>
<a href="/demo" class="flat-button">Request a Demo</a>
```

---

## about.html (About Page)

### Page Title & Banner

```html
<!-- FIND -->
<title>About Us - Gettree</title>

<!-- REPLACE WITH -->
<title>About OMPOI - Online Marketplace of India</title>
```

```html
<!-- FIND (Breadcrumb/Banner Title) -->
<h2 class="title-page">About Us</h2>

<!-- REPLACE WITH -->
<h2 class="title-page">About OMPOI</h2>
```

```html
<!-- FIND (Breadcrumb) -->
<li><a href="index.html">Home</a></li>
<li>About</li>

<!-- REPLACE WITH -->
<li><a href="index.html">Home</a></li>
<li>About OMPOI</li>
```

### Main About Section

```html
<!-- FIND (Main About Title) -->
<h2 class="title-section">Welcome to Gettree</h2>
<p class="sub-title-section">Professional Landscaping Services</p>

<!-- REPLACE WITH -->
<h2 class="title-section">Welcome to OMPOI</h2>
<p class="sub-title-section">Transforming India's Agricultural Commodity Supply Chains</p>
```

```html
<!-- FIND (About Description Paragraph 1) -->
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum et ligula purus. Nulla facilisi. Integer accumsan semper odio, vel vulputate tellus interdum sed...</p>

<!-- REPLACE WITH -->
<p>OMPOI (Online Marketplace of India) is revolutionizing the way agricultural commodities are bought and sold across India. We're building a unified digital ecosystem that brings together buyers, sellers, agents, and logistics providers on one transparent, intelligent platform.</p>
```

```html
<!-- FIND (About Description Paragraph 2) -->
<p>Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat...</p>

<!-- REPLACE WITH -->
<p>Founded with a vision to eliminate inefficiencies in traditional supply chains, OMPOI leverages cutting-edge technology — including AI-powered analytics, real-time tracking, and automated workflows — to create a marketplace where trust, speed, and data-driven decision-making are standard.</p>
```

```html
<!-- FIND (About Description Paragraph 3) -->
<p>Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident...</p>

<!-- REPLACE WITH -->
<p>Our platform serves everyone from small-scale farmers and regional cooperatives to large exporters and multinational buyers, providing tools and insights that level the playing field and enable better business outcomes for all participants.</p>
```

### Mission & Vision

```html
<!-- FIND (Mission Title) -->
<h3>Our Mission</h3>

<!-- KEEP AS IS -->
<h3>Our Mission</h3>
```

```html
<!-- FIND (Mission Text) -->
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>

<!-- REPLACE WITH -->
<p>To unify India's fragmented agricultural supply chains by providing a single, transparent platform with verified trade partners, real-time pricing intelligence, digital workflows, and AI-driven business optimization that empowers every stakeholder to trade with confidence.</p>
```

```html
<!-- FIND (Vision Title) -->
<h3>Our Vision</h3>

<!-- KEEP AS IS -->
<h3>Our Vision</h3>
```

```html
<!-- FIND (Vision Text) -->
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>

<!-- REPLACE WITH -->
<p>To become India's most trusted, transparent, and intelligent digital marketplace — empowering businesses of all sizes to trade agricultural commodities faster, smarter, and with complete confidence while setting new standards for supply chain excellence.</p>
```

### Core Values

```html
<!-- FIND (Values Section Title) -->
<h2 class="title-section">Our Core Values</h2>

<!-- KEEP AS IS -->
<h2 class="title-section">Our Core Values</h2>
```

#### Value 1

```html
<!-- FIND -->
<h3>Quality First</h3>
<p>Lorem ipsum dolor sit amet consectetur adipiscing elit...</p>

<!-- REPLACE WITH -->
<h3>Transparency</h3>
<p>We believe in complete visibility across every transaction. From pricing to logistics to quality standards — no hidden costs, no surprises, just honest business.</p>
```

#### Value 2

```html
<!-- FIND -->
<h3>Customer Satisfaction</h3>
<p>Lorem ipsum dolor sit amet consectetur adipiscing elit...</p>

<!-- REPLACE WITH -->
<h3>Trust</h3>
<p>Every supplier is verified through KYC and quality checks. Every transaction is secure, traceable, and backed by our platform guarantee. Trust isn't given — it's earned through consistent, reliable performance.</p>
```

#### Value 3

```html
<!-- FIND -->
<h3>Professional Team</h3>
<p>Lorem ipsum dolor sit amet consectetur adipiscing elit...</p>

<!-- REPLACE WITH -->
<h3>Innovation</h3>
<p>We continuously invest in AI, machine learning, and automation to make procurement smarter and more efficient. Technology should solve problems, not create them.</p>
```

#### Value 4

```html
<!-- FIND -->
<h3>Eco Friendly</h3>
<p>Lorem ipsum dolor sit amet consectetur adipiscing elit...</p>

<!-- REPLACE WITH -->
<h3>Inclusivity</h3>
<p>From small farmers to large corporates, our platform is designed to serve everyone in the supply chain equitably. We believe in democratizing access to markets and opportunities.</p>
```

### Why Choose Us / Highlights

```html
<!-- FIND (Highlights Section Title) -->
<h2 class="title-section">Why Choose Gettree</h2>

<!-- REPLACE WITH -->
<h2 class="title-section">Why Choose OMPOI</h2>
```

#### Highlight 1

```html
<!-- FIND -->
<h3>15+ Years Experience</h3>
<p>Lorem ipsum dolor sit amet consectetur...</p>

<!-- REPLACE WITH -->
<h3>Pan-India Network</h3>
<p>300+ verified suppliers across 15+ states, giving you access to India's most comprehensive commodity marketplace</p>
```

#### Highlight 2

```html
<!-- FIND -->
<h3>Expert Team</h3>
<p>Lorem ipsum dolor sit amet consectetur...</p>

<!-- REPLACE WITH -->
<h3>Technology Leadership</h3>
<p>AI-driven pricing intelligence, demand forecasting, and automated workflows that set industry standards</p>
```

#### Highlight 3

```html
<!-- FIND -->
<h3>Quality Service</h3>
<p>Lorem ipsum dolor sit amet consectetur...</p>

<!-- REPLACE WITH -->
<h3>Proven Track Record</h3>
<p>2,000+ successful transactions with 4.8/5 customer satisfaction — results that speak for themselves</p>
```

#### Highlight 4

```html
<!-- FIND -->
<h3>Affordable Prices</h3>
<p>Lorem ipsum dolor sit amet consectetur...</p>

<!-- REPLACE WITH -->
<h3>Expert Team</h3>
<p>Seasoned professionals with deep expertise in agri-commodities, technology, logistics, and market intelligence</p>
```

### Team Introduction (if present on About page)

```html
<!-- FIND -->
<h2 class="title-section">Meet Our Team</h2>
<p class="sub-title-section">Professional Landscaping Experts</p>

<!-- REPLACE WITH -->
<h2 class="title-section">Meet Our Team</h2>
<p class="sub-title-section">Experienced Leaders Building India's Future Marketplace</p>
```

---

## services.html (Services Page)

### Page Title & Banner

```html
<!-- FIND -->
<title>Services - Gettree</title>

<!-- REPLACE WITH -->
<title>Services - OMPOI | Agricultural Commodity Trading Solutions</title>
```

```html
<!-- FIND (Page Title) -->
<h2 class="title-page">Our Services</h2>

<!-- KEEP AS IS -->
<h2 class="title-page">Our Services</h2>
```

```html
<!-- FIND (Breadcrumb) -->
<li><a href="index.html">Home</a></li>
<li>Services</li>

<!-- KEEP AS IS -->
<li><a href="index.html">Home</a></li>
<li>Services</li>
```

### Services Introduction

```html
<!-- FIND -->
<h2 class="title-section">Professional Services</h2>
<p class="sub-title-section">Landscaping & Garden Care</p>

<!-- REPLACE WITH -->
<h2 class="title-section">Comprehensive Solutions</h2>
<p class="sub-title-section">For Modern Commodity Trading</p>
```

```html
<!-- FIND (Intro Text) -->
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum et ligula purus...</p>

<!-- REPLACE WITH -->
<p>From sourcing to delivery, we provide end-to-end services powered by technology and intelligence. Our platform streamlines every aspect of agricultural commodity trading.</p>
```

### Service Details (Same as Home Page - Services 1-6)

Use the same replacements as in the [index.html Services Section](#service-1) above for all 6 services.

### Service Call-to-Action

```html
<!-- FIND -->
<h2>Need Professional Landscaping?</h2>
<p>Contact us today for a free quote</p>

<!-- REPLACE WITH -->
<h2>Ready to Transform Your Procurement?</h2>
<p>Schedule a demo to see how OMPOI can streamline operations and improve your bottom line</p>
```

---

## service-details.html (Service Details)

### Page Title

```html
<!-- FIND -->
<title>Service Details - Gettree</title>

<!-- REPLACE WITH -->
<title>Pricing Intelligence & Forecasting - OMPOI Services</title>
```

### Breadcrumb & Title

```html
<!-- FIND -->
<h2 class="title-page">Service Details</h2>

<!-- REPLACE WITH -->
<h2 class="title-page">Pricing Intelligence & Forecasting</h2>
```

```html
<!-- FIND (Breadcrumb) -->
<li><a href="services.html">Services</a></li>
<li>Service Details</li>

<!-- REPLACE WITH -->
<li><a href="services.html">Services</a></li>
<li>Pricing Intelligence</li>
```

### Service Overview

```html
<!-- FIND (Service Name) -->
<h2>Garden Landscaping</h2>

<!-- REPLACE WITH -->
<h2>Pricing Intelligence & Forecasting</h2>
```

```html
<!-- FIND (Overview Paragraph 1) -->
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum et ligula purus. Nulla facilisi. Integer accumsan semper odio...</p>

<!-- REPLACE WITH -->
<p>In the volatile world of agricultural commodities, having accurate, timely pricing information is critical to making profitable decisions. OMPOI's Pricing Intelligence & Forecasting service provides buyers and sellers with comprehensive market insights powered by advanced analytics and machine learning.</p>
```

```html
<!-- FIND (Overview Paragraph 2) -->
<p>Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam...</p>

<!-- REPLACE WITH -->
<p>Our system aggregates real-time data from multiple sources across India — including spot markets, wholesale prices, export quotes, and transaction histories. We analyze this data using proprietary algorithms that account for seasonality, regional variations, transportation costs, quality differentials, and market demand patterns.</p>
```

```html
<!-- FIND (Overview Paragraph 3) -->
<p>Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat...</p>

<!-- REPLACE WITH -->
<p>The result is a powerful intelligence platform that gives you live price quotes, historical trend analysis, predictive forecasting, and actionable alerts — all designed to help you buy smarter and sell better.</p>
```

### Key Features

```html
<!-- FIND (Features Section Title) -->
<h3>Key Features</h3>

<!-- KEEP AS IS -->
<h3>Key Features</h3>
```

```html
<!-- FIND (Feature List Items) -->
<li>Professional landscape design</li>
<li>Custom garden planning</li>
<li>Quality plant selection</li>
<li>Hardscape installation</li>
<li>Outdoor lighting</li>
<li>Water features</li>

<!-- REPLACE WITH -->
<li>Live Market Quotes: Real-time pricing from verified suppliers across India</li>
<li>Price Band Analysis: Historical price ranges and seasonal pattern identification</li>
<li>ML-Powered Forecasts: Predict price movements 1-4 weeks ahead with 85%+ accuracy</li>
<li>Smart Alerts: Custom price thresholds with instant notifications</li>
<li>Regional Comparisons: Compare prices across states to identify arbitrage opportunities</li>
<li>Quality-Adjusted Pricing: Understand price differentials based on quality grades</li>
```

### Methodology / How It Works

```html
<!-- FIND -->
<h3>Our Process</h3>
<p>Lorem ipsum dolor sit amet consectetur adipiscing elit...</p>

<!-- REPLACE WITH -->
<h3>How Our Pricing Intelligence Works</h3>
<p>Our pricing intelligence system is built on three foundational pillars: comprehensive data collection, rigorous analysis, and predictive modeling. We gather pricing data from OMPOI transactions, public market sources, commodity exchanges, and export/import records, ensuring accuracy and minimizing bias.</p>
```

### Benefits / Deliverables

```html
<!-- FIND -->
<h3>Benefits</h3>
<ul>
<li>Beautiful outdoor spaces</li>
<li>Increased property value</li>
<li>Professional maintenance</li>
<li>Eco-friendly solutions</li>
</ul>

<!-- REPLACE WITH -->
<h3>What You Get</h3>
<ul>
<li>Weekly Price Briefs: Detailed reports covering major commodities, price movements, and forecasts</li>
<li>Custom Dashboards: Personalized analytics showing metrics relevant to your business</li>
<li>API Access: Integrate pricing data directly into your systems via RESTful APIs</li>
<li>Historical Data: Access to years of historical pricing for trend analysis</li>
<li>Expert Consultation: Monthly calls with our market analysts to discuss trends and strategy</li>
</ul>
```

### Contact / CTA

```html
<!-- FIND -->
<p class="call-to-action">Need this service? <a href="contact.html">Contact us today</a></p>

<!-- REPLACE WITH -->
<p class="call-to-action">Want to learn more? <a href="/demo">Request a demo</a> or <a href="/contact">contact our team</a></p>
```

```html
<!-- FIND (Quote/Tagline) -->
<blockquote>"Quality service makes the difference"</blockquote>

<!-- REPLACE WITH -->
<blockquote>"Better data leads to better decisions. Our pricing intelligence has helped customers reduce procurement costs by 10-15% on average."</blockquote>
```

### Sidebar Contact

```html
<!-- FIND -->
<h3>Contact Our Expert</h3>
<p>John Doe</p>
<p>Senior Landscaper</p>
<p>Email: john@gettree.com</p>
<p>Phone: 1-800-123-4567</p>

<!-- REPLACE WITH -->
<h3>Contact Our Expert</h3>
<p>Sudhir G</p>
<p>Technology Director</p>
<p>Email: sudhir@ompoi.com</p>
<p>Phone: +91-XXXXXXXXXX</p>
<p>Location: Chennai, Tamil Nadu</p>
```

---

## case-study.html (Case Studies)

### Page Title & Banner

```html
<!-- FIND -->
<title>Case Studies - Gettree</title>

<!-- REPLACE WITH -->
<title>Case Studies - OMPOI Success Stories</title>
```

```html
<!-- FIND -->
<h2 class="title-page">Case Studies</h2>

<!-- REPLACE WITH -->
<h2 class="title-page">Success Stories</h2>
```

```html
<!-- FIND (Page Description) -->
<p>Our recent landscaping projects</p>

<!-- REPLACE WITH -->
<p>Real Results from Real Clients</p>
```

### Case Study 1

```html
<!-- FIND -->
<h3 class="case-title">Garden Renovation Project</h3>
<p class="case-category">Residential</p>
<p class="case-description">Complete garden transformation for luxury home...</p>

<!-- REPLACE WITH -->
<h3 class="case-title">Cashew Kernel Traceability System</h3>
<p class="case-category">Agricultural Export</p>
<p class="case-description">Implemented end-to-end traceability for a major cashew exporter, reducing quality disputes by 35% and improving export compliance to 100%.</p>
```

### Case Study 2

```html
<!-- FIND -->
<h3 class="case-title">Commercial Landscaping</h3>
<p class="case-category">Commercial</p>
<p class="case-description">Professional landscaping for business complex...</p>

<!-- REPLACE WITH -->
<h3 class="case-title">Logistics SLA Optimization</h3>
<p class="case-category">Commodity Trading</p>
<p class="case-description">Optimized dispatch workflows for an agri-commodities buyer, achieving 98% on-time delivery and reducing logistics costs by 18%.</p>
```

### Case Study 3

```html
<!-- FIND -->
<h3 class="case-title">Park Development</h3>
<p class="case-category">Public Spaces</p>
<p class="case-description">Large scale park development project...</p>

<!-- REPLACE WITH -->
<h3 class="case-title">AI Price Bands for Export Markets</h3>
<p class="case-category">Trading & Export</p>
<p class="case-description">Deployed machine learning models to predict export pricing trends, reducing quote variance by 22% and improving margin predictability by 15%.</p>
```

### Case Study 4

```html
<!-- FIND -->
<h3 class="case-title">Rooftop Garden</h3>
<p class="case-category">Urban</p>
<p class="case-description">Modern rooftop garden installation...</p>

<!-- REPLACE WITH -->
<h3 class="case-title">Automated Buyer Onboarding</h3>
<p class="case-category">B2B Platform</p>
<p class="case-description">Reduced onboarding time from 5-7 days to under 24 hours, increasing new buyer acquisitions by 45% and reducing admin overhead by 60%.</p>
```

---

## case-details.html (Case Details)

### Page Title

```html
<!-- FIND -->
<title>Case Details - Gettree</title>

<!-- REPLACE WITH -->
<title>AI Price Bands for Export Markets - OMPOI Case Study</title>
```

### Breadcrumb & Title

```html
<!-- FIND -->
<h2 class="title-page">Case Details</h2>

<!-- REPLACE WITH -->
<h2 class="title-page">AI Price Bands for Export Markets</h2>
```

```html
<!-- FIND (Breadcrumb) -->
<li><a href="case-study.html">Case Studies</a></li>
<li>Case Details</li>

<!-- REPLACE WITH -->
<li><a href="case-study.html">Case Studies</a></li>
<li>AI Price Bands</li>
```

### Project Overview

```html
<!-- FIND -->
<h2>Garden Renovation Project</h2>
<p class="project-meta">Client: John & Jane Doe | Location: California | Duration: 3 months</p>

<!-- REPLACE WITH -->
<h2>AI Price Bands for Export Markets</h2>
<p class="project-meta">Client: AgriSource Solutions | Location: Andhra Pradesh | Duration: 6 months</p>
```

### Challenge

```html
<!-- FIND -->
<h3>The Challenge</h3>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>

<!-- REPLACE WITH -->
<h3>The Challenge</h3>
<p>AgriSource Solutions faced significant challenges with pricing volatility and quote consistency. Their manual pricing process led to quote variance of up to 30% for similar orders, resulting in lost deals and margin unpredictability. Without systematic pricing guidelines, margins fluctuated wildly, and manual calculations took 24-48 hours, causing delays in quote turnaround.</p>
```

### Solution / Approach

```html
<!-- FIND -->
<h3>Our Solution</h3>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>

<!-- REPLACE WITH -->
<h3>Our Approach</h3>
<p>OMPOI's team designed a three-phase solution: (1) Data Collection & Analysis - gathered 3 years of historical transaction data; (2) Model Development - developed ML models using regression, decision trees, and ensemble methods trained on 15+ variables; (3) Integration & Deployment - integrated the price band engine into quoting workflows with intuitive dashboards showing recommended price ranges and confidence intervals.</p>
```

### Results / Impact

```html
<!-- FIND -->
<h3>Results</h3>
<ul>
<li>Beautiful transformed garden space</li>
<li>Increased property value by 15%</li>
<li>Client satisfaction: 5/5 stars</li>
<li>Completed on time and budget</li>
</ul>

<!-- REPLACE WITH -->
<h3>Results</h3>
<ul>
<li>22% Reduction in Quote Variance: Price quotes became consistent and predictable</li>
<li>15% Margin Improvement: Average margins increased from 12.3% to 14.1%</li>
<li>30% Faster Quote Generation: Reduced preparation time from 24-48 hours to under 8 hours</li>
<li>Enhanced Win Rate: Deal win rate improved from 42% to 51%</li>
<li>Better Market Intelligence: Sales team gained visibility into pricing trends and competitive positioning</li>
</ul>
```

### Client Testimonial

```html
<!-- FIND -->
<blockquote>
"Gettree did an amazing job transforming our garden. Highly recommended!"
<cite>- John Doe, Homeowner</cite>
</blockquote>

<!-- REPLACE WITH -->
<blockquote>
"The AI pricing system transformed our export business. We're now quoting with confidence, winning more deals, and making better margins. It's been a game-changer."
<cite>- Ramesh Babu, Export Director, AgriSource Solutions</cite>
</blockquote>
```

### Project Tags/Categories

```html
<!-- FIND -->
<p class="tags">Tags: Landscaping, Garden, Residential, Renovation</p>

<!-- REPLACE WITH -->
<p class="tags">Tags: pricing, AI, machine learning, export, analytics, optimization</p>
```

---

## blog.html (Blog Listing)

### Page Title

```html
<!-- FIND -->
<title>Blog - Gettree</title>

<!-- REPLACE WITH -->
<title>Blog - OMPOI Insights & Updates</title>
```

### Page Banner

```html
<!-- FIND -->
<h2 class="title-page">Latest News & Insights</h2>

<!-- REPLACE WITH -->
<h2 class="title-page">Expert Insights on Commodity Trading</h2>
```

```html
<!-- FIND (Page Description) -->
<p>Garden tips and landscaping news</p>

<!-- REPLACE WITH -->
<p>Market trends, best practices, and technology insights</p>
```

### Blog Post 1

```html
<!-- FIND -->
<h3 class="post-title">10 Tips for Spring Garden Care</h3>
<p class="post-meta">By Admin | March 15, 2024 | Gardening Tips</p>
<p class="post-excerpt">Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>

<!-- REPLACE WITH -->
<h3 class="post-title">How RFQs Become Faster with OMPOI: A Complete Guide</h3>
<p class="post-meta">By Sudhir G | November 08, 2025 | Procurement Best Practices</p>
<p class="post-excerpt">Traditional RFQ processes can take weeks. Learn how OMPOI's digital platform reduces procurement cycles from 14 days to under 48 hours through automation, verified suppliers, and intelligent matching.</p>
```

### Blog Post 2

```html
<!-- FIND -->
<h3 class="post-title">Choosing the Right Plants for Your Garden</h3>
<p class="post-meta">By Admin | March 10, 2024 | Plant Selection</p>
<p class="post-excerpt">Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>

<!-- REPLACE WITH -->
<h3 class="post-title">Understanding Price Spreads in Cashew Supply Chains</h3>
<p class="post-meta">By Sudhir G | November 05, 2025 | Market Intelligence</p>
<p class="post-excerpt">Why do cashew prices vary so dramatically across regions and quality grades? This deep-dive explores the factors driving price spreads and how data transparency helps buyers get fair deals.</p>
```

### Blog Post 3

```html
<!-- FIND -->
<h3 class="post-title">Lawn Maintenance Best Practices</h3>
<p class="post-meta">By Admin | March 05, 2024 | Lawn Care</p>
<p class="post-excerpt">Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>

<!-- REPLACE WITH -->
<h3 class="post-title">Traceability Basics for SMEs: Why It Matters and How to Start</h3>
<p class="post-meta">By Kadaroli | November 01, 2025 | Quality & Compliance</p>
<p class="post-excerpt">Small and medium enterprises often overlook traceability, but it's becoming essential for exports and quality assurance. This beginner-friendly guide covers the basics and implementation steps.</p>
```

### Blog Post 4

```html
<!-- FIND -->
<h3 class="post-title">Water-Wise Landscaping Ideas</h3>
<p class="post-meta">By Admin | February 28, 2024 | Sustainability</p>
<p class="post-excerpt">Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>

<!-- REPLACE WITH -->
<h3 class="post-title">5 Ways AI is Transforming Agricultural Commodity Trading</h3>
<p class="post-meta">By Sudhir G | October 28, 2025 | Technology & Innovation</p>
<p class="post-excerpt">From demand forecasting to automated quality checks, artificial intelligence is revolutionizing how commodities are bought and sold. Explore five practical applications already delivering results.</p>
```

### Blog Categories (Sidebar)

```html
<!-- FIND -->
<h3>Categories</h3>
<ul>
<li>Gardening Tips (12)</li>
<li>Landscaping (18)</li>
<li>Plant Care (9)</li>
<li>Design Ideas (14)</li>
<li>Seasonal Tips (11)</li>
</ul>

<!-- REPLACE WITH -->
<h3>Categories</h3>
<ul>
<li>Procurement Best Practices (12)</li>
<li>Market Intelligence (18)</li>
<li>Technology & Innovation (9)</li>
<li>Logistics & Supply Chain (14)</li>
<li>Quality & Compliance (11)</li>
<li>Sourcing & Verification (8)</li>
</ul>
```

---

## blog-detail.html (Blog Post Detail)

### Page Title

```html
<!-- FIND -->
<title>Blog Post - Gettree</title>

<!-- REPLACE WITH -->
<title>Understanding Price Spreads in Cashew Supply Chains - OMPOI Blog</title>
```

### Post Title & Meta

```html
<!-- FIND -->
<h1 class="post-title">10 Tips for Spring Garden Care</h1>
<p class="post-meta">By Admin | March 15, 2024 | Gardening Tips | 5 min read</p>

<!-- REPLACE WITH -->
<h1 class="post-title">Understanding Price Spreads in Cashew Supply Chains</h1>
<p class="post-meta">By Sudhir G | November 05, 2025 | Market Intelligence | 12 min read</p>
```

### Post Content - Introduction

```html
<!-- FIND -->
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum et ligula purus...</p>

<!-- REPLACE WITH -->
<p>Cashew pricing in India varies dramatically across regions, quality grades, and seasons. Understanding these price spreads is essential for both buyers and sellers to make informed decisions and negotiate fair deals.</p>
```

### Section 1

```html
<!-- FIND -->
<h2>Tip 1: Prepare Your Soil</h2>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>

<!-- REPLACE WITH -->
<h2>What Drives Price Spreads in Cashew Markets?</h2>
<p>Price spreads in cashew supply chains are influenced by multiple factors including regional production variations, quality grading systems, processing costs, transportation logistics, seasonal demand patterns, and export market dynamics.</p>
```

### Section 2

```html
<!-- FIND -->
<h2>Tip 2: Choose the Right Plants</h2>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>

<!-- REPLACE WITH -->
<h2>The Role of Quality Grading</h2>
<p>Cashew kernels are graded based on size, color, and wholeness. W180 (largest whole) commands premium prices, while W320 and W450 (smaller grades) are more affordable. Split and broken grades sell at significant discounts. Quality-adjusted pricing is critical — a W180 kernel might cost ₹800-900/kg while W450 ranges ₹600-700/kg.</p>
```

### Section 3

```html
<!-- FIND -->
<h2>Tip 3: Water Efficiently</h2>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>

<!-- REPLACE WITH -->
<h2>How Data Transparency Helps</h2>
<p>OMPOI's pricing intelligence provides visibility into market rates across regions and quality grades. By aggregating transaction data, we help buyers identify fair prices and sellers price competitively. Our platform shows historical price bands, seasonal patterns, and regional variations — enabling both parties to negotiate from informed positions rather than guesswork.</p>
```

### Pull Quote

```html
<!-- FIND -->
<blockquote>"A beautiful garden is the result of careful planning and maintenance"</blockquote>

<!-- REPLACE WITH -->
<blockquote>"Data consistency drives price discovery. When both buyers and sellers have access to market intelligence, transactions become faster, fairer, and more efficient."</blockquote>
```

### Conclusion

```html
<!-- FIND -->
<h2>Conclusion</h2>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>

<!-- REPLACE WITH -->
<h2>Conclusion</h2>
<p>Understanding price spreads in cashew supply chains requires knowledge of regional dynamics, quality standards, and market trends. With better data and transparency, both buyers and sellers can achieve fair, profitable transactions while building long-term relationships based on trust.</p>
```

### Tags

```html
<!-- FIND -->
<p class="tags">Tags: gardening, spring, tips, maintenance, plants</p>

<!-- REPLACE WITH -->
<p class="tags">Tags: cashew, pricing, analytics, supply chain, market intelligence</p>
```

### Author Bio

```html
<!-- FIND -->
<div class="author-bio">
<h3>About the Author</h3>
<p>Admin has been working in landscaping for over 10 years...</p>
</div>

<!-- REPLACE WITH -->
<div class="author-bio">
<h3>About the Author</h3>
<p>Sudhir G is OMPOI's Chief Technology Officer with 18+ years of experience in AI, product development, and marketplace platforms. He specializes in using technology to solve complex supply chain challenges.</p>
</div>
```

---

## faq.html (FAQ Page)

### Page Title

```html
<!-- FIND -->
<title>FAQ - Gettree</title>

<!-- REPLACE WITH -->
<title>FAQ - OMPOI Frequently Asked Questions</title>
```

### Page Banner

```html
<!-- FIND -->
<h2 class="title-page">Frequently Asked Questions</h2>

<!-- KEEP AS IS -->
<h2 class="title-page">Frequently Asked Questions</h2>
```

### FAQ Category 1: Onboarding

```html
<!-- FIND -->
<h3>General Questions</h3>

<!-- REPLACE WITH -->
<h3>Onboarding & Getting Started</h3>
```

```html
<!-- FIND (Question 1) -->
<h4>What services do you offer?</h4>
<p>We offer comprehensive landscaping services including garden design, lawn care, tree plantation...</p>

<!-- REPLACE WITH -->
<h4>How do I sign up as a buyer or seller on OMPOI?</h4>
<p>Visit our signup page at ompoi.com/signup, choose your user type (Buyer/Seller/Agent), complete the registration form with business details, and submit KYC documents (GST, PAN, business registration). Our team will verify your profile within 24-48 hours and activate your account.</p>
```

```html
<!-- FIND (Question 2) -->
<h4>How much do your services cost?</h4>
<p>Pricing varies based on project scope and requirements. Contact us for a custom quote...</p>

<!-- REPLACE WITH -->
<h4>What documents are required for verification?</h4>
<p>Required documents include: GST certificate, PAN card, business registration certificate (for companies), bank account details, and address proof. Additional documents may be requested based on your business type and transaction volume.</p>
```

```html
<!-- FIND (Question 3) -->
<h4>Do you provide free consultations?</h4>
<p>Yes, we offer free initial consultations to discuss your landscaping needs...</p>

<!-- REPLACE WITH -->
<h4>Is there a fee to join OMPOI?</h4>
<p>Registration is free for all users. We charge a small commission on successful transactions (2-3% for buyers, 1-2% for sellers) to maintain platform operations and provide ongoing support.</p>
```

### FAQ Category 2: Pricing

```html
<!-- FIND -->
<h3>Service Information</h3>

<!-- REPLACE WITH -->
<h3>Pricing & Payments</h3>
```

```html
<!-- FIND (Question 1) -->
<h4>How long does a typical project take?</h4>
<p>Project duration varies based on scope, typically ranging from 1-4 weeks...</p>

<!-- REPLACE WITH -->
<h4>How does OMPOI determine pricing?</h4>
<p>OMPOI doesn't set prices — sellers quote their own prices based on quality, quantity, location, and market conditions. Our pricing intelligence tool provides market data and trends to help both buyers and sellers make informed decisions.</p>
```

```html
<!-- FIND (Question 2) -->
<h4>Do you use eco-friendly practices?</h4>
<p>Yes, we prioritize sustainable and environmentally friendly landscaping methods...</p>

<!-- REPLACE WITH -->
<h4>Can I negotiate prices on the platform?</h4>
<p>Yes, our platform includes a secure messaging system for price negotiations between buyers and sellers. All communication is logged for transparency and dispute resolution.</p>
```

```html
<!-- FIND (Question 3) -->
<h4>What areas do you serve?</h4>
<p>We serve the greater metropolitan area and surrounding regions...</p>

<!-- REPLACE WITH -->
<h4>Are prices inclusive of taxes and shipping?</h4>
<p>Prices are typically quoted FOB (Free on Board) or Ex-Works unless otherwise specified. Sellers should clearly mention if GST, transportation, or other charges are included. Always verify pricing terms before confirming orders.</p>
```

### FAQ Category 3: Logistics

```html
<!-- FIND -->
<h3>Maintenance & Support</h3>

<!-- REPLACE WITH -->
<h3>Logistics & Delivery</h3>
```

```html
<!-- FIND (Question 1) -->
<h4>Do you offer maintenance packages?</h4>
<p>Yes, we provide ongoing maintenance services to keep your garden beautiful year-round...</p>

<!-- REPLACE WITH -->
<h4>Does OMPOI handle logistics and shipping?</h4>
<p>We coordinate with third-party logistics partners and provide real-time tracking. Sellers can choose to arrange their own logistics or use our integrated network. All shipments are tracked through our platform for visibility and accountability.</p>
```

```html
<!-- FIND (Question 2) -->
<h4>What if I'm not satisfied with the work?</h4>
<p>Customer satisfaction is our priority. We'll work with you to address any concerns...</p>

<!-- REPLACE WITH -->
<h4>What if there's a delay in delivery?</h4>
<p>Our platform monitors delivery timelines and sends alerts for potential delays. In case of delays, both parties are notified immediately. Sellers must provide valid reasons for delays, and buyers can file complaints if SLAs are not met.</p>
```

```html
<!-- FIND (Question 3) -->
<h4>How do I schedule a service?</h4>
<p>You can contact us via phone, email, or our online booking form...</p>

<!-- REPLACE WITH -->
<h4>How is product quality ensured during transit?</h4>
<p>We recommend appropriate packaging standards based on commodity type. For sensitive products, we offer temperature-controlled logistics partners. Quality issues upon delivery can be reported through our dispute resolution system.</p>
```

---

## team.html (Team Page)

### Page Title

```html
<!-- FIND -->
<title>Our Team - Gettree</title>

<!-- REPLACE WITH -->
<title>Our Team - OMPOI Leadership</title>
```

### Page Banner

```html
<!-- FIND -->
<h2 class="title-page">Meet Our Team</h2>

<!-- KEEP AS IS -->
<h2 class="title-page">Meet Our Team</h2>
```

```html
<!-- FIND (Page Description) -->
<p>Professional Landscaping Experts</p>

<!-- REPLACE WITH -->
<p>Experienced Leaders Building India's Future Marketplace</p>
```

### Team Introduction

```html
<!-- FIND -->
<h2 class="title-section">Our Professional Team</h2>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>

<!-- REPLACE WITH -->
<h2 class="title-section">Leadership Team</h2>
<p>Our team combines deep domain expertise in agriculture, technology, and supply chain management with a passion for innovation. Together, we're building India's most transparent and intelligent commodity marketplace.</p>
```

### Team Member 1

```html
<!-- FIND -->
<h3>John Doe</h3>
<p class="position">Senior Landscape Designer</p>
<p class="bio">John has over 15 years of experience in landscape design...</p>
<p class="email">john@gettree.com</p>

<!-- REPLACE WITH -->
<h3>Sudhir G</h3>
<p class="position">Chief Technology Officer</p>
<p class="bio">AI & Product Innovator with 18+ years in leadership delivering marketplaces, analytics platforms, and LLM solutions. Expert in backend systems, ML, and product architecture.</p>
<p class="email">sudhir@ompoi.com</p>
<p class="linkedin"><a href="https://www.linkedin.com/in/sudhirgiripp/">LinkedIn Profile</a></p>
```

### Team Member 2

```html
<!-- FIND -->
<h3>Jane Smith</h3>
<p class="position">Horticulturist</p>
<p class="bio">Jane specializes in plant selection and garden maintenance...</p>
<p class="email">jane@gettree.com</p>

<!-- REPLACE WITH -->
<h3>Kadaroli</h3>
<p class="position">Head of Quality & Compliance</p>
<p class="bio">15+ years in agricultural quality standards, export compliance, and supply chain traceability. Ensures every transaction meets the highest quality benchmarks.</p>
<p class="email">kadaroli@ompoi.com</p>
```

### Team Member 3

```html
<!-- FIND -->
<h3>Robert Johnson</h3>
<p class="position">Landscape Architect</p>
<p class="bio">Robert brings creative vision to outdoor spaces...</p>
<p class="email">robert@gettree.com</p>

<!-- REPLACE WITH -->
<h3>Yousuf</h3>
<p class="position">Head of Logistics & Operations</p>
<p class="bio">12+ years in logistics optimization, supply chain management, and operational excellence. Drives on-time delivery and cost efficiency across our network.</p>
<p class="email">yousuf@ompoi.com</p>
```

---

## contact.html (Contact Page)

### Page Title

```html
<!-- FIND -->
<title>Contact Us - Gettree</title>

<!-- REPLACE WITH -->
<title>Contact OMPOI - Get in Touch</title>
```

### Page Banner

```html
<!-- FIND -->
<h2 class="title-page">Contact Us</h2>

<!-- KEEP AS IS -->
<h2 class="title-page">Contact Us</h2>
```

```html
<!-- FIND (Page Description) -->
<p>Get in touch with our team</p>

<!-- REPLACE WITH -->
<p>Have questions? Need support? Want to discuss a partnership? We're here to help.</p>
```

### Contact Information Section

```html
<!-- FIND -->
<h3>Get In Touch</h3>
<p>We'd love to hear from you. Contact us for landscaping services...</p>

<!-- REPLACE WITH -->
<h3>Get In Touch</h3>
<p>Tell us your sourcing needs, questions, or feedback. We'll respond within 24 hours.</p>
```

### Address

```html
<!-- FIND -->
<div class="contact-info">
<i class="icon-location"></i>
<h4>Visit Us</h4>
<p>2072 Pinnickinick Street</p>
<p>WA 98370, United States</p>
</div>

<!-- REPLACE WITH -->
<div class="contact-info">
<i class="icon-location"></i>
<h4>Visit Us</h4>
<p>OMPOI Headquarters</p>
<p>Chennai, Tamil Nadu, India</p>
<p>Regional Offices: Mumbai · Bangalore</p>
</div>
```

### Phone

```html
<!-- FIND -->
<div class="contact-info">
<i class="icon-phone"></i>
<h4>Call Us</h4>
<p>+1-800-643-4500</p>
<p>Monday - Friday: 9AM - 5PM</p>
</div>

<!-- REPLACE WITH -->
<div class="contact-info">
<i class="icon-phone"></i>
<h4>Call Us</h4>
<p>+91-XXXXXXXXXX</p>
<p>Monday - Saturday: 9 AM - 6 PM IST</p>
</div>
```

### Email

```html
<!-- FIND -->
<div class="contact-info">
<i class="icon-email"></i>
<h4>Email Us</h4>
<p>info@gettree.com</p>
<p>support@gettree.com</p>
</div>

<!-- REPLACE WITH -->
<div class="contact-info">
<i class="icon-email"></i>
<h4>Email Us</h4>
<p>info@ompoi.com (General inquiries)</p>
<p>support@ompoi.com (Technical support)</p>
<p>sales@ompoi.com (Sales & partnerships)</p>
</div>
```

### Contact Form

```html
<!-- FIND (Form Title) -->
<h3>Send Us a Message</h3>

<!-- KEEP AS IS -->
<h3>Send Us a Message</h3>
```

```html
<!-- FIND (Service Selection Dropdown) -->
<select name="service">
<option value="">Select Service</option>
<option value="landscaping">Garden Landscaping</option>
<option value="lawn-care">Lawn Care</option>
<option value="tree-planting">Tree Planting</option>
<option value="maintenance">Maintenance</option>
</select>

<!-- REPLACE WITH -->
<select name="service">
<option value="">Select Service of Interest</option>
<option value="sourcing">Sourcing & Verification</option>
<option value="pricing">Pricing Intelligence</option>
<option value="logistics">Logistics & Fulfillment</option>
<option value="quality">Quality & Traceability</option>
<option value="contracts">Contracts & Payments</option>
<option value="analytics">Analytics Dashboards</option>
<option value="general">General Inquiry</option>
</select>
```

```html
<!-- FIND (Message Placeholder) -->
<textarea name="message" placeholder="Tell us about your landscaping needs..."></textarea>

<!-- REPLACE WITH -->
<textarea name="message" placeholder="Please describe your requirements, questions, or feedback..."></textarea>
```

### Business Hours

```html
<!-- FIND -->
<h3>Business Hours</h3>
<p>Monday - Friday: 9:00 AM - 5:00 PM</p>
<p>Saturday: 9:00 AM - 1:00 PM</p>
<p>Sunday: Closed</p>

<!-- REPLACE WITH -->
<h3>Business Hours</h3>
<p>Monday - Friday: 9:00 AM - 6:00 PM IST</p>
<p>Saturday: 9:00 AM - 2:00 PM IST</p>
<p>Sunday: Closed</p>
```

---

## 🎯 Implementation Checklist

After making all the above replacements:

### 1. Global Updates Needed

- [ ] Replace all Gettree logo images with OMPOI logo files
- [ ] Update favicon files (icon/Favicon.png)
- [ ] Update social media links in header and footer
- [ ] Add actual phone number instead of +91-XXXXXXXXXX
- [ ] Set up email addresses: info@, support@, sales@ompoi.com
- [ ] Update all form action URLs to point to your backend

### 2. Image Assets to Create/Replace

- [ ] OMPOI logo (dark and light versions)
- [ ] Hero section images
- [ ] Team member photos (Sudhir, Kadaroli, Yousuf)
- [ ] Case study images (4 case studies)
- [ ] Blog post featured images
- [ ] Service icons
- [ ] Feature icons

### 3. Additional Content to Review

- [ ] Update meta descriptions for SEO
- [ ] Add Open Graph tags for social sharing
- [ ] Review and update all internal links
- [ ] Test all form submissions
- [ ] Verify email links work correctly
- [ ] Test responsive design on mobile devices

### 4. Legal & Compliance

- [ ] Add Privacy Policy page
- [ ] Add Terms of Service page
- [ ] Add Cookie Policy (if applicable)
- [ ] Ensure GDPR/data protection compliance

### 5. SEO Optimization

- [ ] Add structured data (Schema.org markup)
- [ ] Optimize image alt tags
- [ ] Add XML sitemap
- [ ] Set up Google Analytics
- [ ] Submit to Google Search Console

---

## 📝 Notes

1. **Consistency**: All statistics (300+ suppliers, 2000+ shipments, 4.8/5 rating, <24h response) should remain consistent across all pages.

2. **Brand Voice**: The content maintains a professional yet accessible tone, emphasizing transparency, trust, and data-driven intelligence.

3. **CTAs**: All call-to-action buttons point to `/signup` for "Get Started" and `/demo` for "Request a Demo" - update these URLs to match your actual routes.

4. **Placeholders**: Replace `+91-XXXXXXXXXX` with your actual phone number before going live.

5. **Team Information**: The content includes three team members. Add more as needed following the same structure.

6. **Case Studies**: Four case studies are provided. You can add more by following the same format.

7. **Blog Posts**: Content includes 4 blog post examples. Expand your blog section with more posts following the same structure.

---

## 🚀 Ready to Launch!

This comprehensive replacement guide covers all HTML files in your template. Follow the replacements exactly as shown, and your Gettree template will be fully converted to OMPOI branding and content.

**Remember**: This is content only. You may need to adjust CSS classes, IDs, and JavaScript functionality to match OMPOI's specific requirements.

---

**Version**: 1.0  
**Last Updated**: November 8, 2025  
**Total Replacements**: 200+ content items across 12 HTML files

© 2025 OMPOI - Online Marketplace of India. All rights reserved.
