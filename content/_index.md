---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Pathfinders Congressional Internship and Leadership Program
      text: 🧱 From anywhere in USA!  🧱
      primary_action:
        text: Apply Now
        url: https://docs.google.com/forms/d/e/1FAIpQLScCfZdgv3LlZMllhuZBjm7lM0TCObyZYAFny9S90d0StL0AOw/viewform?usp=header/
        icon: rocket-launch
      # secondary_action:
      #   text: Read the requirements
      #   url: https://docs.hugoblox.com
      announcement:
        text: "Enrollment Open"
        # link:
        #   text: "Read more"
        #   url: "/blog/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: bg-triangles.svg
          filters:
            brightness: 0.5
  - block: stats
    content:
      items:
        - statistic: "40k"
          description: |
            Interns from around the country  
            serve in the US Congress
        - statistic: "$24.3M"
          description: |
            House budget for paid  
            interns as of 2023
        - statistic: "All year"
          description: |
            Internships run throughout the fall,  
            spring or summer semesters
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: features
    id: features
    content:
      title: Features
      text: Congressional Internship and Leadership Program details 🧱
      items:
        - name: Gain experience
          icon: star
          description: An immersive internship in state offices for hands-on experience and connecting with high-level policymakers and insiders.
        - name: Workshop
          icon: magnifying-glass
          description: Comprehensive program orientation as well as tailored professional development workshops on leadership and policy.
        - name: Networking
          icon: bolt
          description: Exclusive networking opportunities and access to mentorship throughout the program.
        - name: Placement support
          icon: rectangle-group
          description: Ongoing support for job or internship placements after program completion.
        - name: Stipend
          icon: sparkles
          description: Competitive stipend provided!
        # - name: Swappable Blocks
        #   icon: rectangle-group
        #   description: Build your pages with blocks - no coding required!
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: HINDUACTion PATHFINDERS Internship and Leadership Programs
          text: HINDUACTion is looking for energetic and outgoing American Hindu high school or college students. We offer two distinct internship opportunities for students to develop leadership skills, gain experience, and engage with their communities
          feature_icon: check
          features:
            - "PATHFINDERS American Hindu Congressional Internship: Open to undergraduates, and graduate students of any major"
            - "PATHFINDERS American Hindu State Internship: Open to high school students"
        #     - "No JavaScript knowledge required"
        #   # Upload image to `assets/media/` and reference the filename here
          image: build-website.png
        #   button:
        #     text: Get Started
        #     url: https://hugoblox.com/templates/
        - title: Eligibility
          text: To apply for the program, applicants must meet the following eligibility criteria
          feature_icon: bolt
          features:
            - "Enrolled at an accredited university in the U.S. or graduated within the last year."
            - "A demonstrated interest in politics, government, American Hindu history, or related fields."
            - "Attend a 10-day orientation and weekly leadership development sessions."
            - "Work a minimum of 20 hours a week on congressional office assignments."
            - "Comply with HinduACTion policies regarding work performance and personal conduct."
            - "Grades > 3.0 GPA."
          # Upload image to `assets/media/` and reference the filename here
          image: PATHFINDERS FLYER.png
          button:
            text: Apply Now
            url: https://docs.google.com/forms/d/e/1FAIpQLScCfZdgv3LlZMllhuZBjm7lM0TCObyZYAFny9S90d0StL0AOw/viewform?usp=header/
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: testimonials
    content:
      title: ""
      text: ""
      items:
        - name: "Utsav Chakrabarti"
          role: "Executive Director at HINDUACTion"
          # Upload image to `assets/media/` and reference the filename here
          image: "testimonial-1.jpg"
          text: "I am honored to help shape and empower the next generation of leaders in our community."
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]
  # - block: contact
  #   id : contact
  #   content:
  #     title: Contact
  #     subtitle: ''
  #     text: ''
  #     # Contact details - edit or remove options as needed
  #     email: hinduaction@gmail.com
  #     phone: (202) 838-6655
      # address:
      #   street: 450 Serra Mall
      #   city: Stanford
      #   region: CA
      #   postcode: '94305'
      #   country: United States
      #   country_code: US
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      # contact_links:
      #   - icon: twitter
      #     icon_pack: fab
      #     name: DM Me
      #     link: 'https://twitter.com/Twitter'
      #   - icon: skype
      #     icon_pack: fab
      #     name: Skype Me
      #     link: 'skype:echo123?call'
      #   - icon: video
      #     icon_pack: fas
      #     name: Zoom Me
      #     link: 'https://zoom.com'
      # Automatically link email and phone or display them just as text?
    #   autolink: true
    # design:
    #   # Choose how many columns the section has. Valid values: '1' or '2'.
    #   columns: '1'
  - block: cta-card
    content:
      title: Shape your future
      text: Take the First Step Today—Your Future Awaits!
      button:
        text: Apply Now
        url: https://docs.google.com/forms/d/e/1FAIpQLScCfZdgv3LlZMllhuZBjm7lM0TCObyZYAFny9S90d0StL0AOw/viewform?usp=header/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
