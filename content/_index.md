[build]
  command = "hugo --gc --minify -b $URL"
  publish = "public"

---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: ""
    design:
      css_class: dark
      background:
        color: black
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  - block: markdown
    content:
      title: "🛫 About Me"
      subtitle: ""
      text: |-
        I am a certified flight instructor (CFII-A/H) and a proud member of the National Association of Flight Instructors (NAFI). My mission is to inspire and train the next generation of pilots by combining rigorous instruction with real-world flight experience. I currently provide both helicopter and fixed-wing training in the Portland, OR area. You can learn more about my flight services at [pilotseal.com](https://pilotseal.com).

        I am passionate about safety, mentorship, and helping each student reach their full potential in aviation. Let's fly safe, and fly well.
    design:
      columns: "1"