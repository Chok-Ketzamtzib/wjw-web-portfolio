---
layout: default
title: Home
---

<section class="hero">
    <div class="container">
        <div class="hero-content">
            <h1 class="hero-title">William Wakefield</h1>
            <h2 class="hero-subtitle">C++ Software Engineer</h2>
            <p class="hero-description">
                Passionate software engineer specializing in C++ development, embedded systems, 
                and performance optimization. Dedicated to writing clean, efficient code and 
                solving complex technical challenges.
            </p>
            <div class="hero-actions">
                <a href="{{ '/about' | relative_url }}" class="btn btn-primary">Learn More</a>
                <a href="{{ '/contact' | relative_url }}" class="btn btn-secondary">Get In Touch</a>
            </div>
        </div>
    </div>
</section>

<section class="skills-overview">
    <div class="container">
        <h2 class="section-title">Core Competencies</h2>
        <div class="skills-grid">
            <div class="skill-card">
                <i class="fas fa-code"></i>
                <h3>C++ Development</h3>
                <p>Expert in modern C++ standards, STL, and best practices for performance-critical applications.</p>
            </div>
            <div class="skill-card">
                <i class="fas fa-microchip"></i>
                <h3>Embedded Systems</h3>
                <p>Experience with microcontrollers, real-time systems, and hardware-software integration.</p>
            </div>
            <div class="skill-card">
                <i class="fas fa-tachometer-alt"></i>
                <h3>Performance Optimization</h3>
                <p>Profiling, debugging, and optimizing code for maximum efficiency and reliability.</p>
            </div>
            <div class="skill-card">
                <i class="fas fa-desktop"></i>
                <h3>Cross-Platform Development</h3>
                <p>Building applications that work seamlessly across different operating systems.</p>
            </div>
        </div>
    </div>
</section>

<section class="recent-projects">
    <div class="container">
        <h2 class="section-title">Featured Projects</h2>
        <div class="projects-grid">
            {% for project in site.projects limit: 3 %}
            <div class="project-card">
                <h3><a href="{{ project.url | relative_url }}">{{ project.title }}</a></h3>
                <p>{{ project.excerpt | strip_html | truncatewords: 20 }}</p>
                <div class="project-tech">
                    {% for tech in project.technologies %}
                    <span class="tech-tag">{{ tech }}</span>
                    {% endfor %}
                </div>
            </div>
            {% endfor %}
        </div>
        <div class="text-center">
            <a href="{{ '/projects' | relative_url }}" class="btn btn-outline">View All Projects</a>
        </div>
    </div>
</section>
