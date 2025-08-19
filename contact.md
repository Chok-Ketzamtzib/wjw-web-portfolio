---
layout: page
title: Contact
subtitle: Let's connect and discuss opportunities
---

## Get In Touch

I'm always interested in discussing new opportunities, collaborating on interesting projects, or simply connecting with fellow developers. Whether you have a question about C++ development, want to discuss a potential project, or just want to say hello, I'd love to hear from you.

<div class="contact-methods">
    <div class="contact-card">
        <i class="fas fa-envelope"></i>
        <h3>Email</h3>
        <p>The best way to reach me is via email:</p>
        <a href="mailto:{{ site.email }}" class="contact-link">{{ site.email }}</a>
    </div>
    
    {% if site.linkedin_username %}
    <div class="contact-card">
        <i class="fab fa-linkedin"></i>
        <h3>LinkedIn</h3>
        <p>Connect with me professionally:</p>
        <a href="https://linkedin.com/in/{{ site.linkedin_username }}" class="contact-link" target="_blank">
            linkedin.com/in/{{ site.linkedin_username }}
        </a>
    </div>
    {% endif %}
    
    {% if site.github_username %}
    <div class="contact-card">
        <i class="fab fa-github"></i>
        <h3>GitHub</h3>
        <p>Check out my code and projects:</p>
        <a href="https://github.com/{{ site.github_username }}" class="contact-link" target="_blank">
            github.com/{{ site.github_username }}
        </a>
    </div>
    {% endif %}
</div>

## What I'm Looking For

I'm particularly interested in opportunities involving:

- **C++ Development** - Modern C++ applications, performance optimization, and system programming
- **Embedded Systems** - Real-time systems, microcontroller programming, and IoT development
- **Open Source** - Contributing to meaningful projects and collaborating with the community
- **Mentoring** - Sharing knowledge and helping other developers grow their skills

## Response Time

I typically respond to emails within 24-48 hours during business days. If you have an urgent inquiry, please mention it in your subject line.

## Let's Build Something Great Together

Whether you're looking for a team member, a collaborator, or just want to chat about technology, I'm always happy to connect. Looking forward to hearing from you!
