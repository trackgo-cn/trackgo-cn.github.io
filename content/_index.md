---
title: "首页"
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: 特优拟-让定向越野更智慧
      text: 专注于智能打卡系统研发，提供双通道数据传输、远程升级维护、成绩管理统计的一站式定向越野解决方案
      primary_action:
        text: 联系我们
        url: /#contact
        icon: rocket-launch
      # secondary_action:
      #   text: Read the docs
      #   url: https://docs.hugoblox.com
      # announcement:
      #   text: "Announcing the release of version 1."
      #   link:
      #     text: "Read more"
      #     url: "/blog/"
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
  # - block: stats
  #   content:
  #     items:
  #       - statistic: "1M+"
  #         description: |
  #           Websites built
  #           with Hugo Blox
  #       - statistic: "10k+"
  #         description: |
  #           GitHub stars
  #           since 2016
  #       - statistic: "3k+"
  #         description: |
  #           Discord community
  #           for support
  #   design:
  #     # Section background color (CSS class)
  #     css_class: "bg-gray-100 dark:bg-gray-900"
  #     # Reduce spacing
  #     spacing:
  #       padding: ["1rem", 0, "1rem", 0]
  # - block: features
  #   id: features
  #   content:
  #     title: 我们的使命
  #     text: 让定向越野赛事组织更高效，让比赛体验更精彩
  #     items:
  #       - name: 自动化统计
  #         icon: magnifying-glass
  #         description: 提升赛事组织效率
  #       - name: 实时监控
  #         icon: bolt
  #         description: 确保比赛安全公平
  #       - name: 智能化管理
  #         icon: sparkles
  #         description: 大幅降低赛事运营成本
  #       - name: No-Code
  #         icon: code-bracket
  #         description: Edit and design your site just using rich text (Markdown) and configurable YAML parameters.
  #       - name: Highly Rated
  #         icon: star
  #         description: Rated 5-stars by the community.
  #       - name: 数据驱动
  #         icon: rectangle-group
  #         description: 让每一场比赛更有趣
  - block: cta-image-paragraph
    id: about
    content:
      title: 关于我们
      items:
        - title: 公司简介
          text: 科技赋能体育、智慧点亮赛道
          # text: 我们是一家以"科技赋能体育、智慧点亮赛道"为使命的创新型企业。在这里，芯片与森林同频，算法与心跳共振。数百次黎明前的测试、数万行深夜跳动的代码，只为让每一声"嘀"的打卡，成为选手与荒野最优雅的对话。即将面世的全系设备将让每一场赛事，从起点到终点，都像星辰运行般精准、像晨露滚动般轻盈。我们相信，当科技与定向越野相遇，赛道就不再只是地图上的线条，而是可以被点亮、被记忆、被无限延展的梦想之路。
          feature_icon: check
          features:
            - '在这里，芯片与森林同频，算法与心跳共振。数百次黎明前的测试、数万行深夜跳动的代码，只为让每一声"嘀"的打卡，成为选手与荒野最优雅的对话。即将面世的全系设备将让每一场赛事，从起点到终点，都像星辰运行般精准、像晨露滚动般轻盈。我们相信，当科技与定向越野相遇，赛道就不再只是地图上的线条，而是可以被点亮、被记忆、被无限延展的梦想之路。'
          # Upload image to `assets/media/` and reference the filename here
          image: build-website.png
          # button:
          #   text: Get Started
          #   url: https://hugoblox.com/templates/
        - title: 我们的使命
          text: 让定向越野赛事组织更高效，让比赛体验更精彩
          feature_icon: bolt
          features:
            - "智能化管理，大幅降低赛事运营成本"
            - "自动化统计，提升赛事组织效率"
            - "实时监控，确保比赛安全公平"
            - "数据驱动，让每一场比赛更有趣"
          # Upload image to `assets/media/` and reference the filename here
          image: run.png
          # button:
          #   text: Join Discord
          #   url: https://discord.gg/z8wNYzb
        - title: 我们的愿景
          text: 让定向越野走进千家万户，成为最受欢迎的智慧型运动
          feature_icon: arrow-right
          features:
            - "科技引领 - 打造全球领先的定向越野智能装备"
            - "普及推广 - 让人人知道定向，人人爱上定向"
            - "赛事升级 - 以数字化、智能化助力赛事国际化"
            - "生态共建 - 携手合作伙伴，共创定向运动新时代"
          # Upload image to `assets/media/` and reference the filename here
          image: coffee.jpg
          # button:
          #   text: Join Discord
          #   url: https://discord.gg/z8wNYzb
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  # - block: testimonials
  #   content:
  #     title: ""
  #     text: ""
  #     items:
  #       - name: "Hugo Smith"
  #         role: "Marketing Executive at X"
  #         # Upload image to `assets/media/` and reference the filename here
  #         image: "testimonial-1.jpg"
  #         text: "Awesome, so easy to use and saved me so much work with the swappable pre-designed sections!"
  #   design:
  #     spacing:
  #       # Reduce bottom spacing so the testimonial appears vertically centered between sections
  #       padding: ["6rem", 0, 0, 0]
  - block: cta-card
    id: contact
    content:
      title: 联系我们
      text: "扫码加入客户群 ![二维码](contact.png)"
      # button:
      #   text: Get Started
      #   url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
