## This Project aims to introduce autool JSON/DIFF/MD5/URLDECODE tools
[中文版](README.zh.md)

This project aims to introduce a developer tools website that pursues fast responsiveness, simplicity, and comprehensive functionality. It doesn't prioritize the quantity of tools but focuses on the exceptional usability of each tool. Currently, it includes features such as:
JSON formatting tool, JSON validation tool, text comparison tool, MD5 hashing generate tool, URL decoding tool, and more.
Please visit: https://autool.info/

## Why build this site?

In my development work, I often encounter situations where I need to manipulate JSON data, performing operations such as formatting, sorting, searching, and modifying. Similarly, there are frequent instances where I need to compare texts or code, necessitating preprocessing, sorting, and comparison.

Typically, I would resort to search engines to find tools for these tasks, only to encounter tools that load slowly, have unattractive interfaces, or lack essential features. The needs for JSON editing and text comparison are fundamentally straightforward, and there should be simple, user-friendly tools to fulfill them.

As of 2024, we should no longer tolerate poorly designed tools. JSON editing and text comparison tasks are a routine part of our work, and we deserve tools that are fast, elegant, and feature-rich.

Each day, each hour, we spend our time in front of computers, and we should strive to enjoy rather than endure. Our experience should be as effortless as possible, not cumbersome.

Therefore, I have decided to create an exceptional set of small tools tailored to specific scenarios, making our work easier and more enjoyable. Let's embrace tools that are sleek, efficient, and designed for a delightful user experience.

## How it's done?

The dynamic site was too slow, so I decided to switch to a static site using the Hugo static site generator.

The loading time of CSS and JS was a bottleneck, so I performed frontend optimization to make these resources fully leverage browser caching.

Many other tools simply wrap around some open-source libraries and go live, while the tools on this site are built using the most basic HTML or the most popular open-source libraries. They are carefully designed to provide essential functionality without unnecessary distractions.

Each tool page has a comments section where you can share your requirements, and I will promptly enhance it based on your feedback.

As a result, when you revisit a page, you'll notice that the page loads incredibly fast.
